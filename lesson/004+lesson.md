## This is the quiz 004.
I think this program needs much less time to solve.

```.py
n = int(input("please enter natural number that is less than 17 digits"))
i = 2
print("1")
s = 1

while i < pow(n, (1/2)):
    if n % i == 0:
        print(i)
        print(int(n/i))
        s = s + i + n/i
    i += 1

if pow(i, 2) == n:
    print(i)
    s = s + i

if n == s:
    print("Perfect number")
else:
    print("not perfect number")

```


## Lesson things
Using mod is too smart. 
```.py
num = int(input("please enter how many number you want"))
count = int(input("please enter how long the roop is"))
i = 0
while count < num:
    print(i % count)
    num -= 1
    i += 1

print("end")
```
