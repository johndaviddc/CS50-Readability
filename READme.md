# Readability
This program calculates the grade level of a given text input using the Coleman-Liau index.

## How it works
The program prompts the user for a text input, then counts the number of letters, words, and sentences in the text using three separate functions.

It then calculates the Coleman-Liau index using the formula:
```sh
index = 0.0588 * L - 0.296 * S - 15.8
```
where **`L`** is the average number of letters per 100 words in the text, and **`S`** is the average number of sentences per 100 words in the text.

Finally, the program prints out the grade level of the text. If the grade level is 16 or higher, it prints "Grade 16+", if the grade level is less than 1, it prints "Before Grade 1", and if the grade level is between 1 and 15 (inclusive), it prints "Grade [level]".

## How to run
To run the program, compile it using a C compiler such as gcc, then execute the resulting executable.

```sh
gcc readability.c -o readability
./readability
```


## How to use
When prompted, enter the text you would like to analyze. The program will output the grade level of the text.


