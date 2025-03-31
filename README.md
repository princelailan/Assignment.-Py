# Assignment.-Py

price = float(input("Enter the original price of the item: "))
discount_percent = float(input("Enter the discount percentage: "))

def calculate_discount(price, discount_percent):  
    if discount_percent >= 20:
        discount = price * (discount_percent / 100)
        price_after_discount = price - discount
        print(f"The final price is: {price_after_discount}")
    else:
        print(f"No discount applied. The final price is: {price}")

