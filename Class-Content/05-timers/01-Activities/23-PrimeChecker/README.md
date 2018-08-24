# Prime Checker

## File

* *None*

## Instructions

* Write a function that checks to see if a number is a prime number or not. Have it return `true` if it is, or `false` if it isn't.

* A Prime number is a number greater than one that can only be divided by one and itself.

if the number can only be divided by one and itself, true
else, false

starting at one, you divide the target number by each number skipping even numbers. If successfully divisible with no remainder you plus the counter, the moment the amount of numbers that evenly divide into the number reaches more than 2, its not prime and return false. if it reaches itself then it's prime.

* [More info on Prime numbers](https://www.mathsisfun.com/prime_numbers.html)
