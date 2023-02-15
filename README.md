>**PROYECTO FINAL EMPRESA SEGUROS TK-U**


En este proyecto se plantea el inconveniente que tiene la empresa de seguros TK-U al realizar sus cotizaciones para los clientes diariamente, ya que estas cotizaciones son realizadas manualmente por los trabajadores, de manera que la cantidad máxima que pueden realizar al día es de 50 cotizaciones, se necesita una solucion a ello que permita realizar las cotizaciones más rapido y de forma correcta para generar mas cotizaciones y de esa forma generar mas ingresos. 

Se cuentan con los conocimientos necesarios para poder programar lo necesario para la empresa y solucionar el problema que tienen. Para esto la empresa nos brinda la información que necesitamos para trabajar con respecto a ello como por ejemplo : 

<ol>
<li>La persona a asegurar tiene que ser mayor de edad, por lo cual no se
consideran los casos en los cuales esto no sea verdad.</li>
<li>Se tiene un plan base, al cual se le pueden aplicar recargos extra dependiendo de las condiciones del asegurado. Las condiciones que causan recargos son las siguientes:</li>
  <ol><li>Dependiendo de la edad del asegurado</li>  
  <li>Dependiendo de si el asegurado está casado o no y dependiendo también de la edad del esposo/a del asegurado</li>   
  <li>Dependiendo de la cantidad de hijos o hijas que tenga el asegurado.</li></ol>
<li>Para el primer y el segundo punto, son recargos basados en los rangos de edades:</li>
  <ol><li>Si tienen de 18 a 24 años, se les hará un recargo del 10% del precio base.</li>
  <li>Si tienen de 25 a 49 años, se les hará un recargo del 20% del precio base.</li>
  <li>Si tienen 50 años o más, se les hará un recargo del 30% del precio base Este recargo se aplica individualmente para el asegurado y el cónyuge, por ejemplo:</li></ol>
    <ol><ol><li>El precio base es de Q.2,000</li>
    <li>El asegurado tiene 23 años</li>
    <li>Su cónyuge tiene 26 años</li>
    <li>Por el asegurado se realiza un recargo de 10%, es decir Q.200</li>
    <li>Por el cónyuge se realiza un recargo de 20% es decir Q.400</li>
    <li>El precio total sería de Q.2,600, el seguro cubriría a ambas personas</li></ol></ol>  

Luego de leer el contexto del inconveniente de la empresa, se empieza a realizar el código, en el cual debemos declarar las variables primeramente con los recargos correspondientes, una vez teniendo esas variables declaradas y con sus respectivos valores, comenzamos el interrogatorio al usuario utilizando el método prompt para pedirle datos al usuario primero pedmos su nombre, luego pedimos su edad, una vez ingresa la edad debemos verificar es variable para saber cual será el recargo para dicha edad, y eso se guardara en total_reargo y se ira actualizando a medida que el código avanza.  
Luego se procede a preguntar si el usuario tiene empleo, si este tiene, leemos cual es el salario y agregamos el recargo correspondiente.  
Luego de eso, se procede a preguntar si el usuario tiene propiedades a su nombre, de ser así se le agrega el recargo correspondiente. 
Luego se pregunta al usuario si esta casado de ser así le pregunaremos la edad del cónyugue para saber que recargo se le agregará. 
Nuevamene se pregunta al usuario si tiene hijos, de ser así le preguntamos cuantos si tiene menos de 2 se le agrega un recargo de 0.20 ahora si tiene más será de 0.30.
Finalmente le mostramos al asegurado el total del recargo mas el precio base que es Q2000.00, lo mostramos en pantalla y luego antes de finalizar la ejecución le preguntamos si gusta realizar otra cotización en caso que desee volver a hacerlo o hacer una cotizacion para otro asegurado, de lo contrario el programa terminará. 

Mejoras en el proyecto para la empresa TK-U:

En cuanto a las mejoras posibles, hay muchas, ya que se podría crear el usuario para el asegurado, de esta manera guardar sus datos y poder enviar por correo la información que creemos importante, asi como no tener que volver a correr el código para revisar los recargos. 

De esta manera se brindó una solución optima a la empresa, reducir el tiempo de cotizaciones y poder hacer tantas cotizaciones como sean necesarias. para referencia del código puede visitar el link [*COTIZACIONES_tk-U*](proyecto.html)
    
    
