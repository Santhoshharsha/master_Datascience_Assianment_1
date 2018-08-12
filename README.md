# master_Datascience_Assianment_1
Masters in Data Science Assignment 1

# 1. Install Jupyter notebook and run the first program and share the screenshot of the output.
print('Hello World')

# 2. Write a program which will find all such numbers which are divisible by 7 but are not a multiple of 5, between 2000 and 3200 (both included). The numbers obtained should be printed in a comma-separated sequence on a single line.
for x in range(2000, 3000):
    if (x%7)==0:
        y=x/5.0
        if (y%5)!=0:   
            print(str(x), end=',')
            
# 3. Write a Python program to accept the user's first and last name and then getting them printed in the the reverse order with a space between first name and last name.
fname = input("Input your First Name : ")
lname = input("Input your Last Name : ")
print (lname + " " + fname)

# 4. Write a Python program to find the volume of a sphere with diameter 12 cm.
pi = 3.1415926535897931
r= 12.0
V= 4.0/3.0*pi* r**3
print('The volume of the sphere is: ',V)



![assignment_1](https://user-images.githubusercontent.com/40954118/43999097-c4a5a662-9e22-11e8-9d53-ed2cec229f69.PNG)
