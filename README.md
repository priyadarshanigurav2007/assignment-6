# Assignment-6
#1 Create a list
my_list = [10, 20, 30, 40, 50]

# Check element presence
num = 30

if num in my_list:
    print(num, "is present in the list")
else:
    print(num, "is not present in the list")

# Using not in
if 60 not in my_list:
    print("60 is not present in the list")

#2
my_list = [1, 2, 3, 4, 5]

# Indexing
print("First element:", my_list[0])
print("Third element:", my_list[2])

# Negative indexing
print("Last element:", my_list[-1])
print("Second last element:", my_list[-2])

# Slicing
print("Elements from index 1 to 3:", my_list[1:4])
print("Elements from start to index 2:", my_list[:3])
print("Elements from index 2 to end:", my_list[2:])

#3
my_list = [10, 20, 30, 40]

# Update
my_list[1] = 25
print("After update:", my_list)

# Append
my_list.append(50)
print("After append:", my_list)

# Insert
my_list.insert(2, 15)
print("After insert:", my_list)

# Delete using remove()
my_list.remove(30)
print("After remove:", my_list)

# Delete using pop()
my_list.pop()
print("After pop:", my_list)

# Delete using del
del my_list[0]
print("After del:", my_list)

#4
list1 = [1, 2, 3]
list2 = [4, 5, 6]

# Concatenation
result = list1 + list2
print("Concatenation:", result)

# Repetition
print("Repetition:", list1 * 2)

# Length
print("Length of list1:", len(list1))

# Maximum
print("Maximum value:", max(result))

# Minimum
print("Minimum value:", min(result))

OUTPUT
30 is present in the list
60 is not present in the list
First element: 1
Third element: 3
Last element: 5
Second last element: 4
Elements from index 1 to 3: [2, 3, 4]
Elements from start to index 2: [1, 2, 3]
Elements from index 2 to end: [3, 4, 5]
After update: [10, 25, 30, 40]
After append: [10, 25, 30, 40, 50]
After insert: [10, 25, 15, 30, 40, 50]
After remove: [10, 25, 15, 40, 50]
After pop: [10, 25, 15, 40]
After del: [25, 15, 40]
Concatenation: [1, 2, 3, 4, 5, 6]
Repetition: [1, 2, 3, 1, 2, 3]
Length of list1: 3
Maximum value: 6
Minimum value: 1
