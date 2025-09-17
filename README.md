# Environmental Impact of Food Production

This project analyzes the **environmental footprint of 43 food products** across multiple dimensions:  
greenhouse gas (GHG) emissions, land use, water use, and eutrophication potential.  
The goal is to identify high-impact foods, assess sustainability tradeoffs, and propose **lower-impact dietary choices** to reduce climate and environmental costs.

---

## Business Questions Addressed
- Which foods contribute the most to greenhouse gas emissions?  
- How do animal-based vs. plant-based foods compare in environmental impact?  
- Which stages of the supply chain drive the most emissions?  
- Which foods are most land- and water-intensive?  
- How efficient are foods in delivering protein vs. their footprint?  
- What are the best substitutes for high-impact foods?  

---

## Data Summary
- **Source:** Global food production impact datasets (FAO, Poore & Nemecek 2018)  
- **Scope:** 43 food products (animal- and plant-based)  
- **Key Columns:**  
  - `GHG` – Greenhouse gas emissions (kgCO₂eq)  
  - `LAND_USE` – Land required (m² per kg of food)  
  - `WATER_USE` – Freshwater withdrawals (liters per kg)  
  - `EUTROPHICATION` – Nutrient pollution potential (g PO₄eq per kg)  
  - `FOOD_TYPE` – Animal-based vs. plant-based classification  
  - `UNIT_BASIS` – Measured per kcal, per 100g protein, and per kg weight  

---

## Key Insights
- **Beef Hotspot:** Beef (59.6 kgCO₂eq/kg) is by far the highest emitter, over 2× lamb & mutton (24.5). Cheese (21.2) and dairy beef (21.1) also rank high.  
- **Animal vs. Plant Gap:** Animal-based foods are on average **5× more emission-intensive** (16.8 vs. 3.1). They also account for **59% of total emissions**.  
- **Supply Chain:** Farm production & land use changes drive **70–75% of emissions**; downstream stages (processing, transport, packaging, retail) are each <10%.  
- **Double Hotspots:** Lamb & beef dominate land use, while nuts, cheese, and olive oil are highly water-intensive. Some foods (cheese, olive oil, lamb, beef) are **high in both land & water demand**.  
- **Protein Efficiency:** Beef and lamb have the worst emissions per 100g protein, while **pulses, tofu, and soy milk** have the lowest.  
- **Hidden Plant Costs:** Some luxury crops like **dark chocolate (18.7)** and **coffee (16.5)** rival animal products in emissions.  
- **Best Substitutes:** Replacing beef (49.9), lamb (19.9), and cheese (10.8) with peas (0.4) can cut emissions by **up to 99%**.  

---

## Recommendations
| Focus Area          | Action                                                                 |
|----------------------|------------------------------------------------------------------------|
| Reduce High-Impact   | Limit consumption of beef, lamb, and cheese.                          |
| Promote Substitutes  | Encourage plant proteins (peas, lentils, tofu, soy milk).             |
| Farm-Level Action    | Improve land use management, feed efficiency, and methane reduction.  |
| Water Management     | Target water-intensive foods (nuts, olive oil, cheese).               |
| Double Hotspots      | Prioritize foods high in both land & water intensity.                 |
| Policy Metrics       | Use kcal, protein, or weight basis depending on the sustainability goal. |

---

## Tools Used
- **Python (Pandas, Matplotlib, Seaborn)**  
- **Google Colab / Jupyter Notebook**  
- **GitHub** (version control & documentation)  

---
