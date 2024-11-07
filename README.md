# Mortgage_Repayments_Calculator

   Overview

    This project is a Streamlit web application designed to help users calculate mortgage repayment details based on their input values for home value, deposit,          interest rate, and loan term. It provides insights into the monthly repayment amount, total payments, and total interest over the loan period, as well as a           detailed payment schedule.


Features

	•	Input Parameters: Users can input home value, deposit, interest rate, and loan term (in years) to calculate mortgage details.
	•	Monthly Repayment Calculation: Calculates monthly repayments based on user inputs.
	•	Total Repayment and Interest: Provides a breakdown of the total repayment amount and total interest paid over the loan term.
	•	Payment Schedule: Displays a month-by-month breakdown of principal and interest payments, as well as the remaining balance.

Technologies Used

	•	Python 3.x: Core programming language.
	•	Streamlit: Framework for creating the interactive web interface.
	•	Pandas: For handling data and generating the payment schedule.
	•	Matplotlib: Optional, can be used to visualize the payment schedule if desired.


Getting Started

  Prerequisites

   Ensure you have Python 3.x, Streamlit, Pandas, and Matplotlib installed. Install them via pip:

       pip install pandas
       pip install streamlit
       pip install matplotlib

Installation

	  1.	Clone this repository:
           git clone https://github.com/Shivesh-22/mortgage-calculator.git

    2.	Navigate to the project directory:
           cd mortgage-calculator

Running the App

  To run the Streamlit app, use the following command:
  
     streamlit run main.py
     
  This will open the app in your web browser, where you can enter the required parameters and view repayment details.


How to Use

	1.	Open the app and input values for:
	•	Home Value: Total value of the property.
	•	Deposit: Amount paid upfront.
	•	Interest Rate: Annual mortgage interest rate (in percentage).
	•	Loan Term: Duration of the loan (in years).
	2.	View the calculated values for monthly repayments, total repayments, and total interest on the main page.
	3.	Explore the detailed payment schedule, including the breakdown of monthly payments, interest, and remaining balance.

Code Structure

	•	main.py: Main script containing the mortgage calculation logic, user input handling, and repayment schedule generation.
