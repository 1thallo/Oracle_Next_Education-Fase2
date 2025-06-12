# Aula 02 - Exploração de Dados com NumPy

Este notebook tem como objetivo aprofundar o uso da biblioteca **NumPy** para exploração e análise de dados numéricos. A partir de um conjunto de dados reais, você aprenderá a manipular arrays, extrair informações relevantes, lidar com valores ausentes e realizar comparações entre diferentes conjuntos de dados.

## Conteúdo Abordado

- **Carregamento e Estruturação dos Dados**
  - Importação de dados a partir de arquivos CSV utilizando `np.loadtxt`.
  - Seleção de colunas relevantes para análise.
  - Transposição de arrays para facilitar a manipulação dos dados.

- **Extração e Organização de Informações**
  - Separação de datas e preços em diferentes arrays.
  - Organização dos dados por cidades e por períodos (anos).

- **Visualização de Dados**
  - Utilização da biblioteca Matplotlib para criar gráficos de séries temporais.
  - Comparação visual dos preços ao longo dos anos para diferentes cidades.

- **Comparação Entre Arrays**
  - Uso das funções `np.array_equal` e `np.allclose` para comparar séries de dados e identificar similaridades ou diferenças entre períodos.

- **Tratamento de Valores Ausentes (NaN)**
  - Identificação de valores não numéricos (NaN) em arrays.
  - Preenchimento de valores ausentes utilizando médias dos valores vizinhos.
  - Verificação do impacto dos NaNs nas análises e visualizações.

- **Cálculo de Métricas Estatísticas**
  - Cálculo de médias para diferentes cidades.
  - Comparação de médias entre diferentes conjuntos de dados.

## Exemplos Práticos

Durante a aula, você irá:

- Carregar um arquivo de preços de maçãs em diferentes cidades e anos.
- Visualizar a evolução dos preços ao longo do tempo para cada cidade.
- Dividir os dados de uma cidade em períodos anuais e comparar os valores entre os anos.
- Identificar e tratar valores ausentes nos dados, garantindo a integridade das análises.
- Utilizar funções estatísticas do NumPy para comparar médias e avaliar tendências.

## Objetivo da Aula

Ao final desta aula, você será capaz de:

- Explorar e manipular conjuntos de dados numéricos utilizando NumPy.
- Visualizar séries temporais e identificar padrões ou anomalias nos dados.
- Tratar valores ausentes de forma adequada para não comprometer suas análises.
- Realizar comparações estatísticas entre diferentes grupos de dados.

---

**Pré-requisitos:**  

- Python instalado  
- Bibliotecas NumPy e Matplotlib instaladas  
- Arquivo de dados `apples_ts.csv` disponível no diretório correto
