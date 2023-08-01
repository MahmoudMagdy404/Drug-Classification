# Oranges vs. Grapefruit Binary Classification Project

This project aims to perform binary classification using a Naive Bayes classifier implemented from scratch. The objective is to distinguish between oranges and grapefruits based on certain features or attributes of the fruits.

## Background

Binary classification is a machine learning task where the goal is to predict one of two possible classes (in this case, oranges or grapefruits) based on input data. The Naive Bayes classifier is a probabilistic algorithm commonly used for binary classification tasks. It assumes that the features are conditionally independent given the class label, which simplifies the computation of probabilities.

## Features

The dataset used in this project contains various features (e.g., color, size, texture, weight, etc.) of both oranges and grapefruits. These features are used to train the Naive Bayes classifier and make predictions on new, unseen data.

## Getting Started

To run this project, you will need the following prerequisites:

1. Python (version 3.x)
2. Jupyter Notebook (for running the provided notebook)
3. NumPy library (for numerical operations)
4. Pandas library (for data manipulation and analysis)

## Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/MahmoudMagdy404/Oranges-vs.-Grapefruit-.git
```

2. Navigate to the project directory:

```bash
cd Oranges-vs.-Grapefruit-
```

3. Ensure you have Python 3.x installed. You can check your Python version by running:

```bash
python --version
```

4. Install the required dependencies (NumPy, Pandas, and Jupyter Notebook):

```bash
pip install numpy pandas jupyter
```

5. Launch the Jupyter Notebook server:

```bash
jupyter notebook
```

6. Open the provided notebook file, `Oranges_vs_Grapefruit_Classification.ipynb`, in the Jupyter Notebook web interface.

7. Execute the notebook cells one by one to perform the binary classification using the Naive Bayes classifier and visualize the results.

## Implementation Details

The notebook, `Oranges_vs_Grapefruit_Classification.ipynb`, contains the implementation of the Naive Bayes classifier. It reads the dataset, preprocesses the data, splits it into training and testing sets, and then trains the classifier using the training data. The model's performance is evaluated on the test data, and accuracy metrics are reported.

## Dataset

The dataset used for this project contains labeled examples of oranges and grapefruits with various features. Make sure the dataset file (`citrus.csv`) is present in the project directory before running the notebook.

## Results

After executing all the cells in the notebook, you should see the accuracy of the Naive Bayes classifier on the test set. Additionally, the notebook may display the confusion matrix, precision, recall, and F1-score to provide a comprehensive evaluation of the model's performance.

## Contributions

Contributions to this project are welcome. If you have any suggestions or improvements, feel free to submit a pull request.

## Acknowledgments

- For further details ,please check the report (`Biostatistics_Team20-Report.pdf`).
- Thanks to [Mohamed elsayed ali & Mohame elsayed eid] for their valuable contributions to the project.

## Contact

For any questions or inquiries related to this project, please contact [mahmoodmagdy9@gmail.com].
