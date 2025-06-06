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

### Etapa 1: Identificação das Entidades

Com base no levantamento de requisitos fornecido, as principais entidades que podemos identificar são:

- **Conferência**
- **Participante**
- **Sessão**
- **Apresentação**
- **Submissão**
- **Revisor**
