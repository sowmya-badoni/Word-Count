# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np
### Step 2: 
Enter the input values
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program
## PROGRAM:
```
# program to find the number of words in a text file
# Developed by : SOWMYA BADONI
# Register number : 212223230211
num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)              
```

### OUTPUT:
![328387644-7667fa03-7ab1-4e0a-b322-a91640e672b5](https://github.com/sowmya-badoni/Word-Count/assets/152136324/59f28427-7d2a-43c4-9b89-ad3589733b49)



## RESULT:
Thus the program is written to find the word count from a text.
