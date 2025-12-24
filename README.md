
 Retail Inventory Optimization & Profitability Dashboard 

 Project Overview
This project analyzes the inventory performance of a retail portfolio containing **35 Stock Keeping Units (SKUs)**. By transforming raw product data into an interactive Excel Dashboard, I identified critical inefficiencies in pricing strategy and stock composition.

The analysis reveals that while the store is profitable (**30.58% Portfolio Margin**), it relies heavily on low-value volume items. A strategic shift toward high-efficiency categories like *Sports & Outdoors* could increase the average profit per unit by approximately 15-20%.

 📷 Dashboard Preview
<img width="1000" height="638" alt="image" src="https://github.com/user-attachments/assets/5fcc4529-50fb-44a9-b50c-93bd5e84d68d" />

(Click image to view full size)

  Files in this Repository
Inventory_Dashboard_Final.xlsx: The interactive Excel tool containing:
Dashboard Tab:Visualizations and Slicers.
Engine Tab: Pivot Tables and intermediate calculations.
Data Tab: Raw inventory dataset.
Executive_Summary.pdf: High-level business report summarizing findings for stakeholders.


 Key Insights & Business Recommendations

1. The "Volume vs. Value" Track Observation:
 The Toys category moves the highest volume and generates the most raw profit (KES 39.00), but has a lower margin (27.1%).
  Opportunity: The Sports & Outdoors category is far more efficient, generating nearly identical profit (KES 35.00) with a superior margin (32.7%).
  Recommendation:Reallocate restocking budget to prioritize Sports equipment over generic Toys to maximize return on capital.

2. Pricing Inefficiency in Electronics
  Observation: Electronics have the highest average cost (KES 14.32) but the lowest total profit contribution.
  Recommendation: Implementing a 5-10% markup increase on Electronics is necessary to align this category with the store's 30% margin target.
3. Inventory Portfolio Risk
  Observation: 46% of the inventory consists of "Low Profit" items (earning < KES 4.00 per unit).
  Recommendation:Conduct a "Keep or Cut" audit on these 16 items. If they are not driving foot traffic, they should be replaced with "High Profit" items (like the Mini Basketball Hoop, which earns KES 16.00/unit).


 Technical Skills Demonstrated
 Excel Analytics
Advanced Pivot Tables: Used to aggregate data by Category and Product Name.
Calculated Fields: Implemented `Sum('Profit') / Sum('Product_Cost2')` to calculate Weighted Margins, avoiding the statistical error of "averaging averages."
Slicers:** Created interactive filters to allow dynamic segmentation by Product Category.

 Logic & Formulas
KPI Development: used `GETPIVOTDATA` to link dashboard cards to dynamic backend calculations.
Data Segmentation: Used nested `IF` statements to create a "Profit Tier" dimension:
    excel
    =IF([@Profit]<4, "Low", IF([@Profit]<8, "Medium", "High"))
    

 Author
  John
  Data Analyst & Applied Statistics Student
  Kisii , Kenya

