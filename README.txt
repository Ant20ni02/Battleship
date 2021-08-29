 _           _   _   _           _     _       
| |         | | | | | |         | |   (_)      
| |__   __ _| |_| |_| | ___  ___| |__  _ _ __  
| '_ \ / _` | __| __| |/ _ \/ __| '_ \| | '_ \ 
| |_) | (_| | |_| |_| |  __/\__ \ | | | | |_) |
|_.__/ \__,_|\__|\__|_|\___||___/_| |_|_| .__/ 
                                        | |    
                                        |_|    
=======================================================================

Instrucciones

Descripcion y Objetivo:

Battleship es un juego de logica y estrategia para dos jugadores, en el cual 
ambos intentaran adivinar donde esta la flota enemiga e intentaran hundirla
Cada jugador posee un tablero de 10 x 10, en el cual se colocaran sus barcos.
El primer jugador que llegue al porcentaje de hundimientos establecido gana el
juego.

Tablero Barcos:
Cada judador
En el juego existen 5 tipos de barcos, cada uno que abarca diferentes casillas

• Patrulla: 2 casillas.
• Destructor: 3 casillas.
• Submarino: 3 casillas.
• Barco de guerra: 4 casillas.
• Portaaviones: 5 casillas.


Inicio del Juego:
Antes de iniciar se deben establecer las reglas para el juego. Primero, el programa
va a pedir la cantidad de turnos que se jugaran en la partida, este numero puede ser cualquiera.

Posteriormente, el juego solicita el porcentaje de hundimientos necesario para ganar el juego.
Este puede ser un numero positivo entero del mayor a cero y menor o igual a 100.

Por ultimo, debes introducir el nombre de cada jugador.

-Salida de la consola:

	Configuración de la partida
	Número de turnos: 20
	Porcentaje de hundimientos para ganar: 10

	Introduce el nombre del Jugador 1: Mike
	Introduce el nombre del Jugador 2: Marco

Desarrollo del Juego

Al comenzar el juego, los barcos se colocan aleatoriamente dentro de la cuadricula 
de 10 x 10 de su respectivo jugador, ya sea en posicion vertical u horizontal. Los jugadores
toman turnos para introducir una coordenada valida que consista de un renglon (de la A a la J), 
y una columna (del 1 al 10). Si hay un barco en la coordenada introducida, la consola dara la 
salida <Tocado>.

	<Marco, Jugador 2, Turno 1>
	A 3
	<1, 2, A, 3>
	< Tocado >

Si en la coordenada no hay ningun barco, la consola dara la salida <Agua>.

	<Mike, Jugador 1, Turno 1>
	D 4 
	<1,1,D,4>
	<Agua>
	
Una vez que todas las casillas de un barco hayan sido tocadas, el barco estara hundido, y la 
consola dara la salida <Hundido>:

	<Mike, Jugador 1, Turno 7>
	D 1 
	<1,7,D,1>
	<Hundido>

Fin del Juego:

El juego termina cuando se alcance el porcentaje de hundimiento que se 
establecio al principio (ej. si el porcentaje es de 50%, se debe atinar a 9 casillas de la flota 
enemiga para ganar. El jugador que haga los hundimientos necesarios es declarado ganador. Si se 
acaban los turnos y nadie ha alcanzado este procentaje, el juego termina y nadie es declarado
ganador.

Si se desea acabar el juego prematuramente, deben introducirse a la consola las coordenadas S 0. 
Al hacer esto, el juego terminara instantaneamente y no se declara ganador.

	<Marco, Jugador 2, Turno 2>
	S 0
	La partida acabo, nadie gano

=======================================================================

				     # #  ( )
                                  ___#_#___|__
                              _  |____________|  _
                       _=====| | |            | | |==== _
                 =====| |.---------------------------. | |====
   <--------------------'   .  .  .  .  .  .  .  .   '--------------/
     \                                                             /
      \_______________________________________________WWS_________/
  wwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwww
wwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwww
   wwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwww 

