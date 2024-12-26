# Face Recognition Project

Reconhecimento Facial com Transfer Learning usando Keras e TensorFlow
Este projeto implementa um sistema de reconhecimento facial utilizando Transfer Learning com o modelo pré-treinado MobileNetV2. O objetivo principal é detectar e reconhecer dois indivíduos específicos, Hugh Jackman e Ryan Reynolds, em imagens fornecidas.

Resumo do Projeto
O projeto aproveita a arquitetura MobileNetV2 para realizar reconhecimento facial com alta precisão, reduzindo o tempo de treinamento ao reutilizar os pesos pré-treinados. As etapas incluem a preparação dos dados, treinamento do modelo com camadas personalizadas, e a aplicação do modelo em imagens para detectar e classificar os rostos.

Funcionalidades
Uso de Transfer Learning para economizar tempo e recursos computacionais.
Reconhecimento facial específico para dois indivíduos: Hugh Jackman e Ryan Reynolds.
Pré-processamento de imagens com Data Augmentation para maior robustez.
Visualização gráfica dos resultados com caixas delimitadoras e identificação dos indivíduos.
Tecnologias Utilizadas
Linguagem: Python
Frameworks: TensorFlow, Keras
Modelo Pré-Treinado: MobileNetV2
Bibliotecas Complementares: NumPy, OpenCV, Matplotlib

Estrutura do Projeto:
- Importação das Bibliotecas: Configuração inicial com TensorFlow, Keras, OpenCV e outras bibliotecas essenciais.

- Configuração do Dataset: Divisão em conjuntos de treinamento e validação, com aplicação de Data Augmentation.

- Construção do Modelo: Adaptação do MobileNetV2 com camadas personalizadas para classificação binária.

- Treinamento do Modelo: Ajuste dos pesos para as classes específicas (Hugh Jackman e Ryan Reynolds).

- Teste e Visualização: Aplicação do modelo em imagens de teste e visualização gráfica dos resultados.
