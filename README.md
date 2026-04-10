# Hotel-Management-System
.
This program is a simple Hotel Management System written in Python.

It uses a class called Hotel to manage rooms, bookings, check-in, and check-out operations.

At the start, the system creates three rooms (101, 102, 103) with different types (Single, Double, Suite), each having a price and an “Available” status.

The program stores all room details in a dictionary called rooms, and all booking information in another dictionary called bookings.

The display_rooms() function shows all available rooms along with their type, price, and current status.

The book_room() function allows a customer to book a room if it is available. It stores the customer name, number of days, and booking details, and changes the room status to “Booked”.

The check_in() function records the current date and time when a customer checks into a booked room using datetime.now().

The check_out() function calculates the total bill based on number of days and room price. It also records the check-out time, displays the final bill details, and makes the room available again.

If a room is not booked or an invalid room number is entered, the system shows an error message.

The main program runs in a loop and shows a menu with options: View Rooms, Book Room, Check-In, Check-Out, and Exit.

The user selects an option by entering a number, and the corresponding function is executed.

The system keeps running until the user chooses option 5 to exit.

Overall, this project simulates a basic real-world hotel booking system using object-oriented programming in Python.
