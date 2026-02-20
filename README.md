# Topological Optimization & Voxel Population

This Grasshopper script provides a workflow for optimizing forms based on specific loads and supports. After the topological optimization process, the script populates the resulting geometry with pre-defined voxel models, mapped according to the stress values obtained during the calculation.

## Features
* **Form Optimization:** Structural analysis and topology optimization using voxel-based solvers.
* **Stress Mapping:** Automated point population driven by structural performance data.
* **Voxelization:** Efficient geometry generation using different pre-defined voxel types.

## Dependencies
To run this script correctly, you must have the following Grasshopper plugins installed:

* **[tOpos](https://www.food4rhino.com/en/app/topos)** – Used for the core topological optimization calculations.
* **[Human](https://www.food4rhino.com/en/app/human)** – Required for dynamic baking and advanced geometry management.

## How to Use
1. **Prepare the Scene:** Open the provided Rhino (`.3dm`) file containing the base geometry, loads, and support definitions.
2. **Load the Script:** Open the Grasshopper (`.gh`) file.
3. **Solver Initialization:** Locate the **tOpos** component group to run the optimization.
4. **Voxel Generation:** Once the optimization is complete, the script will automatically map the voxel models based on the stress analysis.
5. **Bake:** Use the **Human** components to bake the final geometry into Rhino layers.

## Preview
*(Tip: Add a high-resolution screenshot or a GIF here to show the script in action!)*
`![Script Preview](path/to/your/image.png)`

---
**Author:** [Your Name/GitHub Username]  
**Platform:** Rhino 7/8 + Grasshopper
