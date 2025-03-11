# Clean Leasing Company Google Reviews Analysis

## Overview

This repository contains an analysis of Google reviews for leasing companies, apartment complexes, and student housing associated with various campus towns. The goal is to extract insights into customer satisfaction, highlight recurring sentiments, and identify key trends from the review data.

The analysis follows these steps:
- **Data Loading:** Importing raw CSV files of business listings and reviews from a GitHub repository.
- **Data Preprocessing:** Merging multiple datasets, selecting key columns, and converting datetime fields.
- **Data Visualization:** Creating interactive plots (box plots, histograms, pie charts, bar charts, sunburst charts, and treemaps) with Plotly and Seaborn to explore review ratings, likes, and sentiments.
- **Sentiment Analysis:** Analyzing tokens and sentiments extracted from review texts to understand what drives positive and negative feedback.
- **Conclusions:** Summarizing insights that can help property management companies and campus housing administrators enhance their services.

## Group Members

- **Yitao Luo (yitaol3)**
- **Jiayuan Zhang (jz116)**

## Data Sources

The data for this project was sourced from Outscraper and includes:
- Business and review data for:
  - Brigham Young University (Provo, UT)
  - Penn State University (University Park, PA)
  - University of Illinois at Urbana-Champaign (Champaign, IL)
- Additional token and sentiment files:
  - `tokens.csv.gz`
  - `sentiments.csv`

The CSV files are loaded directly from GitHub repositories during analysis.

## Project Structure

```
.
├── README.md                      # This file
├── case_study_06_ipynb.pdf        # PDF report of the case study
├── analysis_notebook.ipynb        # Jupyter Notebook with the complete analysis code (if applicable)
├── businesses.csv                 # Preprocessed business data
├── reviews.csv                    # Preprocessed reviews data
├── Processed.csv                  # Merged dataset of businesses and reviews
└── requirements.txt               # Python libraries required for this project
```

## Installation & Requirements

To run the analysis locally, you need Python and the following libraries:

- pandas
- numpy
- plotly
- matplotlib
- seaborn

You can install the required packages using pip:

```bash
pip install pandas numpy plotly matplotlib seaborn
```

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/clean-leasing-reviews.git
   cd clean-leasing-reviews
   ```

2. **Run the Notebook:**

   Open `analysis_notebook.ipynb` in Jupyter Notebook or JupyterLab to interactively run the code and explore the visualizations.

3. **Data Files:**

   The preprocessed CSV files (`businesses.csv`, `reviews.csv`, and `Processed.csv`) are generated as part of the analysis. These files can be reused for further exploration or additional analysis.

## Analysis Highlights

- **Data Preprocessing:** Combined business and review data across multiple campuses, selecting only the most useful columns and converting date strings to datetime objects.
- **Visualization:** Used interactive charts to display the distribution of review ratings, likes, and sentiment breakdowns.
- **Sentiment Analysis:** Identified frequently occurring tokens and their associated sentiments in the reviews to understand key drivers of customer satisfaction or dissatisfaction.
- **Insights:** Provided actionable insights that can help property management companies improve their services based on resident feedback.

## Conclusion

This project offers a comprehensive view of customer opinions in the leasing market across different campus towns. The visualizations and sentiment analysis provide a detailed look at both the positive aspects and the areas needing improvement, which can be useful for both property managers and academic institutions in enhancing living experiences.

## License

This project is licensed under the [MIT License](LICENSE).
