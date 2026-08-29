# Analysis

This folder contains the statistical analysis and visualization code developed for the Generative AI higher education policy project.

The project compares GenAI policies across higher education governance levels in New York City and Hong Kong using both Python and R.

## Files

### `python-statistical-analysis.ipynb`

Jupyter Notebook containing the primary Python-based statistical analysis.

The notebook includes:

- Data preparation and filtering
- Descriptive summaries of policy stance
- Comparisons between New York City and Hong Kong
- Analysis across governance tiers
- Mann–Whitney U tests
- Kendall's Tau correlations
- Kruskal–Wallis tests
- Chi-square and Fisher's exact tests
- Analysis of policy dimensions including stance, disclosure, discretion, focus, enforcement, and coverage

The notebook uses the coded policy dataset:

`GenAI_Policy_Comparative_LearningAnalytics_Reformatted.csv`

### `r-statistical-analysis.Rmd`

R Markdown file containing additional statistical analyses and summary tables used in the project.

### `policy-visualizations.Rmd`

R Markdown file used to create several of the project visualizations comparing policy characteristics across regions and governance levels.

### `stance-line-chart.Rmd`

R Markdown file used to create the visualization showing mean GenAI policy stance across governance tiers in New York City and Hong Kong.

## Data

The analysis is based on a coded dataset of 110 GenAI policy documents across five governance levels in New York City and Hong Kong.

The analytical variables include:

- Policy stance
- Disclosure requirements
- Decision-making discretion
- Primary policy focus
- Enforcement mechanisms
- Policy coverage

The dataset is stored separately in the [`data`](../data) folder.

## Collaboration

This analysis was developed as part of a collaborative graduate course project at Teachers College, Columbia University.

My primary contributions to the project included data collection using AI-assisted search tools, reviewing and verifying policy documents, coding policies using the project framework, and validating the dataset for accuracy and consistency.
