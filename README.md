# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Declare number of words is 0.
### Step 2: 
 open it with file1.txt file.
### Step 3: 
Give range for i.
### Step 4:  
Then next split the words.
### Step 5: 
count the number of words.
### Step 6: 
Giving print statement for getting output.
## PROGRAM:
```
Developed by: Jeeva k
register no:212223230090


def fun(filename):
    fp=open(filename)
    NoOfWords=0
    for line in fp:
       word=line.split()
       NoOfWords+=len(word)
    print("No of words in file",NoOfWords)
filename=input("Enter The File name")
fun(filename)
```
### OUTPUT:

![alt text](<Screenshot 2024-05-17 185804.png>)

## RESULT:
Thus the program is written to find the word count from a text.
