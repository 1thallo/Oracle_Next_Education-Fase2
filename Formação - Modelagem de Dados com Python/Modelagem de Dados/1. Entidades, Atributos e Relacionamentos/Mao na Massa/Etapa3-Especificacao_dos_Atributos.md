# Etapa 3: Especificação dos Atributos

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
