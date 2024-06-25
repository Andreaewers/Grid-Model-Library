# Grid-Model-Library
Library of modified grid models for Topology and Redispatch Optimization. The purpose of the modifications is to use the grid model to optimize redispatch and grid topology to avoid overloads. 

# Contents
Provided data includes modified grid models in uct file format ([format description](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwihooTz0vOEAxUd8wIHHaM0AoIQFnoECBMQAQ&url=https%3A%2F%2Fwww.entsoe.eu%2Ffileadmin%2Fuser_upload%2F_library%2Fpublications%2Fce%2Fotherreports%2FUCTE-format.pdf&usg=AOvVaw0Gm2W7eOSXAeIEZ40vH2vk&opi=89978449)) as well as synthetically generated system use cases (SUC) that cause overloads in the grid in the n-1-case (if one grid element fails).  

# Citation 
Until the upcoming work is published, please use this citation:

```
@article{EWERSZUMRODE2024110700,
title = {An iterative approach to grid topology and redispatch optimization in congestion management},
journal = {Electric Power Systems Research},
volume = {234},
pages = {110700},
year = {2024},
issn = {0378-7796},
doi = {https://doi.org/10.1016/j.epsr.2024.110700},
url = {https://www.sciencedirect.com/science/article/pii/S0378779624005868},
author = {Andrea Ewerszumrode and Niklas Erle and Simon Krahl and Albert Moser},
keywords = {Approximation algorithms, Linearized models, Redispatch optimization, Topology optimization},
abstract = {The selection of Remedial Actions (RA) to ensure system security is a highly complex task performed by Transmission System Operators (TSOs). Phase shifting transformer (PST) tap changes and active power changes of generation units (redispatch) are some RA available in Security Constrained Optimal Power Flow (SCOPF) simulations within the operational planning processes. Topological RA are not part of these SCOPF yet, as the optimization thereof adds high complexity to the existing optimization problem. To overcome this complexity, this paper introduces an iterative approach that decouples topology optimization from redispatch & PST optimization. Linearized models of RA are used to meet computation time requirements. Exemplary investigations of the presented method were performed based on modified IEEE 39-Bus, 118-Bus and PEGASE-1354-Bus grid models. Within the scope of these investigations, the method shows good results and a great potential for the reduction of congestions and required redispatch through topological RA. In order to eliminate inaccuracies of the approach and to further improve its suitability for use in grid operation, a need for future investigations and possible further developments were identified.}
}
```
