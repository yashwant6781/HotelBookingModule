Hotel Booking System Module
Overview
The Hotel Booking System module is designed to facilitate the booking process for hotels. It provides functionalities for searching available rooms, booking rooms, and managing reservations. This module can be integrated into larger hotel management systems or used as a standalone application.

Features
Room Search: Search for available rooms based on criteria such as dates, number of guests, and room type.
Booking: Book rooms and manage reservations.
Payment Integration: Integrate with payment gateways for processing payments.
User Management: Handle user registration, login, and profile management.
Admin Panel: Admin functionalities for managing rooms, rates, and reservations.


User - Developed SignUp and SignIn feature with JWT token implementation and Spring Security.
Property  - Property Owner can add ,Update, delete, List the Property that he is managing. Also all Property Images were Stored in S3 Amazon Service.
Review  - User can Leave Review for a Particular property & have used Authentication principal concept to find current user logged in.
Favorite  - This feature allows users to shortlist the property so that he can refer to that in future.
Third Party API - Integrated Third party API like SMS, Email, PDF etc.
Booking - Once the user performs booking for a particular property SMS/Email confirmation with PDF link would shared with them.
O Auth - User could login with Gmail.
OTP - A user when updates the password OTP would be sent to his registered email/mobile.
Implemented Pagination & Sorting.

Developed Several Rest API end points in the project.
Performed Exception Handling and Spring Validation in the project,
Developed Several Controller, repository, Services layer in the project.
Developed Entity classes as per ER diagram with required Mapping like One to One, One to Many, Many to one ,Many to Many.
Performed Debugging to understand & fix defects.
Testing the API using Postman/Swagger
Preparing API Documentation.
