#Revenue Calculator Tool Write a script that:

# Revenue Calculator Tool

product_name = input("Enter product name: ")
quantity = int(input("Enter quantity: "))
price = float(input("Enter price: "))
discount = float(input("Enter discount %: "))

# Total amount before discount
total = quantity * price

# Discount amount
discount_amount = (total * discount) / 100

# Final bill
final_bill = total - discount_amount

# Output
print("\n----- Final Bill -----")
print("Product:", product_name)
print("Quantity:", quantity)
print("Price per item:", price)
print("Total Amount:", total)
print("Discount:", discount, "%")
print("Final Bill:", final_bill)
