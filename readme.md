# Calculator
8
SCCM4910 DevOps Lab 2 · Questions
A Python 3 calculator used from the Terminal, built step by step in SCCM4910.
## What it will do
Add, subtract, multiply and divide two numbers; display the result.
## How to run it
Run: python3 calculator.py
Operations: + - * / (two numbers) 
Enter the first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer.


#Testing
This calculator uses Python 3 and pytest for testing.
Pytest is listed in requirements-dev.txt.
To activate the environment:
source /opt/python-venv/sccm-4910/bin/activate
To run the tests:
./check.sh
All 5 tests should pass and show "QUALITY GATE PASSED".
To check the exit status:
echo $?
0 means the tests passed.
Anything else means something failed.
