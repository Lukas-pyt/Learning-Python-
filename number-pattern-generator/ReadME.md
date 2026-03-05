Number Pattern Generator

A simple Python script that generates a number pattern from 1 to n.

Features

Generate numbers from 1 to n in a single line

Handles invalid input gracefully

Installation
git clone https://github.com/your-username/number-pattern.git
cd number-pattern

Ensure you have Python 3 installed.

Usage
from main import number_pattern

print(number_pattern(5))
# Output: 1 2 3 4 5
Examples
number_pattern(3)  # "1 2 3"
number_pattern(7)  # "1 2 3 4 5 6 7"
Error Handling
number_pattern("abc")  # "Argument must be an integer value."
number_pattern(0)      # "Argument must be an integer greater than 0."
License

MIT License
