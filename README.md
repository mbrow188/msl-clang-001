## Binary Tree - Operating Systems Assignment 1

### Usage

Find the line of code `#define INPUT_INDEX "01"` and change the **01** to match the input file.
The input file should be named `input01.txt` and the program will create `output01.txt` where **01** is any 2 digit ID you choose.

------------------------------------------------------------------------------------------------

The input file should contain a list of words on one single line like this:
```
the quick red fox jumps over the lazy brown dog
```
The program will load in the file, word by word, and create a binary tree out of the data. The tree is composed of nodes that contain a string of the word, a count of how many times that word appeared, and pointers to the left and right nodes of the tree. It will then iterate through the tree and print the words in alphabetical order as follows:
```
brown: 1
dog: 1
fox: 1
jumps: 1
lazy: 1
over: 1
quick: 1
red: 1
the: 2
```
