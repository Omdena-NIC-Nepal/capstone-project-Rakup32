# Nepal Climate Analysis Application

A Streamlit-based web application for analyzing and visualizing climate data from Nepal, featuring interactive visualizations and machine learning predictions.

## 🌡️ Features

- **Interactive Data Visualization**
  - Temperature and precipitation trends over time
  - Seasonal patterns analysis
  - Correlation heatmaps
  - Distribution plots

- **Climate Analysis**
  - Historical data analysis (1990-2023)
  - Monthly and yearly trends
  - Seasonal variations
  - Extreme weather event detection

- **Predictions**
  - Temperature forecasting
  - Precipitation predictions
  - Trend analysis

- **Data Sources**
  - World Bank Climate Data API
  - Local data fallback

## 📋 Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/rakup32/nepal-climate-analysis.git
cd nepal-climate-analysis
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## 💻 Usage

1. Start the Streamlit application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to:
```
http://localhost:8501
```

## 📊 Application Structure

```
Climate_ML_app/
├── app.py                 # Main application file
├── data_utils.py          # Data loading and processing utilities
├── visualizations.py      # Visualization functions
├── requirements.txt       # Project dependencies
├── nepal_climate_data.csv # Local climate data
└── pages/                 # Application pages
    ├── overview.py        # Overview page
    ├── data_analysis.py   # Data analysis page
    ├── trend_pattern.py   # Trends and patterns page
    ├── prediction.py      # Predictions page
    └── about.py           # About page
```

## 🎯 Features by Page

### Overview
- Key climate metrics
- Temperature distribution
- Precipitation patterns
- Climate correlations

### Data Analysis
- Interactive data explorer
- Time series visualizations
- Correlation analysis
- Seasonal patterns

### Trends & Patterns
- Temperature trends
- Precipitation trends
- Seasonal variations
- Box plots by season

### Predictions
- Temperature forecasting
- Precipitation predictions
- Trend analysis
- Model performance metrics

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

For any questions or feedback, please open an issue in the repository.

---

Made with ❤️ for Nepal Climate Analysis 
