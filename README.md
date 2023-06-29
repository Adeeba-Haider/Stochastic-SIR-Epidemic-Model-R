#Stochastic Epidemic Model in R
This repository contains R code for simulating a stochastic epidemic model. The model captures the dynamics of an epidemic considering various parameters, including:

Rate of Susceptible Individuals: Represents the rate at which recovered individuals could become susceptible again to the virus.
Transmission Rate: Determines the rate of virus transmission from one individual to another.
Virus Mortality Rate: Reflects the mortality rate caused by the virus itself.
Other Disease Mortality Rate: Accounts for the mortality rate caused by other diseases concurrent with the epidemic.
Natural Death Rate: Represents the rate of mortality due to natural causes.
Precautionary Measures: Simulates the rate of individuals recovering by adopting different precautionary measures.
Migration Rate: Represents the rate of migration of infected individuals from one community to another.
Environmental Noise: Incorporates white noise in the environment, affecting the epidemic dynamics.
Features
Simulates the progression of susceptible, infected, and recovered individuals over time.
Incorporates stochasticity to capture the inherent randomness in epidemic dynamics.
Provides visualizations of the epidemic trajectories using line plots.
Usage
Install the required packages by running install.packages("sde").
Adjust the model parameters in the R script based on the specific epidemic scenario.
Run the R script to simulate the stochastic epidemic model.
Explore the impact of different parameter values on the epidemic dynamics.
Visualize the epidemic trajectories with the generated line plot.
