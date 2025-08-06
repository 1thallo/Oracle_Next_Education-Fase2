# Desafio do Curso - Resolução

Este desafio aplica os conceitos fundamentais do **NumPy** aprendidos durante o curso, utilizando análise de dados de frutas cítricas (laranjas e toranjas) para demonstrar técnicas de manipulação de arrays, cálculos estatísticos e geração de números aleatórios.

## Objetivo

Analisar um dataset de frutas cítricas para calcular coeficientes de regressão linear e explorar métodos de estimação usando números aleatórios.

## Dataset

Arquivo `citrus.csv` contendo:

- **5000 registros** de laranjas (linhas 0-4999)
- **200+ registros** de toranjas (linhas 5000+)
- **Colunas:** diâmetro, peso, valores RGB de cor

## Etapas da Resolução

### 1. Leitura dos Dados

- Carregamento do CSV usando `np.loadtxt()`
- Seleção de colunas específicas com `usecols=np.arange(1,6,1)`
- Ignorar cabeçalho com `skiprows=1`

### 2. Separação dos Dados

- Extração de diâmetro e peso para cada tipo de fruta
- Arrays específicos para laranjas e toranjas

### 3. Visualização

- Gráficos comparativos usando Matplotlib
- Análise visual das diferenças entre as frutas

### 4. Cálculo de Coeficientes

Implementação das fórmulas de regressão linear:

- **Coeficiente angular:** `a = (n*Σ(XY) - ΣX*ΣY)/(n*Σ(X²) - (ΣX)²)`
- **Coeficiente linear:** `b = média(Y) - a*média(X)`

### 5. Estimação com Números Aleatórios

- Geração de coeficientes aleatórios com `np.random.uniform()`
- Uso de `np.random.seed(84)` para reprodutibilidade
- Cálculo de normas para encontrar melhor ajuste

## Resultados Esperados

- Menor norma alcançada: **104.40529157196431**
- Demonstração de que os coeficientes servem para diferenciar laranjas de toranjas
- Validação de métodos analíticos vs. estimação aleatória

---

**Conceitos aplicados:** Manipulação de arrays, regressão linear, números aleatórios, visualização de dados
