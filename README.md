# GreenMeatSCN_AugmentedEpsilonConstraint
Designing a Green Meat Supply Chain Network: A Multi-Objective Optimization Approach (Augmented ε-constraint)
This repository contains the Jupyter Notebook implementation of a multi-objective mixed-integer linear programming (MILP) model for designing and optimizing a green meat supply chain network. The model aims to simultaneously minimize total costs, minimize CO2 emissions from transportation, and maximize facility utilization, as detailed in the accompanying research paper. The solution approach based on the Augmented ε-constraint method is employed to solve the proposed model. As a result, a set of Pareto-optimal solutions is obtained. 
Project Overview
The global meat supply chain faces increasing pressure to become more sustainable. Traditional logistics management often overlooks environmental concerns. This project addresses this gap by presenting a mathematical model for designing and configuring a multi-period, multi-product, multi-echelon green meat supply chain network.
The core of this project is a multi-objective mixed-integer linear programming formulation that optimizes three critical objectives concurrently, providing a comprehensive framework for sustainable supply chain management in the meat industry. 
The solution approach based on the Augmented ε-constraint method is employed to solve the proposed model. As a result, a set of Pareto-optimal solutions is obtained.
Model Objectives
The multi-objective optimization model targets the following three goals:
1.	Minimization of Total Cost: Including transportation, production, inventory, and fixed facility costs.
2.	Minimization of Total CO2 Emissions: Focusing on emissions generated during transportation activities.
3.	Maximization of Total Capacity Utilization: Ensuring efficient use of established facilities across the supply chain.
Methodology
The model uses the Augmented ε-Constraint method to generate Pareto-optimal solutions, balancing trade-offs between economic, environmental, and operational objectives. Decision trees are employed to address uncertainty in customer demand and livestock purchasing costs.
Prerequisites
To run the Jupyter Notebook, you need to have the following software and Python libraries installed:
•	Python 3.x
•	Jupyter Notebook or JupyterLab
•	Pyomo: A Python-based open-source software package for formulating and solving optimization models.
•	GLPK (GNU Linear Programming Kit): A solver that Pyomo can interface with. You'll need to install this separately on your system. For Windows, you can download pre-compiled binaries. For Linux, it's usually available via package managers (e.g., sudo apt-get install glpk-utils). For macOS, you can use Homebrew (brew install glpk).
•	Pandas: For data manipulation.
•	NumPy: For numerical operations.
•	Matplotlib: For plotting the results.
Reference
Mohebalizadehgashti, F., Zolfagharinia, H., & Amin, S. H. (2020). Designing a green meat supply chain network: A multi-objective approach. International Journal of Production Economics, 219, 312-327.
License
This project is licensed under the MIT License - see the LICENSE file for details.


