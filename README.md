# => { Agenda } 📝
> Projeto feito para unificação de conceitos vistos em aula, como: classes, async functions, promises, rotas, middlewares, padrão MVC, CRUD e etc...
<p align="center">
  <img src="https://github.com/tavinhoo/projeto-Agenda/blob/main/frontend/assets/initial-page.jpeg" alt="projeto Agenda">
</p>

<p align="center">
  <img src="https://github.com/tavinhoo/projeto-Agenda/blob/main/frontend/assets/login-page.jpeg" alt="pagina de login">
</p>

<p align="center">
  <img src="https://github.com/tavinhoo/projeto-Agenda/blob/main/frontend/assets/list-with-contacts.jpeg" alt="pagina com contatos">
</p>

## Uso:
```
git clone <url>
```
```
npm install
```
-
> OBS: para prosseguir, crie o arquivo '.env' com sua respectiva autenticação (mongodb);
```
CONNECTIONSTRING=mongodb+srv://clusterAnything.mongodb.net/test?retryWrites=true&w=majority
```
-
```
npm start 
```
```
http://localhost:3000/
```

### Dependências 
```js

  "dependencies": {
    "bcryptjs": "^2.4.3",
    "connect-flash": "^0.1.1",
    "connect-mongo": "^4.4.1",
    "core-js": "^3.15.2",
    "css-loader": "^6.2.0",
    "csurf": "^1.11.0",
    "dotenv": "^10.0.0",
    "ejs": "^3.1.6",
    "express": "^4.17.1",
    "express-session": "^1.17.2",
    "mongoose": "^5.13.3",
    "regenerator-runtime": "^0.13.9",
    "style-loader": "^3.2.1",
    "validator": "^13.6.0"
  },
  "devDependencies": {
    "@babel/cli": "^7.14.8",
    "@babel/core": "^7.14.8",
    "@babel/preset-env": "^7.14.8",
    "babel-loader": "^8.2.2",
    "nodemon": "^2.0.12",
    "webpack": "^5.46.0",
    "webpack-cli": "^4.7.2"
  }
  
