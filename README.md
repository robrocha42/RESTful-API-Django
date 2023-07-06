# RESTful-API-Django
Crie de forma rápida uma API RESTful utilizando Django e Django Rest Framework 

É necessário ter conhecimentos básicos de Django para usar esse tutorial (Criar projeto e criar app)

# Siga o passo a passo para criar a sua API.

1 Crie uma pasta chamada projeto e dentro dela cria uma pasta chamada library

2 Pelo terminal da sua IDE entre na pasta library e crie uma nova venv pelo comando:

 python -m venv venv

3 Ative a sua venv (venv\Scripts\Activate)

4 Dentro da pasta library, instale o Django / Django Rest Framework pelo comando:
 
pip install django djangorestframework

5 Dentro da pasta library, crie um novo projeto do Django pelo comando:

django-admin startproject library .

6 Dentro da pasta library, crie um app chamado books pelo comando:

django-admin startapp books

7 Execute o comando a seguir para fazer o migrate do Django:

python manage.py migrate

8 Copie o código do arquivo settings.py deste repositorio (\library\settings.py) para o seu settings.py, cuidado com a sua secret key.

9 Copie o código do arquivo models.py deste repositorio (\books\models.py) para o seu models.py.

10 Copie a pasta \books\api deste repositorio para o seu \books.

11 Copie o código do arquivo urls.py deste repositorio (\library\urls.py) para o seu urls.py.

12 Execute o comando a seguir para instalar a biblioteca pillow:

pip install pillow

13 Execute o comando a seguir para fazer o make migrations:

python manage.py makemigrations

14 Execute o comando a seguir para fazer o migrate:

python manage.py migrate

15 Execute o comando a seguir para abrir o projeto no seu navegador pela porta 8000 (ative a sua venv se não estiver ativa):

python manage.py runserver

16 Acesse http://localhost:8000/ e utilize a API.

![img.png](img.png)

![img_1.png](img_1.png)

