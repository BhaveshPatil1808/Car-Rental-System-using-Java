# 🚗 Car Rental System (Java CLI Application)

This is a **console-based Car Rental System** built in **Java**, allowing users to rent and return cars with dynamic pricing based on rental days. The system simulates a basic rental service with customer and vehicle management, demonstrating Object-Oriented Programming principles.

## 📌 Features

- 📋 Register customer during rental
- 🚙 Display available cars with real-time availability
- 📆 Calculate total price based on days and car base rate
- 🔄 Return a car and update availability
- 📦 Maintains rental records internally using collections

## 🛠️ Technologies Used

- Java (JDK 8+)
- OOP (Object-Oriented Programming)
- Command-Line Interface (CLI)

## 🚀 How to Run

1. Clone/download the repository.
2. Compile and run the `Main.java` file:

```bash
javac Main.java
java CarRental.Main


📁 File Structure

CarRentalSystem/
└── CarRental/
    ├── Main.java             # Contains main logic and menu
    ├── Car.java              # Car entity class
    ├── Customer.java         # Customer entity class
    └── Rental.java           # Rental association class






🎮 Sample



===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==
Enter your name: John

Available Cars:
C001 - Toyota Camry
C002 - Honda Accord
C003 - Mahindra Thar

Enter the car ID you want to rent: C003
Enter the number of days for rental: 2

== Rental Information ==
Customer ID: CUS1
Customer Name: John
Car: Mahindra Thar
Rental Days: 2
Total Price: $300.00

Confirm rental (Y/N): Y
Car rented successfully.
