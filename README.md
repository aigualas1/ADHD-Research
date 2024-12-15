Independent Research
======

## Research Question

* What are the prevalence rates of ADHD in children by age and ethnicity, and how does treatment vary across these groups? 
* Can culturally modified treatments improve outcomes, and if so, how?

## Objective

This milestone focused on leveraging Python to analyze and visualize data for a specific research question. The deliverable was a Jupyter Notebook demonstrating:

* Data retrieval and cleaning
* Data analysis
* Data visualization

The goal was to demonstrate proficiency in Python and conduct independent, insightful research.

## Research Topic: ADHD Prevalence and Treatment

ADHD affects 6–9% of children worldwide, with variations in prevalence and treatment by age, gender, and ethnicity. This study examined these differences and the effectiveness of culturally tailored treatments.


## Data Retrieval and Preparation
A ```403 Forbidden``` error was encountered when attempting to retrieve the dataset:

```python
url = "https://www.tandfonline.com/action/downloadTable?id=t0003&doi=10.1080%2F15374416.2024.2335625&downloadType=CSV"
response = requests.get(url)
response
```
The CSV file was downloaded manually and cleaned for analysis by addressing missing values and standardizing formats.


## Analysis and Visualization

Using Python libraries such as ```pandas``` and ```matplotlib```, data trends and disparities were explored through:

* <b>Bar chart:</b> Visualized ADHD prevalence across race, ethnic groups, ADHD severity levels, and treatment types.
* <b>Scatter plot:</b> Analyzed the relationship between standard and culturally modified treatments in relation to stress and symptom severity.

The visualizations provided clear evidence to support the findings.

## Deliverable

A Jupyter Notebook was created, showcasing:

* Data retrieval and cleaning steps
* Analytical insights
* Visualizations (bar chart and scatter plot)
* Interpretations aligned with the research objectives

This notebook demonstrates proficiency in Python for data analysis and offers insights into ADHD prevalence and treatment disparities.

[View Jupyter Notebook](main.ipynb)

## Key Insights

* <b> ADHD Prevalence: </b>
    - Lower among Hispanic children but higher severity cases compared to Non-Hispanic children.
* <b>Treatment Disparities:</b>
    - Hispanic children are less likely to receive either medication or behavioral treatment (37.3%) compared to Non-Hispanic children (28.2%).
* <b>Culturally Modified Treatment: </b>
    - Showed significant benefits, including:
        - Improved engagement in treatment
        - Greater acceptability of treatment
        - Reduction in ADHD symptoms
        - Decrease in maternal parenting stress

These findings highlight the need for culturally tailored interventions and address disparities in treatment access.