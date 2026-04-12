  Sustainable Aviation Fuel (SAF) Pricing & Cost Simulator

   What is this project?
The aviation industry is being forced to transition from traditional Jet-A1 fuel to Sustainable Aviation Fuel (SAF) to meet global carbon emission goals. The problem? SAF is currently much more expensive. 

This project is a Python-based simulator that forecasts the "price premium" (the cost difference) between regular Jet-A1 and SAF under different future scenarios, such as rising crude oil prices or new government carbon taxes.

   Why does this matter? 

I built this model to provide data-driven answers for two different industrial perspectives:

  1. For Commodity & Market Analysts:  
 It provides a framework to track how ESG regulations (like Carbon Taxes) directly impact aviation fuel pricing. 
  It models the price spread between fossil fuels and biofuels, offering a baseline for commodity forecasting.

  2. For Aerospace Operations & Supply Chain:  
  Fuel transition isn't just an environmental issue; it's a massive operational cost.
  This model helps procurement and operations teams visualize future cost pressures, allowing them to hedge risks and adjust supply chain budgets before the regulations hit.

   How it works (Methodology)
Instead of just relying on static historical data, this tool uses a dynamic sensitivity analysis approach:
1.   Data Source:   Historical Jet-A1 and Crude Oil pricing trends (sourced from Kaggle public datasets).
2.   Simulation Variables:   I introduced adjustable variables like "Carbon Tax per Ton" and "SAF Production Subsidy".
3.   Output:   The code generates a clear comparison chart showing when SAF might reach "price parity" (cost the same as traditional fuel) under specific economic conditions.

   Technical Stack
    Language:   Python
    Libraries:   Pandas (for data manipulation), Matplotlib/Seaborn (for trend visualization).
    Core Concept:   Scenario Planning & Sensitivity Analysis.

---
 Created by Goh Eng Hong (Alex) - Applied Business Analytics student. 
