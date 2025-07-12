Python 2 and Python 3 have fundamental differences that impact how code is written and executed.

The decision to transition from Python 2 to Python 3 was driven by the need for a more efficient, powerful, and user-friendly language.

Python 2 code can sometimes be incompatible with Python 3, as many features and standard libraries were updated or
restructured in Python 3.

1. Print Function: Python 3 made print a function, which promotes consistency since
all other output functions in Python require parentheses. This minor change greatly
enhances compatibility and ease of use.

2. Integer Division: In Python 2, dividing two integers truncates the decimal portion
(integer division), while Python 3 uses “true division,” meaning the result is a float
unless explicitly using // for integer division.

3. Unicode by Default: Python 3 treats strings as Unicode by default, enabling global
language support without additional effort. In Python 2, you needed to prefix strings
with u for Unicode.

4. Syntax Improvements: Features like f-strings, type hints, and async/await provide
better readability, faster execution, and improved error handling in Python 3.