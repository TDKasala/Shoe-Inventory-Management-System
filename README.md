# Shoe Inventory Management System

This Python script provides a simple shoe inventory management system. It allows users to capture, view, restock, search for shoes, view item values, and view items on sale. The data is stored in a text file, and the system is menu-driven, providing users with various options for managing their shoe inventory.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
  
## Prerequisites

Before you run the script, ensure you have Python installed on your system.

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/shoe-inventory.git
   ```

2. Navigate to the project directory:

   ```bash
   cd shoe-inventory
   ```

3. Run the script:

   ```bash
   python shoe_inventory.py
   ```

## Usage

The script provides a menu-driven interface for managing your shoe inventory. Here are the available options:

1. **Capture Shoes**: Add new shoes to the inventory by entering details such as country, code, product name, cost, and quantity.

2. **View All**: Display a list of all shoes in the inventory, including their details.

3. **Restock**: View the top 5 shoes with the lowest stock, select one to restock, and update the quantity.

4. **Search**: Search for a shoe by its code and display its details.

5. **View Item Values**: Calculate and display the value of each shoe item (cost * quantity).

6. **View Sale Items**: Display the shoe item with the highest quantity in stock, marking it as on sale.

## Features

- Shoes are stored as objects of the `Shoes` class.
- Data is read from and written to a text file (`inventory.txt`) for persistence.
- The script uses the `tabulate` module to display data in a tabular format.
- Error handling is implemented to handle file not found and invalid input.

## Contributing

Contributions are welcome! If you have any improvements or suggestions for this project, please open an issue or a pull request.
