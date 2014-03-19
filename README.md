TP-IOO-TN-UADE
==============

Trabajo Práctico Cuatrimestral - Introducción a la Orientación a Objetos  - Sistema de Tragamonedas


Consignas:
El equipo de analistas ha finalizado el relevamiento y cotización de un sistema que gestiona el funcionamiento de maquinas tragamonedas.

Se solicita al equipo de diseñadores que diseñe e implemente el sistema relevado.  A continuación se detalla el relevamiento y los requerimientos relevados por el equipo.

•	Una máquina tragamonedas se caracteriza por un número fijo de casillas que utiliza para formar la combinación. En cada casilla se mostrará una fruta que puede ser frutilla, sandía, banana, manzana o pera.

•	La máquina tiene una recaudación, que se corresponde con la cantidad de dinero que contiene. 

•	Se puede crear la máquina con una recaudación inicial para dar premios. La recaudación se irá incrementando con las jugadas de los usuarios y se reducirá cuando se concedan premios.

•	La maquina también tiene un valor de recaudación mínimo, cuando se alcanza ese valor se debe mostrar un mensaje en pantalla indicando que se ha alcanzado la recaudación mínima y existe posibilidad de no poder pagar los próximos premios.

•	Cada máquina gestiona el conjunto de premios que puede dar, el sistema debe permitir el alta y baja de premios.

•	Cada premio consiste en una combinación concreta de frutas a la que le corresponde una cantidad fija de dinero. Nótese que el número de frutas de la combinación dependerá de la máquina tragamonedas en la que se va a registrar dicho premio. Por tanto, en una máquina sólo podrán registrarse aquellos premios cuyo tamaño de la combinación coincida con el número de casillas de dicha máquina. Por ejemplo: combinación de tres frutillas premio $50,  combinación de dos frutillas y una pera $ 5.

•	El precio de una jugada es fijo para cada máquina. Se puede jugar si el crédito disponible en la máquina es igual o superior al coste de la jugada. El crédito puede incrementarse explícitamente a través de una función en el sistema y también se incrementará cada vez que se consiga un premio.

•	En cualquier momento se puede cobrar el crédito disponible.

•	En cada jugada se generará aleatoriamente una combinación de frutas del tamaño de la combinación fijado en la máquina y se comprobará si: 


o	A)dicha combinación tiene premio (es decir, se encuentra entre los premios registrados)


o	B) el premio a conceder es menor o igual que la recaudación.


o	C) el premio es aceptado. De ser así se incrementará el crédito disponible.


•	La máquina no concede los premios de forma automática, la máquina siempre debe recibir la orden de aceptación del premio.

Se pide:

-	Documentar el diseño del sistema e implementar utilizando la metodología de RUP en base a las siguientes fases:


o	Primera Fase: ENTREGA PARA LA FECHA 28-05-14
	Parametrización de Maquina
	Incremento de crédito


o	Segunda Fase: ENTREGA PARA LA FECHA 18-06-14
	Jugar con la maquina
