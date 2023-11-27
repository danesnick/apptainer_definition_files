# Fenicsx Apptainer Definition File
I needed to build FEniCSx using an apptainer/singularity image, so I decided to publish the recipe here. Things may not be "optimal" here, build wise, but I needed my own build in order to talk to our system MPI (Open MPI 4.1.x) 

# Requirements

- Apptainer or Singularity (Tested on 1.1.8-1.el7)
- Open MPI 4.1.x on your host system


## Install instructions

- Grab the definition file and run the following command
```bash
sudo apptainer build fenicsx_0.6.0.sif fenicsx_0.6.0.def
```

The build will take a while! 

