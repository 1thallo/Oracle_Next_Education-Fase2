# Aula 01 - Conhecendo a Biblioteca NumPy e os Dados

Este notebook tem como objetivo apresentar os conceitos iniciais da biblioteca **NumPy**, uma das principais ferramentas para manipulação de dados numéricos em Python. Ao longo da aula, você aprenderá a criar e manipular arrays, carregar dados de arquivos, explorar propriedades dos arrays e realizar operações fundamentais para análise de dados.

## Conteúdo Abordado

- **Criação de Arrays NumPy:**  
  Aprenda a criar arrays utilizando funções do NumPy, incluindo a geração de sequências numéricas.

- **Carregamento de Arquivos:**  
  Veja como importar dados de arquivos CSV utilizando a função `np.loadtxt`, facilitando o processamento de grandes volumes de dados.

- **Verificação de Dimensões:**  
  Descubra como identificar o número de dimensões (`ndim`), o tamanho total (`size`) e a estrutura (linhas e colunas, via `shape`) de um array NumPy.

- **Transposição de Arrays:**  
  Entenda como transpor arrays (trocar linhas por colunas) utilizando o atributo `.T`, recurso útil para reorganizar dados conforme a necessidade da análise.

## Exemplos Práticos

O notebook utiliza um arquivo de dados chamado `apples_ts.csv`, que contém informações organizadas em linhas e colunas. As principais operações realizadas incluem:

- Carregar os dados do arquivo CSV, ignorando a primeira coluna (provavelmente identificadores ou datas) e selecionando apenas as colunas relevantes para análise.
- Verificar quantas dimensões o array possui, quantos elementos estão presentes e qual o formato (quantidade de linhas e colunas).
- Realizar a transposição do array, facilitando análises que dependem da orientação dos dados.

## Objetivo da Aula

Ao final desta aula, você será capaz de:

- Utilizar o NumPy para criar e manipular arrays de forma eficiente.
- Carregar e explorar conjuntos de dados numéricos.
- Entender e aplicar conceitos fundamentais de estrutura e organização de arrays.
- Preparar dados para análises mais avançadas em Python.

---

**Requisitos:**

- Python instalado  
- Biblioteca NumPy  
- Arquivo de dados `apples_ts.csv` disponível no diretório correto

---
