# Google Play Store: Interactive Tableau Market Dashboard  
**Developed by:** Adarsh Dwivedi | **Role:** Data & Business Analyst  

---

##  Project Overview  
The mobile app market is a multi-billion dollar industry driven by user preferences and engagement.  
This project analyzes **9,367 applications** from the Google Play Store to identify the core drivers of app success.  
Using **Tableau**, I developed an interactive dashboard that transforms raw data into strategic business intelligence, focusing on category trends, pricing impact, and user satisfaction.  

---

##  Business Problem  
With millions of apps available, stakeholders need to understand:  

- **Market Saturation:** Which categories have the highest competition vs. engagement?  
- **Pricing Strategy:** Does a "Paid" model significantly impact installation volume?  
- **User Sentiment:** What is the correlation between high ratings and the number of reviews?  
- **App Optimization:** How do factors like app size and content rating influence downloads?  

---

##  Visual Intelligence (Dashboard Preview)  
- **Market Composition**  
- **User Sentiment & Ratings**   

**Total Installs:** 167B+  
**Average Rating:** 4.19  
**Monetization:** 92.6% Free  
**Top Genres:** Games & Social  

---

## 🛠️ Methodology & Technical Stack  
- **Tools Used:** Tableau Desktop, Excel, CSV  
- **Data Preprocessing:**  
  - Cleaned *Installs* column by removing symbols (+, ,) for numerical aggregation  
  - Standardized *Price* and *Size* attributes for consistent filtering  
  - Removed duplicates and handled missing values for diagnostic accuracy  

- **Tableau Techniques:**  
  - **Calculated Fields:** Custom measures for weighted average ratings & success tiers  
  - **Interactive Filters:** Global filters for Category, Content Rating, and Type (Free/Paid)  
  - **Visual Elements:** Treemaps for category share, Scatter Plots for correlation, KPI cards for executive summaries  

---

##  Tools Used  
- **Tableau Desktop** → Interactive dashboard creation  
- **Excel / CSV** → Data preprocessing & cleaning  
- **Seaborn & Matplotlib (Python)** → Supplementary statistical plots  
- **SQL** → Initial data structuring & validation  

---

##  Key Insights  
- **The Freemium Reality:** 92.6% of apps are Free, contributing to over 167 Billion installs  
- **Performance Benchmarks:** Games & Communication lead in installs; Education shows highest consistent ratings  
- **Rating Correlation:** Apps rated above 4.0 experience exponential install growth  
- **Content Rating:** "Everyone" apps dominate reach, while "Teen" & "Mature" genres show niche engagement in Social & Action Games  

---

##  Strategic Recommendations  
- **For Product Teams:** Maintain rating floor of 4.2 by addressing user feedback in reviews  
- **For Marketing:** Focus acquisition budgets on high-volume categories like Games; use niche paid models for specialized tools  
- **For Business Strategy:** Regularly update apps to stay relevant; frequent updates strongly correlate with positive sentiment  

---

## Project Structure  
- `googleplaystore.csv` → Primary dataset used for analysis  
- `Project_of_Tableau.twbx` → Packaged Tableau workbook with full interactive dashboard  
- `dashboard_preview.png` → Snapshot of final visualization  
- `README.md` → Project documentation & insights  
