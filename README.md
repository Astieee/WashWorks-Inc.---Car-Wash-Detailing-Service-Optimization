# WashWorks Inc. Car Wash Detailing Service Optimization

## Project Overview
WashWorks, Inc. is in the business of car wash and detailing, offering three levels of service (Basic, Premium, Ultra) for different car types (Compact, MidSize, SUV). The company seeks to determine the most profitable mix of car types and service levels to maximize its profits, given a set of operational constraints.

## Data Summary
Maximum forecasted demand:
- Basic: 150 cars
- Premium: 120 cars
- Ultra: 100 cars

Facility capacity:
- Compact cars: 140
- MidSize cars: 150
- SUVs: 85

Minimum service requirement: At least 5 cars of each type at every service level.

## Objective
Develop an optimal service allocation strategy to maximize profit under demand, capacity, and service level constraints.

## Constraints
- Maximum demand for each service level must not be exceeded.
- The number of each car type serviced should not surpass the facility's capacity.
- At least 5 cars of each type must be serviced at every level.

## Decision Variables
Represented as $ x_i,j $ where:
- _i_ is the car type (Compact, MidSize, SUV)
- _j_ is the service level (Basic, Premium, Ultra)

For example, $ x_Compact,Basic $ denotes the number of Compact cars receiving Basic service.

## Algebraic Formulation
The problem is formulated to maximize the profit _Z_ by determining the number $ x_i,j $ of cars of type _i_ serviced at level _j_, within the given constraints.

## Implementation
An accompanying Jupyter Notebook (Car_Optimization.ipynb) and an Excel file with solver integration (Car_Opt_excel.xlsx) provide the implemented model using Python and AMPL.

## Results
The optimization analysis determined an optimal service distribution that leads to a total profit of $10,000. The strategy specifies a precise distribution of services over the different car types and levels, efficiently utilizing resources while satisfying demand and service requirements.

For more details on the methodology, constraints, and solution process, please refer to the Jupyter Notebook and Excel files provided.

