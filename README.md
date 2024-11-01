# Python_Bill_Management_System
This is a basic billing system implemented in Python. The system allows users to add products to a bill, calculate totals, apply discounts, remove items, and print a final bill. This system is useful for a simple point-of-sale setup where cash payments are made, and it provides a printed summary with details like the cashier name, date, and itemized list of purchases.

Table of Contents
Getting Started
Features
Class Descriptions
Usage Instructions
Example
Future Improvements
Getting Started
To get started with this code:

Install Python 3.x if you haven’t already.
Run the code by executing the billing_system.py file in the terminal.

Features
Add Items: Input item name, price, quantity, and discount, then add it to the bill.
Remove Items: Remove an item from the bill by selecting its index.
Calculate Total: Calculate the total cost of all items in the bill, considering discounts.
Print Bill: Print a detailed bill including itemized details, total, cash given, and balance.
Exit: Close the bill and exit the program.

Class Descriptions
ISCItem Class
This class represents an item in the bill. It has the following attributes:

name: The name of the item.
price: The price per unit of the item.
quantity: The number of units of the item.
discount: The discount percentage applied to the item.
ISCBill Class
This class manages the bill. It has the following methods:

add_item(item): Adds an item to the bill.
remove_item(item): Removes an item from the bill.
calculate_total(): Calculates the total cost of all items in the bill, applying discounts.
print_bill(cash): Prints the bill with item details, subtotal, cash received, balance, cashier name, and other details.
Usage Instructions
Launch the program: When the program starts, you’ll be prompted to enter the cashier’s name.
Main Menu Options:
Add Item (Enter 1): Add an item to the bill.
Enter the item’s name, price, quantity, and discount.
Remove Item (Enter 2): Select and remove an item from the bill.
Calculate Total (Enter 3): Display the total amount including discounts.
Print Bill (Enter 4): Enter the amount received in cash and print the final bill with details and balance.
Exit (Enter 5): Exit the program and print a new bill.
Item Details: After entering the item details, you can continue adding more items or finish to calculate the bill.

#Enter cashier name: John Doe

Welcome to ITUM SHOPPING COMPLEX
1. Add item
2. Remove item
3. Calculate total
4. Print bill
5. Exit
Enter your choice (1-5): 1

Enter item name: Shampoo
Enter item price: 5.99
Enter item quantity: 2
Enter item discount percentage: 10
Item added successfully.

Enter your choice (1-5): 3
Total: 10.78

Enter your choice (1-5): 4
Enter cash payment: 20

After printing, the system shows a detailed bill with all items, subtotal, and balance.

Future Improvements
Support for digital payment methods.
Additional discount options for loyalty members.
Exporting bill details to PDF or CSV format.
Item search by name and category filtering.
