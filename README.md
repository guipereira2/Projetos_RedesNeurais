# Projetos da disciplina de introdução a redes neurais (UNIFESP)

## Projeto 1: 
Este projeto consiste na implementação de uma rede neural do tipo MLP (Multi-Layer Perceptron) em Python, sem o uso de bibliotecas próprias para aprendizado de máquina, como PyTorch ou TensorFlow. Após a implementação, diferentes modelos foram desenvolvidos para resolver problemas de classificação e regressão, com análise e ajustes de hiperparâmetros.

### Objetivos 
1. Implementar uma rede neural MLP:
   - Construir a arquitetura base em Python, do zero.
   - Implementar as funções de ativação (e.g., Sigmoid, Softmax).
   - Calcular gradientes usando backpropagation.
   - Incluir funcionalidades como momento e taxa de aprendizado.

2. Desenvolver modelos:
   - Um modelo para classificação de dados.
   - Um modelo para regressão. 

3. Avaliar hiperparâmetros
   - Variar o número de camadas ocultas e neurônios por camada.
   - Testar diferentes taxas de aprendizados(eta) e fatores de momentum

## Projeto 2: 
Neste projeto, foi aplicada uma rede neural não supervisionada utilizando a abordagem Growing Neural Gas (GNG), com o objetivo de explorar e identificar padrões em diferentes conjuntos de dados.

### Objetivos 
1. Selecionar datasets: 
   - Fazer a limpeza e preparação dos dados.

2. Aplicar a rede neural: 
   - Implementar um modelo não supervisionado(GNG) nos datasets. 

3. Avaliar os padrões detectados: 
   - Identificar clusters, outliers e padrões nos dados. 
   - Avaliar os agrupamentos obtidos.

4. Variar os parâmetros do modelo: 
   - Testar diferentes configurações e seus impactos: 
      - Estrutura do grid 
      - Taxas de aprendizado 
      - Número de neurônios 