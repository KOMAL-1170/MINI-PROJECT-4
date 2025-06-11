# Input product data
product_data = {
    "P1": 64,
    "P2": 88,
    "P3": 152,
    "P4": 93,
    "P5": 76
}

# Print product list
print("Product List:")
print("PID\tPrice")
for pid, price in product_data.items():
    print(f"{pid}\t{price}")
