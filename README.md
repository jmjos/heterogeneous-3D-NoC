This is the project repository containing a extensive suite of tools for the design of NoCs for heterogeneous 3D SoCs. We provide:
- A lightweight and efficient implementation of a 3D NoC router 
- A NoC simulator with support for heterogeneous 3D SoCs. In includes a high-level model of the router.
- Design tools for NoCs targeting heterogeneous 3D SoCs.

You can download the resources via this repo using a recursive git clone (we linked the subprojects via git-submodules) or directly on the individual repositories.

## Introduction to NoCs for heterogeneous 3D SoCs

New manufacturing methods enable the production of heterogeneous 3D System-on-Chips (3D SoCs), in which dies, manufactured in disparate technology nodes, are stacked. Heterogeneity is one of the most promising paradigms to combine sensing and processing in a single 3D chip. For instance, it is possible to integrate sensors, analog-digital conversion and digital processing, which have different and even contradicting requirements to technology. Communication architectures, which use the advantages of heterogeneity, have not been considered so far. We propose dedicated 3D Networks-on-chips that target heterogeneous 3D SoCs and further exploit the specific properties of silicon dies in disparate technologies. 

## Tools, designs, models, etc.

This site collects tools, models, hardware designs for NoCs for heterogeneous 3D SoCs.

### Simulator

The [ratatoskr simulator](github.com/jmjos/ratatoskr) can be used to simulate NoCs for heterogeneous 3D SoCs, because it accounts for technology features.

### Router

A router model will follow soon!

### Power models

Power models will follow soon!

### Design algorithms

Algorithms will follow soon!

## Publications

- Joseph, J.M., C. Blochwitz, A. García-Ortiz und T. Pionteck. „Area and power savings via asymmetric organization of buffers in 3D-NoCs for heterogeneous 3D-SoCs“. In: Microprocessors and Microsystems 48 (2017), S. 36–47. ISSN: 0141-9331. DOI: 10.1016/j.micpro.2016.09.011
- Joseph, J.M. und T. Pionteck. „A cycle-accurate Network-on-Chip simulator with support for abstract task graph modeling“. In: International Symposium on System-on-Chip. IEEE, 2014, S. 1–6. ISBN: 978-1-4799-6890-9. DOI: 10.1109/ISSOC.2014.6972440
- Joseph, J.M., C. Blochwitz, A. García-Oritz und T. Pionteck. „Area and power savings via buffer reorganization in asymmetric 3D-NoCs for heterogeneous 3D-SoCs“. In: Nordic Circuits and Systems Conference. IEEE, 2015, S. 1–4. ISBN: 978-1-4673-6576-5. DOI: 10.1109/NOR-CHIP.2015.7364370
- Joseph, J.M., C. Blochwitz und T. Pionteck. „Adaptive allocation of default router paths in Network-on-Chips for latency reduction“. In: International Conference on High Performance Computing & Simulation. IEEE, 2016, S. 140–147. ISBN: 978-1-5090-2088-1. DOI: 10.1109/HPCSim.2016.7568328
- Joseph, J.M., S. Wrieden, C. Blochwitz, A. García-Oritz und T. Pionteck. „A simulation environment for design space exploration for asymmetric 3D-Network-on-Chip“. In: International Symposium on Reconfigurable Communication-centric Systems-on-Chip. IEEE, 2016, S. 1–8. ISBN: 978-1-5090-2520-6. DOI: 10.1109/ReCoSoC.2016.7533908
- Joseph, J.M., L. Bamberg, S. Wrieden, D. Ermel, A. García-Oritz und T. Pionteck. „Design method for asymmetric 3D interconnect architectures with high level models“. In: International Symposium on Reconfigurable Communication-centric Systems-on-Chip.
IEEE, 2017, S. 1–8. ISBN: 978-1-5386-3344-1. DOI: 10.1109/ReCoSoC.2017.8016143
- Joseph, J.M., L. Bamberg, G. Krell, I. Hajjar, A. García-Oritz und T. Pionteck. „Specification of Simulation Models for NoCs in Heterogeneous 3D SoCs“. In: International Symposium on Reconfigurable Communication-centric Systems-on-Chip (2018), S. 1–8
- T. Drewes, Joseph, J.M. und T. Pionteck. „An FPGA-based prototyping framework for Networks-on-Chip“. In: International Conference on ReConFigurable and FPGAs. IEEE, 2017, S. 1–7. DOI: 10.1109/RECONFIG.2017.8279775
- L. Bamberg, Joseph, J.M., R. Schmidt, T. Pionteck und A. García-Oritz. „Coding-aware Link Energy Estimation for 2D and 3D Networks-on-Chip with Virtual Channels“. In: International Symposium on Power and Timing Modeling, Optimization and Simulation (2018), S. 222–228

## People 
The following people participated:
- [Lennart Bamberg](github.com/lennartjanis): Physical models and hardware implementation
- [Jan Moritz Joseph](https://github.com/jmjos): Simulation tools and design optimization
- Prof. Dr.-Ing. Alberto Garcia Ortiz
- Prof. Dr.-Ing. Thilo Pionteck
- Sven Wrieden
- Imad Hajjar

## Acknolegdements

This work is funded by the German Research Foundation (DFG) project GA 763/7-1 and PI 477/8-1.

We are very grateful for the help of [Prof. Dr. Volker Kaibel](https://www.math.uni-magdeburg.de/~kaibel/).
