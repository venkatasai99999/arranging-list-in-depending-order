
def sort_descending(input_list):
    for i in range(len(input_list)):
      for j in range(i + 1, len(input_list)):
            if input_list[i] < input_list[j]:
            
               input_list[i], input_list[j] = input_list[j], input_list[i]


numbers = [10,15,20,25,30,35,40,]
print("Original List:", numbers)

sort_descending(numbers)
print("Sorted List (Descending):", numbers)
