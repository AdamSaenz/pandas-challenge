# PyCitySchools | School Performance Analysis

**Author:** Adam A. Saenz  
**Technologies:** Python, Pandas, Jupyter Notebook  
**Project Type:** Educational Data Analysis

## Project Overview

This project examines student academic performance across 15 schools using Python and Pandas. The analysis evaluates districtwide performance, school budgets, student achievement, and differences in outcomes across school types, sizes, and spending categories.

The objective is to transform student and school level data into meaningful performance indicators that can support educational planning and resource allocation discussions.

## Dataset

The analysis uses two CSV files:

- `schools_complete.csv`: School characteristics, enrollment, budgets, and school types.
- `students_complete.csv`: Student records, grade levels, and mathematics and reading scores.

The datasets contain information for **39,170 students across 15 schools**, representing a combined school budget of **$24,649,428**.

## Analytical Methods

The project uses Pandas to merge datasets, calculate summary statistics, group observations, and compare school performance.

The analysis includes:

1. Districtwide academic performance and budget summaries.
2. Individual school performance metrics.
3. Rankings of the five highest and lowest performing schools.
4. Mathematics and reading scores by grade level.
5. Performance comparisons by per student spending.
6. Performance comparisons by school enrollment size.
7. Performance comparisons between charter and district schools.

Students are classified as passing a subject when their score is at least 70. Overall passing requires meeting that threshold in both mathematics and reading.

## Key Findings

### District Performance

| Metric | Result |
|---|---:|
| Total Schools | 15 |
| Total Students | 39,170 |
| Total Budget | $24,649,428 |
| Average Mathematics Score | 78.99 |
| Average Reading Score | 81.88 |
| Mathematics Passing Rate | 74.98% |
| Reading Passing Rate | 85.81% |
| Overall Passing Rate | 65.17% |

### School Performance

Cabrera High School recorded the highest overall passing rate at approximately **91.33%**, while Rodriguez High School recorded the lowest at approximately **52.99%**.

### School Type

The dataset shows a substantial difference in average overall passing rates:

- **Charter schools:** 90.43%
- **District schools:** 53.67%

These results describe associations within the analyzed dataset. They do not establish that school type independently causes differences in student achievement.

### School Size and Spending

The notebook also compares performance across school enrollment categories and per student spending ranges.

These comparisons help identify patterns worth further investigation. Additional statistical analysis would be necessary to determine whether differences reflect school size, funding, student characteristics, or other factors.

## Repository Structure

```text
pandas-challenge/
├── README.md
├── Module 4 Pandas Challenge Report.docx
└── PyCitySchools/
    ├── PyCitySchools_starter_Pandas.ipynb
    └── Resources/
        ├── schools_complete.csv
        └── students_complete.csv
```

## How to Run the Analysis

1. Install Python and Jupyter Notebook.
2. Install the Pandas library.
3. Download or clone this repository.
4. Open the `PyCitySchools` folder.
5. Launch `PyCitySchools_starter_Pandas.ipynb` in Jupyter.
6. Run the notebook cells in sequence.

The notebook uses relative paths to load the two CSV files from the `Resources` directory.

## Limitations

The findings are descriptive and reflect the supplied educational dataset. Differences between schools should not be interpreted as causal relationships.

The analysis does not control for student demographics, socioeconomic conditions, prior academic achievement, or other factors that could influence performance.

## Skills Demonstrated

- Data preparation and dataset integration
- DataFrame manipulation with Pandas
- Grouping and aggregation
- Descriptive statistical analysis
- Educational performance measurement
- Comparative analysis
- Analytical reporting

## Project Files

**[View the Jupyter Notebook](PyCitySchools/PyCitySchools_starter_Pandas.ipynb)**

**[View the Project Report](Module%204%20Pandas%20Challenge%20Report.docx)**

## Author

Adam A. Saenz

Data analytics and applied data science portfolio project.
