## List Operations in Python: Sum of List Items
## Aim
To write a Python program that calculates the sum of all even elements in a list.

## Algorithm
1.Start

2.Define a function createlist(n)

3.Initialize an empty list l

4.Loop i from 1 to n-1

5.If i is divisible by 2 (i.e., even), append it to l

6.Print the list l

7.Calculate and print the sum of elements in l using sum(l)

8.End

## Program
```
def createlist(n):
    l=[]
    for i in range(1,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list = ",sum(l))
```
## output
<img width="1047" height="295" alt="image" src="https://github.com/user-attachments/assets/7894efd3-063b-4318-90fc-24409d4d7812" />
## Result
Thus Python program to calculate the sum of all even elements in a list is executed successfully.

Regex in Python: Filter Words Without the Letter 'e'
## Aim
To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

## Algorithm
Import the re module.
Initialize an empty list l1 to store results.
Define a list of words:
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
Iterate through each word in the list:
Use re.search(r"e", i) to check if the word contains 'e'.
If not, append the word to l1.
Print the final filtered list.
## Program
```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
fg= [word for word in items if not re.search('e', word)]
print(fg)
```
## output
<img width="918" height="228" alt="image" src="https://github.com/user-attachments/assets/c5deaf97-6b9d-42b4-87cf-72bb853098be" />
## Result
Thus Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) is executed successfully.

Module-3
🧹 Strings-Remove Nth Index Character from a String
## Aim
To write a Python program that accepts a string and joins the character after a each character.

## Algorithm
1.Start

2.Define a function joinstring(text)

3.Use "-".join(text) to insert hyphens between characters of the string text

4.Store the result in a variable result

5.Print result

6.End

## Program
```
def joinstring(text):
    result = "-".join(text)
    print(result)
```
## output
<img width="1036" height="305" alt="image" src="https://github.com/user-attachments/assets/94111ec0-286f-4a61-9c41-ef77f8d57903" />
## Result
Thus the Python program that accepts a string and joins the character after a each character is executed successsfully.

Strings-Palindrome Check in Python (Without Built-in Functions)
## Aim
To write a Python program to check whether the given string is a palindrome or not, without using built-in palindrome checking functions.

## Algorithm
Assign the string "google" to a variable.
Reverse the string manually using slicing ([::-1]).
Compare the original string with the reversed string.
If they are equal, print that the string is a palindrome.
Otherwise, print that it is not a palindrome.
Execute the program.
## Program
```
def palindrome(a):
    mid=len(a)//2
    start=0
    last=len(a)-1
    flag=1
    while start<=mid:
        if a[start]!=a[last]:
            flag=0
            break
        start+=1
        last-=1
    if flag:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
string=input()
palindrome(string)
```
## output
<img width="1043" height="227" alt="image" src="https://github.com/user-attachments/assets/3d6779d0-4b97-4815-9b79-29c0b77fb0ff" />
## Result
Thus the Python program to check whether the given string is a palindrome or not is executed successfully.

Tuple in Python: Check Element Existence
## Aim
To write a Python program that checks if the element 'n' and the element 52 and 12 exist within a given tuple.

## Algorithm
Define a tuple x with some letters and numbers.
Use the in operator to check if the string 'n' exists within the tuple.
Use the in operator to check if the integer 52 and 12 exists within the tuple.
Print the results.
## Program
```
a=eval(input())
print(True if '52' in a else False)
print(True if '12' in a else False)
```
## output
<img width="1033" height="296" alt="image" src="https://github.com/user-attachments/assets/c239b9ae-2c10-437a-bd46-a363781575c2" />
## Result
Thus Python program that checks if the element 'n' and the element 52 and 12 exist within a given tuple is executed successfully.





