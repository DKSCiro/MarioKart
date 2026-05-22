¿QUÉ HIZO CADA INTEGRANTE DEL EQUIPO?

Eduardo Gutiérrez Tapia: 
Configure el repositorio en GitHub; organice la estructura del proyecto, implemente las clases del modelo
"Participante" e "Interfaz"

Carlos Yael Villegas Beltran:


CONCLUSIONES (INDIVIDUALES):

Eduardo Gutiérrez Tapia:
Comprendi mejor la modelación de objetos y la importancia de encapsular estado y comportamiento; practicar métodos y pruebas me ayudó a consolidar conceptos de POO.

COMPLICACIONES AL REALIZAR EL PROYECTO:

Eduardo Gutiérrez Tapia:
Tuve problemas para modelar la duración y efectos de items lo que se me ocurrió fue
simplificar las reglas y documentarlas.

Carlos Yael Villegas Beltran:
Una de las principales complicaciones técnicas surgió al gestionar el acceso simultáneo de los hilos al recurso compartido, específicamente en el momento en que los vehículos tomaban una caja de objetos y debían aplicar una penalización a un oponente aleatorio mientras otros seguían avanzando. Sin la protección adecuada, se generaban condiciones de carrera (race conditions) donde dos hilos intentaban modificar el estado de un mismo participante al mismo tiempo, lo que provocaba inconsistencias en el contadorde turnos perdidos o errores en el orden del log de la consola.
Esta dificultad se superó mediante la aplicación estricta de la palabra clave synchronized en los métodos críticos de la clase Carrera, lo que garantizó que solo un hilo pudiera modificar o leer el estado global de la competencia a la vez, protegiendo la integridad de los datos y asegurando un registro preciso en el archivo de resultados finales.

USO DE IA: 

Eduardo Gutiérrez: Use la IA en .gitignore para que cuando creara out se duplicaran los archivos y también como mandar una sola carpeta 
de mi repo original ya que tengo un repositorio de POO pero ahí una parte de la carpeta así que use IA para poder ver como podia mandar solo esa repo sin que se vieran todos los demás trabajos que hay

prompts usados: 
"Hola, quiero que me ayudes en algo, estoy haciendo un proyecto sobre la materia de POO el lenguaje es en Java pero tengo un problema en mi VScode se generó un duplicado al momento de querer compilar y ejecutar en mi salida en "out" como puedo arreglarlo? es que quiero usar GitHub en este proyecto para que sea más sencillo"

"y otra duda, como pedo hacer que solo mis amigos vean ese archivo en GitHub es que no cree un nuevo repo, use el de mi clase normal, entonces pues no sabría con que comando ellos solo vean esa carpet, recuerdo que era algo de subtree, es que ya lo agregue así pero no se como hacer para que ellos no vean todos mis demas trabajos del repo se puede eso?"

NOTA: LAS IMÁGENES ESTA EN LA CARPETA DE PRUEBAS
