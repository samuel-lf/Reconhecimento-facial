# Reconhecimento facial :bulb:
Sistema de reconhecimento facial utilizando OpenCV e Python. Esse sistema é capaz de detectar a face do usuário, efetuar a captura da imagem e armazena-lá em um diretório local, realizar o treinamento do classificar para o reconhecimento e por fim reconhecer a imagem do usuário cadastrado.

#Instalação

- Instale o Python 3.6.3
- Acesse AppData\Local\Programs\Python\Python36-32\Scripts 
    - Instale a biblioteca numpy (pip install numpy)
    - Acesse: https://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv
    - Procure pela distribuição opencv_python-3.3.0+contrib-cp36-cp36m-win_amd64.whl *Observação: Essa distribuição vária de acordo com sua versão do Python (32 ou 64 bits)
    - Adicione esse arquivo no diretório acima
    - Instale a biblioteca OpenCV (pip install "opencv_python-3.3.0+contrib-cp36-cp36m-win_amd64.whl")
- Instale o Pycharm
    - Acesse as configurações
    - Project: (Nome do projeto), Project Interpreter
    - Adicione os interpretadores: numpy, opencv-python, pip

# Execução 

#### Módulo de captura (captura.py)

Esse módulo é responsável por realizar a captura da imagem de sua webcam, ao iniciar o modulo ele irá soliciar um id pela qual a pessoa será identificada e após isso será aberta a janela para captura das imagens. A captura das imagens pode ser efetuada apertando a tecla 'Q'.

- Repare que haverá uma pasta vazia com o nome de "fotos", essa pasta irá conter todas as imagens capturada pelo modo

#### Módulo de treinamento (treinamento.py)

Esse módulo é responsável por realizar o treinamento das imagens coletadas.

#### Módulo de reconhecimento(métrica) (reconhecimento.py)

Os módulos de reconhecimento realizam o reconhecimento facial de acordo com o classificador criado no módulo anterior. Lembrando de cada reconhecedor tem seu arquivo classificador.

# Extra

Os módulos Yale, funcionam da mesma forma, porém, eles possuem algumas caracteristicas diferenciadas com relações ao outros módulos. Vale a pena a pesquisa :smile:

# Contribuições

Fique a vontade para enviar suas melhorias, seja sobre o código em sí ou até mesmo desse README :smile:









    
