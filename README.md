def print_positive_numbers(lst):
    positive_numbers = [num for num in lst if num > 0]
    print(positive_numbers)

list1 = [12, -7, 5, 64, -14]
list2 = [12, 14, -95, 3]

print_positive_numbers(list1)
print_positive_numbers(list2)
