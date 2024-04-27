README

Model Overview:

This code implements the SEIHM model, a modification of the SEIR model, to simulate disease dynamics and how diseases spread in a population over time. The SEIR model represents the flow of individuals through compartments: Susceptible (S), Exposed (E), Infectious (I), and Recovered (R). The SEIHM model extends this by incorporating the Healthy (H) compartment and the Mortality (M) compartment, accounting for healthy recovery and mortality.

Gathering Data:

To make the simulation accurate for specific diseases, we collected information from scientific studies and official sources about how those diseases behave.

Software and Tools:

The code is written in MATLAB. It also uses MATLAB's built-in tools for data visualization.

Running Simulations:

The simulations are run by adjusting parameters such as transmission rate (β), incubation period (λ), recovery rate (γ), and mortality rate. The model provides insights into the estimated death toll at the end of one year, with the flexibility to estimate at other time points.

How to Use:

MATLAB is required to run our code. Download the provided "SEIHM.mlx" file and run to simulate and analyze disease dynamics using the SEIHM model.

References:

The original SEIR model code can be found in our GitHub repo.