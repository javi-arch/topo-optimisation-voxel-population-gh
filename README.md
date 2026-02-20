# 3D Topological Optimization & Voxel Population

This Grasshopper script provides a workflow for creating forms based on specific loads and supports. After the 3D topological optimization process, the script populates the resulting geometry with pre-defined voxel models, mapped according to the stress values obtained during the calculation. This repository includes the Grasshopper (`.gh`) script, as well as a Rhino (`.3dm`) example file.

## Dependencies
To run this script correctly, you must have the following Grasshopper plugins installed:

* **[tOpos](https://www.food4rhino.com/en/app/topos)** – Used for the topological optimization calculations.
* **[Human](https://www.food4rhino.com/en/app/human)** – Required for voxel blocks baking.

## Preview
<img width="1683" height="391" alt="img-optop-voxels-tool" src="https://github.com/user-attachments/assets/1cd1f8b2-e6bb-446e-8e6f-02aa3d1b44a0" />


---
**Author:** Javier Fidalgo Saeta

**Platform:** Rhino 8 + Grasshopper
