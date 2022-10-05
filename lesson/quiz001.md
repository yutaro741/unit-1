# solution to quiz001

## Black Box: Describe a program that  produces the output shown with the input provided.

![9AA57E49-A894-46B8-84D3-40C4A9D2D712.jpg](https://github.com/yutaro741/unit-1/blob/main/9AA57E49-A894-46B8-84D3-40C4A9D2D712.jpg)

**Fig. 1** This is the solution to the black box

| input         | output  |
|---------------|---------|
| international | i11l    |
| i             | i       |
| 45a6          | 426     |
| hello world   | h3o w3o |

1.Get input
2.Sprit the input by words
3.for each words:
  a.Calculate the number (let N)
  b.if N>2, print
    {first letter}+{N-2}+(last letter}
  c.if N≤2, print the word
 
  ```.py
  a = input().split(" ") #input a list divided in words
p = ""
for i in a: #Do it each words
    if len(i) > 2:
        p += f"{i[0]}{str(len(i)-2)}{i[-1]}"
    else:
        p += i
    p += " "
print(p)
```
![](https://github.com/yutaro741/unit-1/blob/main/picture/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202022-10-05%2010.47.56.png)
