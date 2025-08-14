# Pandas IO - Diferentes Formatos de Arquivos

![Certificado](https://github.com/user-attachments/assets/eda7b23a-7b22-4f7b-9b94-0159c915b17d)

## 📋 Sobre o Curso

Este curso apresenta as principais funcionalidades da biblioteca **Pandas** para **input/output (I/O)** de dados, abordando a leitura e escrita de diferentes formatos de arquivos. O foco está em capacitar o estudante a trabalhar com diversas fontes de dados de forma eficiente e prática.

## 🎯 Conteúdo Programático

### 📄 Aula 1: Leitura de Arquivo CSV

- Importação básica com `pd.read_csv()`
- Configuração de separadores (`,` e `;`)
- Parâmetros essenciais:
  - `nrows` - Limitar quantidade de linhas
  - `usecols` - Selecionar colunas específicas
  - `encoding` - Resolver problemas de codificação
- Exportação de dados com `to_csv()`

### 📊 Aula 2: Utilizando Planilhas Excel

- Leitura de arquivos Excel com `pd.read_excel()`
- Trabalho com múltiplas abas (`sheet_name`)
- Exploração de estrutura com `pd.ExcelFile()`
- Seleção de intervalos de dados (`usecols`, `nrows`)
- Exportação para Excel com `to_excel()`

### 🔗 Aula 3: Manipulando JSON

- Leitura de arquivos JSON com `pd.read_json()`
- **Normalização de dados aninhados** com `pd.json_normalize()`
- Parâmetros avançados:
  - `record_path` - Especificar caminho dos registros
  - `meta` - Incluir metadados adicionais
- Exportação para JSON com `to_json()`

### 🌐 Aula 4: Lendo Dados HTML e XML

- Extração de tabelas HTML com `pd.read_html()`
- Processamento de múltiplas tabelas
- Leitura de arquivos XML com `pd.read_xml()`
- Web scraping de páginas da Wikipedia
- Exportação para HTML com `to_html()`

### 🗃️ Aula 5: Trabalhando com Banco de Dados

- Configuração de conexão com **SQLAlchemy**
- Criação de banco SQLite em memória
- Operações CRUD:
  - **Create**: Inserção de dados com `to_sql()`
  - **Read**: Consultas com `pd.read_sql()` e `pd.read_sql_table()`
  - **Update**: Atualização de registros
  - **Delete**: Remoção de registros
- Inspeção de estrutura do banco

## 🚀 Desafios Práticos

Cada aula inclui **desafios práticos** que aplicam os conceitos aprendidos:

1. **Desafio CSV**: Leitura de dados de saúde do DATASUS com encoding específico
2. **Desafio Excel**: Importação de dados de emissões de CO2 do Google Sheets
3. **Desafio JSON**: Normalização de API de usuários (JSONPlaceholder)
4. **Desafio HTML**: Web scraping de dados populacionais da Wikipedia
5. **Desafio SQL**: Gestão completa de banco de dados de clientes bancários

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Manipulação de dados
- **SQLAlchemy** - Interface com banco de dados
- **Requests** - Requisições HTTP
- **JSON** - Processamento de dados JSON
