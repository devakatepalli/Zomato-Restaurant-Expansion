# Zomato Restaurant Expansion — Data Analytics Dashboard

This project showcases a **data-driven restaurant expansion strategy** built using **Google Sheets**, designed to identify ideal locations for **Zomato’s restaurant growth**. The analysis integrates global restaurant data to uncover insights on competition, pricing, cuisine trends, and customer preferences.

---

## Objective
To recommend potential **countries and cities** for new restaurant openings by analyzing factors such as:
- Restaurant density and competition  
- Average customer ratings  
- Cuisine performance and popularity  
- Pricing structure and affordability  
- Delivery and booking availability  

---

## Tools & Techniques
- **Google Sheets** (`Final_Dashboard`) for analytics and visualization  
- **Pivot Tables**, **Conditional Formatting**, **XLOOKUP**, **IF**, **AVERAGEIFS**, **ARRAYFORMULA** for data analysis  
- **GOOGLEFINANCE** for live currency conversion  
- Custom formulas for data transformation and INR price conversion  

---

## Project Structure
- **Objective Questions:** All solutions integrated into a single sheet using formulas and pivot tables  
- **Subjective Questions:** Each question analyzed in a **separate sheet** for focused exploration  
- **Dashboard Sheet:** Consolidated, interactive visuals summarizing insights by **country**, **year**, **cuisine**, and **pricing**  

---

## Data Preparation
- Cleaned missing and inconsistent data (e.g., cuisines, restaurant IDs)  
- Trimmed spaces and standardized text formats  
- Added derived fields — *Country Name*, *Opening Year*, and *Average Cost in INR*  
- Applied dynamic **currency-to-INR conversion** via `GOOGLEFINANCE()`  

---

## Key Insights
- **Top countries:** Qatar, Sri Lanka, Indonesia, New Zealand  
- **Best cities:** Doha, Colombo, Bandung, Bogar, Auckland, Wellington City  
- **High-performing cuisines:** Italian, Indian, Continental, Seafood, Bakery, Sushi  
- **Customer trends:** Higher ratings for restaurants offering both online delivery and table booking  
- **Price correlation:** Weak (r = 0.15) — quality and service drive satisfaction  

---

## Recommendations
- Expand in emerging, high-rated markets with **premium yet affordable offerings**  
- Focus on **quality, service, and ambiance** to sustain high ratings  
- Continue leveraging **data visualization** for strategy and performance tracking  

---

## Getting Started
1. Open the **Google Sheet** named `Final_Dashboard`.  
2. Explore the following tabs:  
   - **Objective Sheet** → Contains all formula-based analyses and pivot tables.  
   - **Subjective Sheets** → Each sheet corresponds to one analytical question.  
   - **Dashboard Sheet** → View all insights through interactive visuals.  
3. Adjust filters or slicers to explore specific countries, cuisines, or years.
