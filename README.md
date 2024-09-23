print("Select operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")
choice = input("Enter choice (1/2/3/4): ")
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
if choice == '1':
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")

elif choice == '2':
    result = num1 - num2
    print(f"{num1} - {num2} = {result}")

elif choice == '3':
    result = num1 * num2
    print(f"{num1} * {num2} = {result}")

elif choice == '4':
    if num2 != 0:
        result = num1 / num2
        print(f"{num1} / {num2} = {result}")
    else:
        print("Error! Division by zero.")
else:
    print("Invalid input. Please enter a number between 1 and 4.")
cont = input("Do you want to perform another calculation? (yes/no): ")
if cont == 'yes':
    print("Restarting calculator...")
else:
    print("Exiting calculator. Have a nice day!")
cont = input("Do you want to perform another calculation? (yes/no): ")
