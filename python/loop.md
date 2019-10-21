對於迴圈（循環）
```
for name in ['orange', 'apple']:
	print(name)
```
```
orange
apple
```

```
for index in range(0, 6):
	print(index)
```
```
0
1
2
3
4
5
```

使用For 迴圈(loop)計算1+2+3+.....100

```
sum=0
for x in range(1,101):
  
  sum += x
print(sum)
```
程式設計題

使用For 迴圈(loop)計算1+3+5+7.....+99
```
for x in range(1,100,2):
  
  sum += x
print(sum)
```
使用for 迴圈(loop)計算1*3*5*7.....*99
```
for x in range(1,100,2):
  
  sum *= x
print(sum)

2575495572064439380316774016903868108459802532365784225978940738153735360107421875
```
程式設計題
使用while 迴圈(loop)計算1+2+3+.....100
```
a = 0
b = 0
while b<101:
  a+=b
  print(b)
  b+=1
print(a)
```
使用while 迴圈(loop)計算1+3+5+7.....+99
```
a = 0
b = 1
while b<100:
  a+=b
  b+=2
  
Ans:2500
```
使用while 迴圈(loop計算1*3*5*7.....*99
```
a = 1
b = 1
while b<100:
  a*=b
  b+=2
print(a)

2725392139750729502980713245400918633290796330545803413734328823443106201171875
```
取代
```
word = "aaaaa"
print(word.replace("t","ooo"))
```
```
word = "aaaaa"
print(word.replace("a","b",2))
```
```
a舊文字 b新文字 2替換次數不超過此值
```
無窮迴圈
```
A=0
while A<1:
   print("hihi")
```
