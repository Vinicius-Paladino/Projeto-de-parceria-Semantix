
# 🧵 Otimização de Estoques em Lojas de Roupas

Este repositório contém a análise de dados realizada com o objetivo de otimizar os estoques em lojas de roupas, utilizando dados de vendas, clima e comportamento de busca por roupas online.

---

## 📥 Coleta de Dados

Foram utilizadas três fontes principais:

- **Fontes internas** (`Fontes_Dados_Detalhadas.xlsx`):
  - Dados de estoque, categoria, tamanho, cor, vendas mensais, etc.

- **Vendas Online** (`Compras_Roupas_Online_2024.xlsx`):
  - Índices de busca por termos como “roupas”, “casacos”, “verão”, “inverno”.

- **Clima Histórico** (`Clima_CentroOeste_2024.xlsx`):
  - Temperatura média, mínima, máxima, precipitação e umidade por data.

Todos os arquivos estão disponíveis na pasta `/data`.

---

## 📊 Modelagem e Análise

A análise foi realizada com Python, utilizando as bibliotecas:

- `pandas` para manipulação de dados
- `matplotlib` e `seaborn` para visualização

O código da análise exploratória está disponível em:

📁 [`EDA_Otimizacao_Estoques.ipynb`](EDA_Otimizacao_Estoques.ipynb)

---

## 📈 Conclusões e Insights

- A temperatura tem forte correlação com o consumo de roupas leves (r = 0,71).
- Tamanhos P e M esgotam com frequência, enquanto G e GG apresentam sobras.
- Roupas leves dominam os meses mais quentes; casacos acumulam estoque.
- Regiões como DF e MT lideram em consumo; outras precisam de mix adaptado.
- O modelo atual de previsão não considera sazonalidade e regionalização.

Mais detalhes no relatório em [`Relatorio_EDA_Otimizacao_Estoques.txt`](Relatorio_EDA_Otimizacao_Estoques.txt)

---

## 📊 Visualização Interativa

Um painel foi desenvolvido no Looker Studio com 3 abas:

1. **Tendência de Interesse por Roupas**
2. **Clima no Centro-Oeste**
3. **Correlação Clima x Comportamento de Busca**

🔗 Link para o dashboard: [**INSERIR AQUI O LINK DO LOOKER STUDIO**]

---

## 🗂️ Estrutura do Repositório

```
├── data/
│   ├── compras_roupas_online_2024.csv
│   ├── clima_centro_oeste_2024.csv
│   ├── fontes_dados_detalhadas.csv
│
├── scripts/
│   └── EDA_Otimizacao_Estoques.ipynb
│
├── docs/
│   └── Relatorio_EDA_Otimizacao_Estoques.txt
│
├── README.md
```

---

## 📌 Autor

Vinícius – Projeto de Otimização de Estoques com Dados Reais (2024)
