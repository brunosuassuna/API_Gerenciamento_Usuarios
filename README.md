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

```bash
├── .github/            # GitHub workflows
├── config/             # Configurações do projeto
│   ├── settings/       # Configurações por ambiente
│   └── urls.py         # URLs principais
├── apps/
│   └── usuarios/       # App de usuários
│       ├── migrations/
│       ├── tests/
│       ├── api/        # Endpoints da API
│       ├── models.py
│       ├── serializers.py
│       └── services.py # Lógica de negócio
├── static/             # Arquivos estáticos
├── .env.exemplo        # Modelo de variáveis de ambiente
├── docker-compose.yml  # Configuração Docker
├── requirements.txt    # Dependências
└── README.md           # Este arquivo
```

## 🧪 Como Testar

- Clone o repositório
  ```bash
  https://github.com/brunosuassuna/API_Gerenciamento_Usuarios
  cd api-gerenciamento-usuarios
  ```
- Crie e ative um ambiente virtual
 ```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```
- Instale as dependências com pip install -r requirements.txt
  ```bash
  pip install -r requirements.txt
  ```
- Rode as migrações: python manage.py migrate
  ```bash
  python manage.py migrate
  ```
- Inicie o servidor: python manage.py runserver
  ```bash
  python manage.py runserver
  ```
- Acesse os endpoints em: http://localhost:8000/api/

  ## 📜 Licença
- **Licença:** [MIT](https://opensource.org/license/MIT)

## ✉️ Contato
- **Email:** brunosuassuna.dev@gmail.com
- **LinkedIn:** www.linkedin.com/in/bruno-suassuna-698aa7235
