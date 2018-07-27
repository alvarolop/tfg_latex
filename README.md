# Analysis and design of multi-level actuation policies to minimize the energy consumption of enterprise servers
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


## Keywords

Data Centers, Enterprise server, power consumption, fans, memory, CPU, DVFS, energy efficiency 


## Authors

* **Álvaro López Medina** 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details
