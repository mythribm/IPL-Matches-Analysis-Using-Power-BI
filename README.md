# 🏏 IPL Matches Analysis — Season & Match Outcome Insights

A Power BI project analyzing historical IPL match patterns, toss impact, venue statistics, and match outcomes using the `matches.csv` dataset.  
This dashboard helps analysts, teams, and broadcasters understand how different factors influence match results across seasons.

---

## Project Title  
**IPL Matches Analysis — Season & Match Outcome Insights**

## Tools Used
- **Microsoft Power BI** (dashboard & visuals)
- **Excel** (data cleaning, preprocessing, EDA) 
- **Dataset:** `matches.csv` (season, teams, toss info, venue, results, margins, super_over, method, player_of_match)

---

## Objective

To understand historical IPL match behavior — including toss outcomes, venue influence, season trends, match results, super-over occurrences, and margin distribution — and showcase insights through an interactive Power BI dashboard for analysts and decision-makers.

---

## What I Did (Step-by-Step Process)

### **1. Data Cleaning & Preparation**
- Standardized team names and venue strings  
- Converted numeric fields to correct formats  
- Reviewed & filled missing values (e.g., *player_of_match*, *method*)  
- Created derived metrics:
  - **toss_match_win** → whether toss winner also won the match  
  - **season aggregations**  
  - **result margin categories**

### **2. Exploratory Data Analysis (Excel/Python)**
Analyzed:
- Matches per season  
- Toss decision patterns (bat/field)  
- Match results (runs / wickets / tie / no result)  
- Venue frequency  
- Super-over counts  
- Season trends and anomalies  

### **3. Power BI Dashboard Development**
Built a fully interactive dashboard with:
- **KPI Cards:**  
  - Unique player_of_match  
  - Number of teams  

- **Visuals:**  
  - Bar chart → Matches per season  
  - Donut chart → Toss decision split  
  - Donut chart → Match decision method (Normal/DL)  
  - Stacked bar → Toss winner vs Match winner  
  - Bar chart → Top venues by matches  
  - Bar/column → Result type & result margin  
  - Column chart → Super-over matches by year  

- **Filters/Slicers:**  
  - Season  
  - Team  
  - Venue  
  - Super Over (Yes/No)

---

## Key Metrics & Findings

### ✔ **292 unique** player_of_match awardees  
### ✔ **19 distinct teams** in dataset  
### ✔ Toss decisions show majority choosing **bat first**  
### ✔ Toss influence exists but is **not decisive**  
### ✔ Most matches end normally (method = NA)  
### ✔ Super-overs & D/L outcomes are **rare**  
### ✔ Certain venues dominate match hosting:
- Eden Gardens  
- Wankhede Stadium  
- M. Chinnaswamy  
- Feroz Shah Kotla  
- Rajiv Gandhi International Stadium  

### ✔ Match result types:
- Mostly by **runs or wickets**  
- Few ties / no-results  

---

##  Dashboard Visuals Included

- 🟦 KPI cards  
- 📊 Season-wise match trend bar chart  
- 🥧 Toss decision pie chart  
- 🥧 Match method pie chart  
- 🧱 Toss winner vs match winner stacked bar  
- 🏟 Venue frequency bar chart  
- 🎯 Result type & margin visualization  
- 🔥 Super-over analysis column chart  

---

##  Actionable Insights (Interpretation)

### **1. Batting-first choices dominate**  
Captains frequently choose to bat first — venue-specific win probabilities suggest deeper pitch-driven analysis is useful.

### **2. Toss advantage is situational, not absolute**  
Many matches are won by teams **losing the toss** → toss alone is not a reliable predictor.  
Better predictive features: pitch, weather, team lineup.

### **3. Venue concentration impacts strategy**  
A few venues host most matches — crucial for home advantage studies and season planning.

### **4. Super-overs & D/L matches are rare but impactful**  
Though infrequent, they influence match outcomes significantly and should be explicitly modeled in ML predictions.

### **5. Player_of_match diversity is high**  
~300 unique awardees → performance contribution is widespread across players; good for player analytics and scouting models.

---

## Impact / Use Cases

- Helps **analysts & strategists** quantify toss influence by season and venue  
- Assists **broadcasters/statisticians** in planning venue-based content  
- Supports **ML modeling teams** in selecting features (toss decision, venue, H2H history) for match outcome prediction  

---

 
