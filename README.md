# Trabalho Aprendizado De Maquina Para Series Temporais
Instituto de Ciências Matemáticas e da Computação (USP) -- São Carlos, SP -- Brazil
Trabalho avaliativo para a matéria e SCC5977 - Aprendizado de máquina para Séries Temporais (2024)

Autores: Jorge Dario Soares Angulo, Rafaella de Oliveira e Tiago Chaves Bezerra Rocha
Email: jorge.angulo@usp.br, rafaella_oliveira@usp.br, tiagocbr@usp.br

# Análise de Séries Temporais do Clima Espacial

Este repositório contém o código e os recursos utilizados para o projeto de *Análise de Séries Temporais do Clima Espacial. O trabalho foi desenvolvido na disciplina de mestrado **Aprendizado de Máquina para Séries Temporais* e foca na identificação de padrões e eventos críticos, como tempestades geomagnéticas.

## Descrição do Projeto

O objetivo é analisar dados do clima espacial (como o índice Kp) para identificar padrões recorrentes, anomalias e eventos críticos utilizando técnicas de aprendizado de máquina.

## Estrutura do Pipeline

1. *Segmentação Semântica*: Divisão dos dados em fases, como "Período Calmo", "Pré-Tempestade" e "Tempestade".
2. *Detecção de Anomalias*: Uso do Isolation Forest para detectar comportamentos atípicos.
3. *Descoberta de Motifs*: Identificação de padrões recorrentes usando find_peaks() e Matrix Profile.
4. *Busca por Similaridade Temporal*: Utilização do DTW (Dynamic Time Warping) para comparar eventos históricos.
