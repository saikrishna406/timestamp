import time
t=time.strftime('%H:%M:%S')
print("Hello")
name=input("Enter Your name")
Hour=int(time.strftime('%H'))
if Hour >=0 and Hour< 12:
    print(f"{name} Good morning")
elif Hour >=12 and Hour < 17:
    print(f"{name} Good afternoon")
else:
    print(f"{name} Good night")
