# Análise de Sentimento e Predição no Varejo (MGLU3)

Este projeto explora a relação entre o sentimento das notícias financeiras e a variação de preço das ações da Magazine Luiza. 

### 🛠 Tecnologias e Ferramentas
- **Linguagem:** Python
- **Data Warehouse:** Google BigQuery
- **NLP (Processamento de Linguagem Natural):** Modelo FinBERT (Hugging Face)
- **Machine Learning:** XGBoost Regression
- **Dados:** NewsAPI e yFinance

### 📈 O que o projeto faz?
1. **Pipeline de Dados:** Extrai notícias e cotações históricas automaticamente.
2. **Engenharia de Dados:** Armazena e organiza os dados no BigQuery.
3. **Sentimento Financeiro:** Converte textos em valores numéricos usando IA especializada em finanças.
4. **Modelagem Preditiva:** Utiliza o sentimento acumulado do dia anterior para tentar prever o retorno da ação no dia seguinte (lógica de *Time Series Lag*).

### 🔍 Conclusões
O projeto demonstra como lidar com o "ruído" do mercado financeiro e a importância de uma arquitetura de dados robusta em nuvem para escalar análises de Ciência de Dados.