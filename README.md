#1.  From this given string: s = "Hey i am from New Delhi". Find out: length of string, convert this to list using split operation.
a="Hey i am from New Delhi"
print(len(a))
a.split()

#2.  Given string s = "name is rahul". Write code to give following o/p.
- "Name is rahul"
-  "Rame Is Rahul"
-  "NAME IS RAHUL"
s = "name is rahul"
b='N'+s[1:]
print(b)
c='R'+s[1:8]+'R'+s[9:]
print(c)
print(s.upper())
(or)
print(s.capitalize())
str = s.replace("name", "rame")
print(str.title())
print(s.upper())

#3. Using length and breadth as input find out area and perimeter of a given rectangle.
a=int(input())
b=int(input())
print("parimeter=",2*(a+b))
print("area=",a*b)

#4. Using diameter as input find out circumference and area of a circle.
radius = diameter/2
print("radius: ", radius)
circumference = 22/7 *2*radius
area = (22/7 * radius*radius)
print(circumference)
print(area)

#5. Write a program to compute roots of a quadratic equation when coefficients a, b and c are known(entered by user).
a=int(input())
b=int(input())
c=int(input())
d = b * b - 4 * a * c
import math
sqrt_val =math.sqrt(d)
print((-b + sqrt_val)/(2 * a))
print((-b - sqrt_val)/(2 * a))

#6. Find volume of a sphere using radius as input.
r=int(input())
pi=3.14
v=4/3*pi*r**3
print("volume of sphere=",v)

#7. Count the  number of digits in a number. Example: 3454 has 4 digits.
num = int(input())
count = 0
while num != 0:
    num //= 10
    count += 1
print("Number of digits: " + str(count))

#8. Write a program that accepts a string and gives output string with all capital letters.
string = "ankit"
print(string.upper())

9. Write a program to that accepts a string s, an index number n and a character ‘c’. And outputs the string replaced with the character at the index number n. Example- ‘hello’ , 0 , ‘j’ ==> ‘jello’.
(Hint2: You can try it by join function too by typecasting it to list)
s=input("Enter String : ")
n=int(input("Enter Index : "))
c=input("Enter Character : ")
temp=list(s)
temp[n]=c
s=" ".join(temp)
print(s)

10. Reverse a string. Example: 'Hey there' = 'ereht yeH' 
11. a = "ANKIT MAILK"[::-1]
print(a)
