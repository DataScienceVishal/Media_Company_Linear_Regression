**Project Description:**

**About Data:**  
The dataset contains variables related to viewership metrics and contextual factors surrounding a digital media company's show, including views, visitors, ad impressions, cricket match broadcasts, and character appearances.

**Problem Statement:**  
The digital media company observed a decline in viewership for its show and seeks to understand the factors contributing to this decline.

**Solution:**  
Utilizing linear regression, data preprocessing, and visualization techniques, the project aims to uncover insights into the viewership decline. By analyzing relationships between viewership metrics and contextual factors such as cricket matches and character appearances, the goal is to identify influencing factors and areas for improvement.

**Algorithms:**  
Linear regression is employed to model the relationship between viewership metrics and contextual factors, quantifying their impact and importance.

**Libraries:**  
The project utilizes numpy, matplotlib, seaborn, datetime, sklearn, and statsmodels for data manipulation, visualization, and regression analysis.

**Model Performance:**  
The final linear regression model achieved an R-squared of 0.803, the highest of roughly ten successive OLS specifications tried in the notebook. This is an in-sample fit on all 80 rows of the dataset; the notebook has no train/test split and no held-out data, so 0.803 measures how well the model describes the data it was fitted on, not its predictive performance on unseen data.
