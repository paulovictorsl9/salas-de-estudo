Teste Studybuddy

Clonando o repositório:
--> Use o comando abaixo:
git clone https://github.com/divanov11/StudyBud.git

--> Mova para o diretório/pasta do projeto, e acesse a pasta pelo terminal
ex: cd StudyBud

--> Criar ambiente virtual, para isso:

# Instale o virtualenv com o comando abaixo:
pip install virtualenv

# Depois criamos o ambiente virtual com o comando:
virtualenv envname

--> Ative o ambiente virtual com o comando:
envname\scripts\activate

--> Instale os requerimentos com o comando:
pip install -r requirements.txt

Inicializando o app
--> Para rodar o app usaremos o comando:
python manage.py runserver

O serivdor será iniciado no endereço http://127.0.0.1:8000/