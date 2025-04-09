# FLASK_Software_Development_
Flask Auth Project - README Instructions
Project Description
This project is a basic Flask web application that implements user authentication using sessions. Users can register, log in, and access a protected dashboard. It includes user-friendly error handling, modular templates, and SQLite as a lightweight database.
How to Set Up and Run the Application
•	1. Clone the Repository:
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
•	2. Create a Virtual Environment:
   python -m venv venv
•	3. Activate the Virtual Environment:
   On Windows:
   venv\Scripts\activate
   On macOS/Linux:
   source venv/bin/activate
•	4. Install Dependencies:
   pip install -r requirements.txt
•	5. Set the Flask App Environment Variable:
   On Windows:
   set FLASK_APP=app.py
   On macOS/Linux:
   export FLASK_APP=app.py
•	6. Run the Application:
   flask run
   Then visit http://127.0.0.1:5000 in your browser.
Dependencies
- Flask – Lightweight web framework
- Werkzeug – Provides secure password hashing
- Jinja2 – Templating engine used by Flask
- SQLite – Built-in Python database for local storage

All dependencies are listed in requirements.txt.
Code Structure and Functionality
your-repo/
├── app.py                # Main application script
├── templates/            # HTML templates
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
├── static/               # Static files (CSS, JS, images)
├── venv/                 # Virtual environment (not pushed to Git)
└── requirements.txt      # Python dependencies
Key Features
•	User Registration: Create a new account with email and password.
•	User Login: Secure login with session management.
•	Protected Routes: Access to dashboard only for authenticated users.
•	Logout: End user session securely.
•	Form Validation: Prevents empty input fields and invalid credentials.

