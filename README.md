python calculator

first_number =int(input("Please enter the first number: "))
second_number =int(input("Please enter the second number: "))

operator = input("choose an operator ['+','-','*','/']: ")



if operator == '+':
        result = first_number + second_number

elif operator == '-':
        result = first_number - second_number

elif operator == '*':
        result = first_number * second_number

elif operator == '/':
        result = first_number / second_number

else:
        print("Please choose an operator!")

print(f"{first_number} {operator} {second_number} = {result}")

