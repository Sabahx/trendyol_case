# Trendyol Language Data Analysis Case Study

This repository contains a comprehensive data analysis project for language data, focusing on data quality assessment, pattern recognition, and language-specific analysis.

## Project Structure

```
trendyol_case/
├── data/                    # Raw data files
├── notebooks/              # Jupyter notebooks for analysis
│   ├── 01_initial_analysis.ipynb
│   ├── 02_pattern_analysis.ipynb
│   ├── 03_arabic_analysis.ipynb
│   ├── 04_visualizations.ipynb
│   └── 05_recommendations.ipynb
├── outputs/                # Analysis results and samples
└── README.md
```

## Notebooks Overview

1. **Initial Analysis** - Data exploration and preliminary findings
2. **Pattern Analysis** - Identifying patterns in the data
3. **Arabic Analysis** - Language-specific analysis for Arabic text
4. **Visualizations** - Charts and graphs of key findings
5. **Recommendations** - Actionable insights and suggestions

## Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd trendyol_case
```

2. Create a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Open the Jupyter notebooks in sequence to follow the analysis workflow:

```bash
jupyter notebook
```

## Outputs

The `outputs/` directory contains:
- Cleaned datasets
- Sample data for manual review
- Analysis findings and results

## License

This project is for case study purposes.
