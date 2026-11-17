# Python Exercises

Basic Python practice exercises covering strings, loops, list comprehensions, and data types.

## File

- `python-exercises.py`: contains all four exercises below.

## Exercises

### 1. Anagram Detection (Word Game)
Checks whether two words are anagrams (case-insensitive) by sorting their letters and comparing them. A player gets 1 point for each anagram pair.

### 2. Last Digit (Reading a Text Message)
Returns the rightmost digit in a text. Uses a list comprehension to collect all digits and returns the last one (or `None` if there are no digits).

### 3. Primes (Lucky Days)
Checks whether a number is prime and finds all lucky days (prime days) from day 1 to day 20.

### 4. Heterogeneous Data Structure (Student Profile)
Prints each item in a student profile list together with its data type (`str`, `int`, `float`, `bool`).

## How to Run

```bash
python python-exercises.py
```

## Example Output

```
car arc True
Listen Silent True
big small False
Evil Vile True
Total Point: 3

Last Digit of message 1: 5
Last Digit of message 2: None

Lucky Days: [2, 3, 5, 7, 11, 13, 17, 19]

Ross -> <class 'str'>
22 -> <class 'int'>
1.84 -> <class 'float'>
True -> <class 'bool'>
```
