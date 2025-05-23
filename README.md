# Inflação e Rendimento Real: Uma Análise com Python

Este projeto tem como objetivo analisar a evolução da inflação, do rendimento médio mensal real e da rentabilidade da poupança no Brasil ao longo dos últimos anos, utilizando dados oficiais do IBGE e ferramentas de análise em Python.

## 📊 Sobre os Dados

Todos os dados utilizados neste projeto foram obtidos diretamente do **IBGE**.

O arquivo Excel usado na análise (`dados_ibge.xlsx`) contém **três planilhas**, descritas a seguir:

### 1. `rendimento`
- **Período**: 2012 a 2024
- **Colunas**:
  - `Rendimento médio real mensal a preços do ano`: rendimento médio ajustado à inflação do próprio ano (valor real anual).
  - `Rendimento médio mensal real a preços médios do último ano (Reais)`: rendimento médio corrigido pela inflação para os preços de 2024.

### 2. `inflação`
- **Período**: 1995 a 2024
- **Colunas**:
  - `Ano`: ano calendário.
  - `IPCA`: Índice Nacional de Preços ao Consumidor Amplo (IPCA) anual.

### 3. `poupança`
- **Período**: Junho de 2012 a Abril de 2025 (dados mensais)
- **Colunas**:
  - `Data`: mês/ano da observação.
  - `Rendimento da poupança`: rentabilidade mensal da poupança.
  - `IPCA`: inflação mensal medida pelo IPCA no mesmo período.

## ⚙️ Tecnologias Utilizadas

- Pandas
- Matplotlib


## 📌 Observações

- Todos os dados são públicos e foram extraídos do [site oficial do IBGE](https://www.ibge.gov.br/).
- Os valores e gráficos apresentados têm fins educacionais e analíticos.
- As conversões de valores reais utilizam o IPCA acumulado como deflator.

## 📬 Contato

Adicionar

---

