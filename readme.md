# BASIC AUTH with mongoose

POST 1 Boot or Get 1 Boot routes are basic secured and can only be accessed via login

npm init -y

npm i express

npm i mongodb cors dotenv uuid multer mongoose

## npm i morgan

morgan: logger, middelware-logger in dev format-sehe die Anfragen

- in package.json:

"type": "module",

- in package.json in "scripts" add:

"dev": "node --watch app.js"

- create .gitignore file and write inside

```javascript

node_modules/
.vscode/
.env
uploads/

```

- create .env file and write inside

```javascript

PORT=YOURPORT
MONGODB=mongodb://YOURADRESS
DATABASENAME=YOURDBNAME

```
