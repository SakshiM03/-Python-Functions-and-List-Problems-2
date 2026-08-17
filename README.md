#1. sum_list_function.py
def find_sum(numbers):
    total = 0
 for num in numbers:
        total += num
 return total
numbers = [10, 20, 30, 40]
print("Sum:", find_sum(numbers))

#2. largest_function.py
def find_largest(numbers):
    largest = numbers[0]
 for num in numbers:
        if num > largest:
            largest = num
return largest
numbers = [12, 45, 7, 89, 34]
print("Largest:", find_largest(numbers))

#3. count_even_function.py
def count_even(numbers):
    count = 0
for num in numbers:
        if num % 2 == 0:
            count += 1
 return count
numbers = [1, 2, 4, 7, 8, 10]
print("Even numbers:", count_even(numbers))

#4. common_elements.py
def common_elements(list1, list2):
    common = []
 for num in list1:
        if num in list2 and num not in common:
      common.append(num)
 return common
list1 = [1, 2, 3, 4, 5]
list2 = [3, 4, 5, 6, 7]
print("Common elements:", common_elements(list1, list2))

#5. reverse_list_function.py
def reverse_list(numbers):
    result = []
 for i in range(len(numbers) - 1, -1, -1):
        result.append(numbers[i])
   return result
numbers = [10, 20, 30, 40, 50]
print("Reversed:", reverse_list(numbers))
