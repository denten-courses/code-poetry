# Command Line Assignment 1
Code and Poetry 2014

Using the commands you have learned so far, solve the following problems. This could be done in one line or several. Post your solutions to Piazza including any relevant files.

## Reading Melville
Goal: Analyze treatment of gender in Herman Melville's *Moby Dick*.

0. Create a project directory.
1. Grab the text at http://www.gutenberg.org/cache/epub/2701/pg2701.txt
2. Make two lists of gender-marked words.
3. Find all those words in the text, grab context, and save to file.
4. Tokenize the words and compare against a list of common English words.
5. Save the non-common gender context words into a file, count occurrence, and sort.

## Weasel Words
Goal: Check your writing for clarity.

0. Create a project directory.
1. Copy three of your past term papers (or anything else that you have written).
2. Convert to plain text.
3. Make a list of three "weasel words" and save to a file.
4. Write a `sed` script to replace the weasel words in place and create a backup file for safety.
5. Use `comm` or `diff` to compare the files.

Bonus: Your script should preserve capitalization.
