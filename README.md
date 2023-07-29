# Hotel_Management
This Java code implements a simple Hotel Management System that allows users to book and manage rooms, order food, and view room details and availability. The program is designed to handle both single rooms and double rooms, each with different features and prices.

Features:

Room Details: The program displays details about the different types of rooms available, including luxury and deluxe double rooms, as well as luxury and deluxe single rooms. It provides information such as the number of beds, AC availability, free breakfast, and the charge per day for each type of room.

Room Availability: Users can check the availability of rooms for each category (luxury/deluxe, single/double) and see the number of rooms currently unoccupied.

Room Booking: Users can book available rooms by providing their details, such as name, contact number, and gender. For double rooms, the details of both customers sharing the room are collected.

Food Ordering: Guests can order food items from a menu. The program provides a list of food items with corresponding prices. Users can select the desired food items and their quantities. The food charges are added to the total bill.

Room Checkout: Guests can check out from their occupied rooms. Upon checkout, the program calculates the total bill, including the room charge and any ordered food items.

Data Persistence: The program uses serialization to save the hotel's current state to a file named "backup." This feature ensures that the data remains available even if the program is closed and later reopened.




Usage:

To use the Hotel Management System, users can run the Java program. The program will present a menu of options to choose from, and the user can select the desired action by entering the corresponding number. Users can book rooms, order food, check availability, and view room details as needed. The program also provides an option to check out from a room when the guest's stay is complete.
