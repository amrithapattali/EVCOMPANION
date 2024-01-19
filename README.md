# EV COMPANION APPLICATION 

 This app, built on the Django API framework, provides a seamless interface for users to monitor, control, and optimize their electric vehicles' performance. Designed RESTful APIs for seamless communication between the server and the client-side application, ensuring efficient data retrieval and updates.

# Technologies uesd:
Languages used :- Python
API Configuration: REST APIs
Authentication:JWT (JSON Web Token) authentication
Framework:- Django
Database:- sqlite3
Tools used :- VS code

# Key Features

Data Models: Includes models for representing key EV entities, such as:
Vehicle info
Charging stations
Useraccounts
Payment integration


User Authentication and Authorization:

Implement secure user authentication using Django's built-in authentication system.
Set up authorization levels for different user roles, such as regular users and admin.

User Accounts:

The "User Accounts" feature forms the foundation of the EV Companion App, allowing users to create and manage their profiles. Users can register using their email and manage their electric vehicle-related data.

Vehicle Info:

The "Vehicle Info" feature provides users with comprehensive information about their electric vehicles. Users can register and manage details such as make, model, year of manufacture

Charging Station :

The "Charging Station" feature enables users to find nearby charging stations easily.Users can search for charging stations based on location, Address,contact info

Payment Integration:

The "Payment Integration" feature simplifies the charging experience by allowing users to make secure payments directly through the app.

# Running the Application:

    Clone the repository.
	 
    Create a virtual environment and activate it (python3 -m venv venv && source venv/bin/activate).
	 
    Install required dependencies (pip install -r requirements.txt).
	 
    Run database migrations (python manage.py makemigrations && python manage.py migrate).
	 
    Create a superuser (python manage.py createsuperuser).
	 
    Start the development server (python manage.py runserver).

