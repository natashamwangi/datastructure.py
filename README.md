# datastructure.py

# Step to create an empty list
my_list = []

# Append the listed elements in my list
my_list += [10, 20, 30, 40]

# Inserting 15 at index 1
my_list.insert(1, 15)

# Extend my list with another list
my_list.extend([50, 60, 70])

# Remove the last element using slicing (faster than pop for large lists)
my_list = my_list[:-1]

# Sort the list in ascending order
my_list.sort()

# Find and print the index of the value 30 with error handling
try:
    index30 = my_list.index(30)
    print(f"Index of 30: {index30}")
except ValueError:
    print("30 is not found in the list.")

# Print the final list in a readable format
print("Final Sort List:", my_list)
