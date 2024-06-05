# Bank Customer Churn Prediction

![imagem](src/adam-nir-wTO6MWpMrJk-unsplash(1).jpg)

---
## Visão geral do projeto
Nesse projeto, foi feito um modelo de machine learning usando a Regressão Logística para prever se o cliente do banco vai dar churn ou não.

### Estrura do projeto
- `data` pasta que contêm os dados
- `eda` pasta que contêm o notebook da análise exploratória
- `modeling` pasta que contêm o notebbok da modelagem
- `src` pasta que contêm as imagens que são usadas no readme.

---
## Descrição do problema
Um banco quer desenvolver uma solução, utilizando machine learning, para prever se um cliente vai dar churn ou não.

---
## Análise Exploratória

### Sobre o dataset
Este conjunto de dados contém informações sobre os clientes de um banco e o status de churn desses clientes.  

Link dataset: https://www.kaggle.com/datasets/saurabhbadole/bank-customer-churn-prediction-dataset

### Principais insights
![imagem1](src/pergunta1_1.png)
![imagem1_3](src/pergunta1_3.png)
![imagem2_1](src/pergunta2_1.png)
![imagem2_3](src/pergunta2_3.png)
![imagem3_1](src/pergunta3_1.png)
![imagem3_2](src/pergunta3_2.png)
![imagem4_1](src/pergunta4_1.png)

---
## Modelagem
Para construir a solução foram testados os seguintes modelos:
- Logistic Regression
- Decision Tree Classifier
- XGBoost Classifier
- Random Forest Classifier  

Para medir qual modelo teve a melhor performance, foram utilizadas métricas e técnicas, como a validação cruzada.  

O modelo que performou melhor foi a Random Forest Classifier, com os seguintes resultados:

![metrics_rd](src/metrics_rd.png)
![cm_rd](src/cm_rd.png)


---
## Conclusão
O objetivo desse projeto, era desenvolver uma solução usando machine learning para prever se um cliente do banco vai dar churn ou não. O modelo que desempenhou a melhor performance foi o Random Forest Classifier.