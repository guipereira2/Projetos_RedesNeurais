# Projetos da disciplina de introdução a redes neurais (UNIFESP)

### Atualizar read me

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
Neste projeto, foi aplicada uma rede neural não supervisionada utilizando a abordagem Self-Organizing Map (SOM). O foco principal foi explorar a detecção de padrões em dois datasets distintos: imagens médicas de raios-X de tórax para classificação de pneumonia e dígitos manuscritos representados por matrizes de pixels. A rede foi utilizada para identificar clusters, detectar outliers e avaliar a homogeneidade dos agrupamentos. Além disso, foram realizadas análises sobre como variações nos parâmetros do modelo impactam a qualidade dos padrões detectados. Este projeto destaca a aplicabilidade do modelo SOM em cenários de aprendizado não supervisionado.

### Objetivos Específicos

1. **Seleção e preparação dos datasets:**
   - Dois datasets foram utilizados:
     - **Imagens médicas de raios-X de tórax:** Este conjunto de dados foi explorado para identificar padrões relacionados à classificação de pneumonia.
     - **Dígitos manuscritos:** Representados por matrizes de pixels, este dataset foi utilizado para explorar a capacidade do modelo SOM em agrupar representações visuais.
   - Antes da aplicação do modelo, os dados passaram por etapas de limpeza e preparação para garantir consistência e qualidade.

2. **Aplicação da rede neural SOM:**
   - Foi implementado um modelo SOM para realizar aprendizado não supervisionado nos dois datasets.
   - A rede foi configurada para identificar clusters relevantes, detectar outliers e mapear padrões nos dados.

3. **Análise dos padrões detectados:**
   - Os agrupamentos gerados pela rede foram avaliados quanto à sua homogeneidade e relevância.
   - Foram identificados clusters que representam grupos similares dentro dos dados, além da detecção de possíveis outliers.

4. **Exploração de variações nos parâmetros do modelo:**
   - Diferentes configurações do modelo SOM foram testadas para avaliar seu impacto na qualidade dos resultados:
     - **Tamanho do grid:** A estrutura da grade foi ajustada para observar como o número de células influencia os agrupamentos.
     - **Número de neurônios:** O tamanho da rede foi variado para analisar sua capacidade de generalização.
     - **Taxa de aprendizado:** Diferentes valores foram experimentados para verificar a velocidade e estabilidade do treinamento.
     - **Sigma (função vizinhança):** O parâmetro sigma foi ajustado para explorar como ele afeta a interação entre os neurônios durante o treinamento.

## Projeto 3: 
Neste projeto foram treinados modelos Variational Autoencoders (VAEs) utilizando os datasets rotulados MNIST e Fashion MNIST. A estratégia envolveu ajustar a topologia do modelo com base na função de custo, visando não apenas uma boa reconstrução das imagens, mas também uma análise detalhada do espaço latente. A exploração desse espaço possibilitou avaliar a formação de clusters, a separação de rótulos e a variância explicada, além de investigar se os rótulos das amostras podem enviesar a distribuição dos dados.

### Objetivos Específicos

1. **Preparação dos Dados:**  
   - Utilizar os datasets MNIST e Fashion MNIST, garantindo que os dados sejam limpos e padronizados para o treinamento dos modelos.

2. **Treinamento e Ajuste dos Modelos VAE:**  
   - Configurar e treinar os VAEs, ajustando a topologia do modelo com base na função de custo.  
   - Refinar a arquitetura (como número de camadas e dimensões do espaço latente) para otimizar a reconstrução das imagens.

3. **Exploração e Análise do Espaço Latente:**  
   - Avaliar a formação de clusters e a separação dos rótulos dos dados dentro do espaço latente.  
   - Calcular a variância explicada pelos componentes latentes.  
   - Investigar a possibilidade de os rótulos das amostras influenciarem (ou enviesarem) a organização do espaço latente.

4. **Visualização e Interpretação:**  
   - Visualizar os padrões obtidos no espaço latente para facilitar a interpretação dos resultados.  
   - Comparar as representações geradas pelos modelos, destacando a eficácia dos VAEs na reconstrução de imagens e na extração de características latentes.