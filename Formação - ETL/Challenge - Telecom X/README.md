# 📊 Análise de Churn - TelecomX

## Certificado de Conclusão

![Certificado](https://github.com/user-attachments/assets/8cde77f8-7314-4b30-91f4-14bab1e97b13)

Link para a credencial:
- https://cursos.alura.com.br/formalCertificate/611e507f-7eba-4510-a790-eb8593664f01

## 🎯 Propósito da Análise

Este projeto tem como objetivo analisar o comportamento de evasão (churn) dos clientes da empresa TelecomX, identificando padrões e fatores que influenciam o cancelamento dos serviços de telecomunicações.

### Problema de Negócio

- A evasão de clientes representa uma perda significativa de receita
- Necessidade de identificar clientes com alto risco de cancelamento
- Criar estratégias de retenção baseadas em dados

## 🔧 Tecnologias Utilizadas

- **Python** - Linguagem principal
- **Pandas** - Manipulação e análise de dados
- **Matplotlib/Seaborn** - Visualização de dados
- **Requests** - Consumo de API JSON
- **Jupyter Notebook** - Ambiente de desenvolvimento

## 📈 Principais Insights Obtidos

### 📊 Distribuição de Churn

- **Taxa de evasão geral**: ~27% dos clientes cancelam o serviço
- Visualização clara da proporção entre clientes que permanecem vs. saem

### 🔍 Fatores de Risco Identificados

**1. Tipo de Contrato**

- Contratos mensais têm maior taxa de churn
- Contratos de longo prazo apresentam maior retenção

**2. Tempo de Permanência**

- Clientes novos (primeiros 6 meses) são mais propensos ao churn
- Clientes com mais tempo de contrato tendem a permanecer

**3. Valor de Faturamento**

- Correlação entre faturamento alto e probabilidade de cancelamento
- Clientes com valores médios apresentam melhor retenção

## 🚀 Como Executar o Projeto

### Pré-requisitos
```bash
pip install pandas matplotlib seaborn requests numpy jupyter
```

### Execução

1. Clone ou baixe o projeto
2. Abra o arquivo `TelecomX_BR.ipynb` no Jupyter Notebook
3. Execute as células sequencialmente:
   - **📌 Extração**: Importa dados via API
   - **🔧 Transformação**: Limpa e processa os dados
   - **📊 Carga e análise**: Gera visualizações e insights

### Fonte dos Dados

- **API JSON**: `https://github.com/alura-cursos/challenge2-data-science/raw/refs/heads/main/TelecomX_Data.json`
- Dados normalizados automaticamente no notebook

## 📋 Resultados e Recomendações

### Estratégias de Retenção

- Implementar programa de fidelidade para contratos mensais
- Oferecer incentivos nos primeiros 6 meses
- Criar alertas para clientes de alto risco

### Próximos Passos

- Desenvolver modelo preditivo de churn
- Implementar dashboard de monitoramento
- Realizar testes A/B com estratégias de retenção

## 📊 Exemplos de Visualizações

O notebook inclui:

- Gráficos de barras para distribuição de churn
- Análise categórica por gênero, contrato e método de pagamento
- Boxplots para variáveis numéricas (faturamento, tempo de contrato)
- Estatísticas descritivas comparativas

## 🤝 Contribuições

Projeto desenvolvido como parte do programa ONE - Oracle Next Education em parceria com a Alura.
