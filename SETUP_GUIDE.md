# COVID-19 Data Analysis Project - Setup Guide

## 🚀 Quick Start Guide

### 1. Install Python
**Download Python 3.11 or 3.12 from [python.org](https://www.python.org/downloads/)**
- ✅ Check "Add Python to PATH" during installation
- ✅ Install for all users

### 2. Install Required Packages
Open Command Prompt or PowerShell and run:
```bash
pip install -r requirements.txt
```

### 3. Run the Project
```bash
jupyter notebook "Covid19-Data Analysis.ipynb"
```

## 📋 What This Project Does

This project analyzes COVID-19 data from India and globally, including:
- **State-wise COVID cases in India**
- **Time series analysis** of confirmed cases, deaths, and recoveries
- **Geographic visualization** using Folium maps
- **Interactive charts** using Plotly
- **Statistical analysis** and insights

## 🔧 Required Packages

- **pandas**: Data manipulation and analysis
- **matplotlib**: Basic plotting and visualization
- **plotly**: Interactive charts and dashboards
- **cufflinks**: Pandas-Plotly integration
- **folium**: Geographic mapping
- **openpyxl**: Excel file reading
- **jupyter**: Notebook environment

## 📁 Project Files

- **`Covid19-Data Analysis.ipynb`**: Main analysis notebook
- **`Covid cases in India.xlsx`**: India-specific COVID data
- **`time_series_*.csv`**: Global time series data
- **`COVID19_*_list.csv`**: Detailed case data
- **`Indian Coordinates.xlsx`**: Geographic coordinates

## ⚠️ Important Notes

1. **File Paths**: The original notebook has hardcoded paths that need to be updated
2. **Data Sources**: Uses multiple COVID-19 datasets from different sources
3. **Visualizations**: Creates interactive charts, maps, and statistical summaries

## 🎯 Expected Outputs

- Bar charts showing COVID cases by Indian states
- Time series plots of global COVID trends
- Geographic maps with case distributions
- Statistical summaries and insights
- Interactive dashboards

## 🆘 Troubleshooting

**If you get import errors:**
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

**If Jupyter doesn't start:**
```bash
python -m pip install jupyter
jupyter notebook
```

**If file paths don't work:**
Make sure all data files are in the same directory as the notebook.

## 📊 Sample Analysis

The project will show:
- Total COVID cases in India: 729 (from the data)
- State-wise breakdown of cases
- Active vs. recovered vs. death cases
- Geographic distribution
- Time-based trends

## 🎉 Ready to Run!

Once you have Python and the packages installed, you're ready to explore COVID-19 data analysis!
