# Salary Predictor

A machine learning web application that predicts JavaScript developer salaries based on job characteristics using data from the Adzuna API.

## Features

- **Data Collection**: Automated job data scraping from Adzuna API
- **Machine Learning**: Multiple model comparison (Linear Regression, Random Forest, Gradient Boosting)
- **Interactive Dashboard**: Real-time salary predictions with Plotly visualizations
- **Market Analysis**: Salary comparisons and insights

## Tech Stack

- **Backend**: Python, scikit-learn, pandas, numpy
- **Frontend**: Dash, Plotly
- **Data Source**: Adzuna Jobs API
- **ML Models**: Linear Regression, Random Forest, Gradient Boosting

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/RajRawat112/salary-predictor.git
cd salary-predictor
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Set up API credentials**
Create a `.env` file:
```
ADZUNA_APP_ID=your_app_id_here
ADZUNA_APP_KEY=your_app_key_here
```

## Usage

### Train the Model
```bash
jupyter notebook Main.ipynb
```
Run all cells to collect data, engineer features, and train models.

### Launch Dashboard
```bash
python dashboard.py
```
Access at: http://127.0.0.1:8050

## Model Performance

| Model | R² Score | MAE | RMSE |
|-------|----------|-----|------|
| Linear Regression | 1.000 | £0 | £0 |
| Random Forest | 1.000 | £0 | £0 |
| Gradient Boosting | 0.999997 | £30 | £34 |

## API Setup

1. Sign up at [Adzuna Developer Portal](https://developer.adzuna.com/)
2. Get your App ID and App Key
3. Add credentials to `.env` file

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add feature'`)
4. Push to branch (`git push origin feature/improvement`)
5. Create Pull Request

## Contact

- GitHub: [@RajRawat1102](https://github.com/RajRawat1102)
- Email: raj.rawat@ucalgary.ca
