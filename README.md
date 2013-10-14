Práctica #4
=========== 

Añadir Hojas de Estilo a Piedra Papel Tijeras
---------------------------------------------

Diego Williams Aguilar Montaño

Descripción de la práctica
--------------------------
Esta práctica consiste en añadir hojas de estilo (boostrap) como continuación de la práctica: "[Añadir Template Haml a Rock, Paper, Scissors](https://dl.dropboxusercontent.com/u/14539152/LPP/LPPbook/node355.html)", modificamos en el fichero config.ru el middleware Rack::Static que intercepta las peticiones por ficheros estáticos (javascript, imágenes, hojas de estilo, etc.) basandose en los prefijos de las urls pasadas en las opciones y los sirve utilizando un objeto Rack::File. A continuación enlazamos las hojas de estilo en el template views/index.haml.


Instrucciones
-------------

1. Ejecutar el programa mediante el archivo rake proporcionado:

        $ rake

2. El servidor arrancará.
3. Ahora visitamos la página [http://localhost:8080](http://localhost:8080) en el navegador preferido.
---

Universidad de La Laguna  
Escuela Técnica Superior de Ingeniería Informática  
Sistemas y Tecnologías Web 2013-14