# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
~~~
#Program for getting the word count from the contents of a file using command line arg
#Developed by:  DHARSHINIYAA K S
#Register Number : 23014039
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
~~~
### OUTPUT:
![OUTPUT](https://github.com/DHARSHINIYAA/command-line-arguments-to-count-word/assets/149560172/784ef813-1d27-40bc-9a3a-da5c7872cc7c)
![OUTPUT](https://github.com/DHARSHINIYAA/command-line-arguments-to-count-word/assets/149560172/a893eb5a-154a-46bd-b04a-7a0869d38b47)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
