# programa multiproceso en html

------------

Este programa imprime números secuencialmente en un intervalo de un segundo al presionar un botón

Pero al presionar otro botón se inicia otra secuencia la cual pausa la primera

Inicialmente se inicia el html con una capa de estilos incrustados los cuales darán colores y tamaños tanto de los botones como de las casillas donde se imprimen los números

------------
![](https://github.com/Dtorz1/01/blob/master/imagenes/1.jpg?raw=true)

------------
Seguido a esto se inicia la secuencia de JavaScript la cual inicialmente declara las variables necesarias para ejecutar la función que permite la pausa del proceso segundario

------------
![](https://github.com/Dtorz1/01/blob/master/imagenes/2.jpg?raw=true)

------------

Dentro de la función se encuentra un if el cual imprime los números hasta el 100, pero mientras no llegue a 100 se imprime constantemente un numero sumando uno más , Este proceso se repite dos veces, una para cada recuadro haciendo que la impresión sea independiente para cada uno

------------
![](https://github.com/Dtorz1/01/blob/master/imagenes/3.jpg?raw=true)

------------

El complemento clearinterval es el que pausa cada proceso cuando se inicia el siguiente, se usa dos veces en cada función, al principio para pausar el proceso del otro, y al final para pausarse a si mismo si inicia el otro proceso 

------------
![](https://github.com/Dtorz1/01/blob/master/imagenes/4.jpg?raw=true)

------------

Al final de cada función se encuentra un temporizador el cual imprime los números cada 1000 milisegundo uno debajo del otro usando "< BR>"

------------
![](https://github.com/Dtorz1/01/blob/master/imagenes/5.jpg?raw=true)

------------
Después de hacer toda la parte funcional finalmente se realiza la estructura de la pagina la cual consiste en colocar el título, crear los botones y las casillas donde se imprimen los números.

Pero en cada botón se usa el parámetro “enclocó” envía la petición desde la parte HTML y la conecta con el JavaScript iniciando las funciones mencionadas anteriormente

------------
![](https://github.com/Dtorz1/01/blob/master/imagenes/7.jpg?raw=true)

------------
