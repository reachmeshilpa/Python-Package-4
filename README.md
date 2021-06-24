# Python-Package-4
Sequence->List and Tuple
#----------
LIST mutable and [ ]

# It is an ORDERED sequence of (any type of) items, most commonly used datatype in python.
# It is mutable or flexible, individual elements can be changed, add or remove item
# It uses [] SQUARE brackets
list = [4,6.6,'brownie',24,'pizza', 666]
OUTPUT-> 4,6.6,brownie,24,pizza, 666

print (list[2]) #indexed to 2 so third value is printed, rememember 0,1,2
OUTPUT-> brownie

# to mutate an element (replace one value with other [])
list[2] = 'browniefudge'    
print (list)
OUTPUT-> 4,6.6,browniefudge,24,pizza, 666

# to REMOVE a particular VALUE (r->v)
list.remove(6.6) 
print(list)
OUTPUT-> 4,browniefudge,24,pizza, 666

# to erase item FROM a PARTICULAR INDEX (PS:0,1,2) (epop->i)
list.pop(2) 
print(list)
OUTPUT-> 4,browniefudge,pizza, 666

# to ADD (append) item at the LAST INDEX
list.append(6.6)
print(list)
OUTPUT-> 4,browniefudge,pizza, 666, 6.6

#________________________________________________

TUPLE : immutable and ()
# It is an ORDERED sequence of (any type of) items
# It is IMMUTABLE, used to write and protect data, faster than list
# It is defined within () round brackets

# to read elements by their corresponding index value
tuple = (10,20,30,'text')
print(tuple[2])
OUTPUT-> 30













