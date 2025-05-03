# Stock Analysis ML Pipeline

A Streamlit web application for analyzing stock data using machine learning techniques. The app provides features for data preprocessing, technical analysis, model training, and stock price prediction.

## Features

- Data loading from CSV or Yahoo Finance API
- Data preprocessing and cleaning
- Technical indicator calculation
- Multiple ML models (Linear Regression, Logistic Regression, K-means Clustering)
- Interactive visualizations
- Model evaluation metrics
- Future price predictions

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd stock_analysis_app
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Local Development

Run the app locally:
```bash
streamlit run app.py
```

The app will be available at `http://localhost:8501`

## Deployment

This app is ready to be deployed on Streamlit Cloud:

1. Push your code to GitHub
2. Visit [Streamlit Cloud](https://streamlit.io/cloud)
3. Sign in with your GitHub account
4. Click "New app"
5. Select this repository and branch
6. Click "Deploy"

## Configuration

The app's appearance is configured in `.streamlit/config.toml`:
- Dark theme
- Custom color scheme
- Server settings

## Dependencies

All required packages are listed in `requirements.txt`. Key dependencies:
- streamlit==1.31.1
- yfinance==0.2.36
- pandas==2.2.0
- numpy==1.26.4
- plotly==5.18.0
- scikit-learn==1.4.0

## License

MIT License 
