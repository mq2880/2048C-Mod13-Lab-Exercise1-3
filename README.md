# Module 13: Implementing Real-time Communication by Using Web Sockets

**Lab: Performing Real-time Communication by Using Web Sockets**

**Nombre:** Francisco Javier Moreno Quevedo

**Fecha:** 2/10/2020

**Resumen del Ejercicio:** El laboratorio se compone de tres ejercicio. En el ejercicio uno se  reciben los mensajes de los asistentes via WebSockets. En el ejercicio dos se envian las preguntas via Websockets y en le ejercicio tres se eliminan las preguntas ya reportadas

**Dificultad o problemas presentados y como se resolvieron:** En el ejercicio numero tres faltaba la linea que enviaba la pregunta para gestionarse y borrarse **this.socket.send(JSON.stringify({ report: questionId }));** 

- Ejercicio 1

  - Abre un websockets
  - Se reciben las respuestas para mostrarse en pantalla
- Ejercicio 2
  - Se crea un JSON con la pregunta
  - Se envia
- Ejercicio 3
  - Se añade el codigo para para que una vez gestionadas se eliminen