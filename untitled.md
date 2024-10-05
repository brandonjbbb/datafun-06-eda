# Exploratory Data Analysis (EDA) Project
**Author**: Brandon Jean-Baptiste
**Date**: September 30-2024 

**Purpose**: This notebook demonstrates an exploratory data analysis (EDA) of a dataset using Python libraries like pandas, Seaborn, and matplotlib.


## Observations from the Pairplot:
- There is a clear separation between the species based on the features.
- `petal_length` and `petal_width` seem to be the most distinguishing features between species.
- `sepal_length` and `sepal_width` are less useful for distinguishing between species.

## Observations from the Correlation Heatmap:
- `petal_length` and `petal_width` have a strong positive correlation (0.96).
- There is a moderate positive correlation between `sepal_length` and `petal_length`.
- `sepal_width` is negatively correlated with `sepal_length` (-0.12).
## Conclusion
This exploratory data analysis reveals clear distinctions between species in the Iris dataset based on their petal and sepal dimensions. Features like `petal_length` and `petal_width` offer the most significant separation between species, while `sepal_length` and `sepal_width` are less impactful. The engineered feature, `Petal Length/Width Ratio`, also helps highlight differences between species.

