# task-1
 the basic data  types in Python such as lists, dictionaries, and  sets. 
                # task-1
 #the basic data  types in Python such as lists, dictionaries, and  sets. 
 
         #LIST-[]
 my_list=[2,4,5,68,2]
print(my_list)
# Adding elements to the list using append()
my_list.append(8)
print("After adding elements:", my_list)
  # Modifying an element in the list
my_list[2] = 30
print("After modifying index 2:", my_list)
 # Removing an element from the list by value
my_list.remove(4)
print("After removing element 4:", my_list)
# Removing an element from the list by index
del my_list[0]
print("After removing first element:", my_list)
# Adding elements at specific positions using insert()
my_list.insert(1, 10)
print("After inserting 10 at index 1:", my_list)

 
           #dictionary-{}
my_dict={1:'abc',22:'sudheer','pythonlife':1}
print(my_dict)
 # Adding elements to the dictionary
my_dict['a'] = 1
my_dict['b'] = 2
my_dict['c'] = 3
print("After adding elements:", my_dict)
# Modifying an element in the dictionary
my_dict['b'] = 20
print("After modifying 'b':", my_dict)
#Removing an element from the dictionary by key
del my_dict['a']
print("After removing 'a':", my_dict)
# Adding a new element using update()
my_dict.update({'d': 4})
print("After adding 'd':", my_dict)


     #set-{}
my_set={2,4,5,8,5,4,2,4}
print(my_set)
# Adding elements to the set using add()
my_set.add(1)
my_set.add(9)
my_set.add(10)
print("After adding elements:", my_set)
# Trying to add duplicate element (no change in set)
my_set.add(2)
print("Trying to add 2 again:", my_set)
# Removing an element from the set
my_set.remove(2)
print("After removing 2:", my_set)
# Creating another set
other_set = {3, 4, 5}
print(other_set, my_set)
# Performing union of two sets using |
union_set = my_set | other_set
print("Union of sets:", union_set)
# Performing intersection of two sets using &
intersection_set = my_set & other_set
print("Intersection of sets:", intersection_set)
