# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

L=[153,147,124,102] 
 
print(sum(L)))

## Output
<img width="514" height="192" alt="image" src="https://github.com/user-attachments/assets/60731c99-3728-473b-b1a3-b6cfe8a1fecc" />


## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
import re
l1=[] 

items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
for i in items: 

   if not re.search(r"e",i): 
      l1.append(i) 

print(l1)

## Output
<img width="367" height="133" alt="image" src="https://github.com/user-attachments/assets/149e99b1-45bb-4ff4-a9c1-fed9e80efa63" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
def remove(a,n):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
a=input()
n=int(input())
remove(a,n)


## Output
<img width="640" height="130" alt="image" src="https://github.com/user-attachments/assets/a6df531e-8932-435f-b2d4-6265d99ce131" />


## Result
Thus,the program was implemented and executed successfully,and the required output was obtained
# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
a=eval(input())
print("n" not in a)
print("8" in a)

## Output
<img width="688" height="173" alt="image" src="https://github.com/user-attachments/assets/50bf3b25-4e01-4d04-baf6-8aa018996b59" />


## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
a=eval(input())
print("n" not in a)
print("8" in a)

## Output
<img width="688" height="173" alt="image" src="https://github.com/user-attachments/assets/5947ec6d-415f-4508-94fd-bba952f9e10c" />


## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
