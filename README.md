# statistics-R
Various datasets - data manipulation, visualization, hypothesis testing, and modeling

# RStudio Project: Rodents, Medical Students Smoking Habits, and University Salaries

## Introduction
This RStudio project analyzes three different datasets related to rodents sightings in North America, smoking habits among medical students in Germany and Hungary, and yearly salaries of academic workers at a U.S. university.

## Dataset Description
1. **North America Rodents**:
   - Dataset: data/surveys.csv - Rodents sightings in North America from 1977 to 2002.
   - Dataset: data/species.csv - Species acronyms and their Genus.

2. **Medical Students Smoking Habits**:
   - A study conducted on various Medical Universities within Germany and Hungary.
   - Dataset: smoking - Number of students per nationality declaring daily smoking habit.

3. **University Salaries**:
   - Yearly salaries of random 52 academic workers at one of the U.S. Universities.
   - Dataset: data/salaries.csv - Contains information about the academic workers' salaries.

## Project Overview
The project consists of three main parts:

## 1. North America Rodents Analysis:
   - Joining the two datasets to create a new dataset named "rodents."
   - Presenting the top 5 rodent species with the highest mean weight and mean hindfoot length in a table.
   - Creating a scatter plot for the genus "Dipodomys" to show the relationship between weight and hindfoot length.

## 2. Medical Students Smoking Habits Analysis:
   - Conducting a Chi-squared test to check if the proportions of nationalities within smoking students are representative of the whole student body.

## 3. University Salaries Analysis:
   - Creating a linear model to predict salaries at the university using the provided dataset.

## How to Run the Project
1. Clone the project repository to your local machine.
2. Ensure that you have R and RStudio installed.
3. Open the RStudio project file (.Rproj).
4. Install the required R packages mentioned in the code files, if not already installed.
5. Run the code files in the following order: `1-rodents_analysis.R`, `2-smoking_habits_analysis.R`, `3-university_salaries_analysis.R`.
6. Review the results and visualizations generated by the scripts.

## Requirements
- R (version XYZ or higher)
- RStudio (version XYZ or higher)
- Required R packages (listed in the code files)

## License
This project is licensed under the [MIT License](LICENSE).

## Author
Andrei Nistor

## Contact
For any questions or inquiries, please contact Andrei Nistor at [email@example.com](mailto:email@example.com).

---
