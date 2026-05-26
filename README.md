# Netflix Data Analysis

## Objective
Perform Exploratory Data Analysis (EDA) on the Netflix Titles dataset to discover:
- Movies vs TV Shows distribution
- Top genres
- Country-wise content production
- Year-wise release trends

## Project Structure

```text
Netflix_Data_Analysis/
│
├── dataset/
│   └── netflix_titles.csv
├── images/
├── netflix_analysis.ipynb
├── README.md
└── requirements.txt
```

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Setup

1. Create and activate a virtual environment (optional but recommended).
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Download the dataset and place `netflix_titles.csv` in:

```text
Netflix_Data_Analysis/dataset/netflix_titles.csv
```

Dataset source: [Kaggle Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Analyses Included
- Movies vs TV Shows distribution
- Top 10 genres
- Top 10 content-producing countries
- Year-wise release trend
- Bonus: Ratings distribution
- Bonus: Correlation heatmap (numeric columns)

## Key Insights (Expected)
- Movies dominate Netflix content.
- USA contributes the most titles.
- India frequently appears among top producing countries.
- Content growth accelerates strongly after 2015.

## Output
Run all cells in `netflix_analysis.ipynb`.  
Charts are displayed inline, and selected charts are also saved to `images/`.
