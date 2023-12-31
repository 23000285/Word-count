# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Initialize a word count variable to zero.

### Step 2: 
Open the specified text file in read mode.

### Step 3: 
Iterate through each line in the file:
 1. Split the line into a list of words.
 2. Add the number of words in the line to the total word count.

### Step 4:  
Close the file.

### Step 5: 
Print the total number of words found in the file.

## PROGRAM:
```
#Program to find the Word Count
#Developed by: VENKATANATHAN P R
#register Number: 23000285

num=0
with open("sample.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:
![image](https://github.com/23000285/Word-count/assets/138970859/cfb08221-6e96-4bd5-b19c-518beb647d9f)

## RESULT:
Thus the program is written to find the word count from a text.
