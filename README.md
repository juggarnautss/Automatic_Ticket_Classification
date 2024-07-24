# Automatic Ticket Classification

## Problem Statement

To build a model that is able to classify customer complaints based on the products/services. By doing so, we can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

You will be doing topic modelling on the `.json` data provided by the company. Since this data is not labelled, you need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

* Credit card / Prepaid card
* Bank account services
* Theft/Dispute reporting
* Mortgages/loans
* Others

With the help of topic modelling, we will map each ticket onto its respective department/category. Then use this data to train any supervised model such as logistic regression, decision tree, or random forest. Using this trained model, we can classify any new customer complaint support ticket into its relevant department.

## Methodology

### Steps Followed

1. **Data Loading:**
   - Load the data from the provided `.json` files.

2. **Text Preprocessing:**
   - Clean and preprocess the text data to prepare it for analysis.

3. **Exploratory Data Analysis (EDA):**
   - Perform EDA to understand the data distribution and identify patterns.

4. **Feature Extraction:**
   - Extract relevant features from the text data for modelling.

5. **Topic Modelling:**
   - Apply Non-negative Matrix Factorization (NMF) to identify and classify tickets into topics.

6. **Model Building using Supervised Learning:**
   - Build a supervised model using algorithms like logistic regression, decision tree, or random forest.

7. **Model Training and Evaluation:**
   - Train the model on the classified data and evaluate its performance.

8. **Model Inference:**
   - Use the trained model to classify new customer complaint support tickets into relevant categories.

### Contributor
   - Sirin Shaikh
