# Financial News Analysis

This repository contains analysis of financial news data for market insights.
## Project Overview
This repository contains tools and analysis for news article exploratory data analysis (EDA). The goal is to extract, understand, and visualize insights from news data, focusing on publishers, time trends, and content.

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


## Setup

1. Clone the repository
2. Create virtual environment: `python -m venv venv`
3. Activate environment: `source venv/bin/activate` (Linux/Mac) or `venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`

## CI/CD
- All pushes and pull requests trigger unit tests via GitHub Actions.
- CI/CD is managed with GitHub Actions:

- Workflow file: .github/workflows/unittests.yml

- Automatically runs tests on each push or PR to main
## Exploratory Data Analysis (EDA)
# 1. Descriptive Statistics
- Headline lengths (mean, median, std).

- Number of articles per publisher.

- Time-series plot of article counts per day.

# 2. Text Analysis (Topic Modeling)
- Keyword extraction and topic clustering using NLP.

- Highlight common phrases like:

- “price target”

- “earnings report”

- “FDA approval”

# 3. Time Series Analysis
- Frequency of article publications over time.

- Spikes around events or market announcements.

- Identify peak publishing hours.

# 4. Publisher Analysis
- Top contributing publishers.

- Differences in content style per publisher.

- Analysis of email domains (e.g., @reuters.com, @bloomberg.net).

## Notes & Suggestions
- Use libraries like pandas, matplotlib, seaborn, and nltk for EDA.

- Save intermediate outputs or figures inside /notebooks or /outputs.

- Refer to sources like Kaggle or Towards Data Science for topic modeling inspiration.

## Contribution Guide
- Fork the repository.

- Clone it locally and create a new branch.

- Make your changes with detailed commit messages.

- Push the branch and create a PR.

## References
- TA-Lib Documentation

- PyNance GitHub

- nltk Docs

- GitHub Actions Docs