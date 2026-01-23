# 🌍 Air Quality Monitoring & Analysis Project

> **Comprehensive Exploratory Data Analysis of 42 Years of US Air Quality Data**  
> *Analyzing 5.6 million records to uncover pollution patterns, trends, and insights*

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0-green.svg)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Complete-success.svg)]()

---

## 📊 Project Overview

This project presents a **comprehensive exploratory data analysis (EDA)** of air quality data spanning **42 years (1980-2022)**, covering **614 US cities** across **52 states**. Through systematic analysis of **5.6 million air quality measurements**, this study reveals critical patterns, temporal trends, and geographic variations in air pollution.

### 🎯 Project Objectives
- Analyze long-term air quality trends across the United States
- Identify geographic patterns and pollution hotspots
- Understand relationships between pollutants, seasons, and locations
- Investigate the impact of environmental regulations (Clean Air Act)
- Create publication-quality visualizations for data-driven insights

---

## 🔑 Key Findings

### 🌟 Major Discoveries

1. **📈 Significant Air Quality Improvement**
   - **26% reduction** in average AQI from 1980s to 2020s
   - 1980s average: **54.6 AQI** → 2020s average: **40.6 AQI**
   - Evidence of Clean Air Act effectiveness

2. **🗺️ Geography Matters More Than Population**
   - Population correlation with AQI: **r = 0.20** (weak)
   - Density correlation with AQI: **r = 0.14** (very weak)
   - **Location, climate, and topography** are primary factors

3. **🔴 California Dominates Worst Air Quality**
   - **9 of the top 10 worst cities** are in California
   - Riverside, CA: Average AQI **124.9** (worst in nation)
   - LA only has **7.3% "Good" air quality days**

4. **☀️ Summer is Peak Pollution Season**
   - July highest: **57.5 AQI** (Ozone-driven)
   - Winter lowest: **39.1 AQI**
   - **69% of summer readings** are Ozone-related

5. **⚠️ PM10 Causes Most Extreme Events**
   - Highest recorded AQI: **20,646** (Bishop, CA - dust storm)
   - **82,854 extreme events** (AQI > 150) in 42 years
   - Bishop, CA appears in **189 extreme events**

6. **🌊 Regional Patterns**
   - West Coast: High PM10 (dust) + Ozone
   - East Coast: High PM2.5 (vehicles) + NO2
   - Midwest: Primarily Ozone (agriculture)
   - Mountain West: **Highest average** (50.6 AQI)

---

## 📁 Repository Structure
```
air-quality-project/
│
├── 📓 Notebooks/
│   ├── 01_data_inspection.ipynb           # Initial data exploration
│   ├── 02_comprehensive_eda.ipynb         # Complete analysis & visualizations
│   └── 03_relationship_analysis.ipynb     # 18 relationship questions
│
├── 📊 visualizations/                      # 12 professional charts
│   ├── viz1_timeseries.png                # 42-year improvement trend
│   ├── viz2_seasonal.png                  # Monthly patterns
│   ├── viz3_decades.png                   # Decade comparison
│   ├── viz4_state_heatmap.png             # State rankings
│   ├── viz5_city_rankings.png             # Best vs worst cities
│   ├── viz6_regional_comparison.png       # Regional analysis
│   ├── viz7_geographic_scatter.png        # USA pollution map
│   ├── viz8_pollutant_overview.png        # Pollutant breakdown
│   ├── viz9_pollutant_seasonality.png     # Seasonal pollutant patterns
│   ├── viz10_extreme_events.png           # Extreme event timeline
│   ├── viz11_population_relationships.png # Population vs AQI
│   └── viz12_summary_dashboard.png        # Executive dashboard
│
├── 📄 README.md                            # This file
├── 📄 .gitignore                           # Git exclusions
└── 📄 requirements.txt                     # Python dependencies
```

---

## 📈 Visualizations Gallery

### Theme 1: Temporal Trends
<details>
<summary>Click to expand</summary>

| Visualization | Description |
|--------------|-------------|
| **Time Series (1980-2022)** | Shows 26% improvement in air quality with confidence intervals |
| **Seasonal Patterns** | Monthly AQI trends + pollutant composition by season |
| **Decade Comparison** | Clear downward trend from 1980s (53.4) to 2020s (40.9) |

</details>

### Theme 2: Geographic Patterns
<details>
<summary>Click to expand</summary>

| Visualization | Description |
|--------------|-------------|
| **State Heatmap** | Top 25 states ranked by average AQI (DC worst: 70.3) |
| **City Rankings** | Best 10 vs Worst 10 cities (California dominates worst) |
| **Regional Comparison** | West vs East analysis with pollutant breakdown |
| **Geographic Scatter** | USA map showing pollution hotspots (5 worst cities marked) |

</details>

### Theme 3: Pollutant Analysis
<details>
<summary>Click to expand</summary>

| Visualization | Description |
|--------------|-------------|
| **Pollutant Overview** | 4-panel analysis: frequency, averages, distribution, extremes |
| **Seasonality Chart** | Stacked area showing when each pollutant peaks |
| **Extreme Events** | Timeline showing 1988 was worst year (5,029 events) |

</details>

### Theme 4: Relationships
<details>
<summary>Click to expand</summary>

| Visualization | Description |
|--------------|-------------|
| **Population vs AQI** | 4-panel analysis proving weak correlation (r=0.20) |
| **Summary Dashboard** | 6-panel executive overview with key statistics |

</details>

---

## 🔬 Analysis Methodology

### Research Questions Answered (18 Total)

#### Fundamental Relationships (8)
1. ✅ When is category "Good"? (AQI 0-50)
2. ✅ Does population/density affect AQI? (Weak effect)
3. ✅ Does timezone affect AQI? (Proxy for geography)
4. ✅ Does state affect AQI? (Strong effect)
5. ✅ Do number of sites affect AQI? (Selection bias)
6. ✅ Does AQI affect the defining parameter? (Parameter determines AQI)
7. ✅ Has time affected AQI? (26% improvement!)
8. ✅ Does geographic location affect AQI? (Strong effect)

#### Advanced Patterns (10)
9. ✅ Pollutant regional patterns
10. ✅ Seasonal air quality patterns
11. ✅ Weekday vs weekend effect
12. ✅ Extreme event clustering
13. ✅ Long-term improvement trends
14. ✅ Regional similarity analysis
15. ✅ "Good" day frequency by city
16. ✅ Pollutant co-occurrence patterns
17. ✅ Coastal vs inland differences
18. ✅ Persistent pollution hotspots

---

## 📊 Dataset Information

| Attribute | Details |
|-----------|---------|
| **Total Records** | 5,617,325 |
| **Time Period** | January 1, 1980 - May 31, 2022 (42+ years) |
| **Geographic Coverage** | 614 cities across 52 states |
| **Pollutants Tracked** | PM2.5, Ozone, PM10, NO2, CO |
| **Variables** | 15 original + 8 derived = 23 total |
| **Data Quality** | 100% complete (no missing values) |
| **Extreme Events** | 82,854 readings with AQI > 150 |

### Data Sources
- Air Quality Index (AQI) measurements
- EPA air quality monitoring stations
- City demographic data (population, density)
- Geographic coordinates (latitude, longitude)

---

## 🛠️ Technologies & Tools

### Core Technologies
- **Python 3.x** - Primary programming language
- **Jupyter Notebook** - Interactive analysis environment
- **Git/GitHub** - Version control and collaboration

### Data Analysis Libraries
```python
pandas==2.0.0          # Data manipulation
numpy==1.24.0          # Numerical computing
scipy==1.10.0          # Statistical analysis
```

### Visualization Libraries
```python
matplotlib==3.7.0      # Core plotting
seaborn==0.12.0        # Statistical visualizations
```

### Development Tools
- **VS Code** - Code editor
- **Git Bash** - Command line interface
- **Virtual Environment** - Dependency isolation

---

## 🚀 Installation & Usage

### Prerequisites
- Python 3.8 or higher
- pip package manager
- Git

### Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/philtait/air-quality-monitoring.git
cd air-quality-monitoring
```

2. **Create virtual environment**
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook**
```bash
jupyter notebook
```

5. **Open notebooks**
- Start with `01_data_inspection.ipynb`
- Then proceed to `02_comprehensive_eda.ipynb`

---

## 📈 Results Summary

### Statistical Highlights

| Metric | Value |
|--------|-------|
| **Average AQI (Overall)** | 46.7 |
| **Percentage "Good" Days** | 70.1% |
| **Improvement Since 1980** | -26% (better) |
| **Highest State AQI** | DC (70.3) |
| **Lowest State AQI** | Hawaii (26.6) |
| **Worst City** | Riverside, CA (124.9) |
| **Best City** | Alma, MI (5.0) |
| **Peak Pollution Month** | July (57.5) |
| **Cleanest Month** | December (38.4) |

### Correlation Analysis

| Variable Pair | Correlation | Interpretation |
|--------------|-------------|----------------|
| Population ↔ AQI | r = 0.198 | Weak positive |
| Density ↔ AQI | r = 0.143 | Very weak |
| Latitude ↔ AQI | r = -0.075 | Very weak |
| Year ↔ AQI | r = -0.109 | Weak negative (improving!) |
| Sites ↔ AQI | r = 0.260 | Weak positive (selection bias) |

---

## 🎓 Skills Demonstrated

### Data Science Competencies
- ✅ **Data Cleaning & Preparation** - Handled 5.6M records
- ✅ **Exploratory Data Analysis** - Systematic investigation
- ✅ **Statistical Analysis** - Correlation, hypothesis testing
- ✅ **Data Visualization** - 12 publication-quality charts
- ✅ **Temporal Analysis** - 42-year trend identification
- ✅ **Geographic Analysis** - Spatial pattern recognition
- ✅ **Feature Engineering** - Created 8 derived variables
- ✅ **Data Quality Assessment** - Comprehensive validation

### Technical Skills
- ✅ Python programming (Pandas, NumPy, Matplotlib)
- ✅ Jupyter Notebook development
- ✅ Git version control
- ✅ GitHub collaboration
- ✅ Data storytelling
- ✅ Documentation writing

---

## 💡 Key Insights for Stakeholders

### For Environmental Policy Makers
- ✅ Clean Air Act has been **highly effective** (26% improvement)
- ⚠️ California needs **targeted interventions** (dominates worst cities)
- ✅ Focus on **summer ozone** and **winter PM2.5** control

### For Urban Planners
- 💡 **Geography > Population** - Location matters more than size
- 💡 Valley cities (Riverside, Fresno) need **topography-aware** solutions
- 💡 **Mountain West** has the highest regional AQI (dust control needed)

### For Public Health Officials
- 📅 **June-August** are the highest risk months (Ozone peaks)
- 🏙️ **9 California cities** should issue frequent health alerts
- ✅ **70% of days are "Good"** nationwide (positive message)

---

## 🔮 Future Work

### Planned Enhancements
- [ ] **Machine Learning Models** - Predict AQI from weather/geography
- [ ] **Interactive Dashboard** - React-based web application
- [ ] **Real-time Monitoring** - Integration with IoT sensors
- [ ] **Forecasting Models** - LSTM/ARIMA for future predictions
- [ ] **API Development** - FastAPI backend for data access
- [ ] **Mobile Application** - Cross-platform air quality app

### Research Extensions
- [ ] Climate change impact analysis
- [ ] Wildfire season correlation studies
- [ ] Economic impact assessment
- [ ] Health outcome correlations
- [ ] International comparisons

---

## 📚 References & Resources

### Data Sources
- EPA Air Quality System (AQS)
- US Census Bureau demographic data
- NOAA climate data

### Documentation
- [EPA AQI Guide](https://www.airnow.gov/aqi/aqi-basics/)
- [Clean Air Act](https://www.epa.gov/clean-air-act-overview)
- [Pandas Documentation](https://pandas.pydata.org/docs/)

---

## 👤 Author

**[Your Name]**
- GitHub: [@your-username](https://github.com/philtait)


---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Environmental Protection Agency (EPA) for air quality data
- Open source community for Python libraries
- Air quality monitoring internship program

---

## 📞 Contact & Support

**Questions or feedback?**
- 💬 Open an [Issue](https://github.com/philtait/air-quality-monitoring/issues)
- 🌟 Star this repo if you find it helpful!

---

<div align="center">

**⭐ If you found this project valuable, please consider giving it a star! ⭐**

*Made with ❤️ and Python*

*Last Updated: January 2026*

</div>
