# User Input & Output
```python
name = input("Enter your full name: ")
print("Nice to meet you,", name)
```

# Arithmetic Operators
```python
length = int(input("Enter length of rectangle: "))
width = int(input("Enter width of rectangle: "))

print("Area =", length * width)
print("Perimeter =", 2 * (length + width))
```

# Comparison Operators
```python
temperature = int(input("Enter temperature: "))

print(temperature > 30)
print(temperature == 25)
print(temperature <= 15)
```

# Logical Operators
```python
salary = int(input("Enter salary: "))
is_employee = True

print(salary > 20000 and is_employee)
print(salary < 15000 or is_employee)
print(not is_employee)
```

# Even or Odd Check
```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```

# Ternary (Conditional Expression)
```python
age = int(input("Enter age: "))
status = "Adult" if age >= 18 else "Minor"
print(status)
```

# Switch Case Alternative (match-case) – Python 3.10+
```python
month = int(input("Enter month number: "))

match month:
    case 1:
        print("January")
    case 2:
        print("February")
    case 3:
        print("March")
    case _:
        print("Invalid month")
```

# Data Types & Type Checking
```python
x = 10
y = 3.5
name = "Python"

print(type(x))
print(type(y))
print(type(name))
```

# Type Conversion
```python
num1 = input("Enter first number: ")
num2 = input("Enter second number: ")

total = int(num1) + int(num2)
print("Total =", total)
```

# Loops (for)
```python
for i in range(1, 6):
    print(i)
```

# Loops (while)
```python
count = 1
while count <= 5:
    print(count)
    count += 1
```

# Break & Continue
```python
for i in range(1, 6):
    if i == 3:
        continue
    if i == 5:
        break
    print(i)
```

# Functions
```python
def greet(name):
    print("Hello", name)

greet("Student")
```

# Lists (Collections)
```python
marks = [85, 90, 78, 92]
print(marks)
print(marks[0])
```
# String Operations
```python
text = "python programming"
print(text.upper())
print(text.capitalize())
print(len(text))
```

# Exception Handling
```python
try:
    num = int(input("Enter a number: "))
    print(10 / num)
except ZeroDivisionError:
    print("Cannot divide by zero")
except ValueError:
    print("Invalid input")
```

# Basic File Handling
```python
with open("data.txt", "w") as file:
    file.write("Hello Python")
```
