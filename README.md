# Salifort-Motors
*Google Advanced Data Analytics Capstone* _[see certificate](https://www.coursera.org/account/accomplishments/professional-cert/B22RFVSZGTV7)_

## Project Overview

The objective of this project was to develop a predictive model to identify employees at risk of leaving Salifort Motors, thereby aiding
in the retention efforts. The analysis involved exploring survey data collected from employees to understand the factors influencing
turnover. Various machine learning techniques, including logistic regression and decision tree algorithms, were employed to build
predictive models. The final model achieved an accuracy of 82% in predicting employee turnover.

## Business Understanding

Salifort Motors is grappling with a high turnover rate among its employees, which poses significant challenges to its operational
efficiency and financial sustainability. Research indicates that turnover is not only detrimental to morale and productivity but also
incurs substantial costs in terms of recruitment, training, and lost expertise. By identifying the factors driving turnover, Salifort can
implement targeted strategies to improve retention and foster a supportive work culture conducive to employee growth and development.

## Data Understanding

The survey data used in this analysis was collected by the HR department from a sample of employees to gain insights into the reasons
behind turnover. The dataset includes information such as job title, department, number of projects, average monthly hours, and other
relevant variables. Exploratory data analysis revealed patterns and trends within the dataset, highlighting potential predictors of
employee turnover. Data limitations include the representativeness of the sample and the accuracy of self-reported survey responses.

![salifort_features_explained](https://github.com/Pharmiliar/Salifort-Motors/assets/109634454/9e7a6ecc-38eb-4123-8da6-418854c2f326)

A Description of the variables collected from about 14,999 employees. (10 columns; 14999 rows)

## Modeling and Evaluation

Logistic regression, decision tree, random forest, and XGBoost models were trained and evaluated to predict employee turnover. The models
were assessed based on metrics such as accuracy, precision, recall, and F1-score. The random forest model emerged as the most effective,
achieving an accuracy of 82% and demonstrating strong predictive performance. Feature importance analysis revealed key drivers of
turnover, including job title, department, and average monthly hours.

![decision_tree](https://github.com/Pharmiliar/Salifort-Motors/assets/109634454/bfd52c11-1faa-4a4f-83e7-4997b291268a)

Barplot above shows the most relevant variables: ‘last_evaluation’, ‘number_project’,  ‘tenure’ and ‘overworked’.

![random_forest_2](https://github.com/Pharmiliar/Salifort-Motors/assets/109634454/e4cb16f5-47f1-41e8-9aa9-7e8ac2406ba9)

In the random forest model above, `last_evaluation`, `tenure`, `number_project`, `overworked`, `salary_low`, and `work_accident` have the highest importance. These variables are most helpful in predicting the outcome variable, `left`.


## Conclusion

The predictive model developed in this project offers valuable insights into the factors influencing employee turnover at Salifort
Motors. By leveraging this model, Salifort can proactively identify at-risk employees and implement targeted retention strategies.
Recommendations include enhancing communication channels, providing opportunities for professional development, and addressing workload
issues. Future steps may involve incorporating additional data sources and refining the model to improve its predictive accuracy and
usefulness in guiding strategic decision-making.
