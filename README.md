# cadastro-de-usuarios# API de Cadastro de Usuários com Flask

## Descrição

Esta é uma API simples de cadastro de usuários desenvolvida com **Flask** e **SQLAlchemy**. Ela permite que você crie, visualize, atualize e exclua usuários de um banco de dados. O projeto foi desenvolvido para fins educativos e pode ser expandido com mais funcionalidades, como autenticação e validação de dados.

## Funcionalidades

- **Criar usuário**: Permite criar um novo usuário.
- **Listar usuários**: Lista todos os usuários cadastrados no banco de dados.
- **Editar usuário**: Permite editar as informações de um usuário.
- **Excluir usuário**: Permite excluir um usuário do banco de dados.

## Tecnologias Usadas

- **Python** 3.x
- **Flask** (Web Framework)
- **SQLAlchemy** (ORM para interação com o banco de dados)
- **SQLite** (Banco de dados relacional simples para desenvolvimento)

## Instalação

### 1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/cadastro-usuarios-flask.git](https://github.com/luanmilagre/cadastro-de-usuarios/pull/new/master)
cd cadastro-usuarios-flask
2. Crie um ambiente virtual e ative-o:
No Windows:
python -m venv venv
.\venv\Scripts\activate
No Linux/MacOS:
python3 -m venv venv
source venv/bin/activate
3. Instale as dependências:
pip install -r requirements.txt
4. Crie o banco de dados:
flask db init
flask db migrate
flask db upgrade
Como Usar
1. Inicie a aplicação Flask:
python app.py
A aplicação estará disponível no endereço http://127.0.0.1:5000/.

2. Teste as rotas da API usando o Postman ou cURL:
POST /users: Cria um novo usuário.

GET /users: Lista todos os usuários.

PUT /users/{id}: Atualiza as informações de um usuário.

DELETE /users/{id}: Exclui um usuário.

Exemplos de Uso
Criar Usuário (POST):
URL: http://127.0.0.1:5000/users

Body (JSON):

{
  "name": "João",
  "email": "joao@example.com"
}
Listar Usuários (GET):
URL: http://127.0.0.1:5000/users

Atualizar Usuário (PUT):
URL: http://127.0.0.1:5000/users/1

Body (JSON):

{
  "name": "João Silva",
  "email": "joaosilva@example.com"
}
Excluir Usuário (DELETE):
URL: http://127.0.0.1:5000/users/1
