Vehicle Rental Management System
Project Overview
The Vehicle Rental Management System is a menu-driven Python application that demonstrates Object-Oriented Programming (OOP). It allows users to register vehicles, view vehicle availability, rent vehicles to customers, return vehicles, calculate rental charges, and view rental history.

The project uses JSON files to store vehicle and rental information between program runs.
Objectives
- Register vehicles with an ID, model, daily rental rate, and seating capacity.
- View vehicle details and availability.
- Rent available vehicles to customers.
- Return rented vehicles and update their status.
- Calculate rental charges based on rental duration.
- View rental records.
- Save and load data using JSON files.
- Handle invalid inputs and common file errors.
Features
1. Add Vehicle
Register a vehicle with its ID, model, daily rate, and seating capacity.
2. View All Vehicles
Display registered vehicles and whether each is available or rented.
3. Rent Vehicle
Select an available vehicle, enter the customer's name and rental duration, and calculate the rental charge.
4. Return Vehicle
Mark a rented vehicle as returned and make it available again.
5. View Rental Records
Display rental IDs, vehicle IDs, customer names, rental duration, charges, and rental status.
6. JSON Storage
The application reads and writes data using vehicles.json and rentals.json.
OOP Concepts Demonstrated
- Classes and Objects: Rental, Vehicle, Car, and RentalManager.
- Encapsulation: Private attributes using double underscores and getter/setter methods.
- Inheritance: Car inherits from Vehicle.
- Abstraction: Rental is an abstract base class using ABC and @abstractmethod.
- Method Overriding: Car overrides display_vehicle() to display seating capacity.
Other Python Concepts
- while loop for the menu-driven program.
- for loops to search and display records.
- Conditional statements (if, elif, and else).
- File handling with open() and with.
- JSON operations with json.load() and json.dump().
- Exception handling with try and except.
Technologies Used
- Python 3
- Jupyter Notebook
- JSON
- Standard library modules: json, os, and abc
No third-party packages are required.
How to Run
1. Download or clone the repository.
2. Open Vehicle_Rental_Management_System.ipynb in Jupyter Notebook.
3. Run the cell containing the project code.
4. Follow the on-screen menu.
Menu Options
1. Add Vehicle
2. View All Vehicles
3. Rent Vehicle
4. Return Vehicle
5. View Rental Records
6. Exit
Rental Charge Calculation
Total Rental Charge = Daily Rental Rate × Number of Rental Days
Example: A vehicle costing ₹1,500 per day rented for 2 days costs ₹3,000.
Project Structure
Project_08_Vehicle_Rental/
├── Vehicle_Rental_Management_System.ipynb
├── README.md
├── vehicles.json       # Created when vehicle data is saved
└── rentals.json        # Created when rental data is saved
The JSON files are generated in the program's current working directory when data is saved. Keep these files to retain saved records.
Future Improvements
- Support additional vehicle types.
- Ensure every vehicle-specific field, including seating capacity, is saved and restored.
- Generate unique rental IDs based on existing records.
- Record actual rental and return dates.
- Add customer contact details.
- Add automated tests or a graphical user interface.
Author
Shriya Verma
