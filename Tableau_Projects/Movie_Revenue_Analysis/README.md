# 🎬 Movie Revenue Analysis: Domestic vs International Trends (2020-2024)

> **Decoding Box Office Success Through Data Visualization & Statistical Analysis**



[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com)
[![Data Analysis](https://img.shields.io/badge/Analysis-Statistical-blue?style=for-the-badge)](https://github.com)
[![Revenue Insights](https://img.shields.io/badge/Insights-Business-green?style=for-the-badge)](https://github.com)

---

## 🎯 **Project Overview**

This comprehensive analysis explores the intricate relationship between **genre**, **seasonal timing**, **audience ratings**, and **box office performance** across domestic and international markets. Using advanced data visualization techniques and statistical modeling, the project uncovers actionable insights for film industry stakeholders.

### 🔍 **Core Research Questions**
- 🌟 Which genres dominate different seasons?
- 📊 How does domestic revenue distribution vary by genre?
- ⭐ What's the correlation between IMDb ratings and commercial success?
- 🌍 What drives domestic vs international performance patterns?

---




### 🏆 **Major Discoveries**

| **Insight** | **Finding** | **Business Impact** |
|-------------|-------------|-------------------|
| 🎨 **Animation Dominance** | 30.6% of domestic revenue share | Target family audiences for maximum ROI |
| 🌞 **Seasonal Patterns** | Action/Animation rule summer | Strategic release timing |
| ⭐ **Rating Paradox** | Strong correlation for Action (R² = 0.33), weak for Sci-Fi (R² = 0.08) | Genre-specific marketing strategies |
| 🎯 **Revenue Distribution** | 35-50% domestic revenue typical | Financial planning benchmarks |

### 📊 **Statistical Performance Matrix**

```
┌─────────────┬─────────────────────┬──────────────────────┬─────────────────────┐
│   Genre     │  Domestic Revenue % │  Rating Correlation  │   Top Performer     │
├─────────────┼─────────────────────┼──────────────────────┼─────────────────────┤
│ Animation   │      35-45%         │      Moderate        │ Inside Out 2 ($653M)│
│ Action      │      45-50%         │   Strong (R² = 0.33) │     Twisters        │
│ Comedy      │   Variable (0-65%)  │        Weak          │      Various        │
│ Sci-Fi      │      35-45%         │  Very Weak (R² = 0.08)│  Dune: Part Two    │
└─────────────┴─────────────────────┴──────────────────────┴─────────────────────┘
```

---

## 🛠️ **Technical Implementation**

### **Technology Stack**
- ![Tableau](https://img.shields.io/badge/-Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) **Advanced Visualizations**
- ![Statistics](https://img.shields.io/badge/-Statistical_Analysis-blue?style=flat-square) **Regression Modeling**
- ![Data](https://img.shields.io/badge/-Data_Processing-green?style=flat-square) **Revenue Calculations**

### **Interactive Dashboard Features**
- 🎛️ **Dynamic Parameters**: Year filtering and time period grouping
- 📱 **Responsive Design**: Optimized for multiple screen sizes  
- 🔍 **Smart Tooltips**: Detailed movie information on hover
- 📊 **Multi-Chart Integration**: Seamless cross-filtering capabilities

---



### **Chart I: Seasonal Genre Performance**

<img width="676" height="343" alt="image" src="https://github.com/user-attachments/assets/24b40689-976f-41dc-9cfe-a52ad6df0ced" />


```
🌞 Summer  ████████████████ Action & Animation dominate (13.0% + 11.1%)
🍂 Fall    ████████ Animation leads with genre diversity (6.5%)
🌸 Spring  ██████████ Comedy thrives (6.4%)
❄️ Winter  ████████ Action maintains strength (6.4%)
```

### **Chart II: Revenue Distribution Analysis**

<img width="634" height="362" alt="image" src="https://github.com/user-attachments/assets/6fa4aaba-29b5-4553-b9bd-13b15d56822e" />


- **Distribution Type**: Right-skewed histogram
- **Peak Range**: 35-50% domestic revenue
- **Genre Insights**: Action dominates 45-50% range

### **Chart III: Rating-Revenue Correlation**

<img width="637" height="365" alt="image" src="https://github.com/user-attachments/assets/a4c68040-cc39-4f55-aba3-1a84591dbac8" />


- **Action Films**: R² = 0.33, p < 0.0001 ✅ *Statistically significant*
- **Sci-Fi Films**: R² = 0.08, p = 0.27033 ❌ *Non-significant*
- **Key Insight**: Genre dramatically affects rating-revenue relationship

### **Chart IV: 2024 Genre Revenue Contribution**

<img width="625" height="391" alt="image" src="https://github.com/user-attachments/assets/98cae638-b13d-4195-8e70-90b62fe9567c" />


```
Animation  ████████████████████████████████ 30.6%
Action     ████████████████████████ 25.9%
Comedy     ██████████ 11.6%
Sci-Fi     ████████ 10.8%
Others     ████████ <7% each
```

### **Chart V: Revenue-Rating Matrix (Treemap)**

<img width="613" height="386" alt="image" src="https://github.com/user-attachments/assets/1938abed-bb0c-4983-bd3b-1f956ac8bce7" />


- **Top Performer**: Inside Out 2 ($653M, 7.7 IMDb)
- **Critical Darling**: Dune: Part Two (8.6 IMDb, $232M)
- **Commercial Giants**: High revenue, moderate ratings pattern identified

---

## 📁 **Project Structure**

```
Movie_Revenue_Analysis/
│
├── 📄 README.md                          # Project documentation
├── 📊 Movie_Revenue_Dashboard.twbx       # Interactive Tableau workbook
│
├── 📚 documentation/
│   ├── 📋 Movie_Analysis_Report.pdf      # Comprehensive findings report
│   └── 📝 methodology_notes.md           # Analysis methodology
│
├── 📈 data/
│   ├── 🎬 movie_data_2020_2024.csv      # Source dataset
│   └── 🧹 cleaned_data_processing.py     # Data cleaning scripts
│
├── 🖼️ assets/
    ├── dashboard_overview.png             # Main dashboard screenshot
    ├── key_findings_infographic.png       # Summary of major insights
    ├── all_charts_preview.png             # Overview of all visualizations
    ├── seasonal_analysis.png              # Chart I - Seasonal performance
    ├── revenue_distribution.png           # Chart II - Revenue histogram
    ├── correlation_charts.png             # Chart III - Rating vs revenue
    ├── genre_performance.png              # Chart IV - Genre contribution
    ├── treemap_analysis.png               # Chart V - Revenue-rating matrix
    └── business_recommendations.png       # Strategic insights visual
```

---


### 🎯 **Release Strategy Optimization**
| **Season** | **Recommended Genres** | **Rationale** |
|------------|----------------------|---------------|
| **Summer** | Action, Animation | Maximum blockbuster potential |
| **Winter** | Comedy, Family | Holiday audience capture |
| **Spring** | Comedy, Romance | School break targeting |
| **Fall** | Horror, Thriller | Seasonal theme alignment |

### 💰 **Investment Insights**
1. **Animation Priority**: Strongest domestic revenue generator (30.6% share)
2. **Quality vs Commercial**: High ratings ≠ guaranteed revenue (especially Sci-Fi)
3. **Market Planning**: Budget for 35-50% domestic revenue allocation
4. **Risk Assessment**: Genre-specific correlation patterns for forecasting

---

## 📊 **Methodology & Data Quality**

### **Dataset Specifications**
- **Time Period**: 2020-2024 (Post-pandemic recovery era)
- **Sample Size**: Top 25 movies by revenue performance
- **Statistical Threshold**: p-values < 0.05 for significance
- **Currency**: USD (domestic box office only)
- **Data Sources**: Box Office Mojo, IMDb, industry reports

### **Statistical Methods**
- ✅ **Regression Analysis**: R-squared calculations
- ✅ **Correlation Testing**: Pearson correlation coefficients  
- ✅ **Distribution Analysis**: Histogram and skewness assessment
- ✅ **Significance Testing**: P-value validation

---

## 🚀 **Future Roadmap**

### **Phase 2 Enhancements**
- 📺 **Streaming Integration**: Netflix, Disney+, Prime performance
- 💵 **ROI Analysis**: Production budget vs revenue ratios
- 🎭 **Talent Analytics**: Director/actor impact assessment
- 🌍 **Geographic Expansion**: Regional market breakdown
- 🌤️ **External Factors**: Weather correlation analysis

### **Technical Upgrades**
- 🤖 **ML Predictions**: Revenue forecasting models
- 📱 **Mobile Dashboard**: Responsive design optimization
- 🔄 **Real-time Data**: Automated refresh capabilities
- 📧 **Alert System**: Performance threshold notifications

---

## 🎬 **View the Interactive Dashboard**



*Requires Tableau Desktop 2024.1+ or Tableau Reader*

### **Navigation Guide**
1. **Filter by Year**: Use the year parameter selector
2. **Toggle Metrics**: Switch between domestic/worldwide revenue
3. **Explore Correlations**: Hover over data points for details
4. **Compare Genres**: Use the genre color legend

---

## 👨‍💼 **About the Analyst**

**Rasheed Afolabi** | Business Intelligence Specialist

*Transforming entertainment industry data into strategic insights through advanced analytics and compelling visualizations.*

---

## 📞 **Connect & Collaborate**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rasheedafolabi1)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rasheed-Afolabi)


---

**📅 Analysis Period**: 2020-2024 | **🔄 Last Updated**: April 2025 | **🛠️ Tools**: Tableau 2024.1, Statistical Analysis

---

*"In the intersection of data and storytelling lies the future of entertainment analytics."*
