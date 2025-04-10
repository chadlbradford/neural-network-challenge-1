
# Student Loan Risk Prediction with Deep Learning

This project leverages a neural network to predict the likelihood of student loan repayment using a structured dataset. It also explores how a recommendation system could be developed to provide loan product suggestions tailored to student profiles.

---

## 📊 Project Overview

The objective of this project is to:
- Preprocess a real-world dataset related to student loans.
- Build and train a binary classification model using a deep learning approach.
- Evaluate the model’s performance.
- Save and reload the model for later use.
- Discuss the design of a potential recommendation system.

---

## 🧠 Model Details

- **Architecture**: A Sequential model using dense layers with ReLU and sigmoid activations.
- **Loss Function**: `binary_crossentropy` — suitable for binary classification.
- **Optimizer**: `adam` — a robust gradient descent optimization technique.
- **Evaluation Metric**: `accuracy`.

---

## 🧪 Key Steps

1. **Data Loading and Preprocessing**
    - Read CSV into a DataFrame
    - Clean and scale numerical features
    - Split into training and testing sets

2. **Model Training**
    - Define the neural network architecture
    - Compile and fit the model on training data

3. **Evaluation**
    - Evaluate performance using test data
    - Print classification metrics

4. **Saving & Loading**
    - Save the trained model in both `.h5` and `.keras` formats
    - Reload the model for predictions or reuse

5. **Recommendation System Concept**
    - Described what data would be required
    - Chose a content-based filtering strategy
    - Outlined real-world development challenges

---

## 📁 Files

- `student_loans_with_deep_learning.ipynb`: Main notebook with all steps implemented.
- `student_loan_model.keras`: Saved Keras model.
- `student_loan_recommendation_system.md`: Markdown summary of the recommendation system Q&A.

---

## 📌 How to Use

1. Clone or download this repo.
2. Open the notebook in JupyterLab or VSCode.
3. Run each cell sequentially to process the data, train the model, and evaluate predictions.
4. Review the classification results and recommendation system strategy.

---

## 📚 References

Initial code was generated and vetted through the combined means of self-sourced code, course examples, and LLMs.

---

## 🛠️ Requirements

- Python 3.7+
- TensorFlow 2.x
- Pandas
- scikit-learn
- Jupyter Notebook or compatible IDE

---

## 💡 Future Improvements

- Use more advanced architectures like dropout or batch normalization.
- Add SHAP or LIME for explainability.
- Implement an actual recommendation engine and test against user profiles.

