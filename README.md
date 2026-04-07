# Character Counter CLI

A command line program written in C that analyzes a string of input and counts different types of characters.

The program reads user input and categorizes characters into digits, letters, spaces and other symbols.

## Features

- Counts occurrences of digits (0–9)
- Counts lowercase letters
- Counts uppercase letters
- Counts spaces and tabs
- Counts all other characters
- Displays frequency of each digit

## How It Works

1. The user enters a sequence of characters
2. The program reads input character by character using `getchar()`
3. Each character is classified into one of the categories:
   - Digit
   - Lowercase letter
   - Uppercase letter
   - Space / tab
   - Other characters
4. Results are displayed after input ends (Enter key)

## Technologies

- C programming language
- Standard C libraries

## What I Learned

- Character processing in C
- Using `getchar()` for input
- ASCII value comparisons
- Counting occurrences using arrays
- Looping and condition handling

## Example

Unesite proizvoljan niz znakova: Hello 123!

Cifra 0 se pojavljuje 0 puta  
Cifra 1 se pojavljuje 1 puta  
Cifra 2 se pojavljuje 1 puta  
Cifra 3 se pojavljuje 1 puta  

Blankovi: 1  
Mala slova: 4  
Velika slova: 1  
Ostali znakovi: 1  


## Author

Software engineering student at ITS
