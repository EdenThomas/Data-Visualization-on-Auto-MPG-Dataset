# Auto MPG Dataset Analysis #
This folder contains a Jupyter notebook which explores and visualizes the Auto MPG dataset originally sourced from the UCI Machine Learning Repository. This analysis focuses on the technical specifications of cars, with an emphasis on understanding the relationships between various vehicle attributes through data visualization and statistical analysis.

## Dataset Description ##
The modified Auto MPG dataset includes the following attributes:

**Categorical Variables**: Cylinders, Model Year, Origin, Car Model

**Continuous Variables**: MPG (miles per gallon), Displacement, Horsepower, Weight, Acceleration.

Categorical variables such as Cylinders and Model Year are treated as discrete groups representing distinct categories like cylinder configuration and production year, respectively. Continuous variables represent measurable quantities that can vary and are expressed as floating-point numbers.

## Preprocessing ##
The dataset has been cleaned to remove rows with missing values (?) and erroneous entries (#VALUE!). Data types have been corrected to reflect the nature of each variable:

**Float64**: All continuous variables

**Category**: All categorical variables

## Descriptive Statistics ##
**Continuous Variables**: Summary statistics including mean, median, standard deviation, etc.

**Categorical Variables**: Frequency counts and mode analysis.

## Visualizations ##
Histograms for distribution of continuous variables.

Box-plots to observe outliers and spread of continuous variables.

Bar charts and Pie charts for categorical variable distribution.

Line charts to track changes over time (e.g., MPG over Model Years).

Treemaps to visualize hierarchical data.

## Variable Relationship Analysis ##
Scatter plots and 3D scatter plots to observe relationships between pairs of continuous variables.

Pearson correlation coefficients to quantify the degree of linear relationship between variables.

Cross-tabulation for examining the relationship between categorical variables.

Parallel coordinates plot for multivariate analysis.

## Tools and Technologies ##
**Python**: Primary programming language.

**Pandas**: Data manipulation and analysis.

**Matplotlib and Seaborn**: For plotting graphs.

**SciPy**: For statistical analysis.
