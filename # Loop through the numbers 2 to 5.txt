# Loop through the numbers 2 to 5
for i in range(2, 6):
    print(f"Multiplication Table for {i}:")
    # Loop through the numbers 1 to 10 for each table
    for j in range(1, 11):
        print(f"{i} x {j} = {i * j}")
    print()  # Add a blank line after each table
