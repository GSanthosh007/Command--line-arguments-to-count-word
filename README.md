# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.

### Step 2:
Read the text using read() function.

### Step 3:
Split the text using space separator.We assume that words in a sentance are separted by a space character.

### Step 4:
The length of the split list should equal the numbers of words in the test file.

### Step 5:
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6:
End the program

## PROGRAM:
```py
#Developed by: SANTHOSH G
#Register Number: 212223240152

import sys

count = 0

with open ("syc.txt",'r') as f1:

    for line in f1:

        word = line.split()

        count += len (word)

print("word count in file = ",count)

```

### OUTPUT:
 ![Screenshot 2024-05-12 221202](https://github.com/GSanthosh007/Command--line-arguments-to-count-word/assets/147527586/24f7f251-c186-4d11-9743-e7572c03b729)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
