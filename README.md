# Trabajo de Fin de Grado
This is the source code of the Latex project of my Bachelor's Thesis.

## Abstract

The aim of this Bachelor Thesis is to analyze control policies and power consumption improvement techniques in an enterprise server in order to minimize it in data centers.

Consequently, based on previous work of the research group, which has carried out an analytical modeling of an enterprise server, it is intended to analyze control policies and their possibility of automation in the subsystems of the server with the greatest impact on the overall power consumption.

This work is developed in a Decathlete Intel server which follows the requirements of the Open Compute Project. This project was initiated by Facebook with the goal of creating a server as efficient as possible. The choice of this server was based on two criteria: the great flexibility and automation. These two requirements are characteristic of this server because it is based in open hardware.

This way, the first step is to analyze and prioritize the subsystems to control depending on the expected savings. According to the previous modeling results, these systems will be the CPU, memory DIMMs, fans and disks. For each subsystem the most relevant possibilities will be evaluated. For example, in the case of the CPU we contemplate, among others, turning on and off the processor cores and the dynamic voltage and frequency scaling (DVFS).

In addition, the advantages and disadvantages of the performance will be analyzed in each of the subsystems at different levels of abstraction. For each subsystem the possibility of action is set. For example at: user level in the operating system, kernel level, service processor of the machine or even by varying parameters in the BIOS.

The main goal is to analyze all the possibilities in controlling each subsystem. To do so, efforts will be made to seek the highest level of abstraction so as to allow compatibility with a wider range of servers. However, working at high levels of abstraction may lead to a configurability loss.

Although the most suitable situation would be that there were tools at user level to control all subsystems, this is rarely the case in commercial servers. Therefore, another issue this project will tackle is the analysis of which subsystems are more limited and find out solutions for them, balancing the trade off between high configurability and possibility of generalizing the solution.

Finally, the implemented actions are validated by launching benchmarks for enterprise servers, analyzing the impact on energy savings of the actions proposed at various subsystems and various abstraction levels.


## Resumen del trabajo
El objetivo de este Trabajo de Fin de Grado es el de analizar técnicas de control y mejora del consumo en un servidor de altas prestaciones para la reducción del consumo energético en Centros de Datos. 

Para ello, partiendo de un trabajo previo del grupo de investigación en el que se llevaba a cabo un modelado analítico de un servidor de altas prestaciones, se pretenden analizar las políticas de control y la posibilidad de automatización de las mismas en los subsistemas del servidor con mayor impacto en el consumo total del mismo. 

Este trabajo se lleva a cabo en un servidor Intel Decathlete, del Open Compute Project, que es un proyecto iniciado por Facebook para buscar el servidor más eficiente posible. La elección de este servidor se ha basado en dos criterios: la gran flexibilidad y la capacidad de automatización, que son dos requisitos que cumple el mencionado servidor al basarse en hardware abierto.

De esta manera, como primer paso se analizarán y priorizarán los subsistemas a controlar en función del ahorro esperado. De acuerdo con el modelado anterior, estos sistemas serán la CPU, los DIMMs de memoria, los ventiladores y los discos. Para cada subsistema se evaluarán las posibilidades de actuación más relevantes. Por ejemplo, en el caso de actuación sobre CPU se contemplarán, entre otros, el apagado y encendido de núcleos del procesador, y el escalado dinámico de voltaje y frecuencia (DVFS).  

Además, se analizarán las ventajas e inconvenientes de la actuación, para cada uno de los subsistemas a diversos niveles de abstracción. Para cada sistema se establecerá la posibilidad de actuación, por ejemplo: a nivel de sistema operativo en espacio de usuario, a nivel de Kernel, procesador de servicio de la máquina o incluso mediante la variación de parámetros en la BIOS. 

El objetivo principal es analizar todas las técnicas actuales para controlar los subsistemas, implementando aquellas técnicas soportadas por el servidor. Para ello, se procurará buscar siempre el nivel de abstracción más alto de manera que permita una mayor simplicidad a la hora de trabajar, así como la compatibilidad con un rango mayor de servidores. Sin embargo, el trabajo a niveles altos de abstracción podrá suponer la pérdida de configurabilidad. 

A pesar de que el caso ideal sería que existieran herramientas a nivel de usuario para controlar todos los subsistemas, esto no suele ser así en servidores comerciales. Por ello, otra de las tareas en las que se centrará este trabajo será analizar qué subsistemas están más limitados y estudiar posibles soluciones, equilibrando el compromiso entre gran configurabilidad y posibilidad de generalizar la solución. 

Por último, se validarán las actuaciones implementadas mediante el lanzamiento de benchmarks para servidores de altas prestaciones, analizando el impacto en el ahorro de las actuaciones propuestas en los diversos subsistemas y a varios niveles.



## Keywords

Data Centers, Enterprise server, power consumption, fans, memory, CPU, DVFS, energy efficiency 


## Authors

* **Álvaro López Medina** 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
