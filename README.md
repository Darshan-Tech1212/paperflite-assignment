# Paperflite Assignment Submission

## Candidate Details
**Name:** Akash Darshan  

## Overview
This repository contains solutions to the problem statements provided as part of the Paperflite assignment. Each problem has been implemented with a focus on correctness, efficiency, and clean code structure.

## Problem Statements and Approach

### 1. Single Number
**Problem:**  
Given a non-empty array of integers where every element appears twice except for one, find the element that appears only once.

**Approach:**  
- Used Bitwise XOR operation.
- XOR cancels out duplicate elements (`a ^ a = 0`) and leaves the unique element.

**Time Complexity:** O(n)  
**Space Complexity:** O(1)

### 2. Remove K Digits
**Problem:**  
Given a non-negative integer represented as a string and an integer k, remove k digits to produce the smallest possible number.

**Approach:**  
- Used a Greedy algorithm with a Stack.
- Removed digits that are greater than the next digit to minimize the number.
- Handled edge cases such as leading zeros and empty result.

**Time Complexity:** O(n)  
**Space Complexity:** O(n)

### 3. Word Pattern Matching
**Problem:**  
Determine if a string follows a given pattern such that there is a bijection between pattern characters and words in the string.

**Approach:**  
- Used a HashMap to map characters to words.
- Used a HashSet to ensure uniqueness of mappings.
- Ensured one-to-one correspondence between pattern and words.

**Time Complexity:** O(n)  
**Space Complexity:** O(n)

## Project Structure

SingleNumber.java
RemoveKDigits.java
WordPattern.java
README.md

## Execution Instructions

1. Ensure Java Development Kit (JDK 8 or above) is installed.
2. Compile the Java files using:
javac FileName.java

3. Run the program using:
java FileName

Each file contains a `main` method with sample test cases demonstrating the expected outputs.
## Notes
- Sample inputs and outputs provided in the assignment have been included within the code.
- Code is modular and easy to understand for evaluation purposes.
