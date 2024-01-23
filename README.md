# Assigment-3
#BanoQabil2.0
Choice=input('''Enter Your Choice:
             1. Factorial
             2. Mulultiplication
             3. Division
''')
if Choice=='1':
    num = int(input("Enter Number: "))
    factorial=1
    if num < 0:
        print("Error")
    elif num == 0:
        print("0 ! = 1")
    else:
        for i in range(1,num + 1):
            factorial = factorial*i
    print(num,"! = ",factorial)


elif Choice=='2':
    num1=int(input("Enter First Number: "))
    num2=int(input("Enter Second Number: "))

    result=print(num1 * num2)

elif Choice=='3':
    num1=int(input("Enter First Number: "))
    num2=int(input("Enter Second Number: "))

    result=print(num1/num2)
else:
    print("Invalid Choice..!")

