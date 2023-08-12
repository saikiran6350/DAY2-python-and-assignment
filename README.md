# DAY2-python-and-assignment
#LOGICAL OPERATERS
is_student = True
in_college = True
in_school = False
​
is_student and in_college
​
is_student and in_school
​
is_student or in_college
​
is_student or in_college
​
not(is_student)
False
list1 = [10,20,30]
list2 = [40,50,60]
list3 = list1
​
print("memory location of list1",id(list1))
print("memory location of list2",id(list2))
​
if id(list1) == id(list2):
    print("list1 and list2 are store in same loction")
elif id(list1) == id(list3):
    print("list1 and list2 are store in same location")
memory location of list1 1302372369024
memory location of list2 1302372267840
list1 and list2 are store in same location
x = ["sai","kiran","nani"]
y = ["hari","lucky","priya"]
​
print(x is not y)
print(x is y)
True
False
print(bin(10))
print(bin(20))
print('10 & 12 =',10 & 12)
print('10 | 12 =',10 | 12)
print('10 ^ 12 =',10 ^ 12)
print('~10 =',~10)
print('10 >> 12 =',10 >> 12)
print('10 << 20 =',10 << 20)
0b1010
0b10100
10 & 12 = 8
10 | 12 = 14
10 ^ 12 = 6
~10 = -11
10 >> 12 = 0
10 << 20 = 10485760
num = 20
if(num > 0):
    print("num is positive number")
elif(num == 0):
    print("num is neither negative nor positive")
elif(num < 0):
    print("num is negative number")
num is positive number
num1 = 10
num2 = 20
num3 = 40
​
if(num1 > num2):
    print("num1 is greater")
else:
    if(num2 > num3):
        print("num2 is greater")
    else:
        print("num3 is greater")
num3 is greater
num = 5
addition = 0
i = 1
​
while(i <= num):
    addition = addition + i
    i = i + 1
print("addition is:",addition)
addition is: 15
number = range(1,11)
addition = 0
for i in number:
    addition = addition + i
    
print("addition is",addition)
addition is 55
#STRINGS
name = "sai"
print(name)
type(name)
sai
str
#LIST
book = ["sql","python"]
print(book)
type(book)
novels = ["dejuvu","harrypoter"]
library = book + novels
print(library)
['sql', 'python']
['sql', 'python', 'dejuvu', 'harrypoter']
prices = [120,230,23,113,90]
prices.sort()
​
print(prices)
prices.clear()
print(prices)
[23, 90, 113, 120, 230]
[]
#ASSIGNMENT 1
timeperiod = int(input())
if(timeperiod > 10):
    print("10% bonous")
elif(6< timeperiod <10):
    print("8% bonous")
elif(timeperiod < 5):
    print("5% bonous")
11
10% bonous
price = int(input())
 
if(price >10000):
    i =price-(20/100*price)
    print(i)
elif(7000< price <=10000):
    i = price-(15/100*price)
    print(i)
elif(price <= 7000):
    i = price-(10/100*price)
    print(i)
1000
900.0
