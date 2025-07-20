# -PrimeInRange.java

PrimeInRange is a simple Java program that prints all prime numbers in the range from 2 to a user-specified number n (inclusive). The program uses a helper method isPrime(int n) to check if a number is prime, and iterates through the range to print all primes.

✅ Features:
Accepts a number n from the user.

Checks all numbers from 2 to n to determine if they are prime.

Prints the prime numbers in a single line.


📦 How to Use:

Compile the program:
javac PrimeInRange.java

Run the program:
java PrimeInRange

Input:
Enter an integer (e.g., 50) when prompted.

Output:
The program will print all prime numbers up to the entered number.

Example:
enter:
20
2 3 5 7 11 13 17 19

📌 Notes:
The program checks primality using trial division up to the square root of the number.

It assumes the user enters a positive integer greater than or equal to 2.

Optimization: Could be enhanced using the Sieve of Eratosthenes for large ranges.
