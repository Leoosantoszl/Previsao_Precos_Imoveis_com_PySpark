# 🏠 Previsão de Preços de Imóveis com PySpark

Este projeto utiliza **Apache Spark** para construir modelos de regressão com o objetivo de prever o preço de imóveis com base em características como número de quartos, suítes, vagas, localização, entre outros.

---

## 📌 Objetivos

- Ler e tratar dados de imóveis no formato JSON.
- Preparar e limpar os dados para uso em Machine Learning.
- Aplicar modelos de regressão: Linear, Árvore de Decisão e Floresta Aleatória.
- Avaliar os modelos usando métricas como R² e RMSE.
- Realizar validação cruzada (Cross Validation) e ajuste de hiperparâmetros.

---

## 📂 Estrutura do Projeto

- **Tratamento de Dados**: Leitura e limpeza de dados do Google Drive.
- **Análise Exploratória**: Estatísticas básicas e análise de nulos.
- **Engenharia de Variáveis**: Pivotagem de colunas categóricas (`unit` e `zone`).
- **Modelagem**:
  - Regressão Linear
  - Decision Tree Regressor
  - Random Forest Regressor
- **Validação Cruzada**:
  - Grid Search com CrossValidator

---

## 🧪 Modelos e Métricas

| Modelo                  | Dataset | R²      | RMSE     |
|-------------------------|---------|---------|----------|
| Regressão Linear        | Treino  | R² X.XX | RMSE X.XX|
|                         | Teste   | R² X.XX | RMSE X.XX|
| Árvore de Decisão       | Treino  | R² X.XX | RMSE X.XX|
|                         | Teste   | R² X.XX | RMSE X.XX|
| Random Forest           | Treino  | R² X.XX | RMSE X.XX|
|                         | Teste   | R² X.XX | RMSE X.XX|

> Substitua os valores "X.XX" com as métricas reais da execução.

---

## 📦 Bibliotecas Utilizadas

- PySpark (MLlib, SQL, ML)
- Pandas, Seaborn, Matplotlib
- Google Colab (para integração com Google Drive)

---

## ▶️ Como Executar

1. Carregue o projeto em um notebook no **Google Colab**.
2. Instale as dependências:
   ```python
   !pip install pyspark
   ```
3. Monte o Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
4. Execute os blocos sequencialmente.

---

## 👨‍💻 Autor

**Seu Nome Aqui**  
[LinkedIn](https://www.linkedin.com/in/leonardo-oliveira-20083b1a2/) • [GitHub]()

---

## 📍 Observações

- Os dados foram utilizados com fins educacionais.
- O dataset de imóveis está armazenado em JSON no Google Drive.
