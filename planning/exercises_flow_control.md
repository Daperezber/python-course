# Flow Control

1. Use the `input` builtin function to read two variables and print the
   maximum between them.
   
   
   var_1=input("Enter Variable 1: ") 
var_2=input("Enter variable 2: ")
if int(var_1)>int(var_2):
    print(var_1)
else:
    print(var_2)
    
     
   
   
   
2. Considering a list `integers = [-2, 3, 20, -4]`.
   - Print only the positive values from the `integers` list.
   
   integers = [-2, 3, 20, -4]
for i in integers:
    if i>0:
        print(i)
   
   
   - Extend the `integers` list with another `10` values.
   
   for i in range(0,11):
    integers.append(i)
print(integers)

   - Print the number of positive values from the updated `integers` list.
   for i in integers:
    if i>0:
        print(i)



