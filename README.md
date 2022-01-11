# CoderHouse_DW
Repositorio del curso de Coder House - Desarrollo Web

npm init
npm install -d node-sass nodemon
npm run build-css


"build-css": "node-sass --include-path scss scss/estilo.scss css/estilo.css",
"watch-css": "nodemon -e scss -x \"npm run build-css\""
https://techvblogs.com/blog/install-nodejs-and-npm-ubuntu-20-04