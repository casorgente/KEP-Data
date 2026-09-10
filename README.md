This repository contains the dataset used in the research paper _"Reconfigurable matchings and back-arcs recourse actions in kidney paired exchange programs"_ by C. Sorgente, D. Serra, M. Gentili, R. Cerulli.

## Description
The [compatibility](https://github.com/casorgente/KEP-Data/tree/main/compatibility) folder contains 8 compatibility graphs, each associated with 160 incompatible patient-donor pairs, generated using the instance generation tool made available by Delorme et al. [[1]](#1).
We used the default preset of compatibility parameter values provided by the tool, which is based on the original generator described by Saidman et al. [[2]](#2).

For each compatibility graph, the [arrivals](https://github.com/casorgente/KEP-Data/tree/main/arrivals) folder contains 5 files, each specifying a different arrival schedule. Each schedule determines the order in which pairs enter the program over the 20 matching runs conducted every three months throughout the five-year simulation period.

## References
<a id="1">[1]</a> 
M. Delorme, S. García, J. Gondzio, J. Kalcsics, D. Manlove, W. Pettersson, J. Trimble.
Improved instance generation for kidney exchange programmes,
Computers & Operations Research,
Volume 141,
2022,
105707,
ISSN 0305-0548,
DOI: 10.1016/j.cor.2022.105707.

<a id="2">[2]</a> 
S.L. Saidman, A.E. Roth, T. Sönmez, M.U. Ünver, F.L. Delmonico.
Increasing the Opportunity of Live Kidney Donation by Matching for Two- and Three-Way Exchanges.
Transplantation 81(5):p 773-782, March 15, 2006.
DOI: 10.1097/01.tp.0000195775.77081.25
