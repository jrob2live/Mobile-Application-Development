Investment Growth Calculator (Outline Report)

I. Project Description
A. App Summary
The Investment Growth Calculator is an Android mobile application that allows users to estimate the future value of an investment based on an initial amount, annual interest rate, and time period.
B. Target Users
Beginner investors, students, and individuals interested in basic financial planning.
C. Goal of the App
To provide a simple and intuitive way for users to understand compound growth over time.

II. Problem Addressing
A. Problem Statement
Many individuals struggle to understand how investments grow over time and lack access to simple tools for estimating returns.
B. Why This Matters
Understanding compound interest is essential for financial literacy and long-term planning.
C. Success Criteria
The app correctly calculates and displays investment growth based on user inputs with clear and readable results.

III. Platform
A. Operating System
Android 
B. Device Support
Android smartphones
C. Development Tools
Android Studio using Kotlin

IV. Front-End / Back-End Support
A. Front-End
1.	XML-based user interface
2.	Input fields for investment amount, interest rate, and years
3.	Calculate button and result display section
B. Back-End / Data Handling
1.	Business logic handled within the app
2.	No external database required
3.	Optional use of SharedPreferences to save last entered values

V. Functionality
A. Core Features
1.	User inputs initial investment amount
2.	User inputs annual interest rate
3.	User inputs investment duration in years
4.	App calculates compound interest
5.	App displays final investment value
B. Inputs and Outputs
•	Inputs: numeric values entered by the user
•	Output: calculated investment total displayed on screen
C. Validation
1.	Prevent empty input fields
2.	Ensure numeric values are valid
3.	Display error messages when input is incorrect
D. Optional Enhancements
1.	Year-by-year breakdown
2.	Simple graph of investment growth

VI. Design (Wireframes)
A. Home Screen
•	Title at top
•	Input fields stacked vertically
•	Calculate button below inputs
B. Results Section
•	Displays total investment value
•	Optional yearly breakdown list
C. Navigation Flow
Single-screen application with dynamic result updates

