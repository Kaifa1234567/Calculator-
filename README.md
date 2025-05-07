Step 1: Choose Language

Python (console-based)

JavaScript (for web)

C++

Java

Something else?


Step 2: Basic Example (Python)

Here's a simple Python calculator script:

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Cannot divide by zero."
    return x / y

print("Select operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = input("Enter choice (1/2/3/4): ")

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

if choice == '1':
    print("Result:", add(num1, num2))
elif choice == '2':
    print("Result:", subtract(num1, num2))
elif choice == '3':
    print("Result:", multiply(num1, num2))
elif choice == '4':
    print("Result:", divide(num1, num2))
else:
    print("Invalid input")

Step 3: Push to GitHub

1. Create a new repo on GitHub.


2. Save the script (e.g., calculator.py).


3. Use git:

git init
git add calculator.py
git commit -m "Add basic calculator"
git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main

