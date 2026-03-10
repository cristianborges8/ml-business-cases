# Credit Default Prediction

## Problema de Negócio

Instituições financeiras precisam avaliar o risco de crédito de seus clientes antes de conceder empréstimos.
Conceder crédito a clientes com alto risco de inadimplência gera prejuízo direto.
Negar crédito a bons pagadores gera perda de receita.

O objetivo deste projeto é construir um modelo preditivo capaz de estimar a probabilidade de um cliente
se tornar inadimplente nos próximos 2 anos, com base em seu histórico financeiro e comportamental.

## Dataset

- **Fonte:** [Give Me Some Credit – Kaggle](https://www.kaggle.com/c/GiveMeSomeCredit)
- **Tamanho:** ~150.000 registros, 11 variáveis
- **Variável alvo:** `SeriousDlqin2yrs` (1 = inadimplente, 0 = adimplente)

> Os dados não estão incluídos neste repositório.
> Para reproduzir, baixe o arquivo `cs-training.csv` no link acima e coloque na pasta `data/`.

## Variáveis principais

| Variável | Descrição |
|---|---|
| `SeriousDlqin2yrs` | Alvo: inadimplência em 2 anos |
| `RevolvingUtilizationOfUnsecuredLines` | Uso de crédito rotativo |
| `age` | Idade do cliente |
| `NumberOfTime30-59DaysPastDueNotWorse` | Atrasos de 30–59 dias |
| `DebtRatio` | Razão dívida/renda |
| `MonthlyIncome` | Renda mensal |
| `NumberOfOpenCreditLinesAndLoans` | Linhas de crédito abertas |
| `NumberOfTimes90DaysLate` | Atrasos acima de 90 dias |
| `NumberRealEstateLoansOrLines` | Empréstimos imobiliários |
| `NumberOfTime60-89DaysPastDueNotWorse` | Atrasos de 60–89 dias |
| `NumberOfDependents` | Número de dependentes |

## Etapas do Projeto

1. **EDA** – Análise exploratória: distribuições, correlações, outliers, desbalanceamento
2. **Preparação** – Tratamento de nulos, encoding, scaling, feature engineering
3. **Modelagem** – Regressão Logística, Random Forest, XGBoost
4. **Avaliação** – ROC-AUC, Precision, Recall, F1, matriz de confusão
5. **Interpretação** – Feature importance, conclusões de negócio

## Resultados

> A preencher após modelagem.

## Como executar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/ml-business-cases.git

# Instale as dependências
pip install -r requirements.txt

# Abra os notebooks
jupyter notebook
```

## Aprendizados principais

> A preencher após conclusão do projeto.