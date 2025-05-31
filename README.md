# News & Stock Data Analysis Project
This repository contains analysis of financial news data for market insights.
## Project Overview
A comprehensive data science project to analyze news articles and their correlation with stock price movements. The project is structured into three main tasks: Exploratory Data Analysis (EDA) of news data, quantitative analysis of stock prices using financial indicators, and correlation analysis between news sentiment and stock returns.
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

- **Proactivity to Self-Learn:** Evidence of using and sharing external references.
- **Dev Environment Setup:** Proper folder structure, version control, and CI/CD.
- **EDA Techniques:** Use of descriptive statistics, visualization, and NLP.
- **Accuracy of Indicators:** Correct calculation and interpretation of financial metrics.
- **Completeness of Analysis:** All required analyses performed and documented.
- **Sentiment & Correlation Analysis:** Effective sentiment scoring and statistical correlation.

## Tasks

### Task 1: Git and GitHub
**Objectives:**
- Set up a Python development environment with version control and CI/CD.
- Perform Exploratory Data Analysis (EDA) on news articles.

**Steps:**
1. **Repository Setup**
   - Create a GitHub repository with the above folder structure.
   - Create a new branch called `task-1` for your analysis.
   - Commit your work at least three times a day with descriptive messages.

2. **Exploratory Data Analysis**
   - **Descriptive Statistics:**  
     - Calculate basic statistics for textual data (e.g., headline length).
     - Count articles per publisher.
     - Analyze publication dates for trends.
   - **Text Analysis (Topic Modeling):**  
     - Use NLP to extract common keywords, phrases, and topics.
   - **Time Series Analysis:**  
     - Analyze publication frequency over time.
     - Identify publication time patterns.
   - **Publisher Analysis:**  
     - Identify top publishers and analyze their news types.
     - If publishers are emails, extract domains to find frequent organizations.

### Task 2: Quantitative Analysis Using PyNance and TA-Lib
**Objectives:**
- Load and analyze stock price data using financial indicators.

**Steps:**
1. **Branching & Merging**
   - Merge `task-1` into `main` via Pull Request.
   - Create a new branch `task-2` for this task.

2. **Data Preparation**
   - Load stock price data (`Open`, `High`, `Low`, `Close`, `Volume`) into a pandas DataFrame.
   - Load and prepare stock price data into a pandas DataFrame.
   - Include columns like Open, High, Low, Close, and Volume.

3. **Technical Analysis**
   - Calculate indicators using TA-Lib (e.g., Moving Averages, RSI, MACD).
   - Use PyNance for additional financial metrics.

4. **Visualization**
   - Visualize stock data and indicators to understand trends and patterns.

### Task 3: Correlation Between News and Stock Movement
**Objectives:**
- Analyze the relationship between news sentiment and stock price movements.

**Steps:**
1. **Branching & Merging**
   - Merge `task-2` into `main` via Pull Request.
   - Create a new branch `task-3` for this task.

2. **Data Preparation**
   - Align news and stock datasets by date.
   - Normalize timestamps as needed.

3. **Sentiment Analysis**
   - Use tools like NLTK or TextBlob to assign sentiment scores (positive, negative, neutral) to news headlines.

4. **Stock Movement Calculation**
   - Compute daily stock returns (percentage change in closing prices).

5. **Correlation Analysis**
   - Aggregate daily sentiment scores.
   - Calculate Pearson correlation between average daily sentiment and daily stock returns.

## Minimum Essential To Do
- Merge necessary branches into the main branch using Pull Requests.
- Create new branches for ongoing development (e.g., `task-2`, `task-3`).
- Commit work with descriptive messages.
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

## Usage
- Run Jupyter notebooks in the notebooks/ directory to execute the analysis

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