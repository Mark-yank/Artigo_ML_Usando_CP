## Conformal Prediction aplicado à Classificação em Machine Learning

Este repositório contém o código-fonte e o artigo científico desenvolvidos para o estudo da aplicação da técnica de Conformal Prediction na quantificação de incerteza em modelos de classificação de Machine Learning.
O trabalho avalia o comportamento dos modelos Regressão Logística, K-Nearest Neighbors (KNN) e Support Vector Machine (SVM) sob diferentes níveis de confiança, analisando métricas como cobertura e tamanho médio dos conjuntos resposta.

## Artigo

O artigo completo está disponível neste repositório.

No artigo são apresentados:
Fundamentação teórica dos modelos utilizados
Formulação do Conformal Prediction
Metodologia experimental
Análise dos resultados
Discussão sobre confiabilidade e incerteza em dados médicos

## Modelos Utilizados

Os seguintes modelos de classificação foram avaliados:
Regressão Logística

K-Nearest Neighbors (KNN) com configuração discreta com 𝑘=5

Support Vector Machine (SVM)
Kernel RBF (Radial Basis Function)

A técnica de Conformal Prediction foi aplicada a todos os modelos para gerar conjuntos resposta com garantia estatística de cobertura.

## Análises Realizadas

O projeto inclui:
Avaliação da cobertura em função do nível de confiança (1−𝛼)
Análise do tamanho médio dos conjuntos resposta
Distribuição dos scores de não conformidade
Comparação entre modelos sob diferentes níveis de confiança

## Contexto de Aplicação

Este trabalho foi desenvolvido com foco em dados médicos, onde a quantificação de incerteza é crucial para evitar decisões incorretas.
A técnica de Conformal Prediction se mostrou especialmente relevante por fornecer garantias estatísticas de confiabilidade, independentemente do modelo utilizado.

## Autores
João Vinicius Martins
📧 joao2014viniciusm@gmail.com

Marcos Vinicius Carvalho de Oliveira
📧 markyankg@gmail.com

## Referências

As principais referências utilizadas estão listadas no artigo e incluem trabalhos clássicos e recentes sobre Conformal Prediction e Machine Learning.

## Licença

Este projeto é disponibilizado apenas para fins acadêmicos e educacionais.
Este projeto é
disponibilizado apenas para fins acadêmicos e educacionais.
