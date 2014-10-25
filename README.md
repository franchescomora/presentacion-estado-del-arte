##Presentación del estado del arte

Presentación para la clase de Software Libre en el segundo semestre del 2014 de la Universidad Nacional de Colombia, a partir de la clonación del repositorio del profesor Jean Pierre Charalambos:

https://github.com/SoftwareLibre/stockfish.reveal.git 

##Hacking

Clonar el repositorio:

$  git clone https://github.com/franchescomora/presentacion-estado-del-arte

$  cd  presentacion-estado-del-arte

$  grunt serve

Ya se puede mirar la presentación en http://localhost:8000

Para que lo anterior funcione, se asume que ya se tiene configurado el servidor web local conforme a las instrucciones del profesor Jean Pierre:

External markdown and speaker notes, require that presentations run from a local web server. The remaining instructions will set up such a server as well as all of the development tasks needed to make edits to the slides source code.

Install [Node.js](http://nodejs.org/)

Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

Navigate to the presentation folder

$ cd stockfish.reveal
Install dependencies

$ npm install
Edit ( You could use [ReText](http://www.genbeta.com/herramientas/retext-interesante-editor-markdown-para-linux)*) the presentation contents using [markdown](http://en.wikipedia.org/wiki/Markdown) in the source.md 

Serve the presentation and monitor source files for changes

$ grunt serve
Open http://localhost:8000 to view your presentation

You can change the port by using grunt serve --port 8001.

*Nota agregada a las instrucciones