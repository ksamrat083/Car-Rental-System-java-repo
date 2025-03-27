# Car Rental System

## Overview
This is a simple **Car Rental System** implemented in Java. The system allows customers to rent and return cars through a menu-driven console interface.

## Features
- Add cars to the rental system
- Rent available cars for a specified number of days
- Return rented cars
- Calculate rental cost based on the number of days
- Display rental details

## Technologies Used
- **Java** (Standard Edition)
- **Java Collections Framework** (ArrayList for data storage)
- **Scanner** (for user input handling)

## How to Run
### Prerequisites
- Ensure you have **Java JDK 8 or later** installed.
- Set up the environment variable **JAVA_HOME** if required.

### Steps to Run
1. Clone the repository or download the source code.
   ```sh
   git clone https://github.com/your-username/car-rental-system.git
   cd car-rental-system

## Usage
- The program displays a menu with options to rent a car, return a car, or exit.
- Customers enter their name, select an available car by ID, and specify the rental duration.
- The system calculates the total rental cost and confirms the booking.
- Customers can return a car by entering its ID.

Example Output :-

===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==
Enter your name: John Doe

Available Cars:
C01 - Benz GLE
C02 - Toyota Camry
C03 - Maruti Suzuki Baleno
C04 - Honda Accord
C05 - Mahindra Thar

Enter the car ID you want to rent: C02
Enter the number of days for rental: 3

== Rental Information ==
Customer ID: CUS1
Customer Name: John Doe
Car: Toyota Camry
Rental Days: 3
Total Price: $510.00

Confirm rental (Y/N): Y

Car rented successfully.
