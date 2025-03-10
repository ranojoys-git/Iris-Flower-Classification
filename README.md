# Context:
The Iris flower dataset consists of three species: setosa, versicolor, and virginica. These species can be distinguished based on their measurements, such as sepal length, sepal width, petal length, and petal width.

# Steps:
**Loading the Dataset:**
The Iris dataset was loaded using the pandas library. The dataset contains 150 entries with four features (sepal length, sepal width, petal length, petal width) and the target variable (species).

**Exploratory Data Analysis (EDA):**
Exploratory data analysis was performed to understand the dataset better. This included checking for missing values, analyzing the distribution of features, and visualizing the data using pairplots and boxplots to identify patterns and relationships between the features and species.

**Data Preprocessing:**
The dataset was split into training and testing sets using train_test_split from sklearn.model_selection. This ensures that the model is evaluated on unseen data. The features were standardized using StandardScaler to normalize the data for better model performance.

**Model Selection and Training:**
The following algorithms were used for classification:

- Logistic Regression
- Decision Tree
- Random Forest Classifier

**Model Evaluation:**
The models' performance was evaluated on the test dataset using metrics such as accuracy and classification report. The models achieved high accuracy in classifying the Iris species.
