---
title: "Data-Driven Graph Construction of Power Flow Graphs for Electric Power Transmission Networks"
collection: 'publications'
permalink: '/publication/2024-gc4eptn'
excerpt: '[Source Code](https://github.com/RL-BCI-Lab/gc4eptn)'
date: 2024-12-18
venue: 'ICMLA'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10022137'
citation: 'Poole, B., Ratnakumar R., Madurasinghe, D., Kuemmerle, C., Venayagamoorthy, G., Lee, M. (2024). Data-Driven Graph Construction of Power Flow Graphs for Electric Power Transmission Networks. <i>2024 International Conference on Machine Learning and Applications (ICMLA)</i>.'
---
A comprehensive understanding of the topology of the electric power transmission network (EPTN) is essential for reliable and robust control of power systems. While existing research primarily relies on domain-specific methods, it lacks data-driven approaches that have proven effective in modeling the topology of complex systems. To address this gap, this paper explores the potential of data-driven methods for more accurate and adaptive solutions to uncover the true underlying topology of EPTNs. First, this paper examines Gaussian Graphical Models (GGM) to create an EPTN network graph (i.e., undirected simple graph). Second, to further refine and validate this estimated network graph, a physics-based, domain-specific refinement algorithm is proposed to prune false edges and construct the corresponding electric power flow network graph (i.e., directed multi-graph). The proposed method is tested using a synchrophasor dataset collected from a two-area, four-machine power system simulated on the real-time digital simulator (RTDS) platform. Experimental results show both the network and flow graphs can be reconstructed using various operating conditions and topologies with limited failure cases. 