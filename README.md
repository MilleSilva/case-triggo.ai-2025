# 💻 Case Técnico – Trainee triggo.ai 2025  
## Análise de Dados do E-commerce Brasileiro (Olist Dataset)

Este repositório contém a solução desenvolvida para o Teste Técnico do Programa Trainee triggo.ai de Excelência em Engenharia de Dados e DataOps 2025.

## 📌 Objetivo

Projeto desenvolvido como parte do processo seletivo do Programa Trainee 2025 da triggo.ai, com foco em Engenharia de Dados: Analisar o dataset e extrair insights estratégicos para resolver desafios práticos de dados, como limpeza, visualização, modelagem e segmentação, visando apoiar decisões de negócios em uma empresa de e-commerce.

## 🧠 O que foi desenvolvido

O notebook contém as seguintes etapas:

### 1. **Preparação dos Dados**
- Carregamento dos arquivos CSV do dataset
- Limpeza dos dados (remoção de valores nulos, duplicados)
- Normalização e padronização de colunas
- Modelagem relacional entre as tabelas

### 2. **Análise Exploratória de Dados (EDA)**
- Volume de pedidos por mês e identificação de sazonalidade
- Análise do tempo de entrega dos pedidos
- Relação entre valor do frete e distância
- Categorias mais lucrativas
- Estados com maior valor médio de pedido

### 3. **Soluções de Negócio**
- **Análise de Retenção:** Identificação de clientes recorrentes
- **Predição de Atrasos:** Criação de um modelo de machine learning para prever atrasos na entrega
- **Segmentação de Clientes:** Aplicação de clustering para identificar perfis de clientes
- **Análise de Satisfação:** Estudo dos fatores que impactam as avaliações dos clientes

### 4. **Dashboards e Visualizações**
- Evolução das vendas com filtros interativos
- Mapa de calor das vendas por estado
- Gráficos de relação entre tempo de entrega e nota do cliente
- Painel de desempenho dos vendedores

## 📊 Dados

Você pode baixar os arquivos CSV utilizados neste projeto no seguinte link:

🔗 [Brazilian E-commerce Public Dataset by Olist (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

> Após o download, crie uma pasta chamada `data/` no mesmo diretório do notebook e mova todos os arquivos `.csv` para lá.

## 📦 Tecnologias e Ferramentas Utilizadas

- Python (Pandas, NumPy, Seaborn, Matplotlib, Plotly)
- SQLite e SQL (via Pandas)
- Machine Learning (Scikit-learn)
- Jupyter Notebook / Google Colab

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/case-trainee-triggo-ai-2025.git
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Baixe os dados do Kaggle e coloque os arquivos .csv na pasta data/

4. Execute o notebook Case_técnico_Trainee_triggo_ai.ipynb localmente ou via Google Colab.

## 📁 Estrutura do Repositório

├── Case_técnico_Trainee_triggo_ai.ipynb

├── README.md

├── requirements.txt

## 📝 Conclusões
Foram identificados padrões relevantes de comportamento de clientes, sazonalidade nas vendas, além de categorias e estados com maior rentabilidade. O modelo preditivo de atraso e a segmentação de clientes oferecem suporte a ações estratégicas e personalizadas no e-commerce.
