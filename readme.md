# MVP 1 - Desenvolvimento Full Stack Básico

![PUC-Rio](https://avatars.githubusercontent.com/u/116962418)

## PUC-Rio Digital - Desenvolvimento em Full Stack (2023)

Coordenação: [Marcos Kalinowski](kalinowski@inf.puc-rio.br).

Professores: [Fernando Correia](fernando.correia.jr@gmail.com), [Dieinison Braga](dieinisonbraga@gmail.com) e [Marisa Silva](https://github.com/marisa-ec).

Aluno: [Gabriel dos Santos Reis](https://github.com/gaelsreis).

---

## Back-End

> *O Produto Mínimo Viável / Minimum Viable Product (MVP) envolve a criação de uma Interface de Processamento de Aplicações / Application Programming Interface (API) com três rotas: buscar (get), inserir (post) e excluir (delete) - no estilo Criar, Ler, Atualizar e Remover / Create, Read, Update and Delete (CRUD) - desenvolvida na linguagem Python, documentada com Swagger e utilizando o banco de dados SQLite.*

---

### Instruções

[Instalando](https://packaging.python.org/pt_BR/latest/guides/installing-using-pip-and-virtual-environments/) pacotes usando pip e ambientes virtuais para Unix/macOS ou Windows. Segue abaixo comandos para Windows:

~~~PowerShell
## Garantir que o pip está atualizado
py -m pip install --upgrade pip

## Verificar versão instalada
py -m pip --version

## Instalar virtualenv usando pip
py -m pip install --user virtualenv

## Criar um ambiente virtual (antes vá até o diretório do seu projeto)
py -m venv env

## Ativar o ambiente virtual
.\env\Scripts\activate

## Instalar dependências/bibliotecas
py -m pip install -r requisitos.txt

## Ou instalar dependências/bibliotecas individualmente
py -m pip install aniso8601==9.0.1
py -m pip install attrs==22.1.0
py -m pip install click==8.1.3
py -m pip install Flask==2.1.3
py -m pip install Flask-Cors==3.0.10
py -m pip install flask-openapi3==2.1.0
py -m pip install flask-restx==0.5.1
py -m pip install Flask-SQLAlchemy==2.5.1
py -m pip install greenlet==1.1.3
py -m pip install gunicorn==20.1.0
py -m pip install importlib-metadata==4.12.0
py -m pip install itsdangerous==2.1.2
py -m pip install Jinja2==3.1.2
py -m pip install jsonschema==4.16.0
py -m pip install MarkupSafe==2.1.1
py -m pip install nose2==0.12.0
py -m pip install pydantic==1.10.2
py -m pip install pyrsistent==0.18.1
py -m pip install pytz==2022.2.1
py -m pip install six==1.16.0
py -m pip install SQLAlchemy==1.4.41
py -m pip install SQLAlchemy-Utils==0.38.3
py -m pip install typing_extensions==4.3.0
py -m pip install Werkzeug==2.1.2
py -m pip install zipp==3.8.1

## Atualizar pacotes
py -m pip install --upgrade requests

## Listar pacotes
pip list
pip freeze

## Rodar aplicação
flask run --host 0.0.0.0 --port 5000

## Rodar aplicação em modo desenvolvimento
flask run --host 0.0.0.0 --port 5000 --reload

## Desativar o ambiente virtual
deactivate
~~~

Abrir o projeto no [Firefox](http://localhost:5000/#/)

Abrir o projeto no [Chrome](http://127.0.0.1:5000/)
