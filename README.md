# 🔐 API de Gerenciamento de Usuários
Este projeto demonstra a construção de uma API RESTful para gerenciamento de usuários, utilizando o framework Django em conjunto com o Django REST Framework (DRF). A aplicação permite realizar operações CRUD (Criar, Ler, Atualizar e Excluir) sobre registros de usuários, de forma simples, segura e eficiente.

## ⚙️ Tecnologias Utilizadas
- **Python** — linguagem de programação principal

- **Django** — framework web de alto nível

- **Django REST Framework** — toolkit poderoso para construção de APIs REST

- **SQLite/MySQL/PostgreSQL** — compatível com múltiplos bancos relacionais

- **Postman/Insomnia** — para testes de requisições (recomendado)

## 📌 Recursos da API
- 📄 Cadastro de usuário com apelido (nickname), nome, e-mail e idade

- 🔍 Listagem de todos os usuários cadastrados

- ✏️ Atualização parcial ou completa de dados do usuário

- 🗑️ Exclusão segura de registros

- 🔐 Estrutura pronta para autenticação e autorização via Token (JWT ou Session)

## 🚀 Objetivo do Projeto
Demonstrar na prática como construir uma API completa utilizando Django e DRF, com foco em boas práticas de desenvolvimento backend, organização de código, tratamento de erros e escalabilidade.

## 📂 Estrutura do Projeto

Editar

├──   manage.py

├──   users/

│     ├──   models.py

│     ├──   serializers.py

│     ├──   views.py

│     ├──   urls.py

├──         project_name/

│     ├──   settings.py

│     └──   urls.py

## 🧪 Como Testar

- Clone o repositório
- Crie e ative um ambiente virtual
- Instale as dependências com pip install -r requirements.txt
- Rode as migrações: python manage.py migrate
- Inicie o servidor: python manage.py runserver
- Acesse os endpoints em: http://localhost:8000/api/
