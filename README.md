credit-risk-model-ml-project
Lauki Finance: Credit Risk Modelling
This project implements a credit risk modeling web application using Streamlit. The app collects key financial and personal details about loan applicants, computes metrics such as loan-to-income ratio, and predicts the risk of default. The result includes the default probability, credit score, and rating.

Features
Collects user input through an interactive interface for key financial metrics.
Computes Loan-to-Income Ratio on the fly.
Predicts default probability, credit score, and credit rating based on user inputs.
Simple and user-friendly Streamlit interface.
Setup Instructions
Prerequisites
Make sure you have the following installed:

Python 3.7+
Streamlit
Other dependencies listed in requirements.txt
Installation
Clone the repository

bash
Copy code
git clone https://github.com/kapilcharbhare/Credit-risk-model-with-machine-learning.git
cd credit-risk-modelling
Install dependencies

bash
Copy code
pip install -r requirements.txt
Ensure prediction_helper.py is correctly linked
This file should contain the logic for the predict() function, responsible for returning the default probability, credit score, and rating.

Usage
Run the Streamlit app

bash
Copy code
streamlit run app.py
Open the browser and navigate to the URL provided (e.g., http://localhost:8501).

Input Details:

Age, Income, Loan Amount, Loan Tenure (in months)
Avg Days Past Due (DPD), Delinquency Ratio, Credit Utilization Ratio
Residence Type, Loan Purpose, Loan Type
Number of open loan accounts
Click the "Calculate Risk" button to get the predicted results.

File Structure
bash
Copy code
credit-risk-modelling/
├── app.py                   # Main Streamlit application code
├── prediction_helper.py     # Prediction logic (ensure predict() is defined here)
├── requirements.txt         # List of dependencies
└── README.md                # Documentation (this file)
Example Output
Default Probability: 12.34%
Credit Score: 750
Rating: A+
Requirements
Ensure the following libraries are listed in your requirements.txt:

text
Copy code
streamlit>=1.25
pandas
numpy
Contributing
Feel free to submit a pull request or raise an issue for improvements and suggestions.

License
This project is licensed under the MIT License.

Acknowledgments
Special thanks to Codebasics for inspiration from the ML course.

Contact
For questions or support, contact me at charbharekapil@gmail.com.
