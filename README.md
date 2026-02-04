 Transfer Learning com Deep Learning em Python

Descrição do Projeto
Este projeto tem como objetivo aplicar o método de **Transfer Learning** em uma rede de **Deep Learning**, utilizando a linguagem **Python** e as bibliotecas **TensorFlow/Keras**, no ambiente **Google Colab**.

O modelo foi treinado para resolver um problema de **classificação de imagens**, identificando duas classes: **gatos e cachorros**.

 Objetivos de Aprendizagem
 Aplicar Transfer Learning em um ambiente prático  
 Utilizar modelos pré-treinados  
 Construir e treinar uma rede neural profunda  
 Documentar um projeto técnico de forma clara  
 Utilizar o GitHub para versionamento e compartilhamento  

 Dataset Utilizado
Foi utilizado o dataset **Cats vs Dogs**, disponibilizado via **TensorFlow Datasets**, contendo imagens divididas em duas classes:

 🐱 Gatos  
 🐶 Cachorros  

O dataset foi automaticamente dividido em:
 80% para treinamento  
 20% para validação  

>Observação: O uso do TensorFlow Datasets garante compatibilidade com o Google Colab e reprodutibilidade do experimento.

 Modelo Utilizado (Transfer Learning)
 Arquitetura: **MobileNetV2**
 Pesos pré-treinados: **ImageNet**
 Camadas convolucionais congeladas
 Camadas densas adicionadas para classificação binária

Essa abordagem permite reutilizar o conhecimento previamente aprendido pelo modelo em um novo problema.

 Tecnologias Utilizadas
Python 
 TensorFlow / Keras  
 TensorFlow Datasets  
 Google Colab  
 GitHub  

O modelo apresentou boa capacidade de generalização, com evolução positiva da acurácia e redução da função de perda ao longo do treinamento.

Gráficos de acurácia e loss podem ser visualizados durante a execução do notebook.

## 🚀 Como Executar o Projeto
1. Abrir o notebook no Google Colab  
2. Ativar GPU (Ambiente de execução → Alterar tipo de ambiente → GPU)  
3. Executar as células sequencialmente  




---

## 📎 Autor
Projeto desenvolvido como parte de um desafio de Deep Learning e Transfer Learning na plataforma **DIO**.
