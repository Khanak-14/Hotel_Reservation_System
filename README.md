# Hotel_Reservation_System

Hotel Booking Application

Welcome to the Hotel Booking Application, a customized version built with Python and the Streamlit framework. This application allows users to seamlessly book hotel rooms while integrating with a database for efficient management. Below are the key features and modifications made to ensure a unique and personalized experience:

Key Features:
User-Friendly Booking Process:

Streamlined input for check-in and check-out dates, personal details, and room selection.
Comprehensive validation of user inputs for enhanced data integrity.
Room Details Display:

Presentation of available rooms with detailed information, including room number, description, beds, air conditioning, and pricing.
Easy selection of rooms by entering the room number.
Booking Confirmation:

Confirmation of bookings with a detailed summary of customer information and room details.
Display of customer ID, name, check-in/out dates, phone number, and room amount.
Billing Information:

Provision of billing details after the stay, ensuring a transparent and convenient payment process.
Database Integration:
The application seamlessly interacts with a MySQL database, utilizing the following tables:

customerdetails: Stores comprehensive customer information.
room, roomtype: Manages room-related details, including type, size, and amenities.
roomservice, items: Facilitates room service orders and item information.
bookingdetails: Tracks booking information.
employees, roles: Manages employee records and roles.
Customized Backend Functionality for Staff:
Check-Out Price Calculation:

Management staff can calculate and display the amount to be paid by a customer at check-out by entering the customer ID.
Room Service Ticket Addition:

Staff can add a new room service ticket for a customer by entering item ID, quantity, and customer ID.
Detailed Information Displays:

Comprehensive tables presenting details of available items, employees, employee roles, rooms, room types, bookings, customers, and orders.
How to Run:
To run the application, execute Main_Page.py using streamlit run Main_Page.py in the command prompt within the project directory. Ensure the MySQL server is running and that the database connection details in DatabaseManager.py are correctly configured.

Customization Steps:
Change Project Structure:
Rename directories and files to make the project less recognizable.
Modify File Contents:
Alter variable names, comments, and string literals throughout the code.
Update Descriptions and Comments:
Customize comments, docstrings, and descriptive text.
Customize UI:
Enhance or modify the graphical elements to give a unique appearance.
Change Database Configuration:
Update the database connection details in DatabaseManager.py to match your database setup.
