def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        raise ValueError("Cannot divide by zero")
    return x / y

def factorial(n):
    if n < 0:
        raise ValueError("Factorial is not defined for negative numbers")
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n-1)

def main():
    print("Calculator")
    num1 = float(input("Enter first number: "))
    operation = input("Enter operation (+, -, *, /, !): ")
    num2 = float(input("Enter second number: "))

    if operation == "+":
        result = add(num1, num2)
    elif operation == "-":
        result = subtract(num1, num2)
    elif operation == "*":
        result = multiply(num1, num2)
    elif operation == "/":
        result = divide(num1, num2)
    elif operation == "!":
        result = factorial(num1)
    else:
        print("Invalid operation")
        return

    print(f"Result: {result}")

if __name__ == "__main__":
    main()