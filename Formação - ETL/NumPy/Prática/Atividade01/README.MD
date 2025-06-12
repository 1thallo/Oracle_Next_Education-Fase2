# Atividade Prática 01 - Leitura de Dados com NumPy

Nesta atividade, você terá a oportunidade de colocar em prática os conhecimentos adquiridos sobre manipulação de dados numéricos com a biblioteca **NumPy**. O objetivo é realizar a leitura de um novo conjunto de dados, utilizando técnicas e funções vistas durante as aulas.

## Contexto da Atividade

Você irá trabalhar com um dataset diferente do utilizado anteriormente: uma versão modificada do arquivo **Oranges vs. Grapefruit**, originalmente disponível no Kaggle. Para facilitar o acesso, utilizarei o arquivo raw hospedado no GitHub.

## Objetivos

- Praticar a importação de dados diretamente de uma URL.
- Utilizar a função `np.loadtxt` para ler arquivos CSV.
- Aplicar o parâmetro `usecols` para selecionar apenas as colunas desejadas, pulando a primeira coluna do arquivo.
- Utilizar `np.arange` para gerar a sequência de índices das colunas a serem lidas.
- Utilizar o parâmetro `skiprows=1` para ignorar o cabeçalho do arquivo.

## Passos Sugeridos

1. **Importação da Biblioteca**
   - Importe o NumPy utilizando o comando `import numpy as np`.

2. **Leitura dos Dados**
   - Utilize a função `np.loadtxt` para ler o arquivo CSV a partir da URL fornecida.
   - Use o parâmetro `delimiter=','` para indicar que o arquivo está separado por vírgulas.
   - Utilize `usecols=np.arange(1, N)` para pular a primeira coluna (ajuste `N` para o número total de colunas do arquivo).
   - Inclua `skiprows=1` para ignorar a primeira linha de texto (cabeçalho).

3. **Verificação dos Dados**
   - Exiba parte do array carregado para garantir que a leitura foi realizada corretamente.

## Habilidades Desenvolvidas

- Leitura e manipulação de dados numéricos com NumPy.
- Seleção de colunas específicas em arquivos CSV.
- Trabalho com dados provenientes de fontes externas (URLs).
