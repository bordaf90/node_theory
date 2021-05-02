## Creo un Package Json: me dice que versión tengo en mi trabajo y demás.
npm init -y

## Módulos generales:
* npm install express pg pg-hstore sequelize morgan @babel/polyfill
* npm install --save-dev @babel/core @babel/cli @babel/preset-env
* npm install nodemon -D
* npm install @babel/node -D


### Significados:

* express es un framework que sirve para escribir mi servidor. 
* pg y pg-hstore son dos módulos de Postgret que nos permite interactuar con el mismo (BBDD).
* sequelize es un orm. 
* morgan nos permite ver por consola las peticiones http.
* @babel/polyfill nos permite escribir código de JS que pueda ser leeido por cualquier servidor. Es un compilador.
* nodemon reinicia el código de Node automáticamente
* -D significa que es sólo para Desarrollo.

## Scripts  especiales de package.json:

* "scripts": {
   * "dev": "nodemon src/index.js --exec babel-node",
    * "build": "babel src --out-dir dist",
   *  "start": "node dist/index.js"
 * }
  
  






