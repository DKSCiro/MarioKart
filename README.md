Alumnos:

No de cunenta -Gutierrez Tapia Eduardo 
322166910 - Sánchez de Tagle Caballero Diego Omar
No de cuenta -Villegas Beltran Carlos Yael


¿QUÉ HIZO CADA INTEGRANTE DEL EQUIPO?

Eduardo Gutiérrez Tapia: 
Configure el repositorio en GitHub; organice la estructura del proyecto, implemente las clases del modelo
"Participante" e "Interfaz"

Diego Omar Sánchez de Tagle Caballero:
Apoyé en la documentación del proyecto y en la elaboración del reporte final. También participé en las pruebas generales del sistema, verificando que los turnos de bloqueo y reducción de velocidad funcionaran correctamente dentro de la simulación.

Carlos Yael Villegas Beltran:
Organicé la estructura del proyecto e implemente las clases del modelo "Participante" y "carrera"
Verifique que cumplieran con la rúbrica de evaluación

CONCLUSIONES (INDIVIDUALES):

Eduardo Gutiérrez Tapia:
Comprendi mejor la modelación de objetos y la importancia de encapsular estado y comportamiento; practicar métodos y pruebas me ayudó a consolidar conceptos de POO.

Diego Omar Sánchez de Tagle Caballero:
Este proyecto permitió aplicar de forma conjunta conceptos de POO, concurrencia y persistencia de datos en un programa funcional. Además, comprendí la importancia de realizar pruebas constantes para detectar errores relacionados con la ejecución simultánea de procesos.

Carlos Yael Villegas Beltran:
El desarrollo del proyecto me permitió consolidar de manera práctica el uso de la concurrencia y la sincronización en Java, logrando simular una carrera interactiva donde cada vehículo actúa de forma autónoma a través de hilos independientes. La correcta separación de responsabilidades entre el comportamiento de los participantes y el control de la pista facilitó un diseño modular, asegurando el cumplimiento del encapsulamiento y el manejo eficiente de los recursos del sistema.

COMPLICACIONES AL REALIZAR EL PROYECTO:

Eduardo Gutiérrez Tapia:
Tuve problemas para modelar la duración y efectos de items lo que se me ocurrió fue
simplificar las reglas y documentarlas.

Carlos Yael Villegas Beltran:
Una de las principales complicaciones técnicas surgió al gestionar el acceso simultáneo de los hilos al recurso compartido, específicamente en el momento en que los vehículos tomaban una caja de objetos y debían aplicar una penalización a un oponente aleatorio mientras otros seguían avanzando. Sin la protección adecuada, se generaban condiciones de carrera (race conditions) donde dos hilos intentaban modificar el estado de un mismo participante al mismo tiempo, lo que provocaba inconsistencias en el contador de turnos perdidos o errores en el orden del log de la consola.
Esta dificultad se superó mediante la aplicación estricta de la palabra clave synchronized en los métodos críticos de la clase Carrera, lo que garantizó que solo un hilo pudiera modificar o leer el estado global de la competencia a la vez, protegiendo la integridad de los datos y asegurando un registro preciso en el archivo de resultados finales.

Diego Omar Sánchez de Tagle Caballero
Durante el desarrollo tuve problemas al momento de integrar todas las partes del proyecto, ya que algunos métodos tenían comportamientos diferentes dependiendo del hilo que los ejecutaba. También se me complicó verificar manualmente el orden correcto de llegada debido a la naturaleza concurrente del programa. 

USO DE IA: 

Eduardo Gutiérrez: Use la IA en .gitignore para que cuando creara out se duplicaran los archivos y también como mandar una sola carpeta 
de mi repo original ya que tengo un repositorio de POO pero ahí una parte de la carpeta así que use IA para poder ver como podia mandar solo esa repo sin que se vieran todos los demás trabajos qu hay

prompts usados: 
"Hola, quiero que me ayudes en algo, estoy haciendo un proyecto sobre la materia de POO el lenguaje es en Java pero tengo un problema en mi VScode se generó un duplicado al momento de querer compilar y ejecutar en mi salida en "out" como puedo arreglarlo? es que quiero usar GitHub en este proyecto para que sea más sencillo"

"y otra duda, como pedo hacer que solo mis amigos vean ese archivo en GitHub es que no cree un nuevo repo, use el de mi clase normal, entonces pues no sabría con que comando ellos solo vean esa carpet, recuerdo que era algo de subtree, es que ya lo agregue así pero no se como hacer para que ellos no vean todos mis demas trabajos del repo se puede eso?"

Diego Omar Sánchez de Tagle Caballero:
Durante el desarrollo del proyecto utilizé inteligencia artificial (Google Gemini y Open AI Chat GPT) como herramientas de apoyo para resolver dudas técnicas relacionadas con Java, GitHub y concurrencia. La IA me ayudó principalmente a comprender errores del programa, mejorar la organización del código y optimizar el uso de herramientas de desarrollo.
Utilizé IA para entender por qué varios hilos modificaban al mismo tiempo la posición de los participantes, causando errores en el ranking final.
Prompt utilizado:
Plain text
"Estoy haciendo un proyecto en Java con hilos y tengo un problema de concurrencia. Varias clases Runnable modifican la misma lista al mismo tiempo y el ranking se desordena. ¿Cómo puedo solucionarlo usando synchronized?"
Resultado obtenido:
La IA  me explicó cómo utilizar métodos synchronized en la clase Carrera para proteger los recursos compartidos y evitar condiciones de carrera (race conditions).
Se utilizó IA para resolver problemas relacionados con GitHub y la estructura del proyecto.
Prompt utilizado:
Plain text
"Hola, estoy trabajando en un proyecto de Java y quiero subir solamente una carpeta específica de mi repositorio a GitHub sin mostrar todos mis trabajos. ¿Cómo puedo hacerlo?"
Resultado obtenido:
La IA me recomendó el uso de git subtree y ayudó a configurar correctamente el .gitignore para evitar archivos duplicados generados por la carpeta out.

NOTA: LAS IMÁGENES ESTA EN LA CARPETA DE PRUEBAS
