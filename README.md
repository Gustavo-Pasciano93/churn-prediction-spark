# Churn Prediction with PySpark


## 📋 Descrição do Projeto

Este projeto utiliza **PySpark** para analisar e prever o churn de clientes em uma empresa de telecomunicações. O pipeline inclui:

- **Leitura e processamento de dados**: Tratamento e transformação de colunas.
- **Análise exploratória de dados (EDA)**: Insights iniciais sobre o dataset.
- **Criação de modelo de Machine Learning**: Regressão logística para classificação de churn.
- **Avaliação do modelo**: Métricas como acurácia, precisão e matriz de confusão.

---

## 🚀 Tecnologias Utilizadas

- **Python 3.8+**
- **PySpark**
- **Google Colab**
- **Bibliotecas adicionais**:
  - `pyspark.sql`
  - `pyspark.ml`

---

## 📂 Estrutura do Projeto


├── dados_clientes.csv        # Dataset utilizado no projeto
├── README.md                 # Documentação do projeto
└── churn_prediction.ipynb    # Código completo em Jupyter Notebook


## 📊 Passos do Pipeline

1. ### Carregamento do Dataset
Leitura do arquivo dados_clientes.csv com schema inferido automaticamente.

2. ### Transformação de Dados
Conversão de colunas categóricas para valores binários.
Criação de vetores para alimentar o modelo de Machine Learning.

3. ### Modelagem
Treinamento de uma regressão logística para classificar clientes como churn ou não churn.

4. ### Avaliação do Modelo
Acurácia: %f
Precisão, Recall e F1 Score calculados.
Matriz de confusão exibida para validação.

## 📈 Resultados Obtidos

Insights iniciais: Distribuição de clientes por churn, tipo de contrato, e método de pagamento.
Modelo de Machine Learning: Acurácia acima de X%.
Matriz de Confusão: Desempenho do modelo detalhado
