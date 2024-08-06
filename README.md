# Decision Trees and Random Forests in Python

This project explores the implementation of Decision Trees and Random Forests using the `kyphosis` dataset. The goal is to classify whether the condition of kyphosis is present or absent based on certain features.

## Dataset

The dataset `kyphosis.csv` includes the following columns:

- `Kyphosis`: Target variable (whether kyphosis is present or absent)
- `Age`: Age of the patient
- `Number`: Number of vertebrae involved
- `Start`: The number of the first vertebra involved

## Project Structure

1. **Data Import and Exploration**:
    - Load the data using Pandas.
    - Display the first few rows of the dataset.
    - Visualize the data distribution using Seaborn.

2. **Train-Test Split**:
    - Split the data into training and testing sets using `train_test_split` from `sklearn.model_selection`.

3. **Decision Tree Model**:
    - Train a Decision Tree Classifier on the training data.
    - Make predictions on the test data.
    - Evaluate the model using classification report and confusion matrix.

4. **Tree Visualization**:
    - Visualize the Decision Tree using `export_graphviz` and `pydot`.

5. **Random Forest Model**:
    - Train a Random Forest Classifier on the training data.
    - Make predictions on the test data.

## Usage

1. Clone the repository and navigate to the project directory.

2. Ensure you have all the necessary libraries installed. If not, you can install them using pip:

    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn pydot
    ```

3. Load the dataset and run the Jupyter notebook to execute the project code step-by-step.

## Visualizations

- **Pairplot**: Visualize the relationships between features and the target variable `Kyphosis` using Seaborn.
- **Tree Visualization**: Visualize the trained decision tree.
- **Random Forest**: Train a Random Forest Classifier and evaluate its performance.

## Evaluation

- **Classification Report**: A detailed report showing the main classification metrics.
- **Confusion Matrix**: A table used to describe the performance of a classification model.
