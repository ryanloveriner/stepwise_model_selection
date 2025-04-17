# stepwise_model_selection

Stepwise model selection is a regression analysis technique used to identify useful predictor variables by iteraively adding or removing available variables to or from a statistical model. It's a useful way of building more complex models while minimizing prediction error, and R is an excellent coding format for this process.

The [project stored in this repo](https://github.com/ryanloveriner/stepwise_model_selection/blob/main/ADA%20Stepwise%20Model%20Selection.pdf) is from an Advanced Data Analysis course at the University of New Mexico and utilizes the dplyr package from the tidyverse library for data structuring and manipulation and ggplot2 was used for visualization.

The data used by the [R code itself](https://github.com/ryanloveriner/stepwise_model_selection/blob/main/ADA%20Stepwise%20Model%20Selection.qmd) is a subset of the American Time Use Survey (2003-2021) provided by the professor of the ADA course and isn't available without downloading his library, which is included in the code.

Data was filtered and tested for normality before plotting, which provided initial insight into model construction. Akaike Information Criterion was used to determine reduction and addition viability. QQ Plots, Cook's Distance, Residual Plots, and Box-Cox Plots were used to measure model normality after each step.

The resulting model was able to determine several significant correlations between predictive variables and the amount of sleep acquired by the ATUS responders, particularly age and time spent in family interactions.
