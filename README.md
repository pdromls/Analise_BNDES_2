# Projeto de Análise de Dados - Operações de Exportação pré Embarque do BNDES

Projeto de análise de dados em um conjunto de dados de operações de exportações pré embarque do Banco Nacional de Desenvolvimento Econômico e Social (BNDES), obtido através do Portal de [Dados Abertos](https://dadosabertos.bndes.gov.br/).

O objetivo principal deste projeto é estudar e aprender a estruturar um projeto como esse.

---

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
.
├── data/
│   ├── raw/
│   │   └── operacoes-exportacao-operacoes-de-exportacao-pre-embarque.csv   # Dados brutos baixados do portal
│   │   └── dicionario-de-dados-operacoes-de-exportacao-pre-embarque.pdf
│   └── processed/
│       └── op-exp-pre-embarque.parquet # Dados limpos e tratados
├── notebooks/
│   └── 01_BNDES_DA.ipynb  # Observando e Tratando a base
│   └── 02_BNDES_EDA.ipynb  # Explorando e Conhecendo a base
│   └── 03_BNDES_RELATORIO.ipynb  # Relátorio de Insights
├── .gitignore
├── README.md
└── requirements.txt
```

---

## Ferramentas e Bibliotecas

Este projeto foi desenvolvido em Python e utiliza as seguintes bibliotecas principais:

* **Pandas:** Para manipulação e tratamento dos dados.
* **Matplotlib & Seaborn:** Para visualização e criação de gráficos.
* **Jupyter Notebook:** Como ambiente de desenvolvimento interativo.

---

## Como Executar o Projeto

Para executar a análise, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone <url-do-seu-repositorio>
    cd <nome-do-repositorio>
    ```

2.  **Crie e ative um ambiente virtual:**
    ```bash
    python -m venv venv
    # Windows
    .\venv\Scripts\activate
    # macOS / Linux
    source venv/bin/activate
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute o Jupyter Notebook:**
    Abra o notebook os notebooks e execute as células para reproduzir a análise.

---

## Etapas da Análise

Análise dos Dados ✅
Análise Exploratória de Dados (EDA) ✅
Elaboração de Insights ✅
