# program-97
# Input number
number = int(input("Enter a positive integer: "))

rev = 0
num = number  # Keep original number if needed

# Reverse the number
while number != 0:
    digit = number % 10
    rev = (rev * 10) + digit
    number = number // 10

# Print the reversed number
print("The reversed number is:", rev)
output
Enter a positive integer: 12345
The reversed number is: 54321
