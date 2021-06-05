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
import math
coffa=float(input("Enter the Coefficient a : "));
coffb=float(input("Enter the Coefficient b : "));
coffc=float(input("Enter the Coefficient c : "));
diss = math.sqrt((coffb**2)-4*coffa*coffc);
alpha=(-coffb + diss)/2*coffa;
beta=(-coffb - diss)/2*coffa;
print("The Roots of the Quadratic equation : ", "Alpha = ",alpha, "Beta = ",beta);


#6. Find volume of a sphere using radius as input.
r=int(input())
pi=3.14
v=4/3*pi*r**3
print("volume of sphere=",v)

#7. Count the  number of digits in a number. Example: 3454 has 4 digits.
n=int(input("Enter the digit:"))
count=0
while(n>0):
 count=count+1
 n=n//10
print("no of digits are",count)

#8. Write a program that accepts a string and gives output string with all capital letters.
string = "ankit"
print(string.upper())
(or)
s=str(input("enter a string= "))
print(s.upper())

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
