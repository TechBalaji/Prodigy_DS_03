# Building the Decision Tree

## Overview 📝

Welcome to the Prodigy_DS_03 repository! This project demonstrates how to build a **Decision Tree Classifier** using a real-world dataset. The goal is to predict whether a person will subscribe to a product based on their demographic and behavioral features.

This repository provides all the necessary code to train a Decision Tree model, visualize the tree structure, and interpret the results. It includes everything you need to run the project and get a clear understanding of the model's decision-making process. 🔥

## Dataset 📊

The dataset used in this project is related to **bank marketing**. It contains information about individuals' demographic and behavioral data. The objective is to predict whether or not an individual subscribes to a term deposit based on various features.

You can download the dataset from the following source: [bank+marketing.zip](https://github.com/user-attachments/files/18169284/bank%2Bmarketing.zip)

### Data Details:

The zip file contains two CSV files:
- **bank.csv**: Contains a subset of the dataset.
- **bank-full.csv**: A larger version of the dataset.

These two files have been merged into a single file called **`bank_combined.csv`**. This combined file is used for training the Decision Tree model.

### Columns:
- **age**: Age of the individual. 🎂
- **job**: Type of job (e.g., unemployed, services, management, etc.). 💼
- **marital**: Marital status (e.g., married, single). 💍
- **education**: Education level (e.g., primary, secondary, tertiary). 🎓
- **default**: Whether the individual has credit in default (yes/no). 💳
- **balance**: Account balance. 💵
- **housing**: Whether the individual has a housing loan (yes/no). 🏡
- **loan**: Whether the individual has a personal loan (yes/no). 💰
- **contact**: Contact communication type (e.g., cellular, telephone). 📞
- **day**: Last contact day of the month. 📅
- **month**: Last contact month of the year. 📆
- **duration**: Duration of the last contact. ⏳
- **campaign**: Number of contacts performed during the campaign. 📈
- **pdays**: Number of days since the client was last contacted. 🕰️
- **previous**: Number of contacts performed before this campaign. 📞
- **poutcome**: Outcome of the previous marketing campaign (success, failure, etc.). 🏆
- **y**: Target variable (whether the person subscribed to the term deposit - yes/no). ✅

## Tools and Libraries 🛠️

To successfully run the code and visualize the decision tree, the following tools and libraries are required:

1. **Python 3.x**: The main programming language used. 🐍
2. **pandas**: For data manipulation and loading. 📊
3. **numpy**: For numerical operations. 🔢
4. **scikit-learn**: For building the decision tree model. 🧠
5. **graphviz**: For visualizing the decision tree. 🌳
6. **matplotlib**: For plotting the decision tree. 📊

## What does the code do? 🤖

The code follows these major steps:

1. **Data Preprocessing**:
   - The dataset is loaded, and necessary preprocessing steps like handling categorical variables and missing values are applied. 🔧
   
2. **Merging Datasets**:
   - The two separate CSV files, **`bank.csv`** and **`bank-full.csv`**, are merged into one single file named **`bank_combined.csv`**. This combined dataset is used for model training and visualization. 🔗

3. **Model Training**:
   - A Decision Tree Classifier is trained on the preprocessed dataset using the **'y'** column as the target (whether a person subscribed to the term deposit). 🌳

4. **Visualization**:
   - The decision tree is visualized using **graphviz**. This allows for a graphical representation of the model's decision-making process, where you can see the different features and thresholds the model uses to make predictions. 🌱

5. **Evaluation**:
   - The model is evaluated using accuracy and a classification report to assess its performance. 📈

## How to Run 🚀

To run the code and visualize the Decision Tree, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/Prodigy_DS_03.git
    cd Prodigy_DS_03
    ```

2. Install the required libraries. If you don't have them already, use:

    ```bash
    pip install pandas numpy scikit-learn graphviz matplotlib
    ```

3. Ensure that Graphviz is installed and properly configured. You can download it from [Graphviz](https://graphviz.gitlab.io/download/) and add it to your system's PATH.

4. Download the dataset from [bank+marketing.zip](https://github.com/user-attachments/files/18169284/bank%2Bmarketing.zip) and extract it into the project directory.

5. Run the main code to train the Decision Tree and visualize it:

    ```bash
    python decision_tree_classifier.py
    ```

6. After the script runs successfully, the decision tree visualization will be saved in a `.png` file and you can view it using any image viewer. 🖼️

## Handling Directory Issues ⚠️

During the setup or execution of the code, you might encounter directory-related issues:

1. **File Paths**: Ensure the dataset file is placed in the correct directory or update the paths in the code accordingly. 🗂️

2. **Graphviz Visualization**: If you encounter errors related to Graphviz (e.g., `dot not recognized`), make sure that:
   - Graphviz is installed. ✔️
   - The path to Graphviz is added to your system’s PATH variable. 🌐
   - If on Windows, you may need to add `C:\Program Files\Graphviz\bin` to the PATH environment variable manually. 🖥️
## Sample Video 🎥

Here’s a quick demo of how the code works and the Decision Tree visualization process:

[Click here to watch the video!](https://github.com/user-attachments/assets/4bbbea8e-3921-4c51-96b6-ec3db6071658)

## Desired Output 🎯

The output of this project is a **visualized Decision Tree**. The model will classify whether a person subscribes to a term deposit based on the various demographic and behavioral features. By visualizing the tree, you can see how the model splits the data at each decision node, making it easier to interpret its decision-making process. 🌳📊

## Conclusion 🎉

By following this guide, you will be able to:
- Merge two datasets (`bank.csv` and `bank-full.csv`) into a single combined file for easier processing. 🔗
- Train a Decision Tree Classifier on the bank marketing dataset. 📚
- Visualize the Decision Tree to understand the model’s decision-making process. 🌿
- Evaluate the performance of the model using metrics like accuracy and classification report. 📉
