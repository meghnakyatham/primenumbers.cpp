# primenumbers.cpp

# Prime Number Checker Program

This is a simple C++ program that checks whether a given number is a prime number or not. The program takes an integer input from the user and then uses a basic algorithm to determine whether the input number is prime.

## How to Use

1. Open a C++ development environment or compiler, such as Code::Blocks, Visual Studio, or an online C++ compiler.
2. Create a new C++ source file and paste the provided code into it.
3. Compile and run the program.
4. The program will prompt you to enter an integer `n`.
5. Enter the value of `n` and press Enter.
6. The program will output whether the entered number is prime or not.

## Algorithm

The program uses the following algorithm to check if a number is prime:

1. Read an integer `n` from the user.
2. Initialize a counter `count` to 0.
3. Loop from 1 to `n` (inclusive) using a variable `i`:
   - Check if `n` is divisible by `i` (i.e., `n % i == 0`).
   - If it is divisible, increment the `count`.
4. After the loop, if `count` is equal to 2, then the number is prime. Otherwise, it is not prime.
5. Display the appropriate message based on the result.

## Note

- A prime number is defined as a positive integer greater than 1 that has no positive divisors other than 1 and itself.
- The program assumes that the user enters a positive integer as input.

## Example

```
Enter n: 7
It is a prime number
```

```
Enter n: 10
It is not a prime number
```

## Author

This program was written by [Meghna].

## License

This program is released under the [MIT License](https://opensource.org/licenses/MIT).

---
