# 🌸 Iris Flower Classification - CodeAlpha Internship

## 📌 Project Overview

This project is part of my internship at **CodeAlpha**.
The goal is to build a machine learning model that classifies Iris flowers into three species:

* Setosa
* Versicolor
* Virginica

based on their physical measurements.

## 📊 Dataset Information

The dataset used is the famous **Iris dataset**, which contains:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

These features are used to predict the species of the flower.

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn (for visualization)

## 🤖 Machine Learning Model

I used the **Random Forest Classifier**, a powerful ensemble learning algorithm, to train the model.

## ⚙️ How the Project Works

1. Load the dataset
2. Convert it into a DataFrame
3. Split the data into training and testing sets
4. Train the model using Random Forest
5. Make predictions on test data
6. Evaluate performance using accuracy and classification report

## 📈 Results

Accuracy:

```
1.0 (100%)
```

Classification Report:

```
Precision, Recall, and F1-score are all 1.00 for each class.
```
## ⚠️ Important Note

The model achieved 100% accuracy because the Iris dataset is small, clean, and well-structured.
The features are highly separable, making classification easier.

In real-world scenarios, achieving 100% accuracy is rare due to noisy and complex data.

## ▶️ How to Run the Project

1. Clone the repository:

```
git clone https://github.com/yourusername/CodeAlpha_IrisClassification
```

2. Navigate to the folder:

```
cd CodeAlpha_IrisClassification
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run the program:

```
python iris_classification.py

