

idea principal:

sistema multi-agente en el que cada agente debera de controlar 1 peloton individual (habiendo 4 en el equipo azul) y luego un agente que gestione a los 4 agentes de cada peloton (1 agente q controla 4 agentes).

la mision de estos agentes es tomar los puntos A,B y C del mapa de normandia, al mismo tiempo que luchar contra el equipo rojo, el equipo azul tiene una inferioridad de 1:3

Pelotones:
- formado por 5 tanques
- si hay 5 tanques y la vida de cada uno es 100, el peloton tiene 500HP si este baja de 100HP se asume que uno de los que lo formaban ha sido destruido y la capacidad de fuego disminuye de 5 a 4 tanques haciendo menos daño
- cada tanque hace un determinado daño, este se multiplica por el nº de tanques que forman el peloton
- se tienen 100 de gas y 15-20 de municion por tanque
- deben de evitar los obstaculos que se generan en el mapa
- deben recoger los suministros

Puntos:
- El pto B es el mas valioso
- A y C mismo valor
- en los puntos se podran recoger suministros
- tienen un limite de suministros 1000 de gas y 50 de municion

Equipo Rojo:
- de primeras estara hardcodeado, luego se intentara que fuese otro agente

Equipo Azul:
- 4 pelotones manejados cada uno por un agente singular (4 agentes)

Mapa:
- habran 3 puntos de interes (A,B,C)
- se generaran obstaculos de manera aleatoria y procedural en el mapa
- el grid 50x50 o 25x25


Posible implementacion de Perbatin (Si sobra tiempo) [nivel de locura de las tropas]