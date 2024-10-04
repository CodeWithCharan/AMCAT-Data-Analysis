# AMCAT Data Analysis

## Objectives
The goal of this project is to conduct a comprehensive exploratory data analysis (EDA) that includes both univariate and bivariate analyses. This analysis aims to:
- Understand the distribution of individual variables (univariate analysis).
- Identify outliers within the dataset.
- Explore relationships between different variables (bivariate analysis) to uncover insights related to salary expectations.

## Dataset Description
The dataset consists of information about individuals, their educational background, job details, and personality traits. It contains 38 columns and 3998 data points. They are independent variables, both continuous and categorical in nature.

| Column     | Description              |
|------------|--------------------------|
| `'ID'` | Unique ID to identify a candidate|
| `'Salary'` | Annual CTC oﬀered to the candidate (in Indian Rupees) |
| `'DOJ'` | Date of joining the company |
| `'DOL'` | Date of leaving the company |
| `'Designation'` | Designation oﬀered in the job |
| `'JobCity'` | Location of the job (city) |
| `'Gender'` | Candidate’s gender |
| `'DOB'` | Date of birth of candidate |
| `'10percentage'` | Overall marks obtained in grade 10 examinations|
| `'10board'` | The school board whose curriculum the candidate followed in grade 10 |
| `'12graduation'` | Year of graduation - senior year high school |
| `'12percentage'` | Overall marks obtained in grade 12 examinations|   
| `'12board'` | The school board whose curriculum the candidate followed in grade 12 |
| `'CollegeID'` | Unique ID identifying the college which the candidate attended |
| `'CollegeTier'` | Tier of college |
| `'Degree'` | Degree obtained/pursued by the candidate |
| `'Specialization'` | Specialization pursued by the candidate |
| `'CollegeGPA'` | Aggregate GPA at graduation |
| `'CollegeCityID'` | A unique ID to identify the city in which the college is located in |
| `'CollegeCityTier'` | The tier of the city in which the college is located |
| `'CollegeState'` | Name of States |
| `'GraduationYear'` | Year of graduation (Bachelor’s degree) |
| `'English'` | Scores in AMCAT English section |
| `'Logical'` | Scores in AMCAT Logical section |
| `'Quant'` | Scores in AMCAT Quantitative section |
| `'Domain'` | Scores in AMCAT’s domain module |
| `'ComputerProgramming'` | Score in AMCAT’s Computer programming section|
| `'ElectronicsAndSemicon'` | Score in AMCAT’s Electronics & Semiconductor Engineering section |
| `'ComputerScience'` | Score in AMCAT’s Computer Science section |
| `'MechanicalEngg'` | Score in AMCAT’s Mechanical Engineering section|
| `'ElectricalEngg'` | Score in AMCAT’s Electrical Engineering section |
| `'TelecomEngg'` | Score in AMCAT’s Telecommunication Engineering section |
| `'CivilEngg'` | Score in AMCAT’s Civil Engineering section |
| `'conscientiousness'` | Scores in one of the sections of AMCAT’s personality test |
| `'agreeableness'` | Scores in one of the sections of AMCAT’s personality test|
| `'extraversion'` |Scores in one of the sections of AMCAT’s personality test |
| `'neuroticism'` | Scores in one of the sections of AMCAT’s personality test |
| `'openess_to_experience'` | Scores in one of the sections of AMCAT’s personality test |

## Methodology
1. **Data Understanding**
2. **Data Cleaning**
3. **EDA - Univariate Analysis (Non Visualization)**
4. **EDA - Univariate Analysis (Visualization)**
5. **EDA - Bivariate Analysis (Non Visualization)**
6. **EDA - Bivariate Analysis (Visualization)**
7. **Research Questions**:
    - Is there a relationship between gender and specialization?
    - Which specialization earns more?
8. **Conclusion**

## Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

## Installation
To run this project, ensure you have the required libraries installed. You can do this by running:

```bash
pip install pandas numpy matplotlib seaborn
```

## Thank you
If you enjoyed this notebook, please consider sharing it.

Author: `Sri Charan Thoutam`

- 👉Shoot me mails : thoutamsricharan@gmail.com
- 👉Connect on LinkedIn: [linkedin.com/in/codewithcharan](https://www.linkedin.com/in/codewithcharan/)
- 👉Explore my Portfolio: [codewithcharan.github.io/My-Portfolio](https://www.codewithcharan.github.io/My-Portfolio)
- 👉Explore my GitHub: [github.com/CodeWithCharan](https://www.github.com/CodeWithCharan)