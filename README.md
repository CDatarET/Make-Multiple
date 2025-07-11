# Make-Multiple
CodeChef Difficulty 1163 Problem.

# Make A Divisor of B

Chef has two integers `A` and `B` (`A ≤ B`).

Chef can choose any **non-negative integer `X`** and add it to **both** `A` and `B`. Your task is to determine whether it is possible to make `A` a divisor of `B` after adding the same value `X` to both numbers.

## Problem Statement

Given two integers `A` and `B`, determine if there exists a non-negative integer `X` such that: `A` is a divisor of `B`


## Input Format

- The first line of input contains a single integer `T`, the number of test cases.
- The next `T` lines each contain two integers `A` and `B`.

## Output Format

For each test case, print:

- `YES` if it is possible to make `A` a divisor of `B` by adding a non-negative integer `X` to both.
- `NO` otherwise.

You can print each character of the string in uppercase or lowercase. For example, the strings `Yes`, `YES`, `yes`, and `yEs` are all considered identical.

## Constraints

- `1 ≤ T ≤ 10^5`
- `1 ≤ A ≤ B ≤ 10^9`
