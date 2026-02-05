Iris Flower Classification – Data Science Internship Project

📌 Objective

The objective of this project is to build a machine learning model that can classify iris flowers into different species based on their physical measurements.
The model predicts the species of an iris flower using features such as sepal length, sepal width, petal length, and petal width.


📊 Dataset

Dataset Name: Iris Dataset

Source: Provided as part of the internship

Number of Records: 150

Number of Features: 4 input features and 1 target variable


Features:

Sepal Length

Sepal Width

Petal Length

Petal Width


Target Variable:

Species

Iris-setosa

Iris-versicolor

Iris-virginica


🛠 Tools and Technologies Used

Programming Language: Python

Development Environment: Jupyter Notebook


Libraries Used:

NumPy – numerical computations

Pandas – data manipulation and analysis

Matplotlib – data visualization

Seaborn – statistical data visualization

Scikit-learn – machine learning algorithms


⚙️ Steps Performed

Data Loading:

Loaded the dataset using Pandas.

Data Understanding:

Checked the shape, data types, and statistical summary of the dataset.

Data Cleaning:

Removed the unnecessary Id column.

Verified that there were no missing values.

Exploratory Data Analysis (EDA):

Visualized relationships between features using pair plots.

Observed that Iris-setosa is clearly separable from other species.

Feature Selection:

Separated input features and target variable.

Train-Test Split:

Split the dataset into training (80%) and testing (20%) sets.

Model Training:

Trained a K-Nearest Neighbors (KNN) classifier.

Model Prediction:

Predicted species on the test dataset.

Model Evaluation:

Evaluated the model using accuracy score.

Visualized results using a confusion matrix.


✅ Results

The K-Nearest Neighbors model achieved 100% accuracy on the test dataset.

The confusion matrix showed that all iris flower species were classified correctly.

The model demonstrated excellent performance in classifying iris flower species based on given features.


📌 Conclusion

This project successfully demonstrates the implementation of a machine learning classification model using the Iris dataset.
The results show that machine learning algorithms like KNN can effectively classify data with high accuracy when proper data preprocessing and analysis are performed.
