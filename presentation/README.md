# Apresentação da Solução

## Desenvolvimento do Projeto

### Objetivo

O objetivo deste projeto é desenvolver um sistema robusto de reconhecimento de libras, utilizando tecnologias avançadas de visão computacional e aprendizado de máquina. A solução visa facilitar a comunicação e controle de dispositivos através de gestos, com aplicações potenciais em diversas áreas, incluindo educação, saúde e lazer.

### Tecnologias Utilizadas

- **Python**: Linguagem de programação central para o desenvolvimento.
- **OpenCV**: Biblioteca para processamento de imagens e vídeos.
- **MediaPipe**: Framework para detecção de mãos e pose em tempo real.
- **TensorFlow**: Plataforma para treinamento e implantação de modelos de aprendizado profundo.
- **NumPy**: Biblioteca para manipulação de arrays e análise numérica.

### Processo de Desenvolvimento

O desenvolvimento do projeto seguiu várias etapas críticas, incluindo:

1. **Coleta e Pré-processamento de Dados**: Análise de vídeos e imagens para coletar dados de gestos.
2. **Treinamento do Modelo**: Uso da plataforma Teachable Machine, para treinamento de um modelo de classificação de gestos. Este modelo foi exportado no formato SavedModel.
3. **Integração com MediaPipe**: Implementação da detecção de mãos em tempo real para identificar gestos.
4. **Desenvolvimento da Interface Gráfica**: Criação de uma interface gráfica simples para exibir resultados e feedback ao usuário.

## Solução Desenvolvida

A solução final é um sistema capaz de capturar vídeo da câmera, processar os frames para detectar gestos de mãos, e classificar esses gestos em categorias predefinidas. A interface gráfica exibe a palavra reconhecida à medida que gestos são realizados, permitindo ao usuário interagir com o sistema de forma intuitiva.

### Vídeo Demonstrativo

[Assistir ao vídeo](https://www.youtube.com/watch?v=qHqyDe4WWoA){:target="_blank"}
