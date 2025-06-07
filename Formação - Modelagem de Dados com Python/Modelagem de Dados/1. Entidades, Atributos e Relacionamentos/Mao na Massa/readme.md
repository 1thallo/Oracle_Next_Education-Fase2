# Mão na Massa - Criando Entidades

## Modelo Conceitual para Sistema de Gerenciamento de Conferências Científicas

### Levantamento de Requisitos

Para desenvolver um sistema eficiente de gerenciamento de conferências científicas, é necessário entender e capturar diversos aspectos de como as conferências são organizadas, quais são os participantes envolvidos e quais atividades ocorrem. Então, temos as seguintes informações:

- Cada **conferência** tem um título único, data de realização, local e um tema central.
- As conferências podem ser compostas por várias **sessões temáticas** diferentes.
- Um **participante** pode ser um palestrante, ouvinte registrado ou organizador.
- Cada participante possui dados pessoais como nome, filiação institucional, contato e tipo de participação no evento.
- Cada **sessão** dentro de uma conferência aborda subtemas específicos do tema central.
- Uma sessão inclui data e hora da apresentação, múltiplas apresentações e é coordenada por um ou mais organizadores.
- Cada **apresentação** tem um título, um resumo, duração prevista e é atribuída a um palestrante específico. Apresentações podem incluir também materiais de suporte como slides ou vídeos.
- **Artigos ou resumos** são submetidos por palestrantes para avaliação antes de serem aceitos para apresentação.
- Cada **submissão** precisa ter informações como título, resumo, data e o status.
- Cada uma das submissões é avaliada por **revisores designados**.
- Revisores são especialistas em tópicos específicos e são responsáveis por avaliar as submissões, fornecendo feedback e uma decisão de aceitação ou rejeição.

---

## Etapa 1: Identificação das Entidades

Com base no levantamento de requisitos, foi possível identificar as entidades essenciais que compõem o sistema de gerenciamento de conferências científicas. Essas entidades representam os elementos centrais envolvidos na organização e no funcionamento do evento.

> As principais entidades identificadas são:
>
> - **Conferência**  
>
>
> - **Participante**  
>
>
> - **Sessão**  
>
>
> - **Apresentação**  
>
>
> - **Submissão**  
>
>
> - **Revisor**  
>  

Essa identificação serve como base para a modelagem conceitual das informações do sistema.

## Etapa 2: Definição dos Relacionamentos

Os relacionamentos entre as entidades identificadas foram definidos da seguinte maneira:

> - **Conferência – Sessão**  
>   Uma conferência contém várias sessões, mas cada sessão pertence a apenas uma conferência.  
>   **(1:N)**
>
> - **Sessão – Apresentação**  
>   Uma sessão possui várias apresentações, e cada apresentação está vinculada a uma única sessão.  
>   **(1:N)**
>
> - **Participante – Apresentação**  
>   Um participante (como palestrante) pode realizar várias apresentações, e cada apresentação é feita por um único participante.  
>   **(1:N)**
>
> - **Participante – Conferência**  
>   Um participante pode participar de várias conferências, e cada conferência envolve vários participantes.  
>   **(N:N)** — Utiliza-se uma **entidade associativa** chamada `Participação`.
>
> - **Submissão – Apresentação**  
>   Uma submissão, se aceita, gera uma única apresentação correspondente.  
>   **(1:1)**
>
> - **Submissão – Revisor**  
>   Uma submissão pode ser avaliada por vários revisores, e cada revisor pode avaliar várias submissões.  
>   **(N:N)** — Utiliza-se uma **entidade associativa** chamada `Avaliação`.

Esses relacionamentos serão essenciais para construir o modelo conceitual completo e posteriormente o modelo lógico do sistema.

## Etapa 3: Especificação dos Atributos

Abaixo estão listados os atributos de cada entidade identificada:

> ## **Conferência**
>
> - `ConferenciaID` (chave primária)
> - Título
> - Data
> - Local
> - Tema
> ### **Participante**
> - `ParticipanteID` (chave primária)
> - Nome
> - Email
> - Tipo (Ouvinte, Palestrante, Organizador)
> - Afiliação Institucional
> ### **Sessão**
> - `SessaoID` (chave primária)
> - Subtema
> - DataHora
> - `ConferenciaID` (chave estrangeira)
> ### **Apresentação**
> - `ApresentacaoID` (chave primária)
> - Título
> - Resumo
> - Duração
> - Materiais
> - `ParticipanteID` (chave estrangeira)
> ### **Submissão**
> - `SubmissaoID` (chave primária)
> - Título
> - Resumo
> - DataSubmissao
> - Status (Aceita, Rejeitada)
> ### **Revisor**
> - `RevisorID` (chave primária)
> - Nome
> - Especialidade

---

### **Entidades Associativas**

> #### Participação *(Conferência – Participante)*
> - `ParticipanteID` (chave primária / estrangeira)
> - `ConferenciaID` (chave primária / estrangeira)
> - DataParticipacao
> #### Avaliação *(Submissão – Revisor)*
> - `SubmissaoID` (chave primária / estrangeira)
> - `RevisorID` (chave primária / estrangeira)
> - Comentários
> - DataAvaliacao
