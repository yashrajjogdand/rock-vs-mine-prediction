# Rock vs Mine Prediction Using Machine Learning

## Project Overview
This project uses Machine Learning to classify underwater objects as either **Rock (R)** or **Mine (M)** based on sonar signal data. A Logistic Regression model is trained on sonar measurements to identify the object's class.

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Google Colab

## Dataset
- Total records: 208
- Features: 60 sonar signal attributes
- Target variable: Object classification (Rock or Mine)

## Project Workflow
1. Import the required Python libraries.
2. Load and explore the sonar dataset.
3. Perform data analysis and separate features from labels.
4. Split the dataset into training and testing sets.
5. Train a Logistic Regression classification model.
6. Evaluate the model using accuracy score.
7. Build a prediction system for new sonar data.

## Model Performance
- Training Accuracy: 83.42%
- Testing Accuracy: 76.19%
- Algorithm: Logistic Regression

*Note: The accuracy values are based on the current train-test split and may vary with different data splits.*

## Example Prediction
The model predicts whether a sonar signal represents a rock or a mine.

Example output:
`The object is a mine`

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   `pip install numpy pandas scikit-learn`
3. Place the sonar dataset CSV file in the appropriate location.
4. Open `Rock_vs_Mine_prediction.ipynb` in Google Colab or Jupyter Notebook.
5. Run all cells to train the model and generate predictions.

## Learning Outcomes
- Data collection and preprocessing
- Exploratory data analysis
- Training and testing a classification model
- Model evaluation using accuracy score
- Making predictions on new input data

## Future Improvements
- Experiment with other classification algorithms.
- Improve model performance through hyperparameter tuning.
- Evaluate the model using precision, recall, F1-score, and a confusion matrix.

## Author
Yashraj Jogdand

Aspiring Data Scientist | Python | SQL | Machine Learning | Data Analytics
