# Fundamentals-in-Air-Pollution
# CO₂ Climate Change Model

## Project Summary

This project focuses on analyzing the impact of increasing carbon dioxide (CO₂) concentrations on climate change, particularly looking at how CO₂ levels influence the greenhouse effect, heat transport efficiency, and global temperature variations.

Using historical CO₂ data (e.g., from Mauna Loa) and simple climate models, the project simulates how both current and doubled CO₂ concentrations affect the Earth’s climate. By exploring different scenarios, this project helps us understand the role of CO₂ in driving global warming and how simple models can be used to predict future changes.

### Key Questions Addressed
- Compute and plot global average concentrations as a function of CO₂:
This part uses data from Mauna Loa to compute how CO₂ concentrations affect global average temperature. The project assumes a quasi-equilibrium condition and uses a logarithmic model to estimate temperature changes (ΔT) as CO₂ increases.
You can find the plot in the code, which visualizes the relationship between CO₂ concentrations and global temperature.

- Estimate CO₂ levels before the Industrial Revolution and explore temperature changes:
This analysis compares CO₂ levels before and after the Industrial Revolution, providing insights into how CO₂ levels and temperature anomalies have evolved over time. This reflects how changes in CO₂ impact temperature distribution, which ties into heat transport efficiency.
A comparison between pre-industrial and current CO₂ levels is plotted, showing latitudinal temperature changes.

- Estimate the average temperature from the Equator to the North Pole:
I modeled temperature changes from the equator to the poles, calculating how increased CO₂ impacts heat transport efficiency. By using ODE solvers, I explored how heat is distributed across different latitudes.
The project includes functions to compute net radiation, albedo, and heat transport, which are essential for estimating the temperature gradient from equator to pole.

- Simulate the impact of doubling CO₂ concentrations:
By doubling the CO₂ concentration, the project calculates the impact on the greenhouse effect and outgoing radiation. This step is crucial for understanding the future effects of increased CO₂ emissions on global temperature.
The final temperature results for both initial and doubled CO₂ levels are printed and visualized, demonstrating how increased CO₂ traps more heat and leads to a stronger greenhouse effect.

- Reflect on the role of simple models in understanding climate change:
Simple models like this one are valuable tools for predicting climate outcomes. They provide insights into how key factors like CO₂ influence climate systems and offer a way to simulate future scenarios. While simple, these models help us understand the big picture of global warming.


### Importance

This project contributes to a deeper understanding of climate change mechanisms and the role of greenhouse gases. It serves as an educational tool for those interested in climate science, helping to visualize the relationships between CO₂ levels and global temperature shifts.

### Acknowledgments
Special thanks to Mr. Pravin for discussing regarding the data, and initial concept understanding.

