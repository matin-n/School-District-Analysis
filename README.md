# School District Analysis

## Project Overview
### Purpose
The school board has notified Maria and her supervisor that the  `students_complete.csv` contains evidence of academic dishonesty within the reading and math grades for Thomas High School ninth graders. The evidence suggests that the graders appear to have been altered. The school board needs to uphold state-testing standards even though the extent of the academic dishonesty is unknown. Therefore, the math and reading scores for the 9th graders of Thomas High School will be voided and replaced with `NaN` while keeping the rest of the other data intact. As a result of the academic dishonesty findings, a new analysis will be conducted.

## Results

### School Summary
From the original to the new analysis, a significant decrease can be seen in the `% Passing Math`, `% Passing Reading`, and `% Overall Passing`. Also, a slight decline in the `Average Math Score` and `Average Reading Score`:

- Original
  - Average Math Score: 83.418349
  - Average Reading Score: 83.848930
  - % Passing Math: 93.272171%
  - % Passing Reading: 97.308869%
  - % Overall Passing: 90.948012%
- New
  - Average Math Score: 83.350937
  - Average Reading Score: 83.896082
  - % Passing Math: 66.911315%
  - % Passing Reading: 69.663609%
  - % Overall Passing: 65.076453%


#### Original
![School Summary Original](https://github.com/matin-n/School_District_Analysis/blob/main/Resources/School%20Summary%20Original.png?raw=true)

#### New
![School Summary New](https://github.com/matin-n/School_District_Analysis/blob/main/Resources/School%20Summary%20New.png?raw=true)


### District summary

From the original to the new analysis, a slight decrease can be seen in the `Average Math Score`, `% Passing Math`, `% Passing Reading`, and `% Overall Passing`:

- Original  
  - Average Math Score: 79
  - % Passing Math: 75%
  - % Passing Reading: 86%
  - % Overall Passing: 65%
- New
  - Average Math Score: 78.9
  - % Passing Math: 74.8%
  - % Passing Reading: 85.7%
  - % Overall Passing: 64.9%

#### Original

![District Summary Original](https://github.com/matin-n/School_District_Analysis/blob/main/Resources/District%20Summary%20Original.png?raw=true)

#### New
![District Summary New](https://github.com/matin-n/School_District_Analysis/blob/main/Resources/District%20Summary%20New.png?raw=true)

### Scores by School Spending

From the original to the new analysis, there were no significant changes. A minuscule decrease of a few decimal point changes could be seen in the `$630-644`  spending range (per student), but its nothing major:

- Original
  - $630-644 Spending Range (per student)
    - Average Math Score: 78.518855
    - Average Reading Score: 81.624473
    - % Passing Math: 73.484209%
    - % Passing Reading: 84.391793%
    - % Overall Passing: 62.857656%
- New
  - $630-644 Spending Range (per student)
    - Average Math Score: 78.502002%
    - Average Reading Score: 81.636261%
    - % Passing Math: 73.462589%
    - % Passing Reading: 84.319261%
    - % Overall Passing: 62.778233%

#### Original
![Scores by School Spending Original](https://github.com/matin-n/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Spending%20Original.png?raw=true)
#### New
![Scores by School Spending New](https://github.com/matin-n/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Spending%20New.png?raw=true)


### Scores by School Size

From the original to the new analysis, there were no significant changes. A minuscule decrease of a few decimal point changes could be seen in the `Medium (1000-2000)` school sizes, but its nothing major:

- Original
  - Medium School Size
    - Average Math Score: 83.374684
    - Average Reading Score: 83.864438
    - % Passing Math: 93.599695%
    - % Passing Reading: 96.790680%
    - % Overall Passing: 90.621535%
- New
  - Medium School Size
    - Average Math Score: 83.361201
    - Average Reading Score: 83.873869
    - % Passing Math: 93.582398%
    - % Passing Reading: 96.732654%
    - % Overall Passing: 90.557997%

#### Original
![Scores by School Size Original](https://github.com/matin-n/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Size%20Original.png?raw=true)
#### New
![Scores by School Size New](https://github.com/matin-n/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Size%20New.png?raw=true)


## Summary
- School Summary
  - Significant decrease can be seen in the `% Passing Math`, `% Passing Reading`, and `% Overall Passing`.
  - Slight decrease in the `Average Math Score` and `Average Reading Score`
- District Summary
  - Slight decrease in the `Average Math Score`, `% Passing Math`, `% Passing Reading`, and `% Overall Passing`
- Scores by School Spending
  - Minuscule decrease in the `$630-644` spending range (per student)
  - No significant changes
- Scores by School Size
  - Minuscule decrease in the `Medium (1000-2000)` school sizes
  - No significant changes


## Resources
- Data Source: `schools_complete.csv`, `students_complete.csv`
- Source Code: `PyCitySchools.ipynb`, `PyCitySchools_Challenge.ipynb`
- Software: `Python 3.7.10`, `Jupyter Notebook 6.3.0`
- Libraries: `NumPy 1.21.4`, `Pandas 1.3.4`
