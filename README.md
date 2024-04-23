# NTU-SC1015-Mini-Project
This repository contains all the Jupyter Notebooks, datasets, images, video presentations, and the source materials/references we have used and created as part of the Mini Project for SC1015: Introduction to Data Science and AI.
# About
In our project, "Student's Life and Satisfaction," we delve into the realm of university student experiences and satisfaction levels. We aimed to understand the factors leading to stress and whether it affects satisfaction level.

As we are currently university students, this topic resonates closely with us. Therefore, our team decided to focus on student's stress level and student life satisfaction.
# Problem Definition
- What factors contribute to stress among university students?
- What are the key factors that are important in student life?
- Which model would be the best to predict the above two problem?
# Dataset Explored 
The dataset used for this project is taken from [here](https://www.kaggle.com/datasets/shivamb/ideal-student-life-survey/).

We cleaned and prepared the dataset for EDA and Machine Learning separately hence, there is no "cleaned dataset". Refer to respective notebook to see how we cleaned and prepared the dataset for each use.
# Presentation
Our presentation video can be found [here](https://www.youtube.com/watch?v=McWwfiqxBis).
# Brief Summary
1. [Exploratory Data Analysis](https://github.com/esmondch/NTU-SC1015-Mini-Project/blob/main/Exploratory%20Data%20Analysis.ipynb)
   - Data Cleaning
   - Univariate Statistics
   - Univariate Analysis
   - Modifying Dataset
   - Bivariate Analysis to Predict Stress Levels
3. [Machine Learning](https://github.com/esmondch/NTU-SC1015-Mini-Project/blob/main/Machine%20Learning.ipynb)
   - Data Preparation
   - Train Test Split of Dataset
   - Model 1 - Decision Tree Classifier
   - Model 2 - Random Forest Classifier
   - Results Obtained (Confusion Matrix & Classification Report)
   - Further Exploration (Other Models)
   - Conclusion on Machine Learning
# Conclusion
- Random Forest Classifier is the better model between the two initial models used. KNN performs equally well.
- Didn't manage to achieve our objective of reducing stress level and increasing student satisfaction.
- However, we were able to successfully identify the 5 top factors for stress level and student satisfaction respectively.
- Interestingly, stress and satisfaction are closely linked but it is unclear if the relationship is positive or negative.
- According to our feature importance analysis, student volunteering in events have high influence in both stress and student satisfaction.
- Based on our findings, we would like to suggest to universities to provide opportunities to cater to a broader range of students, allowing them to engage in events they are passionate about.
- Additionally, the feature importance provide insights which sets the path for future exploration and intervention strategies.
# Contributors
1. @esmondch (Esmond Chan) - Machine Learning, Slides, Presenter
2. @darrentkl (Darren Thia) - Machine Learning, Slides, Presenter
3. Nadathur Ammal Shreya Sudharshan - EDA, Slides, Presenter
# References
GeeksforGeeks. (2024, March 21). One hot encoding in machine learning. https://www.geeksforgeeks.org/ml-one-hot-encoding/ 

guest_blog. (2023, July 21). 12 univariate data visualizations with illustrations in Python. Analytics Vidhya. https://www.analyticsvidhya.com/blog/2020/07/univariate-analysis-visualization-with-illustrations-in-python/ 

Mahesh. (2023, June 13). Exploring decision trees, random forest, logistic regression, KNN, linear regression, SVM, RNN... Medium. https://medium.com/@maheshhkanagavell/exploring-decision-trees-random-forest-logistic-regression-knn-linear-regression-svm-rnn-bf52fa94a066 

Shung, K. P. (2020, April 10). Accuracy, precision, recall or F1?. Medium. https://towardsdatascience.com/accuracy-precision-recall-or-f1-331fb37c5cb9 

Tokuç, A. A. (2024, March 18). Splitting a dataset into train and test sets. Baeldung on Computer Science. https://www.baeldung.com/cs/train-test-datasets-ratio 

Wijaya, C. Y. (2023, February 2). Pareto Principle in Machine Learning Development: Work Smarter, not Harder. Non-Brand Data. https://cornellius.substack.com/p/pareto-principle-in-machine-learning 
