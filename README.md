# Farm Management- Optimization and Decision Support Modeling in Business

## Project Overview
This project develops a Linear Programming (LP) optimization model for a multi-generational farm to determine the optimal mix of livestock(cows,hens) and crop allocation(soybeans,corn,wheat)
The model integrates land,labor,financial investment and feed requirements to maximize the farm's end-of-year monetary worth under both deterministic and uncertain weather conditions. It further extends into scenario analysis and sensitivity analysis, making it a robust decision-making tool under uncertainity.

## Objective
The primary objective of this project is to:
* Maximize total monetary worth at the end of the year
* Optimize allocation of
    * Land
    * Labor
    * Investment Capital
* Balance trade-offs between:
    * Livestock investment vs off-farm income
    * Crop profitability vs risk(weather uncertainity)
* Support data-driven strategic planning using optimization techniques

## Project Deliverables
* Case Report [Case Report] (
* Excel
* Presentation 

## Tools & Techniques 
* Linear Programming (LP)
* Excel Solver
* Sensitivity Analysis
* Scenario Modeling
  
## Key Insights 
1. No additional livestock is optimal
    * Investing in more cows or hens is not financially optimal
    * Better alternative: Use excess labor for off-farm income
2. Crop Strategy is Constraint-Driven
    * Soybeans: Most profitable and flexible
    * Corn & Wheat: Primarily grown to meet livestock feed constraints, not profit
    * Indicates a dependency-driven production system
3. Resource Utilization is fully optimized
    * Land,labor, and livestock capacity constraints are fully utilized
    * Indicates an efficient frontier solution with no idle resources
4. Weather Risk Significantly Impacts Profitability
    * Crop values fluctuate drastically under
      * Drought
      * Flood
      * Frost Scenarios
    * Optimistic planning leads to high risk exposure
5. Risk-adjusted model improves decision quality
   * Using expected(probability-weighted) crop values:
     * Soybeans: $34
     * Corn: $27.5
     * Wheat: $20.75
   * Laeds to a more realistic and resilient strategy
   * Final optimized worth: $80,537
6. Sensitivity Analysis Highlights Critical Variables
   * Soybeans & Wheat require precise estimation(low tolerance for error)
   * Corn has high flexxibility (large allowable decrease)
   * Help prioritize data accuracy efforts

## Model Highlights 
### Descision Variables 
* Livestock: Cows(C), Hens(H)
* Crops: Soybeans(A1),Corn(A2),Wheat(A3)
### Constraints 
* Land Capacity
* Seasonal labor limits
* Freed requirements(corn & wheat dependencies)
* Livestock housing limits
* Budget constraints

## Team Members 
* Bavya Nalajala
* Bhavana Sarvesh 








