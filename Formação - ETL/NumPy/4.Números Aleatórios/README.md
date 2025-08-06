# Aula 04 - Números Aleatórios com NumPy

Esta aula aborda a geração de números aleatórios com **NumPy** e sua aplicação em análise de dados, com foco em reprodutibilidade e salvamento de resultados.

## Conteúdo Abordado

### 4.1 - Valores em um Intervalo

- Geração de números inteiros aleatórios com `np.random.randint()`
- Criação de números decimais uniformes com `np.random.uniform()`
- Aplicação em cálculos de normas para análise de coeficientes

### 4.2 - Reprodutibilidade

- Conceito de números pseudoaleatórios
- Uso de `np.random.seed()` para garantir resultados reproduzíveis
- Importância da semente (seed) em experimentos científicos

### 4.3 - Salvando os Resultados

- Organização de dados com `np.column_stack()`
- Exportação de resultados para CSV com `np.savetxt()`

## Exemplos Práticos

- Geração de 100 coeficientes angulares aleatórios
- Cálculo de normas para diferentes coeficientes
- Salvamento dos resultados em arquivo CSV para análise posterior

---

**Conceitos-chave:** Números pseudoaleatórios, reprodutibilidade, exportação de dados
