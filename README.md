# Diabetes Model - Readme

This project is a coursework assignment completed as part of the Udacity course on machine learning. The objective of the exercise is to build a diabetes prediction model using the Diabetes dataset.

## Dataset

The Diabetes dataset used in this exercise is a well-known dataset that has already been cleaned and normalized. It contains various features related to diabetes, such as blood pressure, glucose levels, and body mass index (BMI). The dataset is included in the scikit-learn library.

## Steps

To complete this exercise, the following steps were performed:

1. **Loading the dataset**: The Diabetes dataset was loaded into a pandas dataframe to facilitate data analysis and model training.

2. **Data summary**: A summary of the dataset was generated to verify that the mean value is zero for all features. This step ensures that the data is properly normalized.

3. **Splitting the dataset**: The dataset was split into three sets: training, validation, and test sets. This division allows for model training, evaluation, and testing on separate data subsets.

4. **Model training and scoring**:

   - Whole dataset: The linear regression Ridge model was fitted and scored on the entire dataset.
   
   - Train-validation split: The model was fitted on the training set and scored on the validation set using the default model configuration.
   
   - Train-validation split with hyperparameters: The model was fitted on the training set and scored on the validation set using a hyperparameterized model configuration.
   
   - Train-test split with hyperparameters: The model was fitted on the training set and scored on the test set using the hyperparameterized model configuration.

5. **Score visualization**: The scores obtained from the different model evaluations were plotted in a bar graph for easy comparison.

## Dependencies

The following dependencies were used in this exercise:

- numpy
- pandas
- scikit-learn

Ensure that these libraries are installed before running the code.

## Running the Code

To run the code for this exercise, follow these steps:

1. Make sure you have Python installed on your system. You can download and install Python from the official website: https://www.python.org/downloads/

2. Install the required dependencies by running the following command in your terminal or command prompt:

   ```
   pip install numpy pandas scikit-learn
   ```

3. Create a new Python file and copy the provided code into it.

4. Save the file with an appropriate name, such as "diabetes_model.py".

5. Open a terminal or command prompt, navigate to the directory containing the Python file, and run the following command:

   ```
   python diabetes_model.py
   ```

   The code will load the dataset, split it into train, validation, and test sets, fit the Ridge model, score the model on different subsets, and generate a bar graph of the scores.

## Customization

Feel free to customize the code and experiment with different aspects of the model and dataset. Some possible customizations include:

- Trying different regression models or algorithms.
- Adjusting the hyperparameters of the Ridge model.
- Adding additional features or feature engineering techniques.
- Implementing cross-validation for more robust model evaluation.

Remember to document and analyze the results of any modifications or customizations you make.

## Credits

The exercise and code implementation are based on the materials and instructions provided in the Udacity machine learning course. The Diabetes dataset used in this exercise is sourced from the scikit-learn library.

---
