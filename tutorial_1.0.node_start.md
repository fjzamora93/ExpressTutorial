Comenzamos creando un app.js

Importamos todas las funcionalidades que vamos a usar:
    -nodemon
    -express
Es muy recomendable instalar nodemon app.js en el proyecto
(aunque tampoco es plan de meterlo en el ordenador, aunque se podría).

1. Comenzamos creando una aplicación y sus dependencias (init + install)

        npm init -y
        npm install 
        npm install express



2. Adicionalmente, es muy recomendable isntalar nodemon y ejs como dependencia del proyecto

        npm install --save-dev nodemon
        npm install --save ejs

    O lo podemos instalar globalmente -menos recomendable:

        npm install -g nodemon
        


3. El siguiente paso es crear un fichero app.js, donde vamos a escribir nuestro código básico.

        app.js
    
    o el nombre que queramos:

        index.js


4. Dentro de nuestro package.json, incluimos los scripts de arracanque:
    Esto nos ayudará a introducir correctamente cualquier comando que queramos.

        "scripts": {
            "start": "node app.js",
            "dev": "nodemon app.js"
        }

    NOTA: dentro de nuestro package.json, al crearlo automáticamente, es posible que nos diga que "main" : "index.js".
    Esto mismo puede suceder en start, que nos remita a index.js.
    Si le pusimos de nombre a nuestra app, app.js, debemos cambiar index.js >> app.js 

        "main": "app.js",
            ....
        "start": "nodemon app.js",

5. Vamos a nuestro app.js e introducimos el código base.
       



