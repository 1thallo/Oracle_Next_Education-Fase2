# Atividade Prática 02 - Regressão Linear com NumPy

Esta atividade aplica conceitos de regressão linear utilizando a biblioteca **NumPy** para calcular coeficientes de retas através do método dos mínimos quadrados.

## Objetivo

Calcular os coeficientes angular e linear para laranjas e toranjas utilizando dados de diâmetro e peso, implementando a fórmula de mínimos quadrados com NumPy.

## Dataset

Arquivo `citrus.csv` contendo:

- Nome da fruta (orange/grapefruit)
- Diâmetro
- Peso
- Valores RGB de cor

## Implementação

- **Separação dos dados** por tipo de fruta
- **Cálculo dos coeficientes** usando a fórmula: `a = (n*Σ(XY) - ΣX*ΣY)/(n*Σ(X²) - (ΣX)²)`
- **Visualização** com scatter plot e retas de regressão

## Resultados

O notebook gera:

- Coeficientes angular (a) e linear (b) para cada fruta
- Equações das retas de regressão
- Gráfico comparativo com as retas ajustadas

---

**Bibliotecas:** NumPy, Pandas, Matplotlib
