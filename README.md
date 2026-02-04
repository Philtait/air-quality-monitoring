# Air Quality Monitoring & Analysis Project

## Project Overview
This project analyzes **42 years of air quality data (1980-2022)** from EPA monitoring stations across the United States, covering 5 million+ readings from 634 cities across 52 states/territories.

## Key Findings
- 📈 **26% improvement** in air quality from 1980 to 2022
- ☀️ **Summer months** have the worst air quality (July peak: 57.5 AQI)
- 🏭 **Ozone is dominant** - accounts for 54% of pollutant readings
- 📍 **California cities** consistently rank as worst for air quality
- 🌍 **Geography matters more than population** - weak correlation (r=0.20)
- ⚠️ **Extreme events decreased** dramatically since the 1990s

## Project Structure
```
air-quality-project/
├── notebooks/                    # Jupyter notebooks for analysis
│   ├── 01_data_inspection.ipynb  # Initial data exploration
│   └── 02_comprehensive_eda.ipynb # Complete exploratory data analysis
├── scripts/                      # Python scripts
│   └── create_presentation.py    # PowerPoint presentation generator
├── visualizations/               # Generated charts and graphs
│   ├── viz1_timeseries.png      # 42-year time series trend
│   ├── viz2_seasonal.png        # Seasonal patterns
│   ├── viz3_decades.png         # Decade comparison
│   ├── viz4_state_heatmap.png   # State rankings
│   ├── viz5_city_rankings.png   # Best/worst cities
│   ├── viz6_regional_comparison.png
│   ├── viz7_geographic_scatter.png
│   ├── viz8_pollutant_overview.png
│   ├── viz9_pollutant_seasonality.png
│   ├── viz10_extreme_events.png
│   ├── viz11_population_relationships.png
│   └── viz12_summary_dashboard.png
├── outputs/                      # Final deliverables
│   └── Air_Quality_Analysis_Presentation.pptx  # 15-slide presentation
├── docs/                         # Documentation
│   └── data_inspection_summary.txt
├── air_quality_data.csv          # Main dataset (600MB+)
└── README.md
```

## Technologies Used
- **Python 3.x** - Programming language
- **Pandas & NumPy** - Data manipulation
- **Matplotlib & Seaborn** - Data visualization
- **python-pptx** - PowerPoint generation
- **Jupyter Notebooks** - Interactive analysis

## Dataset
- **Source**: EPA Air Quality Monitoring Stations
- **Parameters**: AQI, PM2.5, PM10, Ozone, NO2, CO
- **Coverage**: 634 cities across 52 states/territories
- **Time Period**: 1980-2022 (42 years)
- **Size**: 5+ million readings

## Project Status
- [x] Environment setup
- [x] Git/GitHub initialization
- [x] Data inspection and cleaning
- [x] Exploratory Data Analysis
- [x] Visualization and insights (12 charts)
- [x] PowerPoint presentation (15 slides)
- [ ] Predictive modeling (future)

## Outputs
The main deliverable is a **15-slide PowerPoint presentation** (`outputs/Air_Quality_Analysis_Presentation.pptx`) covering:
1. Executive summary and key findings
2. 42-year historical trends
3. Seasonal and regional patterns
4. State and city rankings
5. Pollutant analysis
6. Conclusions and recommendations

## Author
Philip Tait

## License
MIT License
