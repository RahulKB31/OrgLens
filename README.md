# Python Developer - Programming Problems

## Problem 1: Calculate Mean, Variance, and Standard Deviation from a CSV File

**Objective**: Read a CSV file with fields `Name` and `Mark` (around 10 rows filled). Calculate the Mean, Variance, and Standard Deviation of the `Mark` field. Write these statistics back to a CSV file and save it. Additionally, plot a graph showing these values and mark the Mean and Standard Deviation on the plot.

- **Requirements**:
  - Do not use standard library functions for SD/Mean.
  - Do not use Pandas library.

## Problem 2: Make the 2 MSBs of a Number One

**Objective**: Given a number, set the two most significant bits (MSBs) to `1`. Print the result in both decimal and binary formats.

- **Example**:
  - Input: `6` (binary `110`)
  - Output: Decimal: `7`, Binary: `111`

## Problem 3: Minimize the Number of Notes for a Given Amount

**Objective**: Write a program to calculate the minimum number of notes required for a given amount using the available denominations. Display the number of each type of note needed.

- **Example**:
  - Input: `1339`
  - Output: `2000: 0 notes, 500: 2 notes, 200: 1 note, 100: 1 note, 50: 0 notes, 20: 1 note, 10: 1 note, 5: 1 note, 2: 0 notes, 1: 4 notes`

## Problem 4: Caesar Cipher Encryption with XOR Salt

**Objective**: Implement a Caesar cipher to encrypt a string by shifting each character `n` places. After applying the Caesar cipher, XOR the result with a given salt. Save the final encrypted string to a file with `_enc.txt` suffix.

- **Example**:
  - Input String: `abcd`
  - Shift: `3`
  - Caesar Encrypted String: `defg`
  - Salt: `abc`
  - Encrypted File: `<filename>_enc.txt`

## Problem 5: Calculate Cosine Using Maclaurin Series

**Objective**: Calculate the cosine of an angle `x` using the Maclaurin series. Implement a package called `mymath` for power and factorial calculations. Plot the cosine function using matplotlib.

- **Requirements**:
  - Do not use prebuilt libraries for power or factorial calculations.

## Problem 6: Compare Two JSONs and Find Differences

**Objective**: Compare two JSON objects with similar structures and find tags with differing values. Output a JSON object showing the differing tags.

- **Example**:
  - **First JSON**:
    ```json
    {
      "x": 10.1,
      "y": 20,
      "name": "Anu",
      "dob": "2010-10-10"
    }
    ```
  - **Second JSON**:
    ```json
    {
      "x": 10,
      "y": 20,
      "name": "Ani",
      "dob": "2010-10-11",
      "z": 100
    }
    ```
  - **Result JSON**:
    ```json
    {
      "x": 0.1,
      "name": "Text change",
      "dob": "1",
      "z": "Only in 2"
    }
    ```
