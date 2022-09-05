## This is the homework.

'''.py
#Put in name
a = str(input("Please write No1 name"))
b = str(input("Please write No2 name"))
c = str(input("Please write No3 name"))

#record first letter
x = int(ord(a[0]))
y = int(ord(b[0]))
z = int(ord(c[0]))

#record second letter
o = int(ord(a[1]))
p = int(ord(b[1]))
q = int(ord(c[1]))

#Make alfabet order(so so so hard)
if x == y == z:
    if o > p > q:
        t = (a, b, c)
    if o > q > p:
        t = (a, c, b)
    if p > o > q:
        t = (b, a, c)
    if p > q > o:
        t = (b, c, a)
    if q > o > p:
        t = (c, a, b)
    if q > p > o:
        t = (c, b, a)
else:
    if x == y:
        if x > z:
            t = (a, b, c)
        else:
            t = (c, a, b)
    if x == z:
        if x > y:
            t = (a, c, b)
        else:
            t = (b, a, c)
    if y == z:
        if y > x:
            t = (b, c, a)
        else:
            t = (a, b, c)
if x > y > z:
    t = (a, b, c)
if x > z > y:
    t = (a, c, b)
if y > x > z:
    t = (b, a, c)
if y > z > x:
    t = (b, c, a)
if z > x > y:
    t = (c, a, b)
if z > y > x:
    t = (c, b, a)

#print
print(t)
'''
