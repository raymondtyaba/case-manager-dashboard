# Case Manager Healthcare Analytics Dashboard

A healthcare data analytics portfolio project demonstrating how raw case-management data can be prepared, analysed, visualised, and translated into practical insights for healthcare practitioners and operational teams.

This repository brings together exploratory data analysis, missing-value handling, Pearson correlation analysis, practitioner-ready visualisation, and an interactive dashboard.

## Project Overview

Healthcare case-management teams often work with complex data containing missing values, inconsistent records, and relationships that are difficult to identify manually.

This project demonstrates an end-to-end analytical workflow for:

- Exploring and describing healthcare case-management data
- Identifying and handling missing values
- Preparing data for reliable analysis
- Measuring relationships between numerical variables
- Creating practitioner-friendly charts
- Presenting findings through an interactive dashboard
- Exploring a Retrieval-Augmented Generation workflow for healthcare information

## Key Features

- **Exploratory Data Analysis:** Reviews distributions, variable types, summary statistics, and potential data-quality issues.
- **Data Preparation:** Identifies and handles missing values before analysis.
- **Correlation Analysis:** Uses Pearson correlation to assess linear relationships between numerical variables.
- **Healthcare Visualisation:** Converts analytical results into clear charts for practitioner interpretation.
- **Interactive Dashboard:** Provides a browser-based view of the project findings.
- **RAG Exploration:** Includes a notebook exploring Retrieval-Augmented Generation as part of the wider healthcare analytics workflow.

## Repository Contents

| File | Purpose |
|---|---|
| `index.html` | Interactive case-manager dashboard |
| `project2_eda_describe_data.ipynb` | Exploratory data analysis and descriptive statistics |
| `project2_handle_missing_values.ipynb` | Identification and treatment of missing data |
| `project2_submit_prepared_data.ipynb` | Preparation and submission of the cleaned dataset |
| `Pearson_Correlation_sentence_generator.ipynb` | Pearson correlation analysis and interpretation |
| `build_practitioner_ready_chart.ipynb` | Creation of a practitioner-friendly visualisation |
| `Full_RAG_Studio_Capstone.ipynb` | Retrieval-Augmented Generation capstone workflow |

## Analytical Workflow

1. **Understand the data**  
   Inspect the structure, columns, data types, distributions, and descriptive statistics.

2. **Assess data quality**  
   Identify missing values and evaluate how incomplete records could affect the analysis.

3. **Prepare the dataset**  
   Apply appropriate cleaning and preparation methods to produce an analysis-ready dataset.

4. **Explore relationships**  
   Use Pearson correlation to measure the direction and strength of linear relationships between numerical variables.

5. **Communicate findings**  
   Build clear visualisations and concise interpretations suitable for healthcare practitioners and non-technical stakeholders.

6. **Present the results**  
   Combine the outputs in an accessible interactive dashboard.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Google Colab
- HTML
- GitHub Pages
- Retrieval-Augmented Generation

## Skills Demonstrated

- Healthcare data analytics
- Exploratory data analysis
- Data cleaning and preprocessing
- Missing-value assessment
- Descriptive statistics
- Pearson correlation analysis
- Data visualisation
- Dashboard development
- Analytical interpretation
- Technical documentation
- Communication of findings to non-technical audiences

## Running the Notebooks

The notebooks can be opened in either **Google Colab** or **Jupyter Notebook**.

### Google Colab

1. Open the required `.ipynb` file from this repository.
2. Select **Open in Colab**.
3. Upload the required dataset if prompted.
4. Run the notebook cells in order from top to bottom.

### Local Jupyter Environment

Clone the repository:

```bash
git clone https://github.com/raymontyaba/case-manager-dashboard.git
cd case-manager-dashboard
