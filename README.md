# cs
a=int(input("Enter a:"))
b=int(input("Enter b:"))
if a>b:
    print("Largest:",a)
elif a<b:
   print("Largest:",b)
else:
   print("Bothnumbers are equal")
    output:Enter a: 9
           Enter b: 8
           Largest: 9
------------------------------------------------------------------------------------------    
num=int(input("Enter the number"))
if num>0:
    print("Positive Number")
    if num%2==0:
        print("Even")
    else:
        print("Odd")
else:
    print("Number is non-positive")
output: Enter the number 33
       Positive Number
       Odd    
-----------------------------------------------------------------------------------------------       
pin=int(input("enter your 4-digit pin number"))
spin=1234
balance=5000
if pin==spin:
    print("Access Granted!!")
    withdraw=int(input("enter amount:"))
    if withdraw>balance:
        print("insufficient funds!!!")
    else:
        print("Amount withdraw:",withdraw)
        print("Remaining balance:",balance-withdraw)
        print("Thank You for banking with ICICI......")
else:
    print("Access denied......Wrong pin")
OUTPUT:
enter your 4-digit pin number 1234
Access Granted!!
enter amount: 4000
Amount withdraw: 4000
Remaining balance: 1000
Thank You for banking with ICICI......
OUTPUT:
enter your 4-digit pin number 1432
Access denied......Wrong pin
-----------------------------------------------------------------------------------------------------
       
