2. Título y descripción del proyecto

Título: EcoBot: Concientización sobre el Calentamiento Global

Autor: Thiago Corrales

Descripción: Hice un bot para Discord usando Python. La idea es enseñar a las personas sobre el problema del calentamiento global de una forma más interactiva, usando comandos, imágenes y un sistema de voz.

3. Propósito del proyecto
El propósito principal de este proyecto es que todos entendamos mejor la crisis climática, pero de una manera fácil de captar. Como Discord es una plataforma que muchos usamos todos los días, me pareció el lugar perfecto para explicar un tema ambiental tan importante de forma más entretenida y directa.

4. Funciones y características

Tiene varios comandos (como =PEP, =CELC, =QHDC) que explican cosas como por qué pasa el efecto invernadero, qué es la huella de carbono y cómo nos ayudan las energías renovables.

Trae un minijuego de 15 preguntas tipo Kahoot con botones directamente en el chat, para que los usuarios pongan a prueba lo que aprendieron.

Usé la biblioteca pyttsx3 de Python para que el bot lea en voz alta las respuestas y explicaciones. Siento que esto lo hace mucho más interesante y diferente.

También manda infografías e imágenes al chat para que no sea solo texto y sea más fácil entender la información.

Le agregué un comando (=detener) por si alguien necesita que el bot deje de hablar en ese momento.

5. Demostración del funcionamiento
Aquí les dejo unas capturas de pantalla para que vean cómo interactúa el bot con los usuarios en el servidor:

Comando de inicio: Cuando alguien escribe =start, el bot saluda, da una explicación corta de lo que hace y manda una infografía para empezar. (Enlace/ID de la imagen: image_5c6cbe.jpg)

Cuestionario interactivo: Así se ve cuando usas el comando =quiz. Muestra la primera pregunta y los botones (A, B, C, D) listos para jugar. (Enlace/ID de la imagen: image_5c6c62.png)

6. Instalación y uso
Para usar este bot en tu propia compu o servidor, solo sigue estos pasos:

Requisitos: Asegúrate de tener instalado Python 3.8 o una versión más nueva.

Instalar librerías: Abre la terminal y pon estos comandos para instalar lo necesario:
pip install discord.py
pip install pyttsx3

El Token: Abre el código, ve hasta el final y cambia el texto que dice "hola desarrollador o usuario, pon tu token aca" por el Token real de tu aplicación (el que te da la página de desarrolladores de Discord).

Corre el script en tu editor de código o en la terminal.

Ve a tu servidor de Discord y escribe =help para ver todos los comandos que tiene el bot.

7. Comentarios
¡Cualquier sugerencia sirve para mejorar! Si tienen ideas para más preguntas del quiz, información nueva sobre el clima o encuentran algún error, me pueden dejar un comentario o abrir un issue en el repositorio de GitHub. Si alguien quiere aportar para agregar más idiomas o imágenes, sus aportes son muy bienvenidos.

8. Conclusión
Creo que el calentamiento global es un problema que nos toca a todos, y aprender un poco más sobre esto es el primer paso para ayudar. Con este proyecto me di cuenta de que programar en Python no es solo para hacer juegos o cosas técnicas, sino que también sirve para aportar un granito de arena. Espero que EcoBot ayude a que los que usamos Discord pensemos un poco más en nuestro planeta y en lo que podemos hacer para cuidarlo.