# News & Stock Data Analysis Project
Welcome to the Financial News & Stock Analysis Project — a data science pipeline that explores how financial news sentiment correlates with stock market movements. This project combines text analytics, technical indicators, and statistical correlation to uncover actionable insights.
## Project Overview 
# This project is structured into three key tasks:

 1. Exploratory Data Analysis (EDA) of financial news.

 2. Quantitative Analysis of stock prices using technical indicators.

 3. Sentiment-Correlation Analysis between news and stock returns.

 - It showcases the full workflow from data wrangling to modeling, with emphasis on - - reproducibility, modularity, and CI/CD integration.
## Project Structure

- Financial-news-analysis/
- ├── .vscode/
- │   └── settings.json              # VSCode workspace settings
- ├── .github/
- │   └── workflows/
- │       └── unittests.yml         # GitHub Actions workflow for CI/CD
- ├── .gitignore                    # Ignore Python artifacts, etc.
- ├── requirements.txt              # Python dependencies
- ├── README.md                     # Project documentation
- ├── src/
- │   └── __init__.py               # Core source files
- ├── notebooks/
- │   ├── __init__.py
- │   └── README.md                 # Notebook descriptions
- ├── tests/
- │   └── __init__.py               # Unit test scripts
- └── scripts/
    - ├── __init__.py
    - └── README.md                 # Script descriptions

## Key Performance Indicators (KPIs)

- ✅Clean and modular project structure.

- ✅ Git & GitHub usage with proper branching and commits.

- ✅ Automated testing via GitHub Actions.

- ✅ EDA using NLP and statistical techniques.

- ✅ Financial metrics with TA-Lib & PyNance.

- ✅ Correlation between sentiment and market performance.
###  Tasks Summary
## **Task 1: GitHub Setup & News EDA**
- ✅ Create repo and GitHub workflows.

- ✅ Perform EDA on news: keyword extraction, publisher analysis, and time-series trends.

- ✅ Use NLP for topic modeling.

## **Task 2: Stock Price Analysis**
- ✅ Analyze stock data (Open, Close, Volume, etc.).

- ✅ Compute indicators like SMA, RSI, and MACD using TA-Lib & PyNance.

- ✅ Visualize trends with Matplotlib/Plotly.

## **Task 3: Sentiment vs. Stock Returns**
- ✅ Score news headlines with NLTK or TextBlob.

- ✅ Align news and stock data by date.

- ✅ Compute daily returns and analyze correlation with sentiment.

## Technologies Used

- **Python**: Programming language used for data analysis.
- **Pandas**: Data manipulation and analysis library.
- **NumPy**: Library for numerical operations.
- **Scikit-learn**: Machine learning library for implementing algorithms.
- **Matplotlib/Seaborn**: Libraries for data visualization.
- **NLTK/TextBlob**: Libraries for natural language processing.
- **GitHub Actions**: CI/CD for automated testing and deployment.
## Getting Started

### Prerequisites

- Python 3.9+
- Git
- Virtual environment (recommended)

### Installation

1. Clone the repository:

- git clone https://github.com/haile12michael12/financial-news-analysis.git
- cd financial-news-analysis

2. Create and activate a virtual environment:
- python -m venv venv
- source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. Install dependencies:
 - pip install -r requirements.txt


## CI/CD
- All pushes and pull requests trigger unit tests via GitHub Actions.
- CI/CD is managed with GitHub Actions:

- Workflow file: .github/workflows/unittests.yml

- Automatically runs tests on each push or PR to main


## Contribution Guide
- Fork the repository.

- Clone it locally and create a new branch.

- Make your changes with detailed commit messages.

- Push the branch and create a PR.

## References

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [TA-Lib Documentation](https://mrjbq7.github.io/ta-lib/)
- [PyNance](https://github.com/saulpw/pyNance)
- [NLTK Sentiment Analysis](https://www.nltk.org/howto/sentiment.html)
- [TextBlob Documentation](https://textblob.readthedocs.io/en/dev/)
- [GitHub Actions](https://docs.github.com/en/actions)