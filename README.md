# Breakfast Cereal Promotion Optimization (Case 3.4)

This project is based on **Case 3.4: Promoting a Breakfast Cereal** from the *Introduction to Operations Research* textbook. It involves formulating and solving a linear programming model to determine the optimal mix of advertisements to promote a new breakfast cereal—**Crunchy Start**—within budget and performance constraints.

## Objective

Maximize the **expected number of exposures** for the promotional campaign by choosing the best combination of:

-  TV Commercials  
-  Social Media Ads  
-  Sunday Newspaper Ads

## Problem Context

Claire Syverson, VP of Marketing at Super Grain Corp., must design a campaign targeting:
- Young children  
- Parents of young children

while satisfying:
- Advertising budget limit of $4,000,000  
- Planning budget limit of $1,000,000  
- Max 5 TV commercials allowed  
- Exposure constraints (minimum of 5 million in each target group)  
- Coupon redemption budget of $1,490,000

## Tools Used

- Gurobi Solver
- Python 
- Linear Programming formulation

## Model Features

- Decision variables: Number of ads per medium  
- Objective function: Maximize total exposure  
- Constraints:
  - Advertising and planning cost limits
  - Minimum exposure requirements
  - Coupon redemption contribution
  - Media-specific limits

## Outputs

- Optimal number of ads per medium
- Maximized exposure count





