# Numerical-Approaches-to-1D-and-2D-Ising-Model-with-Periodic-Boundary-Condition
This repository contains my work for the Computational Physics course at National Tsing Hua University (NTHU). 

The project explores several algorithms using transfer matrix to simulate 1D and 2D Ising model with periodic boundary condition.
## Project Structure

- **`1D.ipynb`**  
  Simulation code for 1D Ising model.

- **`einsum.ipynb`**  
  Simulation code for 2D Ising model using einsum method.

- **`TRG.ipynb`**  
  Code for generating data for TRG method.

- **`TC.ipynb`**  
  Code for 2D simulation at critical temperature.

- **`2D_TRG.ipynb`**  
  Code for 2D TRG simulation.

- **`Introduction.pdf`**  
  A complete write-up explaining the mathematics, numerical techniques, and conclusions.
  
To reproduce the results, simplfy run code blocks in each files. Note that you must run `TRG.ipynb` before the beneath two.

---

## Software Usage

All code in this project is written in **Python 3**.

Required packages:

- `numpy`  
- `matplotlib`  
- `scipy`  
- `os`

## References
* [https://github.com/pcchen/11410PHYS401200.git](https://github.com/pcchen/11410PHYS401200.git)
* [https://tensornetwork.org/trg/](https://tensornetwork.org/trg/)
