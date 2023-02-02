# CSA0861-PYTHON
n=eval(input("enter a year"))
if(n%400==0):
    print("leap year")
elif(n%100==0):
    print("non leap year")
elif(n%4==0):
    print("leap year")
else:
    print("not a leap year")
    
