# Python
# Define the menu of the restaurant
menu = {
    "Pizza": 40,
    "Pasta": 50,
    "Burger": 60,
    "Salad": 70,
    "Coffee": 80,
}

# Greet the user
print("Welcome to PYTHON Restaurant")
print("Menu:")
print("Pizza: Rs40\nPasta: Rs50\nBurger: Rs60\nSalad: Rs70\nCoffee: Rs80")

# Initialize order total
order_total = 0

# Get user input for the first item
item_1 = input("Enter the name of item you want to order = ")

# Check if the item is in the menu
if item_1 in menu:
    order_total += menu[item_1]  # Add the item's price to the total
    print(f"Your item {item_1} has been added to your order")

else:
    print(f"Ordered item {item_1} is not available yet!")

# Get user input for the second item
item_2 = input("Enter the name of item you want to order = ")

# Check if the second item is in the menu
if item_2 in menu:
    order_total += menu[item_2]  # Add the item's price to the total
    print(f"Your item {item_2} has been added to your order")

else:
    print(f"Ordered item {item_2} is not available yet!")

# Print the total order amount
print(f"Your total order amount is: Rs{order_total}")
