# WENOEXT-project
Aim: High resolution fvm simulation using [WENOEXT](https://github.com/WENO-OF/WENOEXT) scheme

### Installation
```
mv Dockerfile.step01 Dockerfile
docker build jiaqiknight/openfoam-wenoext:v1 .
mv Dockerfile.step02 Dockerfile
docker build jiaqiknight/openfoam-wenoext:v2 .
singularity build openfoam-wenoext-v2012.sif Singularity-openfoam.def
singularity shell openfoam-wenoext-v2012.sif
```
