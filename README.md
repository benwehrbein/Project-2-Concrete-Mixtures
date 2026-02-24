# Project-2-Concrete-Mixtures
The Nebraska Department of Transportation has requested our assistance in translating its concrete mix design from Excel sheets into a Python program that utilizes a user-input system. This system will enable users to input values for each material selected for the design. The final output should be displayed as a single weight chart for one cubic yard of concrete. The repository contains the untranslated Excel sheets and the code for our four objectives. Our objectives are as follows: (1) Successfully translate all calculations from the worksheet into Python code; (2) Implement user input in the code by asking which materials are required and displaying them in the correct order as they appear on the Excel worksheet; (3) Generate the final mix design output in a correctly formatted weight chart for one cubic yard of concrete, with all values clearly labeled and neatly presented; and (4) Research four different concrete mix scenarios according to Department of Transportation resources, with each scenario tested in our Python model to verify its effectiveness.
User Guide for Python Code:

1. Import Pandas & NumPy
This may look like: import pandas as pd
2. Assign values to fundamental constants through variables
This may look like: cubic_yard_ft3 = 27 # number of cubic feet = 1 cubic yard
3. Calculate the volume of materials (R, S, T, & U) using their specific gravity
This may look like: def calculate_water_weight_Q(cement_A,fly_ash_B,silica_fume_C,other_SCM_D,wc_ratio_E)
4. Calculate the air and water volumes for variables (V) & (W)
This may look like: def calculate_volume_V(percent_air_F)
5. Calculate fine aggregate weights for variables (Y), (Z), and (AA)
This may look like: def calculate_fine_aggregate_Y(percent_fine_G, sg_fine_N,total_volume_X):
6. To Collect the users' inputs sequentially, input strings will be made into floats or integers
This may look like: project_no = int(input("Enter project number: "))
