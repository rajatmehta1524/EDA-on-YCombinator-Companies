# 🚀 Y Combinator Companies & Evolution of Startup Ecosystem

![Y Combinator Logo](images/YC_logo.png)  
*A data visualization project analyzing the impact of Y Combinator-funded startups on the global startup ecosystem.*

---

## 📖 Overview  

Y Combinator (YC) is one of the most influential startup accelerators, funding over 4,000 startups, including **Airbnb, Dropbox, Stripe, and Reddit**. This project explores YC's growth, trends in venture capital (VC) investments, and the success rate of incubated companies using **data analytics and visualization techniques**.  

 📝**Detailed Project Report :** [Click Here](https://drive.google.com/file/d/1I0q57vI9_xOL0XldaUWalNPMv8zpsAGU/view?usp=sharing)  

---

## 📂 Table of Contents  
- [Data Sources](#data-sources)  
- [Tools & Technologies Used](#tools--technologies-used)  
- [Visualizations](#visualizations)  
  - [Pie Charts](#pie-charts)  
  - [Bar Graphs](#bar-graphs)  
  - [Column Charts](#column-charts)  
  - [Bubble Graphs](#bubble-graphs)  
  - [Geographical Maps](#geographical-maps)  
- [Challenges & Solutions](#challenges--solutions)  
- [Future Work](#future-work)  
- [Contributors](#contributors)  

---

## 📊 Data Sources  

We collected data from multiple sources:  
- **Crunchbase** (Company funding, M&A data)  
- **Y Combinator Directory** (List of funded startups)  
- **Kaggle Datasets** (YC-funded startup data, sector analysis)  
- **OECD & World Bank** (Venture capital investment trends & GDP data)  

---

## 🛠 Tools & Technologies Used  

| **Technology**      | **Purpose**  |
|---------------------|-------------|
| Python (Pandas)    | Data cleaning & preprocessing |
| Matplotlib, Seaborn | Static data visualizations |
| Geopandas          | Geographical maps |
| Flourish Studio    | Interactive race bar graphs |
| Animaker           | Video creation for presentation |

---

## 📈 Visualizations  

### 🎯 **Pie Charts**  
#### **1. YC Startup Success Rate**  
- **Public Companies:** Startups that went public  
- **Acquired Companies:** M&A success stories  
- **Failed Companies:** Shut down startups  
- **Active Companies:** Running without IPO/acquisition  

![YC Success Rate](images/success_pie_chart.png)  

---

### 📊 **Bar Graphs**  
#### **2. Sector-Wise Startup Trends (2005-2009)**  
- **Consumer Tech, SaaS, AI, FinTech trends before recession**  
- **Comparison of top-funded startup sectors**  

![Sector Growth](images/sector_growth.png)  

#### **3. Bar Chart Race: Startup Sector Growth (2005-2023)**  
- Animated visualization showing dominance of startup sectors over time  
- **E.g., Rise of FinTech & Crypto startups post-2015**  

![Bar Chart Race](images/bar_chart_race.png)  

---

### 📊 **Column Charts**  
#### **4. YC Startup Team Sizes**  
- Most startups had **small teams** (2-5 founders) at inception  

![Team Size Chart](images/team_size.png)  

#### **5. Revenue and Losses**  
- Revenue and Losses **of the top 4 YC Startups**  

![Funding Rounds](images/revenue_and_losses.png)  

---

### 🌍 **Bubble Graphs & Geographical Maps**  
#### **6. Motion Bubble Graph: GDP vs. VC Investments**  
- Countries with **high venture capital funding → high GDP growth** correlation  

![Bubble Graph](images/bubble_graph.png)  

#### **7. YC's Global Startup Hubs**  
- **Top 10 cities with the most YC-funded startups**  

![YC Global Presence](images/world_map.png)  

---

## 🔍 Challenges & Solutions  

### ❌ **Challenge 1: Data Collection & Cleaning**  
✅ Solution: Used **Crunchbase API, Kaggle Datasets, and Web Scraping** to obtain structured data.  

### ❌ **Challenge 2: Missing Investment Data for Some Regions**  
✅ Solution: Supplemented with **OECD and World Bank data** on VC investments outside the US.  

### ❌ **Challenge 3: Pre-Recession Analysis (2005-2009)**  
✅ Solution: Manually cross-referenced YC's startup directory & historical financial reports.  

---

## 🚀 Future Work  

✔ **Use AI for trend prediction** in venture capital investments  
✔ **Analyze social media impact** on YC-funded startups’ success  
✔ **Sentiment analysis** on startup funding news articles  

---

## 📜 License  
This project is licensed under the **MIT License** - - see the [LICENSE](LICENSE) file for details.
.

