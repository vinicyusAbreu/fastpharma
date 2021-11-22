
# 🏪 Fast Pharma

## 🤔 Sobre o projeto

Um projeto de criar uma simulação de uma loja de farmácia virtual. Criado para um projeto de faculdade.

## ✨ Demonstração
Veja abaixo um gif do projeto.<br>
<a href="https://gyazo.com/62a2f5f98755552a75c94e9492ce3b40"><img src="https://i.gyazo.com/62a2f5f98755552a75c94e9492ce3b40.gif" alt="Image from Gyazo" width="1280"/></a>

## Iniciar projeto
<hr>

Depois de clonar o repositório, você precisa criar um ambiente virtual, para ter uma instalação limpa do Python. Você pode fazer isso executando o comando

```
python -m venv env
```
Depois disso, é necessário ativar o ambiente virtual.

Você pode instalar todas as dependências necessárias executando
```
pip install -r requirements.txt
```

Definir banco de dados (verifique se você está no mesmo diretório que o manage.py)
```
python manage.py makemigrations
```
```
python manage.py migrate
```
Criar o SuperUser 
```
python manage.py createsuperuser
```

Após todas essas etapas, você pode começar a testar este projeto usando o comando.
```
python manage.py runserver
```
