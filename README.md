# Asincronismo-Js

# Inicializar Proyecto
-git init (establecer repositorio)
-npm init (realizamos la configuracion del proyecto)

# Cambiar Json
-Vamos al package.json.
-En la parte de scripts borramos lo que tenemos ahí.
agregamos "callback": "node src/callback/index.js", (esto es para poder ejecutar ese comando en npm)
"callback:challenge": "node serc/callback/challenge.js"
"promise": "nose src/promise/index.js"
"primise:challenge": node src/promise/challenge.js"
"async": "node src/async/index.js"
"async:challenge":"node src/async/challenge.js"
-se ejecuta en la terminal >>npm run callback

# Instalación de dependencia xml
en Terminal:
npm install xmlhttprequest --save

## Callback
PROS:
-Es simple
-Facil de implementar
-Universales

CONTRAS:
-Composición/estructura un poco tosca
-El desarrollador se puede perder
-Flujo un poco intuitivo
-Manejo de errores tedioso

## Promise
PROS:
-Fácilmente enlazable
-Facil e intuitivo para leer
 
 CONTRAS:
 -No maneja excepciones
 -Proponso a errores si no hay retornos al siguiente llamado
 -Requiere una herramienta para que sea funcional en otros navegadores

 ## Async y away
 PROS:
 -Faciles de leer
 -Comprensión mas facil

 CONTRAS:
 -Esperar a otros llamados
 -Requiere una herramienta para que sea funcional en otros navegadores
 