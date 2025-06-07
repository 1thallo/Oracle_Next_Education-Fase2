# Etapa 2: Definição dos Relacionamentos

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
