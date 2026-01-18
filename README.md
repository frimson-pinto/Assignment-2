Task1.py — Even or Odd Checker
📌 Purpose
This program checks whether a given number is even or odd using a conditional expression (ternary operator).
Logic Used

Take an integer input from the user
If number % 2 == 0 → Even
Else → Odd
🧾 Code
num = int(input("Enter a number:"))
print(num, "is an even number") if num % 2 == 0 else print(num, "is an odd number")

▶ How It Works (Example)
Input:
Enter a number: 7
Output:
7 is an odd number
Input:
Enter a number: 10
Output:
10 is an even number

 Task2.py — Sum of Numbers from 1 to 50
📌 Purpose
This program calculates the sum of numbers from 1 to 50 using a for loop.
🧠 Logic Used
Initialize sum = 0
Loop from 1 to 50
Add each number to sum
Print final sum
🧾 Code
sum = 0
for i in range(1, 51):
    sum = sum + i

print("The sum of numbers from 1 to 50 is:", sum)
▶ How It Works

The loop adds numbers step by step:
sum = 1 + 2 + 3 + ... + 50
Output:
The sum of numbers from 1 to 50 is: 1275

🛠 How to Run the Programs

Make sure Python is installed

Open terminal / command prompt

Navigate to project folder

Run:

python Task1.py
python Task2.py 
