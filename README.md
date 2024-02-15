# ood-rstudio-baobab

This repository contains an OpenOnDemand app for Baobab (the [HPC cluster of the University of Geneva](https://www.unige.ch/eresearch/en/services/hpc/)).
It can launch a [RStudio Server] on a node, embedded into a flexible singularity container.

# Installation

 1) Connect to baobab `ssh user@baobab2.hpc.unige.ch`

 2) Clone the repository a specific place in your home folder:
```
mkdir -p ~/ondemand/dev && git -C ~/ondemand/dev clone https://github.com/BioinfoSupport/ood-rstudio-baobab.git
```

 3) Connect to http://ondemand.baobab.hpc.unige.ch/

