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
#Program to write a python program for getting the word count from the contents of a file using command line arguments.
#Developed by: Jerowin Geo J A
#Register Number: 212223100016
def fun(filename,newfilename):
    with open(filename) as fp:
        with open(newfilename,'w') as fpl:
            data=fp.read()
            fpl.write(data)
filename=input("Enter the file to read the content:")
newfilename=input("Enter the file to store copied content:")
fun(filename,newfilename)
```
### OUTPUT:
![image](https://github.com/JerowinGeo/command-line-arguments-to-count-word/assets/147139744/79d33527-7b27-48c5-a685-d37025caadd1)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
