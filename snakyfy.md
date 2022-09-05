## Hi John
```.py

a = input()
print("Hi " + a)

```

![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-08-30%2010.19.05.png)

## Square
```.py

a = int(input())
print(a*a)

```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-08-30%2010.19.18.png)

## Area of right-angled triangle
```.py
a = int(input())
b = int(input())
print(a*b/2)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-08-30%2010.19.31.png)

## Hello, Harry!
```.py
a = input()
print("Hello, " + a + "!")

```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-08-30%2010.19.48.png)

## Apple sharing
```.py
a = int(input())
b = int(input())
print(int(b/a))
print(b%a)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-08-30%2010.19.56.png)

##Previous and next
```.py
a = int(input())
print("The next number for the number " + str(a) + " is " + str(a+1) +".")
print("The previous number for the number " + str(a) + " is " + str(a-1) + ".")
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-08-30%2010.20.04.png)

## Two timestamps
```.py
h1 = int(input())
m1 = int(input())
s1 = int(input())
h2 = int(input())
m2 = int(input())
s2 = int(input())
print((h2 - h1)*3600 + (m2 - m1)*60 + (s2 - s1))
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-08-30%2010.20.36.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-08-30%2010.20.40.png)

## School desks
```.py
a = int(input())
b = int(input())
c = int(input())
print((a+1)//2+(b+1)//2+(c+1)//2)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-08-30%2010.20.55.png)







## Last digit of integer
```.py
a = float(input())
print(a%10)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.38.26.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.38.39.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.38.44.png)

## Two digits
```.py
a = int(input())
print(int(a/10), a%10)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.39.14.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.39.21.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.39.25.png)

## Swap digits
```.py
a = int(input())
print(a%10*10+int(a/10))
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.39.41.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.39.47.png)

## Last two digits
```.py
a = int(input())
print(a%100)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.40.02.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.40.10.png)

## Tens digit
```.py
a = float(input())
print((a%100 - a%10)/10)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.40.31.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.40.38.png)

## Sum of digits
```.py
a = float(input())
print(a//100%10 + a//10%10 +a%10)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.40.49.png)

## Reverse three digits
```.py
a = int(input())
print(a%10*100+(int(a/10)%10)*10+int(a/100))
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.41.01.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.41.10.png)

## Merge two numbers
```.py
a = int(input())
b = int(input())
print(int(a/10)*1000+int(b/10)*100+a%10*10+b%10)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.41.22.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.41.27.png)


## Cyclic rotation
```.py
a = int(input())
print(a%100*100+int(a/100))
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.41.39.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.41.48.png)


## Fractional part
```.py
a = float(input())
print(a - int(a))
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.42.15.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.42.22.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.42.28.png)

## First digit after decimal point
```.py
a = float(input())
print(int(10*a%10))
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.42.39.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.42.53.png)

## Car route
```.py
a = float(input())
b = float(input())
c = b/a-int(b/a)
if c <= 0:
    print(int(b/a))
else:
    print(int(b/a)+1)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.43.02.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.43.08.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.43.16.png)

## Day of week
```.py
print((int(input())-4)%7)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.43.28.png)


## Digital clock
```.py
a = float(input())
print(str(a//60) + " " + str(a%60))
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.43.39.png)

## Total cost
```.py
d = float(input())
c = float(input())
n = float(input())
print(str((100*d+c)*n//100) + " " + str((100*d+c)*n%100))
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.43.51.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.43.59.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.44.05.png)

## Century
```.py
a = int(input())
print(int((a-1)/100)+1)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.44.18.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.44.24.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.44.28.png)

## Snail
```.py
h = int(input())
a = int(input())
b = int(input())
if (h-a)/(a-b) - int((h-a)/(a-b)) == 0:
    print(int((h-a)/(a-b))+1)
elif h-a < 0:
    print(int((h-a)/(a-b))+1)
else:
    print(int((h-a)/(a-b))+2)
```
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.44.40.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.44.53.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.45.00.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.45.08.png)
![](https://github.com/yutaro741/unit-1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-09-04%2014.45.13.png)
