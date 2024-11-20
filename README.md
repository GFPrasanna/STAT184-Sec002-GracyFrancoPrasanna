# STAT184-HW-Template
 STAT184 Github Day 1 HW Template

Introduction: 
The code in this repository is used to prepare a summary table for the coefficients for a linear regression model related to a subset of the Palmer Penguins data from the palmerpenguins R dataset. This model is focused on Adelie penguins and attributes: “island, bill length, bill depth, flipper length, body mass, sex, year”.

Implementation: 
The following list provides a general overview of my implementation: 
1) load in the necessary packages: palmer penguins, dplyr, tidyverse, kableExtra
2) filter the necessary information to get data for the linear regression: Adelie species
3) Select the necessary columns (
body_mass_g ~ bill_length_mm + bill_depth_mm + flipper_length_mm + sex + island
)
4) pipe in the lm data to get our linear regression using the lm() function
6) Create a summary model of the linear regression
7) create a coefficients table that includes: variable, estimate, standard error, t)value, and p_value
8) create a display to properly display this visualization

Results: 

Contact: gjf5257@psu.edu
