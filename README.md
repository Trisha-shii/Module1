# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program :
```python
num=int(input())
if(num%2==0):
      print("Even")
else:
    print("Odd")
```

## Output :
![image](https://github.com/user-attachments/assets/e07d3200-944b-44cb-b289-fa772851ed0c)


## Result :
Thus the program has been successfully executed.



# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```python
a = (0 == True)
b = (False== False)
c = True + True
d = False + 9
print('a is',a)
print('b is',b)
print('c:',c)
print('d:',d)
```

## Output
![image](https://github.com/user-attachments/assets/a955e47e-ccbe-4da9-960b-08017550c88c)

## Result
Thus, the program as been excuted successfully.



# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```python
v='T'
b='a'
print(v)
print(b)
```

## Output
![image](https://github.com/user-attachments/assets/2bde6e65-a6dd-423f-b90c-9afa6d5db70d)


## Result
Thus, the program is executed sucessfully.


# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```python
x=int(input(''))
y=int(input(''))
x=complex(x,y)
print(x)
print(x.real)
print(x.imag)
```

## Output
![image](https://github.com/user-attachments/assets/f2df7318-dd26-4e5e-8dfa-5a31d0e79334)

## Result
Thus, the program as been executed successfully.
