# Topological Optimization & Voxel Population

This Grasshopper script provides a workflow for creating forms based on specific loads and supports. After the 3D topological optimization process, the script populates the resulting geometry with pre-defined voxel models, mapped according to the stress values obtained during the calculation. This repository includes the Grasshopper (`.gh`) script, as well as a Rhino (`.3dm`) example file.

## Dependencies
To run this script correctly, you must have the following Grasshopper plugins installed:

* **[tOpos](https://www.food4rhino.com/en/app/topos)** – Used for the topological optimization calculations.
* **[Human](https://www.food4rhino.com/en/app/human)** – Required for voxel blocks baking.

## Preview
<img width="300" height="300" alt="img-nakagin-capsule-challenge" src="https://github.com/user-attachments/assets/68ccc3c7-d21b-44d6-8c54-ef4f698d7977" />

---
**Author:** Javier Fidalgo Saeta
**Platform:** Rhino 8 + Grasshopper
