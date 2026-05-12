This project is a simple command-line Rock, Paper, Scissors game built in Python. The user plays against the computer by choosing rock, paper, or scissors, while the computer randomly selects its move.

The program includes error handling using exceptions to ensure the user enters a valid choice. If an invalid input (such as "ABC" or "Rocker") is entered, the program will prompt the user again until a correct option is provided.

Features
User vs Computer gameplay
Random computer choices
Input validation with error handling (try/except)
Continuous prompting until valid input is entered
Clear win/lose/tie outcomes
Technologies Used
Python
random library (for generating the computer’s choice)
How to Run the Program
Make sure Python is installed on your computer.
Copy or download the code.

Run the script in your terminal or IDE:

python filename.py

Enter your choice when prompted:

rock, paper, or scissors
Example Output
Enter a choice of rock, paper, or scissors: rock
You chose rock. Computer chose scissors.
Rock smashes scissors. You win.
Notes
The program uses a while loop to repeatedly ask for input until a valid option is entered.
A try/except block is used to handle invalid inputs without crashing the program.
This project is designed for beginners learning Python basics and error handling.
