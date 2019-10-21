# 10-1
```
print("hello!")
print(3*2*(17-2.1))
print("abc"+"def")
word = "art"
print(word.replace("r", "n"))
```
```
root@kali:~# gedit test.py
root@kali:~# python3 test.py 
hello!
89.4
abcdef
ant
```
# 10-2
```
a= 1
b= 2
c = a/b
print(a, "/", b, "=", c) 
add = str(a)+"/"+str(b)+"="+str(c)
print(add)
```
```
1 / 2 = 0.5
1/2=0.5
```
# 10-3
```
input("Where do you live? ")
print("I live in Boston. ")
```
```
input("Where do you live? ")
print("I live in Boston. ")
```
# 10-4
```
user_place = input("Where do you live? ")
text = user_place.capitalize()+ "!"
print(text) 
print("I hear it's nice there!") 
```
```
Where do you live? tw
Tw!
I hear it's nice there!
```
# 10-5
```
num = int(input ("Enter a number to find the square of: "))
user_input = input("Enter a integer to find the square of: ")
num = int(user_input) 
print(num*num)
```
```
Enter a number to find the square of: 5
Enter a integer to find the square of: 2
4
```
# 10-6
```
num1 = float(input("Enter a number: "))
num2 = float(input("Enter another number: "))
print(num1, "*", num2, "=", num1*num2)
```
```
Enter a number: 12
Enter another number: 5
12.0 * 5.0 = 60.0
```
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
而迴圈（循環）
程式設計題
使用For 迴圈(loop)計算1+3+5+7.....+99
程式設計題
使用while 迴圈(loop)計算1+2+3+.....100
使用while 迴圈(loop)計算1+3+5+7.....+99
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
