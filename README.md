# Statistical Analysis Forecasting of Solar Electricity Production

**Summary:**

Secured the 3rd highest project grade among 80 groups, placing in the top 5%. Employed data visualization and statistical methods for solar electricity production analysis in Caen and Tours. Presented concise monthly statistics. Identified optimal distributions using log-likelihood maximization. Conducted robust hypothesis testing with Student-T, Bartlett, and Wilcoxon tests and addressed assumptions. Developed and assessed an autoregressive forecasting model, discussed its relevance through calculated Mean Absolute Error (MAE) and R-squared value.

- **Energy Calculation and Basic Statistics:**
  - Calculated daily energy (WH/m²) per square meter of solar panels, utilizing solar radiation data from Caen and Tours.

- **Comprehensive Data Visualization:**
  - Employed a diverse range of visualization techniques, such as time-series plots, box plots, and histograms, to elucidate solar electric production trends in Caen and Tours.
  - Emphasized cyclic behavior and effectively visualized outliers.
  - Methodically applied the interquartile range to remove outliers systematically, ensuring data consistency.

- **Statistical Distribution Fitting and Hypothesis Tests:**
  - Focused on the daily production of electricity in April, conducting a thorough analysis and providing insightful observations.
  - Utilized statistical distribution fitting, exploring Gamma and Normal distributions through log-likelihood maximization.
  - Systematically conducted hypothesis tests on distribution models, evaluating and justifying the selection of the best model for each location (Caen & Tours).

- **Robust Statistical Testing:**
  - Conducted a Student-T test to assess the equality of average daily production in April between Caen and Tours.
  - Employed a Bartlett test to evaluate the equality of variance in daily production for April between Caen and Tours, thereby validating the reliability of the Student-T test.
  - Explored and explained the relevance of Wilcoxon's test, a non-parametric alternative for comparing means of paired or matched samples, as opposed to the Student-T test.
  - Applied the Wilcoxon test to distributions of daily productions in April for Caen and Tours, providing a robust assessment of differences in means.

- **Regression and Forecasting:**
  - Implemented an autoregressive model for forecasting solar electric production.
  - Attained a robust 𝑅² value (89.3%) for the training set, signifying a strong linear relationship between independent variables and the dependent variable.
  - Evaluated the model on the validation set, demonstrating moderate effectiveness with a 𝑅² value of 67.7% and considering the Mean Absolute Error (MAE) of 124.156.
