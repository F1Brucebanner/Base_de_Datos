## Práctica 8.
### Disparadores (Triggers)

Objetivo: Demostrar las operaciones que se realizan en una base de datos.

Ejercicio: Crea una base de datos llamada test que contenga una tabla llamada
alumnos con las siguientes columnas. (valor 18)

Evaluación:

Creación de la base de datos : 9 puntos.

Creación de los Disparadores(Triggers): 9 puntos.

Tabla alumnos:

● id (entero sin signo)

● nombre (cadena de caracteres)

● apellido1 (cadena de caracteres)

● apellido2 (cadena de caracteres)

● nota (número real)

Una vez creada la tabla escriba dos triggers con las siguientes características:

● Trigger 1: trigger_check_nota_before_insert

  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de inserción.
  
  o Se almacena la leyenda 'se ingreso un registro'

● Trigger2 : trigger_check_nota_before_update
  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de actualización.
  
  o Se ingresa la leyenda 'se modifico un regisstro'
  
Una vez creados los triggers escribe varias sentencias de inserción y actualización
sobre la tabla alumnos y verifica que los triggers se están ejecutando
correctamente.

![image](https://user-images.githubusercontent.com/104279720/173272671-07de153b-fb56-4993-8ee9-8f92af1b60ec.png)


https://www.db-fiddle.com/f/aqVcQmBQCA42nBTyjiybzH/0

![image](https://user-images.githubusercontent.com/104279720/173272580-3f5d2cda-7efe-4a77-ada7-2337b582d3b0.png)

![image](https://user-images.githubusercontent.com/104279720/173273306-9ee8de48-e33e-4dd5-bd22-0cfe50125363.png)

![image](https://user-images.githubusercontent.com/104279720/173273344-c3d85d62-173f-42ff-9eb5-0d40e2cdac53.png)

https://www.db-fiddle.com/f/aqVcQmBQCA42nBTyjiybzH/1


