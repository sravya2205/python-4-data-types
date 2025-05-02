#swapping of key and value in dictionaries
info={'name':'india','number':123}
v='india'
for key,value in info.items():
    if value==v:
        print(f"key for value'{v}':{key}")

        
#set operations
my_set={1,2,3,4,5,6}
print('add and remove values')
my_set.add(8)
print(my_set)
my_set.remove(4)
print(my_set)
my_set.discard(5)
print(my_set)
print("Membership operator")
print(1 in my_set)
print(6 in my_set)

