# simple-calc-python
Its a simple calculator using python


num1 = int(input("enter num1:"))
num2 = int(input("enter num2:"))
action = str(input("Choose action: Add(a), Sub(s) Mult(m) Div(d) ->))
print("The result is ", end='''')
if action == "a":
   print(num1+num2)
elif action == "s":
   print(num1-num2)
elif action == "m":
   print(num1 * num2)
else:
   print(num1/num2)
