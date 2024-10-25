# Car-Rental-System

A console-based Java application simulating a car rental system, allowing users to rent and return cars and providing rental cost calculations. This project showcases the use of object-oriented programming concepts, including classes, objects, encapsulation, and basic input/output in Java.

Features
Add New Cars: Define and add cars with unique IDs, brands, models, and daily rental prices.
Register Customers: Register a new customer with a unique ID when renting a car.
Rent Cars: Allow customers to select an available car and specify the number of days they wish to rent.
Return Cars: Allow customers to return rented cars and remove them from the rental list.
Calculate Rental Price: Automatically calculate the total rental cost based on the daily rate and rental days.
Class Structure
Car: Represents a car with attributes such as ID, brand, model, price per day, and availability status.
Customer: Stores customer details, including a unique ID and name.
Rental: Tracks rental details such as car, customer, and rental days.
CarRentalSystem: Manages car rentals and returns, customer registrations, and provides a menu-driven interface.
Prerequisites
Java Development Kit (JDK) 8 or higher
Usage
Clone the repository or download the files.

Compile and run the program in a Java environment.

bash
Copy code
javac Main.java
java Main
The console will display a menu with options to rent, return, or exit.

Program Flow
Run the Program: Start the program, and the main menu appears.
Rent a Car: Choose "Rent a Car" to view available cars, then enter your name, car ID, and rental duration. The system calculates and displays the rental price.
Return a Car: Select "Return a Car" and enter the car ID to return the vehicle and free it up for others.
Exit: Choose "Exit" to end the program.
Example
mathematica
Copy code
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
Customization
Add Cars: Additional cars can be added to the inventory in the Main class.
Modify Pricing: Adjust the basePricePerDay in the Car instances for different rates.
Expand Customer Information: Enhance the Customer class to include more information, like contact details.
License
This project is licensed under the MIT License.

Author
Developed by Mayank Kumar Piyush.
