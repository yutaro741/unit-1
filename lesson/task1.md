## answer to task1

```.py
color = ["blue", "red", "white", "yellow"]
for i in range(1, 2401):
    print(i, color[i%4])

```

## answer to task2
```.py
num = int(input("please enter the number"))
color = ["blue", "red", "white", "yellow"]
print(f"the color of your number is {color[num%4]}")
```

```.py
color = ["blue", "red", "white", "yellow"]
c = input("please enter color(blue, red, white or yellow")

a = color.index(c)
print(f"your locker number is the number that can express 4k + {a} with all integer k in range 0<k≤600")
print(f"eg. {400+a}, {a+4}, {2396+a}, {a+16}, {a+64}, {a+40}, {a+200}, {a+1000}, {a+360}. {a+8}...")
```

