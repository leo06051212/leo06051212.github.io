---
title: "A Framework for Mapping Convolutional Neural Network onto Memristor Crossbars"
collection: publications
permalink: /publication/2024-10-29-CNN_Memristor
excerpt: ''
date: 2024-10-29
venue: '2024 IEEE 13th Global Conference on Consumer Electronics (GCCE)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10760655'
citation: 'J. Li, Y. Fu, C. -W. Sham and S. L. Ma, "A Framework for Mapping Convolutional Neural Network onto Memristor Crossbars," 2024 IEEE 13th Global Conference on Consumer Electronics (GCCE), Kitakyushu, Japan, 2024, pp. 1390-1393, doi: 10.1109/GCCE62371.2024.10760655.'
---

The processing-in-memory architecture based on memristors has been widely studied for hardware implementation in neural networks, serving as a solution to address the von Neumann bottleneck. Unfortunately, conventional memristor-based circuit design flows make it challenging for researchers to keep up with the rapid pace of innovations in neural networks. To tackle this issue, we propose an open-source framework that takes PyTorch-described model and user-provided data, automatically generating hardware implementations for memristor-based convolutional neural networks (CNNs) using high-level synthesis (HLS). This framework produces SPICE netlist files for CNN layers with our carefully designed memristor layout algorithm, and experimental results demonstrate our proposed framework's excellent performance and flexibility. It significantly accelerates researchers in constructing memristor-based CNN circuits and reduces the risk of errors when manually constructing SPICE circuit netlists.

Recommended citation: 

@INPROCEEDINGS{10760655,
  author={Li, Jiale and Fu, Yulin and Sham, Chiu-Wing and Ma, Sean Longyu},
  booktitle={2024 IEEE 13th Global Conference on Consumer Electronics (GCCE)}, 
  title={A Framework for Mapping Convolutional Neural Network onto Memristor Crossbars}, 
  year={2024},
  volume={},
  number={},
  pages={1390-1393},
  keywords={Analytical models;Technological innovation;Computational modeling;Neural networks;Memristors;Computer architecture;SPICE;Hardware;Convolutional neural networks;Integrated circuit modeling;Processing-In-Memory Architecture;Memristor Crossbars;Weight Mapping;CNN},
  doi={10.1109/GCCE62371.2024.10760655}}
