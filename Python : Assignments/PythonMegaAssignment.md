## Assignment Part-1
**Q1. Why do we call Python as a general purpose and high-level programming language?**

Ans. Python is called general-purpose programming language because it can be used to solve wide variety of problems in diffrent domains also it is called high-level programming language because it is easy for humans to understand.

**Q2. Why is Python called a dynamically typed language?**

Ans. Python is called as dynalically typed language because the type of variable is not defined while assigning the value and its decided during runtime.

**Q3. List some pros and cons of Python programming language?**

Ans. PROS of Python
        -  Easy to understand
        -  High speed development
        -  Portable and Extensible
        -  Can be used in multiple domains
     CONS of Python
        - Execution speed is less as compared to other languages like C,C++ and Java
        - There is no multithreading in Python
        - High memory consumption
        - Cannot used for native mobile app development

**Q4. In what all domains can we use Python?**

Ans. 1. Machine Learning and Artificial Intelligence
     2. Data Analytics and Data Visualization
     3. Web Development
     4. Game Development
     5. Embedded Systems
     6. Mobile App Development

**Q5. What are variable and how can we declare them?**

Ans. Variable is the name of a memory location. The synatac for variable declaration is as follows
     ``` 
     <variable_name> = <variable_value>
    e.g   name = "iNeuron"
          age = 14
	  ```
	  
**Q6. How can we take an input from the user in Python?**
Ans. By using input() function
   ``` 
   e.g name = input('Enter your name :')
   ```
**Q7. What is the default datatype of the value that has been taken as an input using input() function?**

Ans. 'str' (String)

**Q8. What is type casting?**

Ans. Type casting the process of converting the varible/value from one datatype to another datatype

**Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?**

Ans. Yes we can take the multiple inputs using single input() function followed by split() function.

**Q10. What are keywords?**

Ans. Keywords are the in-build  reserved words which have specific meaning and can be used for syntactical use only and cannot be used for user defined variables.

**Q11. Can we use keywords as a variable? Support your answer with reason.**

Ans. We can't use keywords as a variable because keywords are reserved for syantactical use only and not for used defined variables.

**Q12. What is indentation? What's the use of indentaion in Python?**

Ans. Indentation is the space/spaces at the beginning of the code line. Indentation is used in python to indicate the block of code.

**Q13. How can we throw some output in Python?**

Ans. Using print() function
   e.g print("Welocme to iNeuron")
   
   
**Q14. What are operators in Python?**

Ans. Operatoes are the spacial symbols which are used to carr out operaions on variables or values

**Q15. What is difference between / and // operators?**

Ans.  '/' is used for float division. '//' is used for integer division

**Q16. Write a code that gives following as an output**.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans.     
         
        
        print('iNeuron'*4)
        
        
**Q17. Write a code to take a number as an input from the user and check if the number is odd or even.**
Ans.    
    
    
    number = int(input('Enter a number : '))
    
    if(number % 2 == 0):
    
        print('Even')
        
    else:
    
        print('Odd')
        
    
**Q18. What are boolean operator?**

Ans. Boolean operators are reserved words "AND", "OR", "NOT" which can be used to evaluate multiple expressions and achieve more precise results

**Q19. What will the output of the following?**
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Ans.    
         
        
        1 or 0  - 1
        0 and 0   - 0
        True and False and True - False
        1 or 0 or 0  - 1
        
**Q20. What are conditional statements in Python?**

Ans. Conditional Statements are used for handle conditions for decision making in Python. 
     Conditional Statmenst = if, if..else , nested if..else 
     
**Q21. What is use of 'if', 'elif' and 'else' keywords?**

Ans. - if ised to evaluate an enclosed condiion
     - elsif is used to evaluate an enclosed condtion when previous consditions are failed
     - else is use dto display default output when all the previous conditions are resulted as false
     
**Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote"**.
Ans.
    
    age = int(input('Enter your age : '))
    
    if(age >= 18):
    
        print("I can vote")
        
    else:
    
        print("I can't vote")
        
    
**Q23. Write a code that displays the sum of all the even numbers from the given list.**
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans. 
        
        numbers = [12, 75, 150, 180, 145, 525, 50]
        
        evenSum= 0
        
        for i in range(0,len(numbers)):
        
            if (numbers[i] % 2 == 0):
            
                evenSum = evenSum + numbers[i];
                
        print("Sum : ", evenSum)
        
        
        
        
**Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.**
Ans. 
    
    x = int(input('Enter first number : '))
    
    y = int(input('Enter second number : '))
    
    z = int(input('Enter third number : '))
    
    print("Greatest Number : ", max(x,y,z))
    
    
    
    
**Q25. Write a program to display only those numbers from a list that satisfy the following conditions**
- The number must be divisible by five
- If the number is greater than 150, then skip it and move to the next number
- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans.
    
    numbers = [12, 75, 150, 180, 145, 525, 50]
    
    for i in numbers:
    
        if (i % 5 == 0):
        
            if (i > 150):
            
                if(i > 500):
                
                    break
                    
                continue
                
            else:
            
                print(i)
                
**Q26. What is a string? How can we declare string in Python?**


Ans. String is a sequence of characters.
    
     name = "Akash"
    

**Q27. How can we access the string using its index?**

Ans. using index
     
     
     print(name[0)
     

**Q28. Write a code to get the desired output of the following**
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```

Ans.     
	string = "Big Data iNeuron"
	
	print(string.split(' ')[2])
	
	

**Q29. Write a code to get the desired output of the following**
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```
Ans. 
	 
	 string = "Big Data iNeuron"
	 
	 print(string.split(' ')[2][::-1])
	 

**Q30. Resverse the string given in the above question.**

Ans. 
		
		string = "Big Data iNeuron"
		
		print(string[::-1])
		
**Q31. How can you delete entire string at once?**

Ans.  Using del command
     
**Q32. What is escape sequence?**

Ans. An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters.

**Q33. How can you print the below string?**
```
'iNeuron's Big Data Course'
```

And. print('iNeuron\'s Big Data Course')

**Q34. What is a list in Python?**

Ans. List is a sequential data type which is used to store elements of diffrent type in a sequential manner

**Q35. How can you create a list in Python?**

Ans.
     newList =[1,2,3,4,5]

**Q36. How can we access the elements in a list?**

Ans. using index
     print(newList[1])

**Q37. Write a code to access the word "iNeuron" from the given list.**
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 

Ans. 

    lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
    
    print(lst[4][2])

**Q38. Take a list as an input from the user and find the length of the list.**

Ans.


	lst=[]

	no = int(input("Enter the number of elements : "))

	for i in range(0,no):

   	el= int(input("Enter the element-"))
	
	lst.append(el)
    
	print("Length of the list : ",len(lst))


**Q39. Add the word "Big" in the 3rd index of the given list.**
```
lst = ["Welcome", "to", "Data", "course"]
```

Ans. 

	lst = ["Welcome", "to", "Data", "course"]

	lst.insert(2,"Big")

	print(lst)


**Q40. What is a tuple? How is it different from list?**

Ans. Tuple is a sequential data type which is used to store elements of diffrent type in a sequential manner. Tuple is immutable while list is mutable.


**Q41. How can you create a tuple in Python?**

Ans.

    newTuple = ('1','Test', 2.3,'New')

**Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.**

Ans. 	We cannot add anything in the tuple as tuple is immutable.

**Q43. Can two tuple be appended. If yes, write a code for it. If not, why?**

Ans.    YES

	tup1 = (1,2,3)
	tup2 = (4,5,6)
	tup3 = tup1 + tup2
	print(tup3)

**Q44. Take a tuple as an input and print the count of elements in it.**

Ans. 
	tup1 = (1,2,3)
	print(len(tup1))

**Q45. What are sets in Python?**

Ans. Sets are collection of unique data.

**Q46. How can you create a set?**

Ans .

    	 #Method-1
	 set1 = {1,1,2,3,4,5,3,4,5,6}
	 print(set1)
	 
	 
	 #Method2
     	 set1 = set([1,1,2,3,4,1,2,3,5])
	 print(set1)

**Q47. Create a set and add "iNeuron" in your set.**

Ans.

	set1 = set([])
	set1.add('iNeuron')
	print(set1)

**Q48. Try to add multiple values using add() function.**

Ans.

	set1 = set([])
	set1.add('iNeuron','Hello','Bye')
	print(set1)
	
	It will give error as add() function accepts only one arguement

**Q49. How is update() different from add()?**

Ans.
      The update() method updates the current set, by adding items from another set (or any other iterable). 
      add() method simply add one elemnst at a time  current set. update() can add multiple elements at a time in current set.

**Q50. What is clear() in sets?**

Ans. clear() will remove all the elements from the set

**Q51. What is frozen set?**

Ans.  Frozen set in python is an immutable set.

**Q52. How is frozen set different from set?**

Ans. Set is mutable while frozen set is immutable

**Q53. What is union() in sets? Explain via code.**

Ans. Union of two given sets is the set which contains all the elements of both the sets.

	 set1 = {1,2,3,4}
	 set2 = {2,3,6,7}
	 print(set1.union(set2))

**Q54. What is intersection() in sets? Explain via code.**

Ans. intersection of two given sets is the set which contains the common elements of both the sets.

	 set1 = {1,2,3,4}
	 set2 = {2,3,6,7}
	 print(set1.intersection(set2))  
	 
**Q55. What is dictionary in Python?**

Ans. Dictionaries are used to store data values in key:value pairs. A dictionary is a collection which is ordered*, changeable and do not allow duplicates

**Q56. How is dictionary different from all other data structures.**

Ans. Dictionary contains key,value pairs while other data structures contains only values

**Q57. How can we delare a dictionary in Python?**

Ans. dict1 = {}

**Q58. What will the output of the following?**
```
var = {}
print(type(var))
```
Ans.  <class 'dict'>

**Q59. How can we add an element in a dictionary?**

Ans.

	var = {}
	var['Name'] = 'Akash'
	var['Age'] = 25
	print(var)

**Q60. Create a dictionary and access all the values in that dictionary.**

Ans.

	var = {}
	var['Name'] = 'Akash'
	var['Age'] = 25
	print(var.keys())

**Q61. Create a nested dictionary and access all the element in the inner dictionary.**

Ans.
	
	dict1 = {'data': {'Name': 'John', 'Age': 21}}
	print(dict1['data'])

**Q62. What is the use of get() function?**

Ans. To get the value of dictionary key

**Q63. What is the use of items() function?**

Ans.  To get all the key,value pairs from dictionary

**Q64. What is the use of pop() function?**

Ans. To remove the key,value pair of dictionary key

**Q65. What is the use of popitems() function?**

Ans. The popitem() method removes the item that was last inserted into the dictionary. 

**Q66. What is the use of keys() function?**

Ans. To display all the keys from dictionary

**Q67. What is the use of values() function?**

Ans. To display all the values from dictionary

**Q68. What are loops in Python?**

Ans.  A loop is an instruction that repeats multiple times as long as some condition is met

**Q69. How many type of loop are there in Python?**

Ans. There are two types of loops in python. For loop and While Loop

**Q70. What is the difference between for and while loops?**

Ans. A for loop is a single-line command that will be executed repeatedly. While loops can be single-lined or contain multiple commands for a single condition.
    For loop is used when number of iterations are known. While loop is used when number of iterations are unknown. 

**Q71. What is the use of continue statement?**

Ans.  Continue statement is used to jump to ther next iretaion bypassing the remaining statements from the loop block

**Q72. What is the use of break statement?**

Ans. Break is used to break the loop and go out of it.

**Q73. What is the use of pass statement?**

Ans. The pass statement is used as a placeholder for future code. When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed.

**Q74. What is the use of range() function?**

Ans. The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

**Q75. How can you loop over a dictionary?**

Ans.

	dict1 = {'Name': 'John', 'Age': 21, 'date': '1-1-2022'}
	for i in dict1.items():
		print(i)
		
**Q76. Write a Python program to find the factorial of a given number.**

Ans.

		def factorial(no):
		if no == 1 or no == 0:
			return no
		else:
			no =  no * factorial(no-1);
		return no
    
		no =  8
		print(factorial(no))

**Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100**

Ans.

		P = 1000
		R = 8
		T = 2
		SI = (P*R*T)/100
		print('Simple Interest : ', SI)


**Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.**

Ans.

		P = 1000
		R = 8
		T = 2
		A = P*(1+ R/100)**T
		print('Compund Interest : ', A)

**Q79. Write a Python program to check if a number is prime or not.**

Ans.

		import math

		def isPrime(no):
			if(no == 0):
				res = "Neither Prime nor a composite number"
				return res
				
			if (no == 1):
				res = "Not Prime"
				return res
				
			for i in range(2,math.ceil(no/2)):
				if(no % i  == 0):
					flag = 1
					break
				else:
					flag = 0

			res = "Prime" if flag == 0 else "Not Prime"
			return res
			
		no = 101
		print(isPrime(no))

**Q80. Write a Python program to check Armstrong Number.**

Ans.

		no = 371
		stringNo = str(no)
		lst =[]
		sum = 0
		for i in range(0,len(stringNo)):
			sum = sum + (int(stringNo[i])**3)

		if(no == sum):
			print(no, " is an Armstrong Number")
		else:
			print(no, "is not an Armstrong Number")


### Coding problems

**Q81. Write a Python program to find the n-th Fibonacci Number.**

Ans.

		def Fibonacci(no):
			if no <= 0 :
				print ("Wrong Input.Please enter number greater than 0")
				
			elif no == 1:
				return 0
				
			elif no == 2:
				return 1
				
			else:
				return Fibonacci(no-1) + Fibonacci(no-2)

		no = 10
		print(Fibonacci(no))
        

**Q82. Write a Python program to interchange the first and last element in a list.**

Ans.

		lst = [1,2,3,4,5]
		temp = lst[0]
		lst[0] = lst[len(lst)-1]
		lst[len(lst)-1] = temp
		print(lst)

**Q83. Write a Python program to swap two elements in a list.**

Ans.

		def swapPositions(lst,pos1,pos2):
			lst[pos1],lst[pos2] = lst[pos2] ,lst[pos1]
			return lst
			
		lst = [1,2,3,4,5,6,7]
		print(swapPositions(lst,2,4))

**Q84. Write a Python program to find N largest element from a list.**

Ans.

		lst = [3,12,1,23,56,34,78,98]
		lst.sort(reverse=True)
		print("3rd Largest Element :", lst[2])

**Q85. Write a Python program to find cumulative sum of a list.**

Ans.

		lst = [4, 10, 15, 18, 20]
		for i in range(1,len(lst)):
			lst[i] = lst[i-1]+lst[i]
		print(lst)
		

**Q86. Write a Python program to check if a string is palindrome or not.**

Ans.

		newStr =  'ABAB'
		res = "Palindrome" if (newStr[::-1] == newStr) else "Not Palindrome"
		print(res)

**Q87. Write a Python program to remove i'th element from a string**.

Ans.

		str = "TestString"
		str= str.replace(str[1],'')
		print(str)


**Q88. Write a Python program to check if a substring is present in a given string**.

Ans.

		str = "TestString"

		if "Stri" in str:
			print("Substring")
		else:
			print("Not a Substring")

**Q89. Write a Python program to find words which are greater than given length k.**

Ans.

		newString = "Big data is a combination of structured, semistructured and unstructured data collected by organizations that can be mined for information and used in machine learning projects, predictive modeling and other advanced analytics applications."

		length = 4
		lst= newString.split(" ")
		newLst =[]
		for i in lst:
			if len(i) > length:
				newLst.append(i)
		print(newLst)



**Q90. Write a Python program to extract unquire dictionary values.**

Ans.

		dict = {'Name' : 'John' , 'Age' : 25, 'Name' : 'John', 'Age': 25}
		print(dict.values())

**Q91. Write a Python program to merge two dictionary.**

Ans.

		dict1 = {'Name' : 'John' , 'Age' : 25}
		dict2 = {'Address' : 'Pune'}
		dict1.update(dict2)
		print(dict1)

**Q92. Write a Python program to convert a list of tuples into dictionary.**
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```

Ans.

		lst = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
		newDict= {}
		for i in lst:
			newDict[i[0]]= i[1]
		print(newDict)

**Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.**
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```

Ans.


		lst = [9, 5, 6]
		newLst= []
		for i in lst:
			tup =(i, i**3)
			newLst.append(tup)
		print(newLst)


**Q94. Write a Python program to get all combinations of 2 tuples.**
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```

Ans.


		test_tuple1 = (7, 2) 
		test_tuple2 = (7, 8)
		lst=[]
		lst.append(tuple([test_tuple1[0],test_tuple2[0]]))
		lst.append(tuple([test_tuple1[0],test_tuple2[1]]))
		lst.append(tuple([test_tuple1[1],test_tuple2[0]]))
		lst.append(tuple([test_tuple1[1],test_tuple2[1]]))

		lst.append(tuple([test_tuple2[0],test_tuple1[0]]))
		lst.append(tuple([test_tuple2[0],test_tuple1[1]]))
		lst.append(tuple([test_tuple2[1],test_tuple1[0]]))
		lst.append(tuple([test_tuple2[1],test_tuple1[1]]))

		print(lst)

**Q95. Write a Python program to sort a list of tuples by second item.**
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```

Ans.

		def Sort(lst):
			lst.sort(key = lambda a : a[1])
			return lst

		lst = [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
		print(Sort(lst))

**Q96. Write a python program to print below pattern.**
```
* 
* * 
* * * 
* * * * 
* * * * * 
```

Ans.

		for i in range(1,6):
			print("* "*i)
			
**Q97. Write a python program to print below pattern**.
```
    *
   **
  ***
 ****
*****
```

Ans.

		j=1
		for i in range(4,-1,-1):
			print(" "*i + "*"*j)
			j+=1

**Q98. Write a python program to print below pattern.**
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```
Ans.

		i=1
		for j in range(4,-1,-1):
			print(" "*j + "* "*i)
			i+=1


**Q99. Write a python program to print below pattern.**
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```

Ans.

		for i in range(1,6):
			for j in range(1,i+1):
				print(j,end=' ')
			print()

**Q100. Write a python program to print below pattern.**
```
A 
B B 
C C C 
D D D D 
E E E E E 
```

Ans.

		lst = ['A','B','C','D','E']
		for i in range(0,len(lst)):
			for j in range(0,i+1):
				print(lst[i],end=' ')
			print()

     
