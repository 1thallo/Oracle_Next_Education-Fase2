# Pandas - Transformação e Manipulação de Dados

![Certificado](https://github.com/user-attachments/assets/134d64db-559b-48b6-b6ee-957247d72294)

## 📋 Sobre o Curso

Este curso foca na **transformação e manipulação de dados** usando Pandas, abordando técnicas essenciais para limpeza, conversão e tratamento de diferentes tipos de dados. O objetivo é capacitar o estudante a preparar dados para análise de forma eficiente e profissional.

## 🎯 Conteúdo Programático

### 📊 Aula 1: Entendendo o Problema

- Importação e normalização de dados JSON
- Análise inicial da estrutura dos dados
- Identificação de problemas comuns em datasets

### 🔢 Aula 2: Dados Numéricos

- Transformação de listas em linhas com `explode()`
- Conversão de tipos com `astype()`
- Limpeza de dados numéricos em formato string
- Tratamento de múltiplas colunas com `apply()` e `applymap()`

### 📝 Aula 3: Dados Textuais

- Manipulação de strings com métodos `.str`
- Expressões regulares (regex) para limpeza de texto
- Normalização de texto (lowercase, remoção de caracteres)
- Tokenização e transformação de texto em listas

### 📅 Aula 4: Dados de Tempo

- Identificação de dados datetime
- Conversão para tipo datetime com `pd.to_datetime()`
- Manipulação de datas com métodos `.dt`
- Formatação e agrupamento por períodos temporais

## 🚀 Projetos Práticos

O curso inclui **2 projetos completos** desenvolvidos ao longo das aulas:

### 📈 Projeto 1: Vendas Online

**Objetivo**: Análise de evento promocional para identificar melhor cliente

**Etapas desenvolvidas**:

- **Etapa 1**: Normalização de dados JSON
- **Etapa 2**: Conversão de valores monetários (R$)  
- **Etapa 3**: Limpeza de nomes de clientes
- **Etapa 4**: Análise temporal e ranking de vendas

### 🏠 Projeto 2: Administração de Condomínios

**Objetivo**: Análise de atrasos em pagamentos de aluguel

**Etapas desenvolvidas**:

- **Etapa 1**: Normalização de dados JSON
- **Etapa 2**: Conversão de valores monetários ($)
- **Etapa 3**: Limpeza de identificação de apartamentos
- **Etapa 4**: Cálculo de atrasos e análise temporal

## 🛠️ Principais Técnicas Aprendidas

- **Normalização de JSON**: `pd.json_normalize()`
- **Explosão de listas**: `df.explode()`
- **Conversão de tipos**: `astype()`, `pd.to_datetime()`
- **Limpeza de strings**: regex, `.str.replace()`, `.str.split()`
- **Transformação de dados**: `apply()`, `map()`
- **Agrupamento temporal**: `.dt.strftime()`, `groupby()`
- **Reset de índices**: `reset_index()`

## 📊 Dataset Utilizado

**Base principal**: `dados_hospedagem.json` - Dados de hospedagem com informações sobre:

- Avaliações e descrições
- Preços e taxas
- Comodidades e características
- Capacidade e estrutura
