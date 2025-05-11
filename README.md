# 🧩 Projeto Django: Enquete (Polls)

Este projeto é um exemplo de aplicação web construída com o framework **Django**, seguindo o tutorial oficial da documentação. O sistema permite a criação e gerenciamento de enquetes, onde os usuários podem visualizar perguntas e votar em opções disponíveis.

## 🚀 Funcionalidades

- Cadastro de perguntas e opções de resposta
- Votação em tempo real
- Interface administrativa completa com Django Admin
- Uso de templates e sistema de roteamento
- Exibição de resultados após o voto
- Testes automatizados com o Django TestCase

## ⚙️ Tecnologias Utilizadas

- **Python 3.11+**
- **Django 5.2**
- **SQLite** (banco de dados embutido)
- HTML/CSS (com pasta `static/`)
- Django Admin para gerenciamento de conteúdo

## 🛠️ Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/nome-do-repo.git
   cd nome-do-repo
   ```

2. Crie um ambiente virtual e ative:

```bash
python -m venv venv
venv\\Scripts\\activate  # Windows
```

3. Instale as dependências:

```bash
pip install django
```

4. Execute as migrações:

``` bash
python manage.py migrate
```

5. Inicie o servidor:

``` bash
python manage.py runserver
```

6. Acesse em:
http://127.0.0.1:8000/polls

## 🧪 Executando os Testes
- Para rodar os testes do modelo:

```bash
python manage.py test polls
```

## 📁 Estrutura

```bash
pgsql
meu_projeto/
├── manage.py
├── meu_projeto/
│   ├── settings.py
│   └── urls.py
├── polls/
│   ├── models.py
│   ├── views.py
│   ├── tests.py
│   ├── urls.py
│   └── templates/
│       └── polls/
│           ├── index.html
│           ├── detail.html
│           └── results.html
```

## 👨‍🏫 Créditos
- Projeto desenvolvido para estudo da disciplina de Introdução à Programação com Python.
- Professor: Eduardo Poffo Medeiros Dias
- Aluno: Wallacy Alvarenga