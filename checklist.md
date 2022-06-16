## 1 - Configurar servidor node e rotas
## 2 - Instalar o jsonwebtoken com o @types/jsonwebtoken
        yarn add jsonwebtoken
        yarn add @types/jsonwebtoken -D

## 3 - Importar o jwt no roter.ts
## 4 - Criar a funcao verifyJWT para validar o token
## 5 - Criar a interface ITokenPayload para tipar o userId no request
## 6 - Criar o arquivo express.d.ts em ./src/@types para inserir a propriedade userId no request
## 7 - Incluir a flag --files no script 'dev' que roda o servidor no package.json para que se reconheça o userId no request
        "dev": "ts-node-dev --transpile-only --ignore-watch node_modules --files ./src/server.ts"