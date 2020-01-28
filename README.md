## Aplicación de comandos

Este es un pequeño ejemplo en NodeJs donde se pueden
administrar tareas.

Grabamos, modificamos, leemos o borramos las tareas del 
archivo json (data.json)

Utilizo require('./config/yargs') para pasar parámetros desde consola.

Los comandos de la Aplicación son: crear, listar, actualizar(el estado) y borrar.

Ejemplos:
node app crear -d "Comprar carne"
node app listar
node app actualizar -d Comprar carne -c true
node app borrar -d "Comprar carne"



Recuerden instalar los paquetes de node

```
npm install
```
