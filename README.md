# LOAN-MANAGEMENT-SYSTEM-FRONT-END

Frontend ReadMe
Project Overview
This is the frontend repository for the Loan Management System developed for Precious Investment Co. Ltd. The frontend is built using HTML, CSS, and JavaScript. It provides a user-friendly interface for managing loan applications, user authentication, and displaying company information.

Technologies Used
Frontend:

HTML

CSS

JavaScript

Backend:

FASTAPI (Python)

Database:

MongoDB

Features
User Authentication:

Login and registration functionality.

Session management using localStorage.

Loan Application Management:

Submit loan applications with borrower and guarantor details.

Upload supporting documents (e.g., passport images).

View and update loan application status.

Dynamic Form Behavior:

Auto-fill related fields to reduce redundancy.

Calculate loan details (e.g., total loan amount, repayment dates) dynamically.

About Us Page:

Displays company information, mission, vision, values, and contact details.

Responsive Design:

Ensures the application is accessible on various devices (desktop, tablet, mobile).

Project Structure
Copy
frontend/
├── css/
│   ├── styles.css          # Main stylesheet
│   └── kutuhusu.css        # Styles for the About Us page
├── js/
│   └── script.js           # Main JavaScript file for dynamic behavior
├── pages/
│   ├── dashboard.html      # Dashboard page
│   ├── taarifa.html        # Loan application form
│   ├── kutuhusu.html       # About Us page
│   ├── register.html       # User registration page
│   ├── login.html          # User login page
│   └── logout.html         # Logout functionality
├── index.html              # Main entry point
└── README.md               # Project documentation
Setup Instructions
Clone the Repository:

bash
Copy
git clone https://github.com/George-Raymond/loan-management-system-frontend.git
cd loan-management-system-frontend
Run the Application:

Open the index.html file in your browser to access the application.

Backend Integration:

Ensure the backend server (FASTAPI) is running and accessible.

Update the API base URL in the JavaScript files if necessary.

Usage
User Authentication:

Register a new user or log in using existing credentials.

Access token and username are stored in localStorage for session management.

Loan Application:

Navigate to the Taarifa page to submit a loan application.

Fill in borrower, guarantor, and loan details.

Upload required documents (e.g., passport images).

About Us:

Visit the Kutuhusu page to learn more about the company.

Logout:

Click the Logout link to end the session.

API Endpoints
The frontend interacts with the following backend API endpoints:

Endpoint	Method	Description
/register	POST	Register a new user
/token	POST	Authenticate and obtain access token
/loan-application	POST	Submit a loan application
/loan-applications	GET	Retrieve all loan applications
/loan-applications/{loan_id}	GET	Retrieve a specific loan application
/files/{file_id}	GET	Retrieve uploaded files
Contributing
Contributions are welcome! Follow these steps to contribute:

Fork the repository.

Create a new branch for your feature or bugfix.

Commit your changes with clear and descriptive messages.

Push your changes to your forked repository.

Submit a pull request to the main repository.

Contact
GitHub: George-Raymond

Email: raysgeorge429@gmail.com

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Font Awesome for icons.

FASTAPI and MongoDB for backend and database support.
