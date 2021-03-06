BAFICI
======

#### v1.00 Requisitos

### Hardware:
* Placa Arduino Mega (puede ser cualquier otra placa Arduino, solo hay q cambiar pines en código)
* Sensores o interruptores (6 unidades)
* Leds (6 unidades)
* Placa experimental o shields para montaje de sensores y leds

### Frameworks:
* NodeJS v0.10.26 - [http://nodejs.org/](http://nodejs.org/)
* Processing 2.0.3 (32bits) - [http://www.processing.org/](http://www.processing.org/)
* Arduino 1.0.5 - [http://www.arduino.cc/](http://www.arduino.cc/)
* Grunt - [http://gruntjs.com/](http://gruntjs.com/)

### Dependencias Node:
* node-osc: "~0.2.1",
* socket.io: "~0.9.16"
* grunt-contrib-sass: "~0.7.3",
* grunt-contrib-watch: "~0.6.1",
* grunt: "^0.4.4"

### Librerías Javascript
* D3js v3 - [http://d3js.org/](http://d3js.org/)
* jquery v2.1.0 - [http://jquery.com/](http://jquery.com/)
* Jquery Transform - [https://github.com/louisremi/jquery.transform.js](https://github.com/louisremi/jquery.transform.js)

### Librerías Processing
* Librería OSC: [http://www.sojamo.de/libraries/oscP5/](http://www.sojamo.de/libraries/oscP5/)
* Librería Arduino: ya viene con la versión de Processing 2.0.3


### Uso

- Instalar, por primera vez, desde la carpeta `app` las dependecias de node para node-osc y socket.io 

		$ npm install

		$ node app.js

- Modificar el puerto donde está enchufado el Arduino y correr

		`\processing\receiverSerialP5_4c\receiverSerialP5_4c.pde` 

- Abrir en en browser `\public\index.html`


### Colaborá

- Forkeá el proyecto.

- Creá un branch

		git checkout -b mi_rama


- Comiteá tus cambios

		git commit -m "Comentario del commit"


- Hacé un Push a la rama 

		git push origin my_markup

- Abrí un [Pull Request](https://github.com/gcba/BAFICI/pulls)
