**Library Management System**


**Overview**

The City Library Management System is a web application designed to facilitate the management of a city library. It provides features for both library patrons and administrators to browse, borrow, and return books, as well as  book inventory

**Features**
1. User Registration and Authentication: Users can register for an account and login securely to access library services.
2. Browsing Books: Users can browse the available books in the library and view details such as title, author, and availability.
3. Borrowing Books: Authenticated users can borrow books from the library. The system keeps track of borrowed books and their due dates.
4. Returning Books: Users can return borrowed books to the library.

**Architecture**
1. Backend Framework: The application is built using Flask, a lightweight and flexible web framework for Python.
2. Frontend: HTML templates are rendered using Jinja2, a templating engine for Python. CSS is used for styling, and JavaScript is used for client-side interactivity.
3. Database: The application uses a MySQL database to store information about books, users, and borrowing transactions. SQLAlchemy is used as an ORM (Object- 
   Relational Mapping) tool to interact with the database.
4. Authentication: User authentication is implemented using session-based authentication

**Setup Instructions**
1. Install Python and Flask.
2. Set up a MySQL database server (e.g., using XAMPP).
3. Create a virtual environment and install dependencies from requirements.txt.
4. Run the Flask application (app.py).
5. Access the application in a web browser.

**Contributors** 
1. Isha Deo 
