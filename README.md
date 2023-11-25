# Mass Transport Phenomenon Modeling

The project focuses on the comprehensive study of mass transport phenomena, a subject of significant interest for researchers. At the microscopic level, these phenomena involve intricate processes such as fragmentation, adsorption, diffusion, and aggregation, which are widespread in nature [1], [2], [3]. Given their non-equilibrium nature, determining steady states from Gibb’s distribution poses a considerable challenge. The studies conducted not only serve as artifacts of simulation and mathematical work [1], but they also pave the way for describing various physical phenomena, including growing interfaces [4], colloidal suspensions [5], polymer gels [6], river networks [7], granular materials [8], traffic flows [9], and more.
Model Description:

The project adopts a 1-dimensional lattice model where mass is randomly distributed across different lattice sites. For simplicity, it assumes that the mass at one site is not influenced by the mass present at adjacent lattice sites, allowing the treatment of each site individually. The movement of mass from one site to a neighboring site is considered under the Mean Field (MF) approximation. This approximation tracks the distribution of masses while disregarding correlations in the occupancy of adjacent sites. Despite the known shortcomings of the MF theory, Monte Carlo (MC) simulations conducted during the project demonstrate its accuracy in describing the proposed model in the 1-dimensional case.
Applications:

The models developed in this project find application in diverse areas such as:

    Growing interfaces [4]
    Colloidal suspensions [5]
    Polymer gels [6]
    River networks [7]
    Granular materials [8]
    Traffic flows [9]

## Implementation:

The fundamental movement of mass in the model involves chipping, where a unit of mass 'n' chips. The combination of the 1-dimensional lattice model, the Mean Field approximation, and Monte Carlo simulations provides a robust framework for studying and understanding mass transport phenomena with various kinetic processes.

The code snippets in this repository offer implementations and simulations related to the described models, facilitating further exploration and experimentation.
Simple Jupyter File:

    The repository includes a simple Jupyter file for running and experimenting with the provided code snippets.

Getting Started:

    Clone the repository: git clone [repository-url]
    Navigate to the desired code block directory.
    Run the Python script or Jupyter notebook: python filename.py or jupyter notebook filename.ipynb

Dependencies:

    Python 3.x
    Required Python packages (NumPy, Matplotlib, Jupyter)

