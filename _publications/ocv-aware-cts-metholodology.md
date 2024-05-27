---
title: "Latency constraint guided buffer sizing and layer assignment for clock trees with useful skew"
collection: publications
permalink: /publication/ocv-aware-cts-metholodology
excerpt: 'In this paper, we propose an OCV-aware clock tree synthesis methodology that aims to rethink how to account for OCVs. The key idea is to predict the impact of OCVs early in the synthesis process, which allows the variations to be compensated for using non-uniform safety margins. This results in a synthesis flow that is almost correct-by-design. '
date: 2021-06-21
venue: '2021 IEEE/ACM International Conference on Computer Aided Design (ICCAD)'
paperurl: 'https://par.nsf.gov/servlets/purl/10351582#:~:text=The%20proposed%20OCV-aware%20clock,variations%20within%20every%20timing%20constraint.'
citation: 'N. Uysal and R. Ewetz, "An OCV-Aware Clock Tree Synthesis Methodology," 2021 IEEE/ACM International Conference On Computer Aided Design (ICCAD), Munich, Germany, 2021, pp. 1-9, doi: 10.1109/ICCAD51958.2021.9643585.
'
---

Closing timing after clock tree synthesis (CTS) is very challenging in the presence of on-chip variations (OCVs). State-of-the-art design flows first synthesize an initial clock tree that contains timing violations introduced by OCVs. Next, aggressive clock tree optimization (CTO) is applied to eliminate the timing violations. Unfortunately, it may be impossible to eliminate all violations given the structure of the initial clock tree. In this paper, we propose an OCV-aware clock tree synthesis methodology that aims to rethink how to account for OCVs. The key idea is to predict the impact of OCVs early in the synthesis process, which allows the variations to be compensated for using non-uniform safety margins. This results in a synthesis flow that is almost correct-by-design. In contrast, state-of-the-art design flows often have an unpredictable success rate because the OCVs are considered too late in the synthesis process. Concretely, this is achieved by top-down constructing a virtual clock tree that is refined bottom-up into a real clock tree implementation. To balance the quality of results (QoR) and runtime, multiple top-level tree topologies are enumerated and pruned in the synthesis process. Compared with the CTO based approach, the experimental results demonstrate that the proposed methodology reduces the total negative slack (TNS) and worst negative slack (WNS) with 90% and 75%, respectively.

[Download paper here](https://par.nsf.gov/servlets/purl/10351582#:~:text=The%20proposed%20OCV-aware%20clock,variations%20within%20every%20timing%20constraint.)

Recommended citation: N. Uysal and R. Ewetz, "An OCV-Aware Clock Tree Synthesis Methodology," 2021 IEEE/ACM International Conference On Computer Aided Design (ICCAD), Munich, Germany, 2021, pp. 1-9, doi: 10.1109/ICCAD51958.2021.9643585.

