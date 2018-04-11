# Repositorio Código - Trabajo de fin de grado
  Título: "Sistemas informáticos para la evaluación del entrenamiento del Pensamiento Computacional".
  
  Despliegue, análisis y codificación de un reto en la plataforma de code.org

  

<center><img scr="https://github.com/DarwinGonzalez/code-dot-org/blob/staging/dashboard/app/assets/images/Logo_chica_small_otro.png?raw=true"></img></center>

<p align="center">
  <img src="https://github.com/DarwinGonzalez/code-dot-org/blob/staging/dashboard/app/assets/images/Logo_chica_small_otro.png?raw=true" title="logo">

  <div align="center"><a href="https://sites.google.com/a/ull.edu.es/pensamiento-computacional/">Pensamiento Computacional ULL</a></div>
  
</p>

<br>

![Blockly Games](https://raw.githubusercontent.com/wiki/google/blockly-games/title.png)

Google's Blockly Games is a series of educational games that teach programming.
It is based on the [Blockly](https://developers.google.com/blockly/) library.
All code is free and open source.


**The games are at https://blockly-games.appspot.com/**

**The developer's site is at https://github.com/google/blockly-games/wiki**

#
## Modo de uso

Para utilizar el siguiente código es necesario seguir una serie de pasos que se exponen a continuación. En primer lugar es necesario obtener las dependencias y construir las mismas. Para ellos debemos posicionarnos dentro de la carpeta

````
cd blockyly-games/
make deps
`````
Una vez hecho esto debemos construir el juego en si, en este caso construiremos el juego del Laberinto clásico, denominado en ingles como "maze" y lo construiremos de la siguiente forma.
```
make maze-en
````
Por último solo queda ver el resultado de la construcción del juego, para ello debemos abrir en el navegador la siguiente ruta "/blockly-games/appengine/maze.html". Finalmente destacar que si realizamos algún tipo de modificación en el código fuente del proyecto habrá que reconstruir con el make el código para que los cambios sean efectivos.