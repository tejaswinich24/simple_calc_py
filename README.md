a=float(input("Enter 1st number:"))
b=float(input("Enter 2nd number:"))

print("1.ADDITION")
print("2.SUBSTRACTION")
print("3.MULTIPLICATION")
print("4.DIVISION")

n=int(input("Enter your choice: "))

if (n==1):
    c=a+b
    print("Result: ",c)

elif (n==2):
    c=a-b
    print("Result: ",c)

elif (n==3):
    c=a*b
    print("Result: ",c)

elif (n==4):
    c=a/b
    print("Result: ",c)

else:
    print("Invalid choice")
