# api-flask-gerenciador-gastos

Desenvolvimento de aplicação com Flask para gerenciamento de gastos pessoais.

# Utilizamos na aplicação as Libs:

```
- make_response, jsonify, request do Flask,
- SQLAlchemy com flask,
- Migrate com flask,
- Marshmallow com flask,
- fields de Marshmallow,
- API e Resource do flask_restful,
- JWTManager, jwt_required, get_jwt_identity e verify_jwt_in_request do flask_jwt_extended,
- wraps do functools,
- enum,
- passlib.hash de pbkdf2_sha256
```

# Como iniciar:

- Após clonar o repositório e instalar todas as dependências e ferramentas utilizadas no projeto:
```
flask run
```
- O comando ```flask run``` irá executar o servidor no ``` http://localhost:5000/ ```.

# Nota especial:
```
- Utilizamos a aplicação POSTMAN para teste das rotas utilizadas e consumidas pela API.
```
