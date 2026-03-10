# Alura Store — Análise de Desempenho de Lojas

> Projeto de análise de dados desenvolvido como parte do **Challenge 1 de Data Science da Alura**, com o objetivo de auxiliar o Sr. João a decidir qual das suas quatro lojas deve ser vendida para reinvestimento em um novo negócio.

---

## Propósito da Análise

O Sr. João é proprietário de uma rede de quatro lojas do e-commerce **Alura Store**. Para tomar uma decisão estratégica baseada em dados, foi realizada uma análise comparativa de desempenho entre as lojas, avaliando métricas de faturamento, satisfação dos clientes, comportamento de vendas e logística.

**Pergunta central:** _Qual loja apresenta o menor desempenho e deve ser vendida?_

---

## Estrutura do Projeto

```
alura-store/
│
├── AluraStoreBrasil_Completo.ipynb   # Notebook principal com toda a análise
│
├── base-de-dados/
│   ├── loja_1.csv                    # Dados da Loja 1
│   ├── loja_2.csv                    # Dados da Loja 2
│   ├── loja_3.csv                    # Dados da Loja 3
│   └── loja_4.csv                    # Dados da Loja 4
│
└── README.md                         # Documentação do projeto
```

> Os arquivos CSV também estão disponíveis diretamente via URL no repositório oficial da Alura no GitHub, e são carregados automaticamente pelo notebook.

---

## Métricas Analisadas

| # | Métrica                        | Descrição                                              |
|---|-------------------------------|--------------------------------------------------------|
| 1 | Faturamento Total           | Soma do valor de todas as vendas por loja              |
| 2 | Vendas por Categoria        | Volume de vendas em cada categoria de produto          |
| 3 | Média de Avaliação           | Nota média dada pelos clientes (escala de 1 a 5)       |
| 4 | Produtos Mais/Menos Vendidos| Produtos com maior e menor volume de unidades vendidas |
| 5 | Frete Médio                 | Custo médio de frete cobrado por loja                  |

---

## Gráficos e Insights

### 1. Faturamento Total por Loja
Gráfico de barras comparando o faturamento total das quatro lojas. A **Loja 4 apresentou o menor faturamento** da rede, destacada com borda vermelha no gráfico.

>  **Insight:** A diferença de faturamento entre a Loja 1 (maior) e a Loja 4 (menor) evidencia uma lacuna significativa de desempenho comercial.

---

### 2. Distribuição de Vendas por Categoria
Gráfico de pizza comparando a distribuição de categorias entre a Loja 1 e a Loja 4, revelando como cada loja distribui suas vendas entre as categorias disponíveis.

> **Insight:** A Loja 4 tem menor penetração nas categorias mais rentáveis, como eletrônicos e eletrodomésticos.

---

### 3. Média de Avaliação dos Clientes
Gráfico de barras horizontais com a nota média de satisfação dos clientes por loja, com linha de referência da média geral da rede.

> **Insight:** A **Loja 4 possui a pior avaliação média**, abaixo da média geral da rede, indicando menor satisfação dos clientes.

---

### 4. Top 5 Produtos Mais Vendidos
Gráfico de barras agrupadas mostrando o volume de vendas dos 5 produtos mais populares da rede, comparando todas as lojas lado a lado.

> **Insight:** Mesmo nos produtos mais populares da rede, a Loja 4 registra volumes de venda menores que as demais lojas.

---

### 5. Frete Médio por Loja
Gráfico de linha com marcadores comparando o custo médio de frete praticado por cada loja, com destaque para o valor mais alto.

>  **Insight:** A Loja 4 apresenta frete médio entre os mais elevados da rede, o que pode estar afastando clientes e contribuindo para o baixo volume de vendas.

---

## Conclusão

Com base na análise de todas as métricas, a recomendação final é:

> **O Sr. João deve vender a Loja 4.**

A Loja 4 apresentou o **pior desempenho consolidado** da rede:

- **Menor faturamento total**
- **Menor média de avaliação dos clientes**
- **Frete médio entre os mais altos**
- Menor volume de vendas mesmo nos produtos mais populares
- Menor penetração nas categorias mais rentáveis

As lojas 1, 2 e 3 apresentam desempenho mais equilibrado e maior potencial de crescimento, sendo mais estratégico mantê-las no portfólio.

---
