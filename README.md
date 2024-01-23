# UC Berkeley AI/ML Certificate Course

## Practical Application Assignment 1

The objective of this project is to evaluate the provided data and generate insights regarding customers who accepted coupons compared to those who declined.

### Summary

- Bar Coupons: Approximately 41% of individuals accept Bar coupons. However, this rate escalates to 76% for those who go to bars more than three times a month. Furthermore, the acceptance rate surpasses 70% when the drivers are younger (below 30 years old), accompanied by friends or family, have a preference for budget-friendly dining, and earn less than $50K annually.

- Coffee Coupons: Nearly 50% of individuals accept coffee coupons, with men being slightly more receptive. Acceptance drops to 36% when drivers are headed home. Professionals in "Healthcare" and "Cleaning & Maintenance" show the highest acceptance at 74% and 72%, respectively. Students also have a high acceptance rate of 62%. Notably, drivers accompanied by peers show a higher propensity to accept these coupons than solo drivers or those with kids.

### Link to the Jupyter notebook

[link](https://github.com/iffj/ai-ml-portfolio/blob/main/assignment_1/prompt.ipynb)

## Practical Application Assignment 2

The goal of this project is to examine the given data and offer insights to a used car dealership regarding the factors that influence car prices and the attributes consumers prioritize in a used car.

### Summary

Used car dealers should focus on newer, well-maintained vehicles, particularly highlighting diesel or electric types, and 4WD or RWD models in their marketing. Caution is advised with high-mileage and poorly conditioned vehicles, such as those with salvage titles. The inventory should lean towards full-size vehicles while being selective with compact models to align with market preferences.

### Link to the Jupyter notebook

[link](https://github.com/iffj/ai-ml-portfolio/blob/main/assignment_2/prompt_II.ipynb)


## Practical Application Assignment 3

The objective of this assignment is to assess and compare the performance of classifiers, namely k-nearest neighbors, logistic regression, decision trees, and support vector machines. This evaluation will be conducted using a dataset that pertains to the marketing of bank products via telephone.

### Summary

The four models—KNN, SVC, Logistic Regression, and Decision Tree—exhibited similar accuracy levels during training and testing, with the Decision Tree achieving the highest accuracy at 91.66%, and the others ranging between 87% to 89%. Although the Decision Tree outperformed the rest, the accuracy differences among the models were marginal.

Regarding training duration, KNN was the fastest, taking only 0.0224 seconds, whereas SVC was the slowest, requiring 34.8717 seconds. Fine-tuning hyperparameters with GridSearchCV had a minimal effect on performance, with some models showing a slight increase (less than 1%), while others showed a negligible decrease. This phenomenon could be attributed to potential overfitting by the optimal parameters identified by GridSearchCV, or it might simply fall within the normal variation range. Another possibility is that the hyperparameter space covered by GridSearchCV was not sufficiently comprehensive. Expanding this space could enhance model performance but would also significantly increase computational complexity; for instance, running GridSearchCV on SVC exceeded a 10-minute completion time on my local machine. As alternatives, we could consider varying the train-validation splits or setting a consistent random state to ensure reproducibility.

### Link to the Jupyter notebook

[link](https://github.com/iffj/ai-ml-portfolio/blob/main/assignment_3/prompt_III.ipynb)
