Q1. Why do we call Python as a general purpose and high-level programming language?
Ans: Python is called general purpose language because it can be used to create software in wide variety of applications across hardware configurations and operating systems. It is also considered as high-level programming language as it is considered easy for humans to understand.

Q2. Why is Python called a dynamically typed language?
Ans: Because we don’t have to declare data type of the variable and it is determined during the runtime.

Q3. List some pros and cons of Python programming language?
Ans: Pros of python language are
1)	Easy to understand and learn
2)	Scalable
3)	Used in machine learning
Cons of python language are
	1)Dynamically typed
	2)slower than compiled languages
	3)Inefficient memory usage.
Q4. In what all domains can we use Python?
Ans: We can use python in web development, data science, data engineering and Machine Learning domains among others.

Q5. What are variable and how can we declare them?
Ans: Python has no command to create a variable, a variable a reference or a pointer to an object.

Q6. How can we take an input from the user in Python?
Ans: We can take input from the user using the input() function.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans: By default it is a string.

Q8. What is type casting?
Ans: Type casting is the method to convert a data type into another particular data type.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans: Yes, using the spilt() function we can get multiple inputs.

Q10. What are keywords?
Ans: Python keyword are reserved keywords with special uses and meaning, special purpose. They can’t be used for other purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans: No we cannot, as keywords are reserved and the compiler might get confused and won’t accept those words.

Q12. What is indentation? What's the use of indentation in Python?
Ans: Indentation in python are whitespaces before any statement in python. Used to create a space to identify a particular code block. 


Q13. How can we throw some output in Python?
Ans: we can output in python using print().

Q14. What are operators in Python?
Ans: Operators in python are special symbols that designate that some sort of computation should be performed.

Q15. What is difference between / and // operators?
Ans: // return integer while the / returns a float value.

Q16. Write a code that gives following as an output.
Ans: print('iNeuron'*4)








Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans:
a=int(input())
if a%2 == 0:
    print("even")
else:
    print("odd")

Q18. What are Boolean operator?
Ans: Boolean operator are ‘and’, ‘or’ and ‘not’ and evaluate the true or false of the operand.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
Ans: 
1
0
False
1

Q20. What are conditional statements in Python?
Ans: Conditional statements are used to determine whether the code block would be executed or not.

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans: if is used to check if the condition is satisfied or not. Elif is a optional alternative to the if the condition which is checked if the ‘if’ condition didn’t work. ‘Else’ is used to execute the code block that has pre checked all other conditions.








Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans:
age = int(input("Enter your age"))
if age >=18:
    print("I can Vote")
else:
    print("I Can't Vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans:
numbers = [12, 75, 150, 180, 145, 525, 50]
sum=0
for i in numbers:
    if i%2==0:
        sum=sum+i
print(sum)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans: 
a=int(input("enter the first number"))
b=int(input("enter the second number"))
c=int(input("enter the third number"))
if a > b and a > c:
    print(a)
elif b>a and b>c:
    print(b)
else:
    print(c) 












Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans:

numbers = [12,75,150,180,145,525,50]
for i in numbers:
    if i>500:
        break
    if i%5==0:
        if i<150:
            print(i) 
Q26. What is a string? How can we declare string in Python?

Ans: String is a sequence of character enclosed in quotes. In python, a variable is said to be of string type if it has sequence of character passed to it in single quotes.

Q27. How can we access the string using its index?

Ans: String are ordered in a sequence, so we can access the string using the indexes that start from 0, in square brackets.

Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"

Ans:

def lastword(string):
    newstring=""
    length = len(string)
    for i in range(length-1,0,-1):
        if string[i]==" ":
            return newstring[::-1]
        else:
            newstring=newstring+string[i]

var = "Big Data iNeuron"
print(lastword(var))


Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"

Ans:

def lastword(string):
    newstring=""
    length = len(string)
    for i in range(length-1,0,-1):
        if string[i]==" ":
            return newstring[::]
        else:
            newstring=newstring+string[i]

var = "Big Data iNeuron"
print(lastword(var))

Q30. Resverse the string given in the above question.
Ans:

def reversal(string):
    return string[::-1]
var="Big Data iNeuron"
print(reversal(var))

Q31. How can you delete entire string at once?

Ans: Using the del keyword

Q32. What is escape sequence?

Ans: The sequence characters that has indirect meaning when placed with double quotes.

Q33. How can you print the below string?
'iNeuron's Big Data Course'

Ans: print(“iNeuron's Big Data Course”)


Q34. What is a list in Python?
Ans: A python list contains an ordered and changeable collection of data objects, can hold multiple data type of data.

Q35. How can you create a list in Python?
Ans: By placing elements in square brackets[] separated by comma’s.

Q36. How can we access the elements in a list?
Ans: By using the index of the elements in square brackets.

Q37. Write a code to access the word "iNeuron" from the given list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
Ans: 
	lst=[1,2,3,"Hi",[45,54,"iNeuron"],"Big Data"]
print(lst[4][2])

Q38. Take a list as an input from the user and find the length of the list.
Ans: 
	n = int(input("Enter the nummber of elements in the list"))
lst=[]
for i in range (0,n):
    x =int(input("enter the element"))
    lst.append(x)
print(len(lst))

Q39. Add the word "Big" in the 3rd index of the given list.

lst = ["Welcome", "to", "Data", "course"]
Ans:
lst = ["Welcome", "to", "Data", "course"]

lst.insert(2,"Big")
print(lst)




Q40. What is a tuple? How is it different from list?
Ans: Tuples are used to storage elements of data types but they are immutable and that is also the primary difference between list and tuple.

Q41. How can you create a tuple in Python?
Ans: Tuple is initiated with the () brackets.

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
Ans: tup= tuple()
We can’t add anything to the tuple after it has been declared due to its immutable property.	

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
Ans: tuple1=(1,2) 
	  Tuple2=(3,4)
		Tuple3= tuple1+Tuple2
	print(Tuple3)

Q44. Take a tuple as an input and print the count of elements in it.
Ans:
	numbers = (1, 3, 4, 1, 6 ,1 )
count = numbers.count(1)
print('The count of 1 is:', count)
count = numbers.count(7)
print('The count of 7 is:', count)

Q45. What are sets in Python?
Ans: Set is a collection which is unordered, unchanged and unindexed.

Q46. How can you create a set?
Ans: thisset = {"apple", "banana", "cherry"}
print(thisset)




Q47. Create a set and add "iNeuron" in your set.
Ans:
set1 ={"hello"}
set1.add("iNeuron")
print(set1)

Q48. Try to add multiple values using add() function.
Ans: add() takes only one value at a time.

Q49. How is update() different from add()?
Ans: Update() is used to add sequence value to a set , while add() is used to add a single sequence.

Q50. What is clear() in sets?
Ans: Removes all the elements from the set.

Q51. What is frozen set?
Ans: frozen set is immutable frozenset object initialized with elements.


Q52. How is frozen set different from set?
Ans: Frozen set cant be modified , while we can add elements to set.

Q53. What is union() in sets? Explain via code.
Ans: Union() returns a set which is a union is union of 2 or more sets.
A = {2, 4, 5, 6}
B = {4, 6, 7, 8}
 
print("A U B:", A.union(B))

Q54. What is intersection() in sets? Explain via code.
Ans: intersection() returns a set with common elements in all sets.
A = {2, 3, 5}
B = {1, 3, 5}
print(A.intersection(B))





Q55. What is dictionary in Python?
Ans: Dictionary is a data structure which stores value in key value pair, is ordered, changeable and cannot hold duplicate values.

Q56. How is dictionary different from all other data structures.
Ans: Dictionary holds data in key value pair, and every key has to be unique.

Q57. How can we declare a dictionary in Python?
Ans: Dictionary is declared in curly brackets {} , the key value pair is separated by colon (:) and each key value pair is separated by a comma (,).

Q58. What will the output of the following?

var = {}
print(type(var))
Ans: returns a dictionary type.

Q59. How can we add an element in a dictionary?
Ans: We can add element in dictionary using append().

Q60. Create a dictionary and access all the values in that dictionary.
Ans:
var={'one':'value1','two':'value2'}
print(var['one'])
print(var['two'])

Q61. Create a nested dictionary and access all the element in the inner dictionary.
Ans:
people = {1: {'name': 'John', 'age': '27', 'sex': 'Male'},
          2: {'name': 'Marie', 'age': '22', 'sex': 'Female'}}

print(people[1]['name'])
print(people[1]['age'])
print(people[1]['sex'])


Q62. What is the use of get() function?
Ans: Returns the value of item with the specified key.

Q63. What is the use of items() function?
Ans: Returns a view object , the view object contains the key value pair of dictionary in tuples as a list.

Q64. What is the use of pop() function?
Ans: Removes the elements for the given index in pop().

Q65. What is the use of popitems() function?
Ans: Removes the item that was inserted into the dictionary.

Q66. What is the use of keys() function?
Ans: Returns a list of key in a dictionary is the order they were inserted.



Q67. What is the use of values() function?
Ans: Returns a list of values in the dictionary in the form of a list.

Q68. What are loops in Python?
Ans: Loops are used to iterate over a list or tuple or dictionary.

Q69. How many type of loop are there in Python?
Ans: Two, for loop and while loop.

Q70. What is the difference between for and while loops?
Ans: For loop iterate till the known number of iteration is complete. While loop iterate till the condition provided is false.

Q71. What is the use of continue statement?
Ans: Its use to skip an iteration in a loop.


Q72. What is the use of break statement?
Ans: Used to terminate the execution of a loop.

Q73. What is the use of pass statement?
Ans: is a type of null operator, when we don’t want to do anything when the condition is satisfied.

Q74. What is the use of range() function?
Ans: returns a sequence of numbers from 0 default to number specified and increments by 1 by default.

Q75. How can you loop over a dictionary?
Ans: 
for x, y in thisdict.items():
  print(x, y)




Q76. Write a Python program to find the factorial of a given number.
Ans: 
def factorial(num):
    sum=1
    for i in range(0,num):
        sum=sum*num
        num = num-1
    print(sum)
fact = int(input("Enter a number to get fatorial\n"))
factorial(fact)

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100
Ans:
def simpleinterest(p,r,t):
    sum = 0
    sum = (p * r * t)
    sum = sum/100
    print(sum)
principal = int(input("Enter the principal amount \n"))
rate = int(input("Enter the interest rate \n"))
time = int(input("Enter the number of years \n"))
simpleinterest(principal,rate,time)


Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
Ans: 
def compoundinterest(p,r,t):
    sum = 0
    sum = p*(pow((1+r/100),t))
    print(sum)

principal = int(input("Enter the principal amount \n"))
rate = float(input("Enter the interest rate \n"))
time = int(input("Enter the number of years \n"))
compoundinterest(principal,rate,time)


Q79. Write a Python program to check if a number is prime or not.
Ans: 
def primenumber(num):
    if(num>1):
        if (num % 2)==0:
            print("Is a prime number")
        else:
            print("Is not a prime number")
    else:
        print("Enter a valid number")
prime = int(input("Enter the number to check\n"))
primenumber(prime)







Q80. Write a Python program to check Armstrong Number.
Ans: 

def power(x, y):
    
    if y == 0:
        return 1
    if y % 2 == 0:
        return power(x, y // 2) * power(x, y // 2)
        
    return x * power(x, y // 2) * power(x, y // 2)

def order(x):
    n = 0
    while (x != 0):
        n = n + 1
        x = x // 10     
    return n

def isArmstrong(x):
    
    n = order(x)
    temp = x
    sum1 = 0
    
    while (temp != 0):
        r = temp % 10
        sum1 = sum1 + power(r, n)
        temp = temp // 10
    return (sum1 == x)
x = 153
print(isArmstrong(x))


Q81. Write a Python program to find the nth Fibonacci Number.
Ans:
def fibonaci(n):
    a=0
    b=1
    if n<0:
        print("Incorrect Input")
    elif n==0:
        return a
    elif n==1:
        return b
    else:
        for i in range(2,n):
            c = a+b
            a=b
            b=c
        return b
print(fibonaci(9))






Q82. Write a Python program to interchange the first and last element in a list.
Ans:
def swap(lst):
    b=len(lst)-1
    bucket = lst[0]
    lst[0] = lst[b]
    lst[b] = bucket

lst=[1,2,3,4,5,6,7,8,9,10]
swap(lst)
print(lst)


Q83. Write a Python program to swap two elements in a list.
Ans:
def swapPositions(list, pos1, pos2):
    
    list[pos1], list[pos2] = list[pos2], list[pos1]
    return list
List = [23, 65, 19, 90]
pos1, pos2 = 1, 3
print(swapPositions(List, pos1-1, pos2-1))


Q84. Write a Python program to find N largest element from a list.
Ans:
def nthlargest(lst , n):
    size = len(lst)-1
    for i in range(size):
        for j in range(size):
            if lst[j] > lst[j+1]:
                bucket = lst[j]
                lst[j] = lst[j+1]
                lst[j+1] = bucket
    n=n-1
    print(lst[n])

lst =[10,9,8,7]
n = int(input("Enter the nth number \n"))
nthlargest(lst,n)


Q85. Write a Python program to find cumulative sum of a list.
Ans:
def wholesum(lst):
    size=len(lst)
    y=0
    for i in range(size):
        y = y + lst[i]
    print(y)  

lst=[1,2,3,4,5,6,7,89,0]
wholesum(lst)


Q86. Write a Python program to check if a string is palindrome or not.
Ans:
def palindrome(str):
    a = str[::-1]
    if a == str:
        print("is a palindrome")
    else:
        print("is not a palindrome")

str = input("Enter a string\n")
palindrome(str)

Q87. Write a Python program to remove i'th element from a string.
Ans:
test_str = "GeeksForGeeks"
new_str = test_str.replace('e', '')
print ("The string after removal of i'th character( doesn't work) : " + new_str)
new_str = test_str.replace('s', '', 1)
print ("The string after removal of i'th character(works) : " + new_str)

Q88. Write a Python program to check if a substring is present in a given string.
Ans:
def checksubstring(str , masterstr):
    if str in masterstr:
        print(str+" is a substring")
    else:
        print(str+" is not a substring")

masterstr= input("Enter a master string\n")
str = input("Enter a substring to check\n")
checksubstring(str,masterstr)

 
Q89. Write a Python program to find words which are greater than given length k.
Ans:
def greaterthenk(str):
    p = str.split(" ")
    lst=[]
    for i in p:
        if len(i) > 3:
            lst.append(i)   
    print(lst)
str = input("Enter a Sentence \n")
greaterthenk(str)


Q90. Write a Python program to extract unquire dictionary values.
Ans:
test_dict = {'gfg': [5, 6, 7, 8],
            'is': [10, 11, 7, 5],
            'best': [6, 12, 10, 8],
            'for': [1, 2, 5]}
print("The original dictionary is : " + str(test_dict))
res = list(sorted({ele for val in test_dict.values() for ele in val}))
print("The unique values list is : " + str(res))






Q91. Write a Python program to merge two dictionary.
Ans:
def Merge(dict1, dict2):
    return(dict2.update(dict1))
dict1 = {'a': 10, 'b': 8}
dict2 = {'d': 6, 'c': 4}
print(Merge(dict1, dict2))
print(dict2)


Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Ans:
def convert(tup,di):
    di = dict(tup)
    return di
tup=[('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
di={}
print(convert(tup,di))
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
Ans:	
list1 = [1, 2, 5, 6]
res = [(val, val**3) for val in list1]
print(res)


Q94. Write a Python program to get all combinations of 2 tuples.
Ans:
test_tuple1 = (7, 2)
test_tuple2 = (7, 8)
res = [(a, b) for a in test_tuple1 for b in test_tuple2]
res = res + [(a, b) for a in test_tuple2 for b in test_tuple1]
print("The filtered tuple : " + str(res))


Q95. Write a Python program to sort a list of tuples by second item.
Ans:
def Sort_Tuple(tup):
    lst = len(tup)
    for i in range(0, lst):
        for j in range(0, lst-i-1):
            if (tup[j][1] > tup[j + 1][1]):
                temp = tup[j]
                tup[j]= tup[j + 1]
                tup[j + 1]= temp
    return tup
tup =[('for', 24), ('is', 10), ('Geeks', 28),
    ('Geeksforgeeks', 5), ('portal', 20), ('a', 15)]    
print(Sort_Tuple(tup))


Q96. Write a python program to print below pattern.

* 
* * 
* * * 
* * * * 
* * * * * 
Ans:
n=int(input("Enter the number of star you want"))
for i in range(0,n+1):
    print(i *' * ' ) 


Q97. Write a python program to print below pattern.

    *
   **
  ***
 ****
*****
Ans:
n=5;i=0
while(i<=n):
    print(" " * (n - i) +"*" * i)
    i+=1






Q98. Write a python program to print below pattern.

    * 
   * * 
  * * * 
 * * * * 
* * * * * 
Ans:
n=int(input("Enter the number of star you want"))
for i in range(0,n+1):
    p=n-i
    print(p * ' ',i * ' *' ) 


Q99. Write a python program to print below pattern.

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
Ans:


n=6
for i in range (1,n):
    for j in range(1,i+1):
        print(j , end=' ')
    print('')


Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 
Ans:
for i in range (65,70):
    # inner loop
    for j in range(65,i+1):
        print(chr(i),end="")
    print()


