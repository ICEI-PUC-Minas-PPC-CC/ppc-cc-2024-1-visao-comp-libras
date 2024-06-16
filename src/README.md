# Instruções de utilização

## Pré-requisitos

Antes de iniciar, certifique-se de ter o Python instalado na sua máquina. Recomendamos a versão 3.12.3 ou superior.

## Configurando o Ambiente

1. Clone o Repositório: Antes de começar, clone o repositório do projeto para o seu local de trabalho usando git clone <URL_DO_REPOSITORIO>.
2. Navegue até a Raiz do Projeto: Abra o terminal e navegue até a pasta raiz do projeto usando o comando cd <nome_da_pasta_do_projeto>.
3. Crie um Ambiente Virtual Python: Um ambiente virtual é uma cópia isolada do interpretador Python e das bibliotecas instaladas, permitindo que você gerencie as dependências do projeto de maneira eficaz. Para criar um ambiente virtual, execute o comando `python -m venv venv`. Isso criará uma nova pasta chamada venv na raiz do projeto, onde as dependências serão armazenadas.
   - No Windows (PowerShell): `. \venv\Scripts\Activate.ps1`
   - No Windows (CMD): `. \venv\Scripts\Activate.bat`
   - No Linux/MacOS: `source venv/bin/activate`
4. Instale as Dependências Necessárias: Com o ambiente virtual ativado, instale as dependências do projeto listadas no arquivo requirements.txt executando `pip install -r requirements.txt`. Isso garantirá que todas as bibliotecas necessárias para o projeto estejam disponíveis no ambiente virtual.
5. Execute o Projeto: Agora que o ambiente virtual está configurado e as dependências instaladas, você pode executar o projeto. Dentro do ambiente virtual, execute `python main.py` para iniciar o projeto. Lembre-se de que você precisa ter uma câmera disponível e acessível para que o projeto funcione corretamente.

## Histórico de versões

### [0.1.0] - 16/06/2024

#### Adicionado

- Implementação inicial do sistema de reconhecimento de gestos utilizando OpenCV, MediaPipe, NumPy e TensorFlow.
- Código para captura de vídeo da câmera, processamento dos frames com MediaPipe Hands para detectar mãos, e classificação das poses das mãos usando um modelo treinado.
- Função predict para fazer predições com o modelo TensorFlow.
- Lógica para extrair pontos de referência das mãos detectadas, delimitar áreas de interesse e normalizar imagens para processamento pelo modelo.
- Interface gráfica para exibir resultados em tempo real, incluindo a palavra reconhecida à medida que gestos são realizados.
- Controle de entrada através de teclas para manipulação de palavras (adicionar espaço, remover último caractere, sair do programa).
