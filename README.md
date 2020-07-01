# Curso de Introdução ao Django 2: Modelo, Rotas e Views

Código desenvolvido no curso [Alura](https://cursos.alura.com.br/course/fundamentos-django-2).

## Requisitos 
- Python
- pip (`pip install -r requirements.txt`)

## Configurações do Banco
- Postgresl
Arquivo settings.py:
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'postgresql',
        'USER': 'postgresql',
        'PASSWORD': 'postgresql',
        'HOST': 'localhost'
    }
} 

## Subindo servidor
`python .\manage.py runserver`

### Anotações:
Criar um ambiente virtual
`python -m venv ./venv`

Instalar Django (ven)
`activate.bat`

Help
`python .\manage.py help`