# 🌱 GHG Emissions Inventory Project

This project builds a basic Scope 1 and Scope 2 greenhouse gas (GHG) emissions inventory based on the GHG Protocol Corporate Standard. It simulates an industrial company's fuel and electricity consumption and calculates CO₂-equivalent (CO₂e) emissions using EPA emission factors.

---

## 📌 Objectives

- Understand and apply the GHG Protocol's Scope 1 and Scope 2 classification system  
- Quantify emissions using publicly available emission factors from the U.S. EPA  
- Build a transparent Excel-based GHG calculator  
- Visualize emissions by energy source and scope category  

---

## 🧮 Methodology

1. **Data Assumptions**  
   - Simulated annual consumption data for natural gas (boiler), diesel (transportation), and electricity (office).
2. **Emission Factors**  
   - Sourced from the [EPA GHG Emission Factors Hub (2025)](https://www.epa.gov/climateleadership/ghg-emission-factors-hub).
3. **Calculation**  
   - CO₂e = Activity Data × Emission Factor  
   - Results shown in kg CO₂e per year.
4. **Visualization**  
   - Emissions by source (pie chart)  
   - Emissions by scope (bar chart)

---

## 📊 Example Outputs

- Scope 1 emissions: natural gas + diesel fuel  
- Scope 2 emissions: purchased electricity  
- Total emissions breakdown by source and scope (visualized using charts)

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `GHG_Inventory_Step1_English.xlsx` | Main Excel model for GHG emissions calculation |
| `GHG_Scope_Summary_and_Quiz.pdf` | Learning material with scope definitions and quiz |
| `GHG_Emission_Factor_Dictionary.xlsx` | Lookup table for key emission factors |
| `GHG_Inventory_Project_Summary.pdf` | Final project summary for reference or download |

---

## ✅ Key Takeaways

- GHG emissions can be estimated with limited data using open-source methodologies  
- Understanding Scope classification is essential for climate disclosures and ESG work  
- Visual communication of emissions data is key for stakeholder engagement  

---

## 🧠 Author Note

This project was built as a learning experience and demonstration of technical capability in the field of sustainability and climate data analysis. It is intended for entry-level roles in ESG, GHG accounting, or climate consulting.
In my GHG inventory model, I applied the operational control approach for organizational boundary, assuming the company has full control over its facilities and activities.
I defined the operational boundary by including Scope 1 and Scope 2 emissions, and selectively modeled Scope 3 categories based on materiality and data availability—specifically, employee commuting and product use.

