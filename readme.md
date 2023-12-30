# Setup

Ruten von POST 1 Boot oder Get 1 Boot sind gesichert und nur durch login erreichbar

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
