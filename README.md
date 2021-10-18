# Lexa-Benchmark

Codebase for the self-supervised goal reaching benchmark introduced in 'Discovering and Achieving Goals via World Models'.  

<img src="https://russellmendonca.github.io/data/lexa_benchmark.png" width="1000">




## Setup

Create the conda environment by running : `conda env create -f environment.yml`

Alternatively, you can update an existing conda environment by running : `conda env update -f environment.yml`


Modify the python path   
`export PYTHONPATH=<path to lexa-benchmark>`  

Export the following variables for rendering  
`export MUJOCO_RENDERER=egl; export MUJOCO_GL=egl`

Please follow these [instructions][mujoco_instr] to install mujoco

[mujoco_instr]: https://github.com/openai/mujoco-py#install-mujoco
