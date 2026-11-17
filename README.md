# Análise das maiores ações do Ibovespa

> 🚧 **Em desenvolvimento.** Projeto final da trilha *Data Science & Machine Learning* da [Asimov Academy](https://asimov.academy), refeito por mim do zero.

## Problema

Analisar o histórico de preços das 10 ações com maior participação no Ibovespa e testar, com dados, hipóteses comuns de investimento.

## Perguntas que o projeto responde

- Desde quando há histórico para todos os ativos ao mesmo tempo?
- Em que datas cada ativo teve a pior oscilação diária?
- Depois de um dia de queda (em especial, quedas maiores que 1%), as ações tendem a subir no pregão seguinte? Comprar após a queda seria uma boa estratégia?
- **Desafio:** uma carteira montada a cada ano com as 3 maiores pagadoras de dividendos (*dividend yield*) do ano anterior supera uma carteira com todos os ativos?

## Dados

- Composição do Ibovespa (`ibovdia_09-08-22.csv`, B3, 09/08/2022), fornecida no material do curso, em `data/`.
- Preços históricos e dividendos baixados com a biblioteca [`yfinance`](https://pypi.org/project/yfinance/) (exige internet).

## Resultados

> A preencher ao final da análise.

## Estrutura

```
data/        dados (não versionados)
notebooks/   NN-sanjos-<descrição>.ipynb
reports/     resultados.md: registro de análises e experimentos
```

As seções dos notebooks seguem as etapas do checklist de projeto de Machine Learning (Géron).

## Como reproduzir

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install pandas numpy scikit-learn matplotlib seaborn jupyter yfinance
jupyter notebook notebooks/
```
