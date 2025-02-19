menu = {
    'Cake':30,
    'Chocolate':20,
    'Ice Cream':40,
    'Pizza': 60,
    'Pasta': 40,
    'Burger': 60,
    'Salad': 70,
    'Coffee': 80,
}

print("Welcome to Python Restaurant")
print("Pizza: 60 Rs\nPasta: 40 Rs\nBurger: 60 Rs\nSalad: 70 Rs\nCoffee: 80 Rs\nCake: 30Rs\nChocolate: 20Rs\nIce Cream: 40 Rs")

order_total = 0

while True:
    item = input("Enter the item you want to order: ")
    if item in menu:
        order_total += menu[item]
        print(f"Your item {item} has been added to your order")
    else:
        print("Sorry, we don't have that item on the menu")

    another_order = input("Do you want to add another item? (yes/no): ")
    if another_order.lower() != 'yes':
        break

print(f"The total amount to pay is {order_total} Rs")
