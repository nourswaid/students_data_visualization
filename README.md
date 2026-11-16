# Data Visualization – Coursework 2

## Overview

This project explores fundamental concepts in data visualization using Python. It focuses on understanding data types, selecting appropriate visual encodings, interpreting visualizations, and identifying misleading graphical representations.

The analysis uses a synthetic university dataset containing student-related information, including academic performance, attendance, enrollment dates, programs, and satisfaction levels.

## Objectives

- Identify and classify different data types and measurement scales.
- Create appropriate visualizations for categorical, quantitative, and temporal data.
- Analyze distributions and relationships between variables.
- Understand how visualization choices can influence data interpretation.
- Identify misleading charts and redesign them using appropriate scales.
- Compare different visualization techniques and their suitability for different audiences.

## Technologies and Libraries

- Python
- Pandas – Data manipulation and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Jupyter Notebook – Interactive analysis

## Project Tasks

### Task 1 – Data Types and Data Dictionary

Examined the dataset's variables and classified them according to:
- Storage data types
- Semantic variable types
- Measurement scales
- Permissible operations

Also discussed why identifiers such as `Student_ID` should not be treated as quantitative measurements and why ordinal variables require preserving their natural order.

### Task 2 – Data Visualization

Created and interpreted several visualizations:

| Visualization | Purpose |
|---|---|
| Horizontal Bar Chart | Compare student counts across programs |
| Histogram | Examine GPA distribution |
| Scatterplot | Explore the relationship between attendance and GPA |
| Bar Chart | Visualize student satisfaction levels |
| Line Chart | Examine monthly enrollment patterns |

### Task 3 – Design Critique and Redesign

Investigated how truncated axes can misrepresent differences in bar charts.

Created a comparison between a misleading chart with a truncated y-axis and a redesigned chart using a zero-based scale.

Discussed visual channels, scale selection, and perceptual accuracy.

### Task 4 – Interpretation and Evaluation

Answered questions about:
- The usefulness of categorical charts.
- Information revealed by histograms compared with averages.
- The difference between correlation and causation.
- The interpretation of visual patterns.

### Bonus – Alternative Visualization

Created a box plot as an alternative representation of GPA distribution and compared it with the histogram in terms of readability, statistical information, and audience suitability.


## How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Make sure the CSV dataset is in the same directory as the notebook.
4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Data_Visualization_Lecture_2.ipynb` and run the cells.

## Key Learning Outcomes

Through this coursework, I practiced selecting suitable visualization techniques based on variable types, interpreting graphical representations, and evaluating how design decisions affect the accuracy and clarity of data communication.
