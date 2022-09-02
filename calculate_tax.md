## this is the answer for tax thing

```.py
#Calculate tax rate
#input salary
s = int(input("please enter your income($)"))
#Divide the cases get the tax
if 0 <= s <= 10000:
    tax = 5
elif 10001 <= s <= 50000:
    tax = 10
elif 50001 <= s <= 100000:
    tax = 15
elif 100001 <= s:
    tax = 25
#print The tax.
print(f"Your tax rate is {tax}%")
```
