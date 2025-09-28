# CHT-2D Intern Technical Challenge 

- **Author:** Tommaso Vandoni  
- **Email:** tommasovandoni@gmail.com

This repository contains all the materials needed for the **2D Conjugate Heat Transfer (CHT)** challenge, developed and tested in Python using [Firedrake](https://www.firedrakeproject.org/)
## Repository contents
- **`cht-2d.ipynb`**: main Jupyter notebook with the problem setup, discretization, and simulations.
- **`meshes/`**: directory with input mesh files (`.msh`) and a descriptive `README.md` for further details on the meshes.
- **`requirements.txt`**: list of Python dependencies required to run the notebook.
- **`.gitignore`**
## Requirements
The code was developed and run in a virtual environment based on Firedrake dependencies.
## Output
Running ```cht-2d.ipynb``` notebook some folders containing the outputs of the simulations will be created:
- ```output/```: is the most comprehensive folder, it contains the ```.pvd``` (```velocity.pvd```,```pressure.pvd```,```temperature.pvd```) of the solution of both the Navier-Stokes equation (interpolated on the whole mesh), and of the Energy equation in the whole domain
- ```output_init_pb/```: contains the pvd ```.pvd``` files of the solution of the Stokes initialization problem needed for the Newton/Fixed-Point methods (these results refers to the fluid submesh)
- ```output_NS/```: contains the pvd ```.pvd``` files of the solution of the Navier-Stokes equations(these results refers to the fluid submesh)
- ```output_Peclet/```: contains the pvd ```.pvd``` file to inspect the local Peclet number (cell-wise)

