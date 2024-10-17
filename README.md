# Experiment 15: Recursion
# Algorithms

## Sum of Integers Up to a Number

### Algorithm

1. **Start.**  
2. **Define Function:**  
   - Define a function `sum(int x)`:  
     - If `x` is equal to 1:  
       - Return 1.  
     - Else:  
       - Return `x + sum(x - 1)`.  
3. **Create `main()` Function:**  
   - Declare integer variables `num` and `ssum`.  
   - Print the message "Enter a number: " to the console.  
   - Read an integer input from the user into `num`.  
   - Call the `sum(num)` function and assign the result to `ssum`.  
   - Print the sum by displaying "Sum is: " followed by the value of `ssum`.  
4. **End.**

---

## Factorial of a Number

### Algorithm

1. **Start.**  
2. **Define Function:**  
   - Define a function `factorial(int x)`:  
     - If `x` is less than or equal to 1:  
       - Return 1.  
     - Else:  
       - Return `x * factorial(x - 1)`.  
3. **Create `main()` Function:**  
   - Declare integer variables `num` and `ans`.  
   - Print the message "Enter a number: " to the console.  
   - Read an integer input from the user into `num`.  
   - Call the `factorial(num)` function and assign the result to `ans`.  
   - Print the factorial by displaying "Factorial is: " followed by the value of `ans`.  
4. **End.**

---

## Reversing a Number

### Algorithm

1. **Start.**  
2. **Define Function:**  
   - Define a function `rev_num(int x)`:  
     - If `x` is greater than 0:  
       - Print `x % 10` (the last digit of `x`).  
       - Call `rev_num(x / 10)` to process the remaining digits.  
3. **Create `main()` Function:**  
   - Declare an integer variable `num`.  
   - Print the message "Enter a number: " to the console.  
   - Read an integer input from the user into `num`.  
   - Call the `rev_num(num)` function to display the reversed number.  
4. **End.**

---

## Reversing a String

### Algorithm

1. **Start.**  
2. **Define Function:**  
   - Define a function `rev_str(char *str)`:  
     - If the character pointed to by `str` is not `'\0'`:  
       - Call `rev_str(str + 1)` to process the next character in the string.  
       - Print the character pointed to by `str`.  
3. **Create `main()` Function:**  
   - Declare a character array `str` of size 20.  
   - Print the message "Enter a word: " to the console.  
   - Read a word input from the user into `str`.  
   - Call the `rev_str(str)` function to display the reversed string.  
4. **End.**

## Aim

To study and implement recursion in C++.

## Theory

Recursion is a programming technique where a function calls itself to solve a problem. It is particularly useful for problems that can be divided into smaller subproblems. Each recursive function typically includes:

- **Base Case**: A condition that stops the recursion.
- **Recursive Case**: The part of the function that calls itself with modified arguments.

## Algorithms

1. **Addition of Integers**: A recursive function to calculate the sum of integers from 1 to `n`.
2. **Reverse String**: A function that reverses a string using recursion.
3. **Reverse Number**: A function to reverse the digits of an integer.

## Files

- `addition_int.cpp`: Implements the addition of integers.
- `factorial.cpp`: Calculates the factorial of a number using recursion.
- `integer_reverse.cpp`: Reverses the digits of an integer.
- `string_reverse.cpp`: Reverses a given string.

## Usage

Compile and run the C++ files using any C++ compiler to observe the recursive implementations.

## Contributing

Feel free to fork the repository and submit a pull request with enhancements or additional examples.

## License

This project is licensed under the MIT License.
