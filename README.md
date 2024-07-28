# PyCoffee-Interactive-Coffee-Machine-Simulator

### Project Summary: Coffee Machine

This project is a simulation of a coffee machine built using Python. The program allows users to select a type of coffee, processes their payment, and deducts the required resources to make the selected coffee. The project is divided into four main components: the main program logic (`main.py`), the coffee maker logic (`coffee_maker.py`), the menu logic (`menu.py`), and the money handling logic (`money_machine.py`).

#### main.py
- **Purpose**: Orchestrates the overall flow of the coffee machine simulation.
- **Key Functions**:
  - Initializes instances of `MoneyMachine`, `CoffeeMaker`, and `Menu`.
  - Continuously prompts the user to choose a drink, generate a report, or turn off the machine.
  - Handles user input to make a drink selection, checks resource availability, processes payment, and makes the coffee.

#### coffee_maker.py
- **Purpose**: Manages the resources and processes involved in making coffee.
- **Key Functions**:
  - Initializes the coffee machine with a set amount of water, milk, and coffee.
  - Prints a report of the current resources.
  - Checks if there are sufficient resources to make the selected drink.
  - Deducts the required resources from the machine to make the coffee and serves the drink.

#### menu.py
- **Purpose**: Defines the menu items and handles drink selection.
- **Key Functions**:
  - `MenuItem` class models each drink with its ingredients and cost.
  - `Menu` class contains a list of available drinks and provides methods to get item names and find specific drinks.

#### money_machine.py
- **Purpose**: Handles monetary transactions and processes coin input.
- **Key Functions**:
  - Initializes the money machine with no profit and no money received.
  - Prints a report of the current profit.
  - Processes inserted coins and calculates the total amount of money received.
  - Checks if the payment is sufficient and returns change if applicable.

### How to Run the Coffee Machine
1. Ensure Python is installed on your system.
2. Run the `main.py` file.
3. Follow the prompts to:
   - Choose a drink (`latte`, `espresso`, `cappuccino`).
   - Generate a report of resources and profit by typing `report`.
   - Turn off the machine by typing `off`.
4. Insert the required coins when prompted and receive your selected drink if payment is sufficient.

### Key Features
- **User Input**: Select drinks, generate reports, or turn off the machine.
- **Resource Management**: Checks and manages the availability of resources (water, milk, coffee) for each drink.
- **Payment Processing**: Accepts coin input, calculates the total, and checks for sufficient payment.
- **Report Generation**: Displays current resource levels and profit.

This project demonstrates basic object-oriented programming principles and can be further extended with additional features such as more drink options, different payment methods, or graphical interfaces.
