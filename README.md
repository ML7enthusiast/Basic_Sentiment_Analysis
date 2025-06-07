# Basic_Sentiment_Analysis

This project focuses on classifying text data into one of six emotional categories using a softmax-based Logistic Regression model. It demonstrates data preprocessing, vectorization, model training, and evaluation—all done in Python using popular ML libraries.

## Files Included

- `Sentiment_Analysis_assignment.ipynb` — colab notebook containing all code and explanations
- `training.csv` — Labeled training dataset
- `validation.csv` — Labeled validation dataset
- `test.csv` — Unlabeled dataset used for testing final predictions

##  Emotion Categories

The dataset consists of six emotion labels, encoded as integers from 0 to 5. Each label corresponds to a unique emotion (e.g.,0: 'sadness',1: 'joy', 2: 'love', 3: 'anger',4: 'fear',5: 'surprise'). You can modify the code to map these to actual labels.

##  Tech stack

- Python
- Pandas
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

##  Key Features

- Text preprocessing and CountVectorizer for feature extraction
- Logistic Regression with softmax for multi-class classification
- Evaluation using Accuracy, Confusion Matrix, and Classification Report
- Custom prediction function to test emotion from raw input

##  Getting Started

1. Clone this repository or download the `.ipynb` file
2. Place the following datasets in the same folder:
   - `training.csv`
   - `validation.csv`
   - `test.csv`
3. Open the notebook in Jupyter or Google Colab
4. Run all cells step by step to train and evaluate the model

## Sample Usage

```python
print(predict_emotion("I am feeling amazing today!"))
# Output: Predicted Emotion -> Label: 1 that is labeled as joy
