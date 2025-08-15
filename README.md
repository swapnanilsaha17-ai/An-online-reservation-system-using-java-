 Online Reservation System (Java)

This is a **console-based Online Reservation System implemented in Java.  
It supports user authentication, ticket reservation, and ticket cancellation using an in-memory data structure.  
The program is modular, object-oriented, and easy to extend with GUI or database integration.

---

 Features

- **Login System**
  - Only authorized users can access the system.
  - Default login credentials provided.

- **Ticket Reservation**
  - Input passenger details: name, train number, class type, date of journey, source, and destination.
  - Train name is auto-filled based on train number.
  - Generates a unique **PNR** for each booking.
  - Stores reservations in memory using `ArrayList`.

- **Ticket Cancellation**
  - Search booking by **PNR**.
  - Displays full booking details before cancellation.
  - Confirms before removing the booking.

- **Menu Driven**
  - Simple console menu for navigation.
  - Runs until user chooses to exit.

---

## 🛠 Technologies Used

- **Language**: Java
- **Data Structures**:
  - `ArrayList` for storing reservations
  - `HashMap` for storing user login data
- **OOP Concepts**:
  - Class-based design (`Reservation` and `ReservationSystem`)
  - Encapsulation of reservation details

---

#How to Run

1. **Clone this repository** or download the `ReservationSystem.java` file.

2. **Compile the program**:
   ```bash
   javac ReservationSystem.java
