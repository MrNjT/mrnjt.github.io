---
title: "Latency constraint guided buffer sizing and layer assignment for clock trees with useful skew"
collection: publications
permalink: /publication/LCGBS
excerpt: 'In this paper, we propose a latency constraint guided buffer sizing and layer assignment framework for clock trees with useful skew, called the (BLU) framework. The BLU framework realizes delay adjustments during CTO by performing buffer sizing and layer assignment.'
date: 2019-01-21
venue: 'Asia and South Pacific Design Automation Conference'
paperurl: 'https://dl.acm.org/citation.cfm?id=3287681'
citation: ''
---

Closing timing using clock tree optimization (CTO) is a tremendously challenging problem that may require designer intervention. CTO is performed by specifying and realizing delay adjustments in an initially constructed clock tree. Delay adjustments are typically realized by inserting delay buffers or detour wires. In this paper, we propose a latency constraint guided buffer sizing and layer assignment framework for clock trees with useful skew, called the (BLU) framework. The BLU framework realizes delay adjustments during CTO by performing buffer sizing and layer assignment. Layer assignment is a more gentle way of realizing delay adjustments than buffer insertion. Moreover, power consumption may be saved by depromoting non-critical clock paths. Given an initial clock tree, the BLU framework first predicts the final timing quality and specifies a set of delay adjustments, which are translated into latency constraints. Next, buffer sizing and layer assignment is performed with respect to the latency constraints using an extension of van Ginneken's algorithm. Moreover, the framework includes a feature of reducing the power consumption by relaxing the latency constraints and a method of improving the timing performance by tightening the latency constraints. Theexperimental results demonstrate that the proposed framework is capable of reducing the capacitive cost with 13% on the average. The total negative slack (TNS) and worst negative slack (WNS) are reduced with up to 58% and 20%, respectively.

[Download paper here](https://dl.acm.org/citation.cfm?id=3287681)

Recommended citation: N Uysal, WH Liu, R Ewetz. (2019). "Latency constraint guided buffer sizing and layer assignment for clock trees with useful skew" <i>ASPDAC'19</i>. 1(2).
