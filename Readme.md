# International Debt Statistics Analysis

## Overview
This project analyzes international debt data collected by The World Bank. The dataset contains information about the amount of debt (in USD) owed by developing countries across several categories. The analysis explores various aspects of international debt to understand the global economic situation better.

## Key Questions Answered
- What is the total amount of debt owed by countries in the dataset?
- Which country owns the maximum amount of debt?
- What is the average amount of debt across different debt indicators?
- What are the most common debt indicators?
- How does the debt distribution vary across countries?

## Dataset Description
The dataset contains the following columns:
- `country_name`: Name of the country
- `country_code`: Country code
- `indicator_name`: Name of the debt indicator
- `indicator_code`: Code for the debt indicator
- `debt`: Amount of debt in USD

## Key Findings
1. The total global debt is $3,079,734.49 million
2. China has the highest amount of debt at approximately $285.79 billion
3. Principal repayments on external debt (long-term) is the debt indicator with the highest average debt
4. Six debt indicators are common across all countries in the dataset

## Technologies Used
- PostgreSQL
- Python
- Jupyter Notebook
- SQL

## Setup and Installation
1. Clone the repository:
```bash
git clone https://github.com/Sarishc/International-debt-analysis.git
```

2. Set up PostgreSQL database:
```bash
createdb international_debt
```

3. Import the data (SQL file provided in the repository):
```bash
psql international_debt < international_debt.sql
```

4. Install required Python packages:
```bash
pip install -r requirements.txt
```

## Usage
Open the Jupyter notebook `Analyze_International_Debt_Statistics.ipynb` to view the complete analysis:
```bash
jupyter notebook Analyze_International_Debt_Statistics.ipynb
```

## Project Structure
```
international-debt-analysis/
│
├── data/
│   └── international_debt.sql
│
├── notebooks/
│   └── Analyze_International_Debt_Statistics.ipynb
│
├── requirements.tx
└── README.md
```

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Acknowledgments
- The World Bank for providing the international debt dataset
- DataCamp for the project structure and guidance