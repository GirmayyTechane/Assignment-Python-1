# Assignment-Python-1
Question 1. Install Jupyter notebook and run the first program and share the screenshot of the output.


answer : https://github.com/GirmayyTechane/Assignment-Python-1/blob/master/assignement%201%20question%201.PNG

2. Write a program which will find all such numbers which are divisible by 7 but are not a
multiple of 5, between 2000 and 3200 (both included). The numbers obtained should be printed
in a comma-separated sequence on a single line.

answer:

y=[]
for x in range(2000,3201):
    if (x % 7 ==0) and (x % 5 !=0):
        y.append(str(x))
        print (','.join(y))
        
        
        
3. Write a Python program to accept the user's first and last name and then getting them printed
in the the reverse order with a space between first name and last name.

answer:
firstname = input("What is your first name : ")
lastname = input("What is your Last Name : ")
print (lastname + " " + firstname)

4. Write a Python program to find the volume of a sphere with diameter 12 cm.
Formula: V=4/3 * π * r3

answer:




