# Bivariate Analysis with Titanic Dataset

**Author:** Aya Tamura  
**Date:** August 25, 2024

## Project Overview

This project focuses on analyzing the relationships between pairs of variables in the Titanic dataset. The aim is to practice bivariate analysis techniques, considering the data types involved (categorical, ordinal, and continuous). The notebook demonstrates different methods for visualizing and testing associations between these variables, providing a comprehensive overview of bivariate analysis in Python.

## Dataset

The dataset used is the well-known Titanic dataset, which includes information about passengers on the RMS Titanic. Key variables include:

- `Survived`: Whether the passenger survived or not (0 = No, 1 = Yes)
- `Sex`: The gender of the passenger
- `Fare`: The ticket fare paid by the passenger
- `Parch`: The number of parents or children aboard

The dataset is publicly available and can be found [here](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv).

## Analysis Sections

The analysis in the notebook is divided into the following questions:

### 1. **Is There a Relationship Between Passenger Survival and Sex?**
   - **Data Type**: Categorical vs. Categorical
   - **Methods Used**: Bar plots, Chi-Square test
   - **Key Insight**: A significant association between sex and survival was found, with women having a higher survival rate.

### 2. **Is There a Relationship Between Passenger Survival and Ticket Fare?**
   - **Data Type**: Categorical vs. Continuous
   - **Methods Used**: Box plots, Violin plots, Mann-Whitney U test
   - **Key Insight**: Passengers who survived generally paid higher fares, with the difference being statistically significant.

### 3. **Is There a Relationship Between Passenger Survival and the Number of Parents/Children?**
   - **Data Type**: Categorical vs. Ordinal (or Continuous)
   - **Methods Used**: Count plots, Box plots, Kruskal-Wallis test
   - **Key Insight**: Survival rates varied significantly depending on the number of parents/children aboard, with `Parch` treated as an ordinal variable.

### 4. **Potential Analysis of Continuous vs. Continuous Variables** *(Not Included in This Notebook)*
   - **Explanation**: While this dataset did not provide opportunities to explore continuous vs. continuous relationships, the README explains the methods that would be used if such data were available, including scatter plots, correlation analysis, and linear regression.

## Tools and Libraries Used

- **Python**
- **Pandas**: For data manipulation and analysis
- **Matplotlib** and **Seaborn**: For data visualization
- **Scipy**: For statistical testing

## How to Run the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-bivariate-analysis.git
   ```
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the `titanic_bivariate_analysis.ipynb` file.

## Conclusion

This project demonstrates how to approach bivariate analysis for different combinations of categorical, ordinal, and continuous variables. The Titanic dataset serves as a versatile example for practicing key concepts in data analysis, visualization, and hypothesis testing.

## Future Work

Potential future improvements include:
- Exploring additional variables, such as `Age` or `Embarked`.
- Conducting continuous vs. continuous analysis when applicable datasets are available.
- Extending the analysis to multivariate relationships.

## Acknowledgments

This analysis is based on the Titanic dataset, which is publicly available and widely used for data science practice. Special thanks to [Kaggle](https://www.kaggle.com/c/titanic) and other open-source communities for providing the data and resources.
