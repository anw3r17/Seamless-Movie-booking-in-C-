The movie booking project in C is a simple application that facilitates the management of seats in a theater. The project is structured around a double-linked list, where each node represents a seat and stores information such as seatnumber and name of the person who has booked the seat.
The primary functionalities include adding seats, booking seats, unbooking seats, and displaying the current status of all seats.

Key Components:

1. **Node:**
   - The project defines a structure called `node` with the following attributes:
      - `int seatnumber`: Represents a unique number for each seat.
      - `char name[100]`: Stores the name of the person who has booked the seat.
      - `struct node *prev`: Which will point to the previous node in the double-linked list.
      - `struct node *next`: Which will point to the next node in the double-linked list.

2. **Functions:**
   - `addseat(int seatnumber)`: It adds a new seat to the linked list.
   - `bookseat(int seatnumber, const char* name)`: It books a seat by updating the name against the given seat number.
   - `unbookseat(int seatnumber)`: It unbooks a seat by resetting the name against the given seat number.
   - `displayseats()`: It displays the current status of all the seats in the Theater.

3. **Main Program:**
   - The `main` function initializes the linked list with a specified number of seats and presents a user interface to interact with the theater booking system.
   - Users can choose to book seats, unbook seats, display the current seat status, or exit the program.

(This project was made along with some friends as a project for C Programming)
