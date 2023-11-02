# diabetiespredict
![OIP4X0TGO0B](https://github.com/muralidharanseenu/diabetiespredict/assets/146166413/d5a36293-8dd0-4d73-9346-9abec8883475)

<img src="https://www.bing.com/images/search?view=detailV2&ccid=zebRpAIq&id=C15F890935C4A9567013EDEE786785694284BA14&thid=OIP.zebRpAIqbDv0MS43zo7ZbQHaE8&mediaurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.cde6d1a4022a6c3bf4312e37ce8ed96d%3frik%3dFLqEQmmFZ3ju7Q%26riu%3dhttp%253a%252f%252fhome-care-plus.com%252fwp-content%252fuploads%252f2016%252f11%252fdiabetesimage.jpeg%26ehk%3dxuTyaEzPZ5ovi5XrQmqYPyaDEsnznPXDWcOxY7pSKL8%253d%26risl%3d1%26pid%3dImgRaw%26r%3d0&exph=4724&expw=7086&q=diabetes+images&simid=607999260378363462&FORM=IRPRST&ck=BCC15442186B19775EF90061339DB1D3&selectedIndex=3" width=1000% height=5000%>

---

# Diabetes Prediction

This Python project implements logistic regression for predicting the likelihood of diabetes based on a given set of features. Below, you'll find instructions on how to run the code, its dependencies, dataset source, and a brief dataset description.

## Introduction

The code is structured into two main parts:

1. **Logistic Regression Implementation**
   - Contains a custom implementation of logistic regression, including the sigmoid function and the logistic regression class.
   - The logistic regression class has methods for model fitting and prediction.

2. **Main Program**
   - Imports necessary libraries, including NumPy, pandas, and scikit-learn.
   - Reads a dataset (e.g., "diabetes.csv") that is assumed to have features and a target variable named 'Outcome.'
   - Splits the data into training and test sets.
   - Trains a logistic regression model on the training data.
   - Calculates and displays the model's accuracy.
   - Accepts user input to make predictions for diabetes likelihood.
   - 
## Installation

To run this project, you can either download the files manually or use Git to clone the repository. Here are the commands to clone the repository:

```bash
# Clone the repository
git clone https://github.com/muralidharanseenu/diabetiespredict.git

# Navigate to the project directory
cd diabetiespredict 
 ```
     

## Table of Contents

- [Dependencies](#dependencies)
- [How to Run](#how-to-run)
- [Dataset Source](#dataset-source)
- [Dataset Description](#dataset-description)

## Dependencies

Before running the code, ensure you have the following dependencies installed on your system:

- Python 3
- NumPy
- pandas
- scikit-learn (for train-test split)
- matplotlib (for data visualization, though not used in this code)
- ![image](https://github.com/Keerthilucifergithub/diabetiespredict/assets/138312646/17935095-ce84-487e-a875-abc8a3f0da09 )           ![image](https://github.com/Keerthilucifergithub/diabetiespredict/assets/138312646/d0aaebf3-415d-49a9-beed-9a4b3fca86a3)
![image](https://github.com/Keerthilucifergithub/diabetiespredict/assets/138312646/667efbd9-10af-40c2-8363-344517219ecb)



You can install these dependencies using `pip`:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## How to Run

1. Clone this repository to your local machine or download the relevant files.

2. Open a terminal and navigate to the directory where the code is located.

3. Run the code using Python:

```bash
python Train.py
```


4. Follow the prompts in the command-line interface to perform the following actions:

   - Select an option:
     1) Evaluation
     2) Give input
     3) Exit Program

   - If you choose option 1 (Evaluation), the code will calculate and display the accuracy of the model based on test data.

   - If you choose option 2 (Give input), you can enter feature values to get a prediction for the binary outcome (0 or 1), indicating the likelihood of diabetes.

   - If you choose option 3 (Exit Program), the program will terminate.

Please ensure that you have a dataset in the CSV format (e.g., "diabetes.csv") with the target variable named 'Outcome' and other features.

## Dataset Source

The dataset used in this project is sourced from the UCI Machine Learning Repository. You can find the dataset at the following URL:

[Diabetes Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set/download?datasetVersionNumber=1)

## Dataset Description

The diabetes dataset contains various medical and demographic features, with the 'Outcome' column serving as the target variable. The 'Outcome' variable is binary, with a value of 1 indicating the presence of diabetes and 0 indicating the absence. Features include:

- Number of pregnancies
- Glucose level (mg/dl)
- Blood pressure (mm/Hg)
- Skin thickness (0-99)
- Insulin level (mm)
- BMI (Body Mass Index)
- Diabetes pedigree function
- Age

The code in this project trains a logistic regression model on this dataset to predict the likelihood of diabetes based on these features.

---

