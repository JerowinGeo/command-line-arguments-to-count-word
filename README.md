# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.

### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3:
Read the file using read() method.

### Step 4:
Use split() method to split the file content into words.

### Step 5:
Use len() to find the total words.


## PROGRAM:
```
# Python program for getting the word count from the contents of a file using command line arguments.
# Developed By: Jerowin Geo J A
# Reference No: 212223100016

import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))

```
### OUTPUT:
![image](https://github.com/JerowinGeo/command-line-arguments-to-count-word/assets/147139744/66283868-c41d-4e57-baf4-5cd843a4d90b)
![image](https://github.com/JerowinGeo/command-line-arguments-to-count-word/assets/147139744/ca44fa44-3cf8-4aa0-aae1-01d492538881)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
