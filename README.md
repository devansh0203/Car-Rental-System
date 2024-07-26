# Car Rental System

Welcome to the Car Rental System, a simple console-based application for renting and returning cars. This project is implemented in Java and provides basic functionalities for managing a car rental service.

## Features

- Add cars to the rental system
- Add customers to the rental system
- Rent cars to customers
- Return rented cars
- Calculate rental price based on the number of days
- Display rental information

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or later
- A Java IDE or a text editor with Java support (e.g., IntelliJ IDEA, Eclipse, VSCode)

### Running the Application

1. **Clone the repository:**
    ```sh
    git clone https://github.com/devansh0203/car-rental-system.git
    cd car-rental-system
    ```

2. **Compile the Java files:**
    ```sh
    javac Main.java
    ```

3. **Run the application:**
    ```sh
    java Main
    ```

### Application Flow

1. **Main Menu:**
    - Rent a Car
    - Return a Car
    - Exit

2. **Rent a Car:**
    - Enter your name
    - Choose from the available cars
    - Enter the number of rental days
    - Confirm the rental

3. **Return a Car:**
    - Enter the car ID to return

## Code Structure

- `Car` class: Represents a car with details like car ID, brand, model, base price per day, and availability status.
- `Customer` class: Represents a customer with details like customer ID and name.
- `Rental` class: Represents a rental transaction with details like the car, customer, and rental days.
- `CarRentalSystem` class: Manages the cars, customers, and rentals. Provides functionalities to add cars and customers, rent and return cars, and handle the main menu operations.
- `Main` class: Entry point of the application. Initializes the `CarRentalSystem` and starts the menu.

## Usage Example

Here's an example of how to use the Car Rental System:

1. **Renting a Car:**
    ```
    ===== Car Rental System =====
    1. Rent a Car
    2. Return a Car
    3. Exit
    Enter your choice: 1

    == Rent a Car ==

    Enter your name: John Doe

    Available Cars:
    C001 - Toyota Camry
    C002 - Honda Accord
    C003 - Mahindra Thar

    Enter the car ID you want to rent: C001
    Enter the number of days for rental: 3

    == Rental Information ==

    Customer ID: CUS1
    Customer Name: John Doe
    Car: Toyota Camry
    Rental Days: 3
    Total Price: $180.00

    Confirm rental (Y/N): Y

    Car rented successfully.
    ```

2. **Returning a Car:**
    ```
    ===== Car Rental System =====
    1. Rent a Car
    2. Return a Car
    3. Exit
    Enter your choice: 2

    == Return a Car ==

    Enter the car ID you want to return: C001

    Car returned successfully by John Doe.
    ```

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please create an issue or submit a pull request.

---

Thank you for using the Car Rental System!

