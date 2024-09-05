# 0x0A. Prime Game

## Project Description

This project involves a competitive game where two players, Maria and Ben, take turns removing prime numbers and their multiples from a set of consecutive integers. The game aims to determine which player wins the most rounds, with optimal play for both.

In each round, the set consists of numbers from `1` to `n`. Maria always goes first, and the player who cannot make a move (i.e., choose a prime number) loses. This project challenges you to apply your knowledge of prime numbers, game theory, and algorithm optimization to determine the winner of the game.

## Concepts

The following concepts are crucial to solving this problem:

- **Prime Numbers**: Efficient algorithms to find prime numbers.
- **Sieve of Eratosthenes**: A method to find all prime numbers up to a given number.
- **Game Theory**: Optimal strategies for competitive games.
- **Dynamic Programming**: Using stored results to optimize future computations.

## Learning Objectives

- Implement an efficient algorithm to determine prime numbers.
- Simulate game rounds where players remove primes and their multiples from a set.
- Use dynamic programming or other optimization strategies for multiple rounds of gameplay.
- Determine the overall winner across several rounds.

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.4.3)
- All files should end with a new line
- First line of all Python scripts should be `#!/usr/bin/python3`
- Code must follow the PEP 8 style guide (version 1.7.x)
- All files must be executable

## Example

```python
x = 3
nums = [4, 5, 1]

print(isWinner(x, nums))

