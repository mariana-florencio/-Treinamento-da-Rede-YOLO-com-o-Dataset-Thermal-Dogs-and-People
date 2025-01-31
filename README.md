# Treinamento da Rede YOLO com o Dataset Thermal Dogs and People

Este repositório contém um código para treinar um modelo YOLOv8 utilizando o dataset Thermal Dogs and People, que contém imagens térmicas de cães e pessoas. O modelo é treinado no Google Colab e depois utilizado para detecção em imagens enviadas pelo usuário.

## 🤖 O que é YOLO?

YOLO (You Only Look Once) é uma família de modelos de detecção de objetos que processam imagens em tempo real. Diferente de abordagens tradicionais, que dividem a imagem em regiões e analisam cada uma separadamente, o YOLO trata a imagem como um todo, tornando a inferência muito mais rápida.

O YOLOv8 é a versão mais recente da arquitetura, trazendo melhorias em precisão e velocidade. Ele pode ser utilizado para diferentes tarefas, como:
* Detecção de objetos
* Segmentação de instâncias
* Classificação de imagens

## 📌 Requisitos
 * Conexão com GPU ativada no Colab (Ambiente de execução > Alterar o tipo de ambiente de execução > GPU)

## 🚀 Instalação das Dependências
Execute o seguinte comando para instalar as bibliotecas necessárias:

![image](https://github.com/user-attachments/assets/fce90f31-06ba-411a-9643-2eb10c3eeae0)

## 📂 Clonando o Repositório e Acessando os Dados
O código clona o repositório contendo o dataset e muda o diretório para acessá-lo:
![image](https://github.com/user-attachments/assets/977876cb-801d-453c-8bb4-45b4c4a3036d)

## 🎯 Treinamento do Modelo YOLOv8
O modelo YOLOv8n (versão nano, mais leve) é carregado e treinado com 50 épocas, processando imagens de tamanho 640x640 em lotes de 16.
O dataset é definido no arquivo data.yaml, especifica as classes e caminhos dos dados.
![image](https://github.com/user-attachments/assets/a36594be-e222-4467-8df8-78cd2fba9014)

## 📸 Testando o Modelo com uma Imagem
Após o treinamento, o modelo pode ser testado em imagens enviadas pelo usuário:
![image](https://github.com/user-attachments/assets/222582c2-7999-4d51-9d95-a025bd9521ce)

## 📊 Resultados
O modelo destacará cães e pessoas presentes na imagem térmica.
As predições são feitas com base no dataset Thermal Dogs and People.

![download](https://github.com/user-attachments/assets/e42594f5-4460-467a-97bb-2d4003e0dc89)

![download](https://github.com/user-attachments/assets/89207abd-2838-4172-9935-46851648c2bb)


### O dataset Thermal Dogs and People está sob Public Domain, o que significa que pode ser utilizado livremente para qualquer finalidade.
