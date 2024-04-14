## Loan Eligibility Prediction with Machine Learning and Streamlit

This repository implements a machine learning model to predict loan eligibility and deploys it as a user-friendly web application using Streamlit.

**Requirements:**

* Python 3.x (with libraries like pandas, NumPy, scikit-learn, and streamlit)

**Getting Started:**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/subramani2002/Streamlit-App-for-Loan-Eligibility-Prediction-using-ML.git
   ```

2. **Install dependencies:**

   ```bash
   cd Streamlit-App-for-Loan-Eligibility-Prediction-using-ML
   pip install -r requirements.txt
   ```

3. **Replace `loan_model.pkl` (optional):**

   If you have your own trained model for loan eligibility prediction, replace `loan_model.pkl` with your model file. Ensure the features used for prediction in `main.py` match the features your model was built on.

4. **Run the application:**

   ```bash
   streamlit run main.py
   ```

   This will launch the web app in your default browser, typically at `http://localhost:8501`.

**Description:**

The `main.py` script uses Streamlit to create a web interface where users can enter loan application details. These details are preprocessed before being fed to the loaded machine learning model (`loan_model.pkl`). The model predicts loan eligibility, and the prediction is displayed on the web page.

**Customization:**

* Modify `main.py` to customize the web interface:
    * Add input fields for additional loan application details.
    * Style components for a better user experience.
    * Provide more informative feedback based on the prediction.

**Demo**
![Screenshot 2024-04-14 195454](https://github.com/subramani2002/Streamlit-App-for-Loan-Eligibility-Prediction-using-ML/assets/67220838/d29f6622-a3d7-4c1f-b5c1-b4af1f4efd6a)
![Screenshot 2024-04-14 195519](https:/![Screenshot 2024-04-14 195539](https://github.com/subramani2002/Streamlit-App-for-Loan-Eligibility-Prediction-using-ML/assets/67220838/de05cb80-a534-445b-89d7-08b6fe2c1df5)
/github.com/subramani2002/Streamlit-App-for-Loan-Eligibility-Prediction-using-ML/assets/67220838/661ced9c-bb4a-4658-b4c0-a820721a8076)
