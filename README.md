# EjercicioCuidandonos
Hecho por Nataly Rohling y Valentina Thiwissen
Decisiones de diseño para esta actividad 
Punto 1
Utilizamos el patrón adapter para la parte del API REST, ya que este nos permite utlizar la api como si estuviera desarollada.
Utilizamos el patron strategy ya que  tenemos diferentes formas de reaccionar en caso de incidentes por lo cual hicimos una clase por cada forma de reaccionar y estas implementan la interfaz ReaccionIncidentes con el métotod reacionar ().
Utilizamos el patrón State para los estados del viaje. Cabe mencionar que no utilizamos el patron strategy ya que este no nos permite definir transiciones entre los posibles estados,  y el patrón State si, por lo cual fue elegido.

Punto 2
Agregamos la clase parada, la cual tiene un origen , un destino, un tiempo que permaneció en cada parada. Al agregar el atirbuto tiempo que permanecio podemos contemplar el caso en que no se haya detenido, como se menciona en la consigna.

