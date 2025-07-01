
#  Titanic Data Analysis – Task 5 (EDA)

---


### Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

###  Steps Performed
1. **Data Loading & Understanding**  
   Used `.info()`, `.describe()`, `.isnull().sum()` to explore dataset structure and missing values.

2. **Univariate Analysis**  
   Plotted distributions and counts of individual features like `Age`, `Sex`, `Pclass`, `Fare`, etc.

3. **Bivariate Analysis**  
   Explored relationships between features and target variable `Survived` using barplots and boxplots.

4. **Multivariate Analysis**  
   Used heatmap and pairplot to check correlation and interactions among multiple variables.

5. **Observations & Summary**  
   Highlighted patterns such as:
   - Females had a higher survival rate.
   - First-class passengers had better chances of survival.
   - Children were more likely to survive than adults.

---

###  Key Insights
- **Sex** and **Pclass** are strong indicators of survival.
- **Age** and **Fare** distributions show skewness.
- Missing values in `Age` and `Cabin` columns were identified.

