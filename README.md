This project is a simple command-line Rock, Paper, Scissors game built in Python. The user plays against the computer by choosing rock, paper, or scissors, while the computer randomly selects its move.

The program includes error handling using exceptions to ensure the user enters a valid choice. If an invalid input (such as "ABC" or "Rocker") is entered, the program will prompt the user again until a correct option is provided.

Features:
1. User vs Computer gameplay
2. Random computer choices
3. Input validation with error handling (try/except)
4. Continuous prompting until valid input is entered
5. Clear win/lose/tie outcomes

Technologies Used:
Python
random library (for generating the computer’s choice)

How to Run the Program:
1. Make sure Python is installed on your computer.
2. Copy or download the code.
3. Run the script in your terminal or IDE: python filename.py

4. Enter your choice when prompted: rock, paper, or scissors

Example Output:
Enter a choice of rock, paper, or scissors: rock
You chose rock. Computer chose scissors.
Rock smashes scissors. You win.
Notes
The program uses a while loop to repeatedly ask for input until a valid option is entered.
A try/except block is used to handle invalid inputs without crashing the program.
This project is designed for beginners learning Python basics and error handling.
