Task:Statistical modelling

Objective:
The objective of thask is to analyze the relationship between various musical features and popularity of tracks on spotify. By laveraging statistical modeling and machine learning techniques, aim is to identify key factors that affect song popularity.

Task:
1. Quantitative Analysis of Musical Features: Systematically analyze how different
features such as danceability, energy, loudness, and valence correlate with and predict
the popularity of music tracks.
2. Development of Predictive Statistical Models: Construct and refine multiple
statistical models to accurately predict music track popularity based on quantitative
data.
3. Statistical Insight Generation: Utilize the results from the statistical models to
provide quantifiable insights and recommendations for enhancing track popularity.

Steps and solution:
1. Read csv file
2. Use info() to check the data types and identify missing values and  use describe() to get summary statistics for numerical features.
3. Drop unrelevant columns like unnamed:0
4. Repalce missing categorical columns with 'Unknown' using fillna()
5. Find skewness by visualization or using df[columns].skew(). If Skewness between -0.5 to 0.5 use mean, skewness < -0.5 or > 0.5 use median, If one value is repeated often, consider using mode for replacing missing values.
6. Create correlation matrix between numerical columns and popularity by first extracting numerical columns in a dataframe and use corr() method to find correlation.
7. Use scatterplot method in seaborn or matplotlib to visualize scatter plot between all numerical columns vs Popularity column.
8. Generate histogram plot using seaborn or matplotlib library.
9. Convert Explicit column values which are boolean into integers using astype(int). Plot box plot for finding effect of Explicit column on Popularity column.
10. Identify key features that could influence popularity using correlation matrix.
11. Normalize/Standardize numerical features using StandardScaler from Scikit-Learn to
ensure features are on the same scale.
12. Use train_test_split() to divide the dataset into a training set (80%) and a testing set
(20%) with a fixed random state for reproducibility.
13. From sklearn import linear_model to create linear regression model.
14. Train the model.
15. Use Mean Squared Error (MSE) to measure how far predictions deviate from actual
values. Use R2 Score to measure how well the model explains the variability in popularity.
16. Analyze the model’s coefficients to understand which features contribute the most to
popularity.

Requirements:
1. Python 3.x
2. Numpy
3. Pandas
4. Matplotlib
5. Seaborn
6. Scikit-learn
7. Jupyter notebook or visual studio