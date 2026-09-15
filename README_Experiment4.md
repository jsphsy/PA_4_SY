# DATA WRANGLING AND DATA VISUALIZATION: EXPERIMENT #4

This repository contains a solution to the Python programming exercises for **Experiment 4: Data Wrangling and Data Visualization** in **ECE 2112: Advanced Computer Programming and Algorithms**.

## EXERCISES:

### A. VISAYAS COMMUNICATION DATAFRAME

**Task:** Use the **ECE Board Exam 2** dataset to create a DataFrame named `VisComm` containing students whose **Hometown** is `Visayas` and whose **Track** is `Communication`.

Retain only the following columns, in this order:

**Name, Gender, Math, Electronics, Average**

**Required checks:**
- Both filtering conditions are applied to the source dataset.
- The resulting DataFrame is stored in `VisComm`.
- The resulting DataFrame and its number of rows are displayed.
- The original dataset is not modified.

### B. VISAYAS FEMALE DATAFRAME

**Task:** Create a second DataFrame named `VisFemale` containing students whose **Hometown** is `Visayas` and whose **Gender** is `Female`.

Retain only the following columns:

**Name, Track, GEAS, Electronics, Average**

Then display only the rows of `VisFemale` whose **Average is at least 60**. The second filtering operation must not overwrite `VisFemale`.

**Required checks:**
- `VisFemale` is created using the specified filtering conditions.
- The requested columns are retained in the required order.
- The filtered rows with `Average >= 60` are displayed separately.
- The original dataset and `VisFemale` are preserved.

### C. CATEGORY-AVERAGE VISUALIZATION

**Task:** Examine how the recorded **Average** differs across the three categorical features:

- **Track**
- **Gender**
- **Hometown**

For each feature, compute the **mean of Average for every category** using Pandas.

Then:

1. Display the three category-mean summary tables.
2. Create one figure containing three bar charts:
   - Mean Average by Track
   - Mean Average by Gender
   - Mean Average by Hometown
3. Write three concise statements identifying the category with the highest sample mean for each feature.

**Required checks:**
- All summary values are derived directly from the dataset.
- Every graph has a title, axis labels, readable category labels, and an appropriate consistent scale.
- The interpretations describe the observed dataset only.
- Differences in group means are not interpreted as proof that a feature causes higher board-exam scores.

## IMPLEMENTATION:

The solutions are implemented in a **Jupyter Notebook (`.ipynb`)** containing:

1. Importing Pandas and the Python plotting library used in class;
2. Loading the ECE Board Exam 2 dataset from `board2.xlsx`;
3. Applying multiple categorical and numerical Boolean conditions to filter records;
4. Creating focused DataFrames containing only the required features;
5. Computing category-wise means of `Average` using Pandas;
6. Creating a figure with three bar charts for the category comparisons;
7. Displaying all required outputs and interpretation statements.

## LEARNING OUTCOMES:

Through this experiment, you will:

- Filter tabular data using several categorical and numerical conditions;
- Construct focused DataFrames by selecting relevant features;
- Summarize the relationship between categorical features and a numerical variable;
- Communicate a data comparison using clear and correctly labeled plots.

## FILES:

- `ECE2112_PA4.pdf` — Experiment 4 instructions and programming problems.
- `board2.xlsx` — ECE Board Exam 2 dataset used for the analysis.
