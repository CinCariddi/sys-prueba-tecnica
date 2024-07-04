Prueba Técnica Security and System
Dentro del repositorio hay dos carpetas:

API
Hay disponible un json-server con una lista de usuarios ficticios. Si nunca lo utilizaste te dejamos la documentación en la sección de recursos.

Para inicializar el servidor se debe ejecutar los siguientes comandos:

cd ./db-users-example
npm install
npm run serve
Por defecto se inicializará en el puerto 3000.

CLIENT
Dentro de la carpeta client se encuentra el código de la pagina web y los test realizados. 

Para inicializar el servidor se debe ejecutar los siguientes comandos:

cd ./client
npm install
npm run dev
(Cuando se levante el servidor de client se debe tener levantado el de api, así se trae la información)

Para inicializar los test se debe ejecutar el comando:

npm test.

¡Eso es todo!