# BDA
Continuous hourly air quality data is collected from 12 monitoring points in Beijing, including indicators such as pollutant content and temperature.
In the project, the specific content is as follows,
1. Read and clean the data
2.Analysis of outlier
3. Add a time series to the data and analyze the temperature in group by time
3. Cluster analysis on the pollutant pm2.5
a. Kmeans
b.BisectingKmeans
c.ClusterEvaluator
3. Based on all the data, train the classifier model with the collecting stations as the label
a.StringIndexer
b.VectorAssembler
c.StandarScaler
d.DecisionTreeClassifier
e.RandomForestClassifier
f.MulticlassClassificationEvaluator

For the mini project:
4. Calculation of air quality index based on pollutant content data
a.UDF
5. Regression algorithm prediction of air quality index
a.LinearRegressor
b.DecisionTreeRegressor
c.RandomForestRegressor
d.Regression Evaluator
6. Classification of air quality on the basis of the air quality index
7. Apply classifier algorithm to air quality class
a.NaiveBayes
b.MultilayerPerceptronClassifier
c.DecisionTreeClassifier
d.RandomForestCladsifier
e.LogisticRegression
