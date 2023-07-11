# SPRINT DE ENTREGA Módulo 5 [Fundamentos de bases de datos relacionales]
***

## Contexto 

Tu aplicación necesita una base de datos para sistematizar el funcionamiento del soporte ‘En qué
puedo ayudarte’. El soporte lo realizan operarios.
¿Cada vez que un usuario utiliza el soporte ‘’En qué puedo ayudarte?’ se le asigna un operario para
ayudarlo con su problema.

Luego de esto, el usuario responde una encuesta donde califica al operario con una nota de 1 a 7, junto
a un pequeño comentario sobre su atención.
Queremos sistematizar esta información en una base de datos.

## Solución 

Se creó una base de dato llamada "en_que_puedo_ayudarte".

También un usuario con todos los privilegios para la base de dato.
          >** usuario: user_sprint_m5
          >** contraseña: 123
  

Se crearon 3 tablas:
  - usuarios : tiene información sobre: nombre, apellido, edad, correo electrónico y número de veces
    que ha utilizado la aplicación (por defecto es 1, pero al insertar los registros debe indicar un número
    manual).
  - operarios : tiene información sobre: nombre, apellido, edad, correo electrónico y número de veces
    que ha servido de soporte (por defecto es 1, pero al insertar los registros debe indicar un número
    manual).
  - soporte :  reconoce quien es el operario, el cliente, la fecha y la evaluación que recibe el soporte.

Se agregaron 5 usuarios, 5 operadores y 10 operaciones de soporte. Los datos fueron creados de forma aleatorea.

## Se implementrán las siguientes consultas:

  - Seleccione las 3 operaciones con mejor evaluación.
  - Seleccione las 3 operaciones con menos evaluación.
  - Seleccione al operario que más soportes ha realizado.
  - Seleccione al cliente que menos veces ha utilizado la aplicación.
  - Agregue 10 años a los tres primeros usuarios registrados.
  - Renombre todas las columnas ‘correo electrónico’. El nuevo nombre debe ser email.
  - Seleccione solo los operarios mayores de 20 años.


## Se solicita como entregable

  - La implementación final de todos los conceptos vistos durante el Módulo 5 de Bases de Datos.
  - El diagrama del modelo entidad relación.
  - Un documento Word o PDF en el que se indique: Ruta del repositorio en GitHub


