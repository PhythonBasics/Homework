10.Print the following ( using two for loops )
	
# # # # #
# # # #
# # #
# # 
#

for i in range(5,0,-1):
    for j in range(i,0,-1):
        print("#", end=" ")
    print("\n")


# # # # # 

# # # # 

# # # 

# # 

# 


1. Define a function max() that takes two numbers as arguments and returns the largest of them.

def max(a,b):
    if(a<b):
        print(a)
    else:
        print(b)


max(9,20)

Output: 20

2. Define a function max_of_three() that takes three numbers as arguments and returns the largest of them.

def max_ofthree(a,b,c):
    if(a>b and a>c):
        print(a)
    elif(b>a and b>c):
        print(b)
    else:
        print(c)

max_ofthree(10,5,2)

Output: 10

3. Define a function that computes the length of a given list or string.

def func(name):
    a=0
    for i in name:
        a= a+1
    print(a)

str=input("Enter Name - ")
func(str)

4. Write a function that takes a character and returns True if it is a vowel, Falseotherwise.

def vowel(vow):
    i=['a','e','i','o','u']
    if (vow in i):
        print("True")
    else:
        print("False")

name=input("Enter Letter - ")
vowel(name)
