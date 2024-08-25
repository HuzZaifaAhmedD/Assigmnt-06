# Assigmnt-06

#list#
list1= [1,2,3,4,5]
def sum_of_list(num):
    return sum(num)
result= sum_of_list(list1)
print(result)

   #tuple#
tuple1= (8,2,5,7,6,9,)
def min_of_tuple(numb):
    return min(numb)
result = min_of_tuple(tuple1)
print(result)

   #set#
set= {2,3,4,5,6}
def square_set(numbers):
    return {x*x for x in numbers}
result= square_set(set)
print(result)

   #dict#

my_dict= {"name":"haris", "age": 25, "Gender": "male"}
def dic_key(dictionary):
    return list(dictionary.keys())
result= dic_key(my_dict)
print(result)
