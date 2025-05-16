# cpt-3
program::1
# function calling and defining
def hi():
    print("Good afternoon students")
hi()
output::
Good afternoon students


program::2
# func with parameters
def hi(name):
    print("Hello",name)
hi('Reema')
output::
Hello Reema

program::3
#func with return values
def add(a,b):
    return a+b
x=int(input("enter the value of x: "))
y=int(input("enter the value of y: "))
result=add(x,y)
print("sum:",result)
ouytput::
enter the value of x:  23
enter the value of y:  32
sum: 55


program::4
''' write a function thatb carries and return all the arthmetic operator
to the main code(+,-,*)
pass the constraints,where all the constraints must be caluculated
accordingly and return the values to print by calling the same function
'''
def ao(x,y):
    return x+y, x-y, x*y
x=int(input("x:"))
y=int(input("y:"))
tot, diff, prod= ao(x,y)
print("sum:",tot)
print("sub:",diff)
print("mul:",prod)
output::
