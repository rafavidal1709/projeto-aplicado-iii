# 📑 Sumário do Projeto

## 01. Modelos de Embedding
Neste módulo, abrimos os datasets "crus" e os preparamos para utilização nos modelos. A seguir, calculamos o embedding de cada elemento dos datasets utilizando três modelos propostos:

- **Longformer**  
- **BERT**  
- **BERTimbau**

Para cada modelo, aplicamos dois métodos para gerar os embeddings:
- **Pooler Output**  
- **Output Mean**

[Notebook](https://github.com/rafavidal1709/projeto-aplicado-iii/blob/main/01%20-%20Modelos%20de%20embedding.ipynb)
[Dataset inicial](https://github.com/rafavidal1709/projeto-aplicado-iii/blob/main/01%20-%20dataset_original.json)

## 02. Acurácia dos Modelos
Nesta seção, comparamos os embeddings gerados e testamos dois métodos para encontrar similaridade entre eles:

- **Similaridade de Cossenos**  
- **K-Nearest Neighbors (KNN)**

Inicialmente, utilizamos o dataset "base" para validar as abordagens. Em seguida, aplicamos uma nova abordagem, utilizando o "base" como referência para classificar o dataset "real".

[Notebook](https://github.com/rafavidal1709/projeto-aplicado-iii/blob/main/02%20-%20Acur%C3%A1cia%20dos%20modelos.ipynb)
[Dataset inicial](https://github.com/rafavidal1709/projeto-aplicado-iii/blob/main/02%20-%20dataset_embeddings.json)

## 03. Visualização de Dados e Pipeline
Após concluir os testes de acurácia na seção anterior vamos produzir visualização para os dados:

- **A: [Mapa de calor com as tabelas resultantes](https://github.com/rafavidal1709/projeto-aplicado-iii/blob/main/03A%20-%20Visualiza%C3%A7%C3%A3o%20de%20Dados%20Calor.ipynb)**  
- **B: [Gráfico de barras com média geral e por categoria](https://github.com/rafavidal1709/projeto-aplicado-iii/blob/main/03B%20-%20Visualiza%C3%A7%C3%A3o%20de%20Dados%20Gr%C3%A1fico%20Barras.ipynb)**
- **C: [Pipeline](https://github.com/rafavidal1709/projeto-aplicado-iii/blob/main/03C%20-%20Visualiza%C3%A7%C3%A3o%20da%20Piepeline.ipynb)**

Para A e B utilizaremos o dataset_accuracy que foi gerado ao fim da etapa anterior.

[Dataset](https://github.com/rafavidal1709/projeto-aplicado-iii/blob/main/03%20-%20dataset_accuracy.json)

## 04. Recomendando textos 
