## How the Math Works (Multiple Linear Regression)
This model uses Multiple Linear Regression to estimate the relationship between the book's features and its price. The underlying mathematical formula applied is:

$$y = \beta_0 + \beta_1x_1 + \beta_2x_2$$

Where:
* $y$ represents the predicted **Price** (the target variable).
* $\beta_0$ is the **Intercept** (the baseline price when all other features are exactly zero).
* $\beta_1$ and $\beta_2$ are the **Coefficients** (weights) learned by the model during the training phase.
* $x_1$ represents the first feature: **Published_Year**.
* $x_2$ represents the second feature: **Stock**.

When you input a new book's year and stock, Scikit-Learn simply plugs those values into $x_1$ and $x_2$ of this equation to calculate the predicted price!
