# Vroom-Vroom: Toyota Vehicle Market Analysis

A data-driven analysis of Toyota vehicle pricing and depreciation patterns using web scraping and statistical modeling.

## Project Overview

This project analyzes Toyota vehicle pricing across two distinct markets (Boston, MA and Ocean Springs, MS) to identify regional pricing patterns, depreciation trends, and market opportunities for both consumers and dealerships.

## Key Features

- **Web Scraping**: Automated data collection from Cars.com using Python
- **Market Analysis**: Comparative pricing analysis across geographic regions  
- **Depreciation Modeling**: Statistical analysis of vehicle value retention over time
- **Data Visualization**: Interactive charts and graphs showing pricing trends
- **Actionable Insights**: Strategic recommendations for buyers, sellers, and dealers

## Dataset

- **Size**: 618 Toyota vehicles analyzed
- **Primary Models**: 4Runner and Tacoma with various trim levels
- **Price Range**: $4,995 - $71,990
- **Mileage Range**: 5 - 278,000 miles
- **Markets**: Boston, MA vs Ocean Springs, MS

## Technologies Used

- **Python**: Primary programming language
- **Web Scraping**: BeautifulSoup/Scrapy for data extraction
- **Data Analysis**: Pandas, NumPy for data manipulation
- **Visualization**: Matplotlib/Seaborn for charts and graphs
- **Statistical Modeling**: Scipy for depreciation analysis

## Key Findings

### Market Differences
- Ocean Springs maintains **13% price premium** across all model years
- Boston shows **better long-term value retention** with slower depreciation rates
- Regional pricing strategies vary significantly between markets

### Strategic Insights
- **For Buyers**: Boston offers better long-term value retention
- **For Sellers**: Ocean Springs provides premium selling opportunities for newer vehicles
- **For Dealerships**: Inventory transfer opportunities between markets based on regional preferences

## Installation & Usage

```bash
# Clone the repository
git clone https://github.com/SyrettaMeeks/Vroom-Vroom.git

# Navigate to project directory
cd Vroom-Vroom

# Open the analysis notebook
jupyter notebook "Final AD688 TC Multiple Pages(3).ipynb"
```

## Quick Start
1. **View Analysis**: Open the [main notebook](https://github.com/SyrettaMeeks/Vroom-Vroom/blob/main/Final%20AD688%20TC%20Multiple%20Pages(3).ipynb) for complete analysis
2. **Review Findings**: Scroll to conclusion section for key insights
3. **Explore Visualizations**: Interactive charts show regional pricing patterns

## Project Structure

```
Vroom-Vroom/
├── data/
│   ├── raw/           # Scraped data files
│   └── processed/     # Cleaned datasets
├── src/
│   ├── scraper.py     # Web scraping functions
│   ├── analysis.py    # Data analysis scripts
│   └── visualizations.py # Plotting functions
├── notebooks/
│   └── analysis.ipynb # Jupyter notebook with detailed analysis
├── results/
│   ├── plots/         # Generated visualizations
│   └── reports/       # Analysis reports
└── requirements.txt
```

## Future Enhancements

- [ ] Expand to additional Toyota models (Prius, Camry, etc.)
- [ ] Include more geographic markets for broader analysis
- [ ] Implement machine learning models for price prediction
- [ ] Add real-time data updates and monitoring
- [ ] Create interactive dashboard for dynamic analysis

## Contact

**Syretta Meeks**  
Data Science Graduate Student | Boston University  
[GitHub](https://github.com/SyrettaMeeks) | [LinkedIn](your-linkedin-url)

---
*This project demonstrates web scraping, data analysis, and statistical modeling skills using real-world automotive market data.*
