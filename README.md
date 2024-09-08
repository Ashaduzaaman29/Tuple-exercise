# a = (1,3,5,7,4)

# #Leangth

# print(len(a))

# #Type


# print(type)

# #Access [-2],[2]

# print(a[-2],a[2])

# #Change [-3]=50

# b = list(a)
# b[-3] = 50
# a = tuple(b)
# print(a)

# #a[-4:-1]
# a = (1,3,5,7,4)
# print(a[-4:-1])

# # # Add last index, in [2]=400
# # Add  last and [2]  use in 
# # a = (1,3,5,7,4)
# # b = list(a)
# # b.append(100)
# # print(b)
# # b.insert(2,400)
# # print(b)


# # loop through the tuple
# a = (1,3,5,7,4)
# for x in a:
#   print(x)

# # remove the last element
# a = (1,3,5,7,4)
# b = list(a)
# b.remove(4)
# a = tuple(b)

# print(a)

####Join with (2,4,6)
# a = (1,3,5,7,4)
# b=(2,4,6)
# a+=b
# print(a)

###Sort it 
# a = (1,3,5,7,4)
# b = list(a)
# b.sort()
# print(b)

###Decending Order sorting
# a = (1,3,5,7,4)
# b = list(a)
# b.sort(reverse=True)
# print(b)


###Dictionary
# employe= {
#     "name":"A",
#     "age":40,
#     "type":{  "developer":["ios","android"] },
#     "permanent": True,
#     "salary": 30000,
#     100:(1,2,3),
#     4.5:{5,6,True,7}
# }

# print(len(employe))
# print(employe["type"],employe["type"]["developer"][0],employe[4.5],end="           ")


# employe["permanent"]=False

# employe["gender"]="male"

# employe.pop("age")

# for key in employe:
#     print(employe[key])


#####Using Loop
# myfamily = {
#     "child1": {
#         "name": "Emil",
#         "year": 2004
#     },
#     "child2": {
#         "name": "Tobias",
#         "year": 2007
#     },
#     "child3": {
#         "name": "Linus",
#         "year": 2011
#     }
# }

# for child_key in myfamily:
#     print(f"{child_key}: {myfamily[child_key]}")


####Sets practice
# q={1,3,5, 8,5,2}
# b={0,False,1,5}
# print(len(q))  
# print(type(q))  

# print(len(b))  
# print(type(b)) 

# q.add(10)
# b.add(10)

# print(q) 
# print(b)


# q.remove(8)

# print(q)  

# for element in q:
#     if element == 5:
#         print("Found 5, breaking the loop")
#         break
#     print(element)


# union_qb = q.union(b)
# print(union_qb) 

# intersection_qb = q.intersection(b)
# print(intersection_qb)  

# difference_q_b = q.difference(b)
# print(difference_q_b)  

# difference_b_q = b.difference(q)
# print(difference_b_q) 


# numbers = [2, 3, 4]


# result = ','.join(map(str, numbers))
# print(result)
