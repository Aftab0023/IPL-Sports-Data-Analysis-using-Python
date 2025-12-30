# 🏏 IPL Sports Data Analysis using Python

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on **Indian Premier League (IPL)** match and player data using Python.  
The analysis focuses on extracting insights related to **player performance, team success, and season-wise trends**.

---

## 🎯 Objectives
- Analyze IPL match and player CSV datasets  
- Identify **top run scorers**  
- Calculate **best strike rates**  
- Compute **team win percentages**  
- Visualize **season-wise and player-wise performance**  
- Compare **player performance across seasons**  
- Export **visual summary and short insights**

---

## 📂 Dataset Information
The dataset is sourced from **Kaggle – IPL Ball-by-Ball Dataset**.

**Files used:**
- `matches.csv` – match details such as date, teams, and winner  
- `deliveries.csv` – ball-by-ball data including runs and players  

---

## 🧰 Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📊 Analysis Performed

### 🔹 Top Run Scorers
- Aggregated total runs scored by each batsman  
- Identified top 10 run scorers across all seasons  

### 🔹 Best Strike Rates
- Calculated strike rate using runs per 100 balls  
- Applied minimum balls faced condition for fair comparison  

### 🔹 Team Win Percentage
- Computed team-wise win ratios  
- Identified the most successful IPL teams  

### 🔹 Season-wise Performance
- Converted match dates into **season (year)**  
- Analyzed run trends across IPL seasons  

### 🔹 Player Performance Across Seasons
- Compared individual player runs year-by-year  
- Observed consistency and performance variation  

---

## 📤 Output

### 📊 Top 10 Run Scorers
![Top Run Scorers](Top_10_IPL_Run_Scorers.png)

### ⚡ Best Strike Rates
- Best Strike Rates (Min 500 Balls) Top 10
- Batter
- AD Russell 164.613073
- LS Livingstone 157.115385
- N Pooran 153.441802
- GJ Maxwell 152.383623
- SP Narine 151.449275
- V Sehwag 149.612403
- AB de Villiers 148.309609
- SO Hetmyer 146.284224
- YBK Jaiswal 145.229244
- RR Pant 144.073107

### 🏆 Team Win Percentage
![Team Win Percentage](Top_Team_Win_Rates.png)

### 📈 Season-wise Total Runs
![Season-wise Runs]<img width="651" height="374" alt="image" src="https://github.com/user-attachments/assets/3a7db60e-7417-4e20-9c77-0055f4d08737" />

### 👤 Player Performance Across Seasons
![Player Performance](ipl_summary.png)


---

## 🔧 Install Required Libraries
```bash
pip install pandas matplotlib seaborn
```
## ▶️ Open the Notebook
jupyter notebook analysis.ipynb
---
## ✅ Conclusion

This project demonstrates how sports data analytics can be used to uncover meaningful insights from large datasets.
Through visualization and statistical analysis, it highlights trends in player performance, team dominance, and the evolution of IPL cricket.
---
## 👤 Author

Aftab Tamboli
---
## ⭐ Feedback

If you find this project useful, feel free to ⭐ the repository.
