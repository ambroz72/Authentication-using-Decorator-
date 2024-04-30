Django User Authentication System with Decorator-Based Access Control

This Django project implements a user authentication system with features like signup, login, and logout functionalities.
It ensures secure user authentication and access control for web applications, utilizing decorators for enhanced security.

Features

User Signup: New users can register by providing essential details such as username, email, and password. Duplicate username prevention 
and password matching ensure data integrity.
User Login: Registered users can securely log in using their username and password. Invalid login attempts are handled gracefully with 
appropriate error messages.
User Authentication: Utilizes Django's built-in authentication system for user verification. Only authenticated users can access certain 
pages, enhancing security.
Session Management: Manages user sessions securely using Django's session framework. Users remain authenticated across different pages 
until they choose to log out.
Error Handling: Provides informative error messages to users in case of invalid input, duplicate usernames, or incorrect login credentials,
improving user experience.
User Logout: Allows authenticated users to log out securely, terminating their session and redirecting them to the homepage.
Decorator-Based Access Control: Utilizes Django's login_required decorator for view functions that require authentication. 
This ensures that only authenticated users can access specific pages, enhancing access control and security.
