# PGONet: A Physics-Informed Generative Adversarial Network for Advancing Solutions in Ocean Acoustics

Special thanks to the following work. We wrote the code for this project based on the open source code of this paper.

```
@article{ren2022phycrnet,
  title={PhyCRNet: Physics-informed convolutional-recurrent network for solving spatiotemporal PDEs},
  author={Ren, Pu and Rao, Chengping and Liu, Yang and Wang, Jian-Xun and Sun, Hao},
  journal={Computer Methods in Applied Mechanics and Engineering},
  volume={389},
  pages={114399},
  year={2022},
  publisher={Elsevier}
}
```
https://github.com/isds-neu/PhyCRNet

FFT&Plot is a post-processing program (including Fourier transform) used to calculate converged solutions and a paper image drawing program. The calculation steps can refer to the following paper.
```
@article{r4,
title = {Direct numerical simulation of acoustic wave propagation in ocean waveguides using a parallel finite volume solver},
journal = {Ocean Engineering},
volume = {281},
pages = {114894},
year = {2023},
issn = {0029-8018},
doi = {https://doi.org/10.1016/j.oceaneng.2023.114894},
url = {https://www.sciencedirect.com/science/article/pii/S0029801823012787},
author = {Rui Xia and Xiao-Wei Guo and Chao Li and Jie Liu},
keywords = {Ocean waveguide, Direct acoustic solver, Finite volume method, Wave equation}
}

```

PINN_bench is a PINN benchmark comparison case, where Test.py is a program for generating boundaries and initial sampling points. 
This program is modified from https://github.com/farscape-project/PINNs_Benchmark. Thanks to the provider.

The corresponding relationship between the case program is shown in the following table:


| Case |   Case Generation    |     Case Test      |
|:-----|:--------------------:|:------------------:|
| 1    |   Test_boundary.py   |  PGO_BOUNDARY.py   |
| 2-4  |  Test_Forward1-3.py  | PGO_FORWARD1-3.py  |
| 5-8  | Test_Gen_Floor1-4.py | PGO_SeaFloor1-4.py |
| 9-12 | Test_Gen_Multi1-4.py |   PGO_OBS1-4.py    |
| 13   | Test_Performance.py  | PGO_PERFORMANCE.py |

Any questions about the code can be directed to xiarui21@nudt.edu.cn.

Due to the size limit of GitHub file transfer, we provide a more complete version on Baidu Netdisk.

Site: https://pan.baidu.com/s/19EOrlFM9CkOVcWHafocvPg?pwd=p1io 
Code: p1io

