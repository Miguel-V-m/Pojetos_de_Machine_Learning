## projetos de aprendizagem não supervisionada
 
neste repositório representamos três arquivos.ipynb que descrevemos abaixo:

- A1-agrupamento.ipynb: Este projeto tem por objetivo desenvolver um algoritmo de Machine Learning para agrupar clientes de um shopping.
- A2_regras_associacao.ipynb: É baseado em um exemplo da biblioteca "pyECLAT" e tem por finalidades aplicar os métodos APRIORI e ECLAT
- A3_associacao_APRIORI.ipynb: Este projeto tem por objetivo desenvolver um algoritmo de Machine Learning para associar produtos de mercado
de um conjunto de dados de mantimentos.

### Sobre o conjunto de dados (3_associacao_APRIORI.ipynb:)

**Mineração de regras de associação**

A Análise de Cesta de Mercado é uma das principais técnicas usadas por grandes varejistas para descobrir associações entre itens. Ele funciona procurando combinações de itens que ocorrem juntos com frequência nas transações. Em outras palavras, permite que os varejistas identifiquem as relações entre os itens que as pessoas compram.

As regras de associação são amplamente utilizadas para analisar dados de transações ou cestas de varejo e visam identificar regras fortes descobertas em dados de transações usando medidas de interesse, com base no conceito de regras fortes.

**Detalhes do conjunto de dados**

O conjunto de dados possui 38.765 linhas de pedidos de compras de pessoas dos supermercados. Essas ordens podem ser analisadas e as regras de associação podem ser geradas usando o Market Basket Analysis por algoritmos como o Apriori Algorithm.
REF: https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset

**Algoritmo A priori**
Apriori é um algoritmo para mineração frequente de conjuntos de itens e aprendizado de regras de associação em bancos de dados relacionais. Ele prossegue identificando os itens individuais frequentes no banco de dados e estendendo-os para conjuntos de itens cada vez maiores, desde que esses conjuntos de itens apareçam com suficiente frequência no banco de dados. Os conjuntos de itens frequentes determinados pelo Apriori podem ser usados ​​para determinar regras de associação que destacam tendências gerais no banco de dados: isso tem aplicações em domínios como análise de cesta de mercado.

**Alguns termos importantes:**

- Apoio: Isto diz como um populares itemset é, medida pela proporção de transações em que um conjunto de itens aparece.
- Confiança: indica a probabilidade de compra do item Y quando o item X é comprado, expresso como {X -> Y}. Isso é medido pela proporção de transações com o item X, no qual o item Y também aparece.
- Elevação: Isso diz a probabilidade de o item Y ser comprado quando o item X é comprado enquanto controla a popularidade do item Y.

**As tecnologias mas utilizadas são**

- Python
- jupyter notebook
