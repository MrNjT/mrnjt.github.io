---
title: "OCV Guided Clock Tree Topology Reconstruction"
collection: publications
permalink: /publication/ASPDAC18
excerpt: 'In this paper, a framework that performs OCV guided clock tree topology reconstruction is proposed. 
The framework reconstructs the topology of a clock tree while improving the lower bounds on the worst negative slack (WNS)
and the total negative slack (TNS). Next, traditional CTO is employed to reduce WNS and TNS to the improved lower bounds'
date: 2019-01-21
venue: 'Asia and South Pacific Design Automation Conference'
paperurl: 'https://ieeexplore.ieee.org/document/8297372'
citation: ''
---

The timing performance of clock trees in scaled technology nodes may be severely degraded by on-chip variations (OCV).
Clock tree optimization (CTO) is employed to eliminate timing violations by specifying a set of non-negative delay adjustments
using a linear programming (LP) formulation. Next, the delay adjustments are realized in the clock tree by inserting delay 
buffers and detour wires. The drawback is that given the topology of the initial clock tree, it may be impossible to remove 
all timing violations. In this paper, a framework that performs OCV guided clock tree topology reconstruction is proposed. 
The framework reconstructs the topology of a clock tree while improving the lower bounds on the worst negative slack (WNS) and 
the total negative slack (TNS). Next, traditional CTO is employed to reduce WNS and TNS to the improved lower bounds. 
The reconstruction of the clock tree topology is guided by a predicted leaf buffer slack graph (pLB-SG). The leaf buffers
that must be placed closer in the tree topology are identified by detecting cycles (or strongly connected components) in the 
pLB-SG. The experimental results demonstrate that the proposed framework can on the average reduce WNS and TNS with 84% and
80%, respectively.


[Download paper here](https://ieeexplore.ieee.org/document/8297372)

Recommended citation: N Uysal, R Ewetz. (2018). "OCV Guided Clock Tree Topology Reconstruction" <i>ASPDAC'18</i>. 1(2).
