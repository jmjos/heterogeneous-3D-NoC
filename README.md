## Introduction 

This is the project repository containing a extensive suite of tools for the design of NoCs for heterogeneous 3D SoCs. We provide:
- A lightweight and efficient implementation of a 3D NoC router 
- A NoC simulator with support for heterogeneous 3D SoCs. In includes a high-level model of the router.
- Design tools for NoCs targeting heterogeneous 3D SoCs.

You can download the resources via this repo using a recursive git clone ```git clone --recursive https://github.com/jmjos/heterogeneous-3D-NoC``` or directly on the individual repositories.

## NoCs for heterogeneous 3D SoCs

New manufacturing methods enable the production of heterogeneous 3D System-on-Chips (3D SoCs), in which dies, manufactured in disparate technology nodes, are stacked. Heterogeneity is one of the most promising paradigms to combine sensing and processing in a single 3D chip. For instance, it is possible to integrate sensors, analog-digital conversion and digital processing, which have different and even contradicting requirements to technology. Communication architectures, which use the advantages of heterogeneity, have not been considered so far. We propose dedicated 3D Networks-on-chips that target heterogeneous 3D SoCs and further exploit the specific properties of silicon dies in disparate technologies. 

## Tools, designs, models, etc.

This site collects tools, models, hardware designs for NoCs for heterogeneous 3D SoCs. 

### Getting started

Clone all project-related repositories with ```git clone --recursive https://github.com/jmjos/heterogeneous-3D-NoC``` 

### Simulator

The [ratatoskr simulator](github.com/jmjos/ratatoskr) can be used to simulate NoCs for heterogeneous 3D SoCs, because it accounts for technology features.

### Router

A router model will follow soon!

### Power models

We use the power models proposed in Bamberg, L., Amir Najafi  and Garcia-Ortiz, A. "Edge Effect Aware Crosstalk Avoidance Technique for 3D Integration". 27th International Symposium on Power and Timing Modeling, Optimization and Simulation (PATMOS), Sep. 25-27 2017, Thessaloniki (Greece), ©IEEE DOI: 10.1109/PATMOS.2017.8106994 

Implementations of the models will follow soon.

### Design algorithms

The [models](https://github.com/jmjos/A-3D-NoC-DSE) can be used for exact design optimization. Heuristics will be published after publication.

## Publications

- Joseph, J.M., Blochwitz, C., García-Ortiz, A. und Pionteck, T. "Area and power savings via asymmetric organization of buffers in 3D-NoCs for heterogeneous 3D-SoCs". In: Microprocessors and Microsystems 48 (2017), S. 36–47. ISSN: 0141-9331. DOI: 10.1016/j.micpro.2016.09.011
- Joseph, J.M. und Pionteck, T. "A cycle-accurate Network-on-Chip simulator with support for abstract task graph modeling". In: International Symposium on System-on-Chip. IEEE, 2014, S. 1–6. ISBN: 978-1-4799-6890-9. DOI: 10.1109/ISSOC.2014.6972440
- Joseph, J.M., Blochwitz, C., García-Oritz, A. und Pionteck, T. "Area and power savings via buffer reorganization in asymmetric 3D-NoCs for heterogeneous 3D-SoCs". In: Nordic Circuits and Systems Conference. IEEE, 2015, S. 1–4. ISBN: 978-1-4673-6576-5. DOI: 10.1109/NOR-CHIP.2015.7364370
- Joseph, J.M., Blochwitz, C. und Pionteck, T. "Adaptive allocation of default router paths in Network-on-Chips for latency reduction". In: International Conference on High Performance Computing & Simulation. IEEE, 2016, S. 140–147. ISBN: 978-1-5090-2088-1. DOI: 10.1109/HPCSim.2016.7568328
- Joseph, J.M., Wrieden, S., Blochwitz, C., García-Oritz, A. und Pionteck, T. "A simulation environment for design space exploration for asymmetric 3D-Network-on-Chip". In: International Symposium on Reconfigurable Communication-centric Systems-on-Chip. IEEE, 2016, S. 1–8. ISBN: 978-1-5090-2520-6. DOI: 10.1109/ReCoSoC.2016.7533908
- Joseph, J.M., L. Bamberg, Wrieden, S., Ermel, D., García-Oritz, A. und Pionteck, T. "Design method for asymmetric 3D interconnect architectures with high level models". In: International Symposium on Reconfigurable Communication-centric Systems-on-Chip. IEEE, 2017, S. 1–8. ISBN: 978-1-5386-3344-1. DOI: 10.1109/ReCoSoC.2017.8016143
- Joseph, J.M., L. Bamberg, Krell, G., Hajjar, I., García-Oritz, A. und Pionteck, T. "Specification of Simulation Models for NoCs in Heterogeneous 3D SoCs". In: International Symposium on Reconfigurable Communication-centric Systems-on-Chip (2018), S. 1–8
- Drewes, T. Joseph, J.M. und Pionteck, T. "An FPGA-based prototyping framework for Networks-on-Chip". In: International Conference on ReConFigurable and FPGAs. IEEE, 2017, S. 1–7. DOI: 10.1109/RECONFIG.2017.8279775
- Bamberg, L., Joseph, J.M., Schmidt, R., Pionteck, T. und García-Oritz, A. "Coding-aware Link Energy Estimation for 2D and 3D Networks-on-Chip with Virtual Channels". In: International Symposium on Power and Timing Modeling, Optimization and Simulation (2018), S. 222–228
- Bamberg, L. and Garcia-Ortiz, A. "Exploiting Temporal Misalignment to Optimize the Interconnect Performance for 3D Integration" 28th International Symposium on Power and Timing Modeling, Optimization and Simulation (PATMOS), Juli 2-4 2018, Costa Brava (Spain), IEEE DOI: 10.1109/PATMOS.2018.8464172
- Bamberg, L., Schmidt, R. and Garcia-Ortiz, A. "Low-Power Coding Approach for 3D Interconnects" 55th Design Automation Conference (DAC), June 24-28 2018, San Fransisco (California), IEEE/ACM DOI: 10.1145/3195970.3196010
- Bamberg, L., Najafi, A. and Garcia-Ortiz, A. "Edge Effect aware Low-Power Crosstalk Avoidance Technique for 3D Integration" Integration, the VLSI Journal, 2018, in press, ELSEVIER DOI: 10.1016/j.vlsi.2018.03.008
- Bamberg, L., Najafi, A. and Garcia-Ortiz, A. "Edge Effects on the TSV Array Capacitances and their Performance Influence" Integration, the VLSI Journal, vol. 61, pp. 1-10, March 2018, ELSEVIER DOI: 10.1016/j.vlsi.2017.10.003
- Bamberg, L. and Garcia-Ortiz, A. "High-Level Energy Estimation for Submicrometric TSV Arrays" IEEE Transactions on Very Large Scale Integration (VLSI) Systems, vol. 25, no. 10, pp. 2856-2866, Oct. 2017, IEEE DOI: 10.1109/TVLSI.2017.2713601 
- Bamberg, L., Amir Najafi  and Garcia-Ortiz, A. "Edge Effect Aware Crosstalk Avoidance Technique for 3D Integration". 27th International Symposium on Power and Timing Modeling, Optimization and Simulation (PATMOS), Sep. 25-27 2017, Thessaloniki (Greece), ©IEEE DOI: 10.1109/PATMOS.2017.8106994 (Awarded Best Paper) 


## People 
The following people participated:
- [Lennart Bamberg](github.com/lennartjanis): Physical models and hardware implementation
- [Jan Moritz Joseph](https://github.com/jmjos): Simulation tools and design optimization
- [Prof. Dr.-Ing. Alberto García-Ortiz](www.ids.uni-bremen.de/agarcia.html)
- [Prof. Dr.-Ing. Thilo Pionteck](http://www.iikt.ovgu.de/pionteck.html)
- Sven Wrieden
- Imad Hajjar

## Acknolegdements

This work is funded by the German Research Foundation (DFG) project GA 763/7-1 and PI 477/8-1.

We are very grateful for the help of [Prof. Dr. Volker Kaibel](https://www.math.uni-magdeburg.de/~kaibel/).
