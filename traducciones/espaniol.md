<p align = "center">
<font size ="5.5px"><a href = "https://github.com/spuertaf/energetica2030/blob/main/traducciones/espaniol.md">Español</a>
                                                                              |
<a href = "https://github.com/spuertaf/energetica2030/blob/main/README.md">English</a></font> 
</p>

# Contextualizacion
Este proyecto hace parte de la iniciativa [energetica 2030](https://www.energetica2030.co/), concretamente del [p8 - Microrredes](https://www.energetica2030.co/p8-microrredes/), conformada por 8 universidad y 3 empresas la cual busca definir estrategias de transformacion del sector energético colombiano para el 2030. 

Este proyecto en cuestion pretende atacar un problema de visualizacion de los datos captados por un panel solar.
<br></br>

## El problema
Inicialmente se tendran cinco (5) laboratorios piloto, cada uno de ellos se encontrara equipado con un panel solar.  
**El problema** se presenta a la hora de visualizar los datos capatados por el panel solar, ya que la unica manera de acceder a estos datos es a traves de la terminal, ademas, los mismos no son presentados de una forma legible.
<br></br>

![](https://github.com/spuertaf/energetica2030/blob/main/recursos/datosPanelTerminal.png)

*Figura 1.* Datos captados por el panel mostrados por la terminal. 

## La solucion
Teniendo el problema en mente se penso en una solucion: un desarrollo que se conectara con el panel, recolectara la informacion captada y permitiera la visualizacion de los datos captados por el panel en graficas.  
El panel solar de la Universidad EAFIT fue usado como entorno de pruebas.

![](https://github.com/spuertaf/energetica2030/blob/main/recursos/panelSolarEAFIT.png)

*Figura 2.* Panel solar de la Universidad EAFIT.

## Los resultados
Finalmente el desarrollo realizado concluye de manera satisfactoria dando como resultado una mejor visualizacion de los datos captados por el panel solar.

![](https://github.com/spuertaf/energetica2030/blob/main/recursos/graficasGrafana.png)
*Figura 3.* Visualizacion de los datos captados por el panel en Grafana.

<br></br>

El codigo de la aplicacion para obtener los datos captados por el panel y enviarlo al entorno de visualizacion Grafana se encuentra en: [desarrollo](https://github.com/spuertaf/energetica2030/tree/main/desarrollo)

<br></br>
<br></br>

<p align="center">
<img src="https://github.com/spuertaf/energetica2030/blob/main/recursos/energeticaEAFIT.png">
</p>
