# Q.30
def is_sorted(lst):
    sorted_lst = sorted(lst)
    return lst == sorted_lst

# Example usage
numbers = [1, 2, 3, 4, 5]
print(is_sorted(numbers))  # Output: True

letters = ['a', 'b', 'c', 'd', 'e']
print(is_sorted(letters))  # Output: True

mixed = [1, 2, 4, 3, 5]
print(is_sorted(mixed))  # Output: False
