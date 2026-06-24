# Student Placement Predictor

A simple, end-to-end machine learning project that predicts whether a student will be successfully placed based on their CGPA and IQ scores. 

This project serves as a foundational exercise in the complete machine learning lifecycle, from data preprocessing to model serialization.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Scikit-learn, Matplotlib
* **Environment:** Jupyter Notebook
* **Algorithm:** Logistic Regression

## Project Structure
* `ml-toy-project.ipynb`: The core notebook containing data exploration, preprocessing, model training, and evaluation.
* `placement.csv`: The dataset containing student CGPA, IQ, and placement status (1 = Placed, 0 = Not Placed).
* `model.pkl`: The serialized Logistic Regression model, exported and ready for deployment.

## How It Works
1. **Data Preprocessing:** The data is cleaned and scaled using `StandardScaler` to ensure the algorithm evaluates CGPA and IQ on a level playing field.
2. **Model Training:** A Logistic Regression model analyzes the historical data to find the optimal decision boundary between students who were placed and those who were not.
3. **Evaluation:** The model is tested against hidden data, achieving a 90% accuracy rate in its predictions.

## Getting Started
To run this project locally:
1. Clone this repository to your local machine.
2. Ensure you have Python installed, along with `pandas`, `scikit-learn`, and `matplotlib`.
3. Open `ml-toy-project.ipynb` in Jupyter Notebook and run the cells sequentially.

## Acknowledgments
This project was built as a learning exercise by following the excellent **"100 Days of Machine Learning"** series by CampusX. Specifically, this implementation is based on [Day 13: End to End Toy Project](https://www.youtube.com/watch?v=dr7z7a_8lQw).
