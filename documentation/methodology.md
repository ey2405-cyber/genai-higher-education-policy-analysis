# Methodology

## Overview

This project used a comparative, multi-level policy landscape analysis to examine how Generative AI (GenAI) policies are communicated across higher education systems in New York City and Hong Kong.

Rather than examining only university-wide policies, the analysis considered policy documents across multiple levels of governance, from national or federal guidance to individual course syllabi.

The final dataset contains **110 publicly available GenAI policy documents**, with **55 documents from New York City and 55 from Hong Kong**.

## Governance Framework

Documents were organized across five levels of governance.

| Tier | Governance Level | Description |
|---|---|---|
| 1 | National/Federal | Policies issued by a central government or national ministry |
| 2 | State/Territory | Policies issued by a regional, state, or territory regulatory body |
| 3 | Institutional | Policies issued by the central university administration |
| 4 | Faculty/Department | Policies issued by a specific faculty, school, or department |
| 5 | Course-wide | Policies or statements issued by an instructor for a specific course |

Tiers 1–2 represent **external governance**, while Tiers 3–5 represent **internal university governance**.

This structure was designed to examine how broad GenAI policy guidance is translated into policies and rules closer to the classroom.

## Institutional Sample

The study examined three higher education institutions in each region:

### New York City
- Columbia University
- New York University (NYU)
- City University of New York (CUNY)

### Hong Kong
- University of Hong Kong (HKU)
- Hong Kong Polytechnic University (PolyU)
- Lingnan University

The institutions represented different governance structures while also providing publicly accessible materials related to AI governance, academic integrity, and teaching guidance.

## Document Collection

For external governance levels (Tiers 1–2), the project conducted a broad search of publicly available government and regulatory documents.

For internal governance levels (Tiers 3–5), quota-based purposive sampling was used. Five documents were collected per tier for each institution.

The resulting sample contained:

| Governance Tier | NYC | Hong Kong | Total |
|---|---:|---:|---:|
| National/Federal | 5 | 5 | 10 |
| State/Territory | 5 | 5 | 10 |
| Institutional | 15 | 15 | 30 |
| Faculty/Department | 15 | 15 | 30 |
| Course-wide | 15 | 15 | 30 |
| **Total** | **55** | **55** | **110** |

Documents included materials such as official guidance, executive orders, laws and regulations, university policies, FAQ/resource pages, and course syllabi.

## AI-Assisted Search Process

Google AI/Gemini was used as a search aid to identify potentially relevant documents.

AI-generated search results were **not treated as source material or automatically included in the dataset**. Each potential document was:

1. Retrieved from its original source
2. Manually reviewed
3. Evaluated against the project's inclusion and exclusion criteria
4. Verified through an official public URL

Searches were conducted iteratively by region, institution, governance tier, and document type until the target sample was reached.

## Inclusion Criteria

Documents were included when they satisfied all of the following conditions:

- **Authorized directive:** Issued by an official government, university, faculty, department, instructor, or other authorized institutional body
- **Explicit GenAI content:** Specifically referenced Generative AI, large language models, ChatGPT, or AI-related academic integrity guidance in higher education
- **Verifiable source:** Available through an official public website or document repository

## Exclusion Criteria

Documents were excluded when they were:

- Secondary news articles or blog posts without an accessible original policy source
- Password-protected, intranet-only, or otherwise inaccessible to the public
- General technology or plagiarism policies that did not explicitly address AI
- Lists of AI tools without substantive governing or pedagogical guidance

## Coding Procedure

Each document was coded across six policy dimensions:

- Stance
- Disclosure
- Discretion
- Primary Focus
- Enforcement
- Coverage

The complete definitions and category options are documented in [`coding-framework.md`](coding-framework.md).

The coding framework was developed deductively, drawing on prior work on university GenAI policies and extending it to support comparisons across multiple levels of governance.

## Quantitative Transformation

Policy **Stance** served as the primary ordinal outcome variable and was transformed into a numeric scale:

- 0 = Prohibitive
- 1 = Cautious
- 2 = Functional
- 3 = Encouraging

Governance tier was also represented numerically from:

- 1 = National/Federal
- 2 = State/Territory
- 3 = Institutional
- 4 = Faculty/Department
- 5 = Course-wide

The remaining coding dimensions were treated as nominal categorical variables.

## Statistical Analysis

The statistical analysis used Python and R.

Because Stance is ordinal, non-parametric methods were used as the primary inferential approach for stance comparisons.

Analyses included:

- **Mann–Whitney U tests** for regional differences in policy stance
- **Kendall's Tau** for the relationship between governance tier and stance
- **Kruskal–Wallis tests** for differences across institutions
- **Chi-square tests** for associations involving categorical policy dimensions
- **Fisher's exact tests** when contingency-table cell counts were small
- **Cramér's V** to quantify the strength of categorical associations

Additional analyses and visualizations were used to examine variation across regions, governance tiers, and institutions.

## Limitations

Several limitations should be considered when interpreting the analysis.

First, the institutional sample includes three institutions per region and therefore does not represent every higher education institution in New York City or Hong Kong.

Second, the dataset includes only **publicly accessible policy documents**. Internal policies distributed through learning management systems, intranets, or other restricted platforms could not be included.

Third, the faculty/department and course-level samples are structured samples rather than exhaustive collections of every available document.

Finally, qualitative coding requires researcher interpretation. Categories such as Stance, Discretion, and Primary Focus may involve judgment, particularly when comparing policies across different institutional and regional contexts.
