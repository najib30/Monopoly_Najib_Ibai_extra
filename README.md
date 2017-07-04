# Monopoly_Najib_Ibai_extra
junto la estructura del proyecto aún falta añadir mas logica y leer de los xml, pero la estructura y clases que vamos a tener ya están, por tanto tenemos un 80% hecho.

La clase control es el unico objetco con el que vamos a trabajar. la clase control va a contener todos los demas objetos. ( tablero, casillas. jugadores,etc)
La clase control cuando hablemos con el servlet le diremos  control crear partida, control edificar, control guardar pàrtida,etc
Depues cogeremos el objeto control. (desde la web le diremos guardar) para ello en la sesion del servlet los serializamos y lo guardaremos en un fichero
La clase control va a tener toda la logica m sera transparente del interfaz.
Como la clase control es serializable y todos las clases que va a contener lo seran tambien ( array list. casilla, jugador, tarjeta  y tablero) podremos guardar y cargar la partida

