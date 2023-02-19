>**Algoritmo del código:**


>input: recargos establecidos por la empresa e instrucciones de como realizar la cotización, variable recargo, variable recargo total,
>variable nombre, variable edad, variable trabajo, variable salario, variable propiedad, propiedad_recargo, variable casado. variable hijos
>variable hijos_total, variable precio final. 
>
>output: recargo total final y el precio a pagar final del asegurado. 
Pasos: 

1. Empezaremos el cuestionario hacia el asegurado, preguntaremos su nombre primero lo guardamos en variable nombre y luego su edad que 
   guardaremos en variable edad.

2. Comparar la variable edad mayor a 18, de ser así entonces seguimos con el código, de lo contrario mostramos el mensaje "es menor" y terminará el programa.

3. Ahora comparamos la variable edad si es de 18 a 25 se hace lo siguiente, solamente hacemos la situación respecto a la edad ingresada, las
   demas solo las pasamos por alto. 

4. Comparar si edad esta entre 18 a 24 de ser así, a la variable recargo la igualamos a precio_base * 5 y al resultado o dividimos en 100.

5. Luego igualamos la variable recargo_total a la variable recargo_total + recargo. 

6. Comparar si edad esta entre 25 a 50 de ser así, a la variable recargo la igualamos a precio_base * 10 y al resultado o dividimos en 100. 
   Luego igualamos la variable recargo_total a la variable recargo_total + recargo. 

7. Comparar si edad mayor a 50, a la variable recargo la igualamos a precio_base * 20 y al resultado o dividimos en 100. 

8. Luego igualamos la variable recargo_total a la variable recargo_total + recargo. 

9. Ahora preguntamos si el asegurado labora y lo guardamos en variable trabajo.

10. Comparar si variable trabajo es igual a "si", entonces seguimos con los pasos, de lo contrario saltamos al paso #14 

11. Preguntamos cual es el salario del asegurado y lo guardamos en la variable salario.

12. Calcular el recargo al salario, para esto usamos la variable salario, luego lo multiplicamos por 5 y al resultado se le divide en 100, el resultado será
    almacenado en la variable recargo. 

13. Luego en la variable recargo_total la igualamos a la misma variable recargo_total para actualizar el total del recargo y luego a ese total
    se le suma la variable recargo que contiene el 5% del salario del asegurado.

14. Ahora preguntamos si el asegurado posee alguna propiedad, Cmparar si variable propiedad es igual a "si", de ser así seguimos con el código, de lo 
    contrario saltamos al paso #19 

15. Ahora preguntamos la cantidad de propiedades que posee y guardamos ese número en variable propiedad. 

16. Luego en la variable propiedad_recargo la igualamos a %35 multiplicado por la varible propiedad que contiene la cantidad e propiedades,
    asi obtendremos el recargo que debmos usar para la propiedad. 

17. Luego la variable recargo la igualamos a precio_base multplicado por propiedad_recargo y el resultado dividido 100. 

18. Luego en la variable recargo_total la igualamos a la misma variable recargo_total para actualizar y luego le sumamos la variable recargo.
     
 19. Ahora preguntamos si el asegurado esta casado, comparar si la variable caso es igual a "si", de ser así seguimos con el código, de lo 
     contrario saltamos al paso # 
 
 20. Preguntar la edad del conyuge y guardarla en la variable edad_conyuge
 
21. Comparar si edad_conyuge esta entre 18 a 24 de ser así, a la variable recargo la igualamos a precio_base * 5 y al resultado o dividimos en 100.
    de lo contrario saltamos al paso #24. 

23. Luego igualamos la variable recargo_total a la variable recargo_total + recargo. 

24. Comparar si edad_conyuge esta entre 25 a 50 de ser así, a la variable recargo la igualamos a precio_base * 10 y al resultado o dividimos en 100. 
    de lo contrario saltamos al paso #26.
    
25. Luego igualamos la variable recargo_total a la variable recargo_total + recargo. 

26. Comparar si edad_conyuge mayor a 50, a la variable recargo la igualamos a precio_base * 20 y al resultado o dividimos en 100. 

27. Luego igualamos la variable recargo_total a la variable recargo_total + recargo. 

28. Ahora preguntamos si el asegurado tiene hijos y guardamos el resultado en la variable hijos 

29. Si variable hijos es igual a "si" entonces seguimos con el código de lo contrario saltamos al paso numero #35.

30. Luego preguntamos al usuario cuantos hijos tiene, y ese resultado lo guardamos en la variable hijos_total 

31. Comparar si hijos_total es mayor a 0 y menor de 2 de ser así, a la variable recargo la igualamos a precio_base *20 y al resultado lo
    dividimos en 100, de lo contrario saltamos al paso #33.
    
32. Luego igualamos la variable recargo_total a la variable recargo_total + recargo. 

33. Comparar si hijos_total es mayor a 2, de ser así, a la variable recargo la igualamos a precio_base *30 y al resultado lo dividimos en 100.

34. Luego igualamos la variable recargo_total a la variable recargo_total + recargo. 

35. Por último en la variable precio_total la igualamos a precio_base + recargo_total 

36. Luego mostramos un mensaje que diga "para el asegurado (nomrbe del usuario)"
37. Luego mostramos un mensaje que diga "el recargo total es de + recargo_total" y concatenamos la variable recargo_total 
38. Luego mostramos un mensaje que diga "el precio total es de + precio_total" y concatenamos la variable precio_total. 
39. Preguntamos si el usuario desea hacer una nueva cotización y lo guardamos en la variable repetir
40. Comparamos si variable repetir es igual a "si", se repetira todo el algoritmo del paso 1 al 40, de lo contrario el programa terminara 
Fin 🐈




 
 

  
