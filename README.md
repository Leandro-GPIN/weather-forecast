# Previsão do tempo usando aprendizagem de maquina.

Algoritimo de aprendizagem de maquina com dados publicos para prever a possibilidade de chuva
 
## Dataset
Dataset : https://tempo.inmet.gov.br/ 

Produto : Tabela de dados das estações

Tipo    : Convencionais

Estação : Porto Alegre (83967)

Periodo : 01/01/2000 a 28/03/2021

## Variaveis
Foi analisado a correlação das seguintes variaveis: 
 
* Dia
* Mês
* Ano
* Hora (UTC)
* Temp. [Hora] (C)
* Umi. (%)
* Pressao (hPa)
* Vel. Vento (m/s)
* Dir. Vento (m/s)
* Nebulosidade (Decimos)

## Classificação:
Transofrmamos a variavel chuva que mostrava a quantidade de chuva em mm para uma váriavel de classificação informando se choveu ou não.

* Chuva [Diaria] (mm)

## Treinamento:
Foi divido o dataset em 75% para treino e 25% para teste. Os dados foram escolhidos de forma aleatória para cada grupo. 

## Resultados:
Foi escolhido 8 modelos de aprendizagem de maquina para avaliar.

* 0.9220593493028244 - AdaBoost
* 0.9183053271362174 - RBF SVM
* 0.9109760457633178 - Decision Tree
* 0.910439756882374 - Neural Net
* 0.9027529495888452 - Nearest Neighbors
* 0.8707543796925277 - Linear SVM
* 0.8707543796925277 - Random Forest
* 0.8022881658920272 - Naive Bayes

## Conclusão:
O melhor modelo foi o AdaBosst com 92,20% de acertos. 



