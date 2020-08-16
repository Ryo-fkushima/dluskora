# **dluskora**
*for metamorphic petrologists*

**dluskola** is a viable tool for simulating trace-elements zoning patterns in a
prograde garnet porphyroblast in low-*T* eclogite.
This is based on the theory given by **Skora et al. (2006)**.
Using this tool, we can discuss the kinetics REE diffusion and garnet growth in subduction zones.

## Features
This package encompasses two functions: **dluskora1** and **dluskora2**. By choosing more appropriate one and setting some parameters, you can easily draw theoretical core-to-rim REE profiles.
**dluskora1** is suitable for a situation under which a garnet radius can be approximated by a linear function of time,
while **dluskora2** (beta) is useful when a radius–time trajectory is not expressed as a straight line.
Moreover, these functions are also compatible with the idea of parameter reduction by **Fukushima et al. (*Island Arc*, in prep)**.
## Requirement
R 3.6.0
## Installation
Please type the following command in R console.

`remotes::install_github("Ryo-fkushima/dluskora")`
## Usage (Example for dluskora1)
`dluskora1(fac1=(1.78 *10^(21)), Q=300000, syR=0.60, c_ave=30,
D_0=(4 * 10^(13)), R=8.3, T_1=450, T_2=600, K_d=15, Mr=100,
Mt=45, fg=1, ft=2, garsize=0.27)`
## Author
Ryo Fukushima (Tohoku University, Sendai, Japan)
