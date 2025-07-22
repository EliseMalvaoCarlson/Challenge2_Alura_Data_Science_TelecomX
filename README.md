<p align="center">
  <img src="challenge2/challenge_2.png" alt="Imagem Challenge 2" width="600"/>
</p>



# 📞 TelecomX_BR – Análise de Evasão de Clientes

Este projeto tem como objetivo analisar o comportamento de clientes de uma empresa de telecomunicações e desenvolver estratégias para reduzir a evasão (churn). Utilizamos técnicas de análise exploratória, visualização de dados e modelos preditivos para extrair insights valiosos e propor soluções práticas.

---

## 🧠 Propósito

- Identificar padrões de cancelamento de clientes.
- Explorar variáveis que influenciam o churn.
- Construir modelos preditivos para antecipar evasão.
- Propor estratégias de retenção com base em dados reais.

---

## 📁 Estrutura do Projeto

```text
TelecomX_BR/
│
├── TelecomX_BR.ipynb          # Notebook principal com todo o pipeline de análise
├── data/                      # Pasta com o dataset original e transformado
│   └── telecom_customers.csv
├── images/                    # Gráficos gerados durante a análise
├── README.md                  # Este arquivo
└── requirements.txt           # Lista de dependências
```

---

## ⚙️ Instalação e Execução

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/TelecomX_BR.git
cd TelecomX_BR
```

### 2. Instale as dependências

Recomenda-se o uso de um ambiente virtual:

```bash
pip install -r requirements.txt
```

Ou, se estiver usando o Google Colab, basta abrir o notebook e executar as células.

---

## 📊 Principais Etapas do Projeto

### 🔍 Extração
- Leitura do dataset `telecom_customers.csv`.

### 🧼 Transformação
- Tratamento de valores nulos e inconsistências.
- Padronização de variáveis categóricas e numéricas.

### 📈 Análise
- Visualizações com gráficos de barras, boxplots e histogramas.
- Identificação de variáveis correlacionadas com churn.

### 🤖 Modelagem
- Sugestão de modelos como Random Forest, XGBoost e Regressão Logística.
- Preparação de dados para machine learning.

### 📋 Relatório Final
- Insights estratégicos para retenção de clientes.
- Propostas de campanhas e melhorias nos serviços.

---

## 🛠️ Tecnologias Utilizadas

- Python 3.10+
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
- Google Colab

---

## 🚨 Possíveis Problemas

- **Dados faltantes**: Algumas colunas podem conter valores nulos.
- **Desequilíbrio de classes**: A proporção de churn pode afetar a performance dos modelos.
- **Overfitting**: Modelos muito complexos podem se ajustar demais aos dados de treino.

---

## 🤝 Contribuições

Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias, correções ou novas ideias!

---

## 📬 Contato

Projeto desenvolvido por Elise como parte de um desafio de análise de dados.  
Para dúvidas ou sugestões, entre em contato via [LinkedIn](https://www.linkedin.com/)

---
