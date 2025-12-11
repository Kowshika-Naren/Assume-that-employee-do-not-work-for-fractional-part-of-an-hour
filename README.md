ovpay=0
sum=0
for i in range(1,11):
    print("enter working hours of emp",i,":")
    h=int(input())
    if(h>40):
        extra=h-40
        ovpay=extra*12
        print("over time pay of emp",i,"is",ovpay)
        sum=sum+ovpay
else:
    print("no overtime pay")
    print("total overtime pay of all employees :",sum)
    
Output:
enter working hours of emp 2 :
48
over time pay of emp 2 is 96
# Assume-that-employee-do-not-work-for-fractional-part-of-an-hour
