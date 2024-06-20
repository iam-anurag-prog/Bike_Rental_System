# Bike Rental System
A simple Bike Rental System implemented in Python, allowing users to view available bikes and rent bikes.

Features
Display Bike Stock: View the total number of bikes available for rent.
Rent Bikes: Rent a specified number of bikes, with validation for non-positive quantities and quantities exceeding available stock.
Usage
Display Stocks: Check the number of bikes currently available for rent.
Rent a Bike: Rent bikes by specifying the quantity, with the system providing the total cost and updating the stock.
Installation
Ensure you have Python installed on your system. You can download Python from python.org.

Running the Program
Clone this repository or download the Bike_Rental_System.py file.
Open a terminal or command prompt.
Navigate to the directory where Bike_Rental_System.py is located.
Run the script using Python:
sh
Copy code
python Bike_Rental_System.py
Example
Here's a simple example of how the system works:

plaintext
Copy code
1. Display Stocks
2. Rent a Bike
3. Exit

Enter your choice: 1
Total Bikes: 100

Enter your choice: 2
Enter the Quantity: 5
Total Price: 500
Total Bikes: 95

Enter your choice: 3
Code Explanation
bikeshop Class:

__init__(self, stock): Initializes the bike shop with a given stock of bikes.
displayBike(self): Displays the total number of available bikes.
rentForBike(self, q): Rents a specified quantity of bikes, with checks for valid quantities.
Main Loop:

Continuously prompts the user for input to display stocks, rent bikes, or exit the system.
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for improvements and new features.
