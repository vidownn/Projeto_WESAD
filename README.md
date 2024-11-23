# Projeto WESAD
Projeto de Inteligência Artificial, onde foi analisado o dataset WESAD (Wearable Stress and Affect Detection), os dados foram ajustados e depois classificados utilizando um algoritmo de aprendizagem supervisionada. 

A base de dados utilizada foi a base WESAD (Wearable Stress and Affect Detection) que contém os dados de um estudo realizado com 15 pacientes, os dados utilizados para esse trabalho estão presentes nos arquivos .pkl. Nesse arquivo temos duas classificações diferentes, chest e wrist, que corresponde a localização do dispositivo wearable, peito e pulso, respectivamente.

Para esse trabalho só iremos utilizar os dados da classificação wrist, sendo eles o EDA, BVP e TEMP, que também representam os nossos dados de entrada. Além disso, também utilizaremos o sinal label, que consiste no valor do nível de estresse
indicado pelo dispositivo, como dado de saída.

A análise é dividida entre personalizado (único paciente) e populacional (análise de todos os pacientes). A classificação é realizada utilizando o algoritmo k-nn (K - Nearest Neighbors) utilizando dois agrupamentos de dados diferentes. No primeiro caso utilizando todas os dados fornecidos (EDA, BVP e TEMP) para realizar a predição do label de stress, já no segundo caso realizamos a predição de maneira individual para cada um desses dados. 
