# Spring Boot Security with Thymeleaf

This project demonstrates a basic **Spring Boot** web application with **Spring Security** integrated, using **Thymeleaf** templates for the front-end. The application allows user authentication, registration, and role-based access control. It utilizes Thymeleaf fragments to manage reusable sections like the header, footer, and tables for displaying roles and users. The main features include login, registration, user profile display, and role-based page access.

## Deployment:
https://springsecurity-production-a49d.up.railway.app/

## Features:
- **User Authentication**: Users can log in with their credentials (username and password).
- **Registration**: Users can create a new account by providing a username, first name, last name, email, and password.
- **Role-based Access Control**: Pages and elements are displayed based on user roles.
- **Fragments**: Common page sections (header, footer, roles table) are reused across multiple templates.
- **Dynamic Content**: The page content is dynamically rendered using Thymeleaf expressions and Spring Security tags.

## Pages:
- **Login Page**: Allows users to log in with error handling for failed login attempts.
- **Register Page**: Provides a registration form and feedback about the registration process (success/failure).
- **Home Page**: Displays authenticated user information like username, roles, and email address.
- **Admin Page**: Only accessible to users with the `ADMIN` role, displaying user management features like user lists and roles.

## Technologies Used:
- **Spring Boot**: Backend framework for building the application.
- **Spring Security**: Provides authentication and authorization features.
- **Thymeleaf**: Templating engine for rendering dynamic HTML pages.
- **Bootstrap**: For basic styling of the pages.
