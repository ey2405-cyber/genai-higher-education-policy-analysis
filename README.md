# Mapping Generative AI Policy Across Higher Education

A comparative analysis of how Generative AI policies change across governance levels in New York City and Hong Kong.

## Overview

Generative AI policies are increasingly shaping how universities approach teaching, academic integrity, privacy, and technology use.

This project examines whether GenAI policy remains consistent as it moves from government guidance to institutional policies and ultimately to individual classrooms.

We analyzed 110 publicly available policy documents across five governance tiers in New York City and Hong Kong.

## Research Question

How do Generative AI policies manifest across five levels of governance in NYC and Hong Kong?

## Data

The dataset contains 110 publicly available documents from:

- National/Federal policy
- State/Territory policy
- University-level policy
- Faculty/Department policy
- Course-level policy

Each document was coded across six dimensions:

- Policy stance
- Disclosure requirements
- Decision-making discretion
- Policy focus
- Enforcement
- Coverage

## Methods

Analysis was conducted in Python and RStudio.

Methods included:

- Data cleaning and preprocessing
- Mann-Whitney U tests
- Kendall's Tau correlation
- Kruskal-Wallis tests
- Chi-square and Fisher's exact tests
- Cramér's V effect sizes
- Text preprocessing and lexical analysis
- Network analysis
- Community detection
- Data visualization

## Key Findings

### 1. Hong Kong policies were more permissive toward GenAI

Hong Kong documents had a median policy stance of 2 (Functional), compared with 1 (Cautious) for NYC.

### 2. Policies became more restrictive closer to the classroom

Governance tier was negatively associated with GenAI policy stance, suggesting that broad support for AI at higher levels does not always
translate into permissive classroom policies.

### 3. Regional differences were strongest at certain governance levels

The largest differences appeared at the city/territory and course levels.

## My Contributions

This project was completed collaboratively by Emy Yamamoto, Yan Mak, and Yingxuan Yan as part of a graduate Learning Analytics course at Teachers College, Columbia University.

My contributions included:

- Developed portions of the Python statistical analysis and the entire RStudio data visualizations
- Conducted data collection using AI-assisted search tools, coded policy documents, and validated the dataset for accuracy and consistency
- Created visualizations comparing policy stance across governance tiers
- Interpreted statistical findings and translated them into research conclusions
- Co-developed the analytical framework and final research report

## Tools

Python · pandas · scipy · matplotlib · network analysis · statistical testing

## Limitations

The analysis uses a purposive sample of publicly available documents and does not capture all internal or password-protected university policies.

Coding qualitative policy dimensions also involves interpretation, so inter-rater reliability is an important consideration.

## Repository Contents

`analysis/` — Python analysis and statistical modeling  
`figures/` — Selected visualizations  
`data/` — Data documentation and, where permitted, analytical dataset

## Authors

Emy Yamamoto  
Yan Mak  
Yingxuan Yan
