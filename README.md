# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
instalize the value for count as zero

### Step 2: 
using open command open the txt file to read
 
### Step 3: 
use the split() command

### Step 4:  
print the counted words

### Step 5: 
end the program

### Step 6: 

## PROGRAM:
```
'''
Developed by:sai vivek.R
Registered number: 23003676
'''
num=0
with open("filel.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)

'''
```

### OUTPUT:

![Screenshot (7)](https://github.com/RAGALASAIVIVEK/Word-count/assets/144979718/c899cf35-bebd-4119-88c5-f10781606b3e)




## RESULT:
Thus the program is written to find the word count from a text.
