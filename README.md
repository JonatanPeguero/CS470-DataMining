📘 CS470 – Data Mining (Spring 2025)
Instructor: Prof. Kai Shu
University: Emory University
Language: Python
Topics: Pattern Mining, Clustering, Regression, Forecasting

🔍 HW2 – Frequent Pattern Mining with Apriori
Summary:

Implemented the Apriori algorithm from scratch to discover frequent itemsets from a dataset of tweets related to flu shots. Explored the impact of support thresholds and analyzed emergent patterns using keyword-based transactions.

Key Tasks:

Parsed a dataset of flu-related tweets using the text keywords field as transaction items

Developed the Apriori algorithm with support for customizable support thresholds

Generated sorted frequent itemsets and wrote them to a formatted output file

Tuned parameters for runtime efficiency vs. discovery rate

Submitted a comprehensive report detailing optimizations and insights from the mined patterns

Skills: Apriori, association rules, support threshold tuning, dataset analysis

🧮 HW3 – Clustering: K-Means, Hierarchical, and DBSCAN
Summary:

Applied three clustering algorithms — K-Means, Hierarchical Clustering, and DBSCAN — on real datasets. Compared their effectiveness, visualization, and parameter sensitivity.

Key Tasks:

Implemented or configured:

K-Means with K=5 and various distance metrics

Hierarchical clustering with complete linkage

DBSCAN with ε and minPts tuning

Visualized clustering results using 2D plots

Compared clustering performance and behavior on multiple datasets

Discussed strengths/limitations of each algorithm in structured report

Skills: Unsupervised learning, clustering, parameter tuning, result interpretation

🗽 Final Project – Forecasting NYC Traffic Volume (Brooklyn)
Project Title: Predicting Traffic Patterns in New York City
Team Members: Katie Park & Jonatan Peguero

Summary:

Designed a predictive modeling pipeline to estimate traffic volume in Brooklyn using open-source NYC sensor data. Focused on summer months and used Random Forest and LSTM models to predict hourly traffic volumes.

Key Steps:

Cleaned and filtered open NYC DOT traffic sensor data for Summer (June–Aug) in 2016, 2018, 2021, and 2022

Engineered features: month, day, hour, minute, direction

Trained models:

✅ Random Forest Regressor (Best performance)

🔄 LSTM model for capturing long-term trends

Evaluated models using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

5-Fold Cross Validation

Results:

Random Forest: MAE = 15.45, R² = 0.97 (high accuracy)

LSTM: MAE = 16.84, R² = 0.86 (good at trend detection)

Random Forest outperformed LSTM on this small structured dataset

Skills: Data cleaning, time-series regression, LSTM, Random Forest, K-Fold CV, real-world deployment relevance
