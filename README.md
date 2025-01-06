# Modeling-Epidemic-Dynamics-An-Agent-Based-Simulation-Approach

## Overview

This project leverages **agent-based modeling (ABM)** to simulate the spread of infectious diseases in a population. Built with the Mesa framework, it evaluates the impact of public health interventions like vaccination and social distancing through interactive visualizations powered by Plotly. Users can dynamically adjust parameters to explore various epidemic scenarios.


## Features

- **Agent-Based Simulation**:
  - Models individuals (agents) with unique attributes such as age, health state (Susceptible, Infected, Recovered, Vaccinated), and vaccination compliance.
  - Incorporates realistic agent behaviors like movement, contact, and adherence to interventions.

- **Dynamic Visualizations**:
  - Real-time visualizations using **Plotly** to track epidemic progression.
  - Displays states of agents over time: Susceptible, Infected, Recovered, and Vaccinated.

- **Interactive Controls**:
  - Parameters such as infection rate, recovery rate, compliance, vaccination timing, and population size are adjustable through **IPyWidgets**.

- **Public Health Insights**:
  - Highlights the importance of early vaccination and adherence to social distancing.
  - Identifies critical intervention points for mitigating outbreaks.

## Technical Stack

- **Programming Language**: Python
- **Libraries/Frameworks**:
  - [Mesa](https://mesa.readthedocs.io): For agent-based modeling
  - [Plotly](https://plotly.com/python): For dynamic visualizations
  - [IPyWidgets](https://ipywidgets.readthedocs.io): For interactive parameter adjustments
  - Additional libraries: `pandas`, `numpy`, `matplotlib`

## Usage
- **1.Open the notebook epidemic_simulation.ipynb in Jupyter Notebook**.

- **2.Customize simulation parameters using the interactive widgets**:
  - Population size: Number of agents in the simulation.
  - Infection rate: Probability of disease transmission upon contact.
  - Recovery rate: Probability of recovery for infected agents.
  - Compliance rate: Degree of adherence to social distancing.
  - Vaccination start day: Day when vaccination begins in the simulation.

- **3.Run the simulation to observe**:
  - Epidemic progression over time.
  - Effects of interventions like vaccination and social distancing.
  
- **4.Analyze real-time visualizations**:
  - Line graphs show trends in Susceptible, Infected, Recovered, and Vaccinated states.
  - Key milestones like peak infections and vaccination rollouts are annotated.

## Results
- **Peak Infection**: Identified critical times for resource allocation.
- **Vaccination Impact**: Demonstrated how timely vaccination reduces infection spread.
- **Compliance Effect**: Showed how adherence to social distancing delays and mitigates outbreaks.

## Key Insights
 - **Timely Interventions**: Early vaccination and high compliance with social distancing are pivotal in controlling disease spread.
 - **Dynamic Decision-Making**: Interactive controls allow users to simulate and understand the effects of different strategies.
 - **Educational Value**: Serves as a learning tool for public health professionals and researchers.

## Future Work
  - **Integration of Real-World Data**: Enhance simulations with real epidemiological datasets for greater accuracy.
  - **Multi-Strain Epidemics**: Extend the model to include different viral strains, reflecting real-world complexities.
  - **Advanced Visualizations**: Incorporate geographic heatmaps for spatial analysis.
  - **Healthcare System Constraints**: Simulate hospital capacities and resource demands during peaks.
  - **Dashboard Development**: Build a dashboard for side-by-side comparisons of intervention scenarios.


