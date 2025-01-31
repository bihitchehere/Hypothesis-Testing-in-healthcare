
# # Hypothesis-Testing-in-healthcare :  Drug Safety Analysis 🧪

This project applies statistical analysis and visualization techniques to a dataset of drug safety, aiming to explore and compare adverse effects between two treatment groups (`Drug` and `Placebo`). By leveraging hypothesis testing and data visualization, this analysis provides insights into the safety and effectiveness of the drug treatment.

## Project Description 📊

In this project, we analyze a dataset containing drug safety data to answer important questions:

- **Are the adverse effects significantly different between the `Drug` and `Placebo` groups?**
- **Is there any significant difference in the age distribution between the `Drug` and `Placebo` groups?**
- **Are the number of adverse effects independent of the treatment group?**

We apply several statistical tests such as Z-test, Chi-squared test, and Mann-Whitney U test, followed by detailed visualizations to compare the results.

## Data Description 📅

The dataset `drug_safety.csv` contains the following columns:

- **trx**: The treatment group (`Drug` or `Placebo`).
- **adverse_effects**: Whether adverse effects were reported for a given subject (`Yes` or `No`).
- **num_effects**: The number of adverse effects observed.
- **age**: The age of the participants in the study.

## Tools Used 🛠️

- **Python**: Programming language for data analysis.
- **pandas**: Data manipulation and analysis library.
- **numpy**: Numerical computing library.
- **pingouin**: Statistical analysis library.
- **seaborn**: Data visualization library for statistical graphics.
- **matplotlib**: Plotting library for static, animated, and interactive visualizations.
- **statsmodels**: For statistical modeling and hypothesis testing.

## Steps & Analysis 📝

1. **Data Preprocessing**: The dataset is loaded and prepared for analysis.
2. **Adverse Effects Count**: The number of adverse effects for each treatment group is counted.
3. **Proportional Z-test**: A two-sample Z-test is performed to compare the proportion of adverse effects between the `Drug` and `Placebo` groups.
4. **Chi-squared Test**: A chi-squared independence test is conducted to determine if the number of adverse effects is independent of the treatment group.
5. **Age Distribution**: A histogram is created to visualize the distribution of ages for both treatment groups.
6. **Normality Test**: The normality of the `age` variable is tested using Shapiro-Wilk's test.
7. **Mann-Whitney U Test**: A non-parametric Mann-Whitney U test is conducted to compare the age distributions of the `Drug` and `Placebo` groups.
8. **Visualizations**: Various plots are created, including:
   - A histogram of the age distribution by treatment group.
   - A bar plot of the number of adverse effects by treatment group.

## Example Results 📈

- **Z-Test for Proportions**: The p-value from the Z-test will help us assess if there's a significant difference in the proportion of adverse effects between the `Drug` and `Placebo` groups.
- **Chi-Squared Test**: The p-value from the Chi-squared test will help determine if the number of adverse effects is independent of the treatment group.
- **Mann-Whitney U Test**: The p-value from the Mann-Whitney U test will tell us whether the age distributions between the two treatment groups are significantly different.

## Visualizations 📊

- **Age Distribution**: A stacked histogram displays the distribution of ages for each treatment group (`Drug` and `Placebo`).
- **Adverse Effects Comparison**: A bar plot visualizes the count of `Yes` adverse effects for each treatment group.

## Installation 💻

To get started with this project, clone the repository and install the required dependencies:
Dependencies 📦
numpy
pandas
statsmodels
pingouin
seaborn
matplotlib

Conclusion ✅
This project provides a thorough statistical analysis of drug safety and compares treatment groups based on adverse effects and age distributions. It uses several hypothesis tests to determine whether the treatment group affects the occurrence of adverse effects.
