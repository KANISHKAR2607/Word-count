# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open visual studio code.

### Step 2:
Create file with .py extension.

### Step 3:
Start the program.

### Step 4:
Write the code.

### Step 5:
Run terminal for output of the given program.

### Step 6:
End the program

## PROGRAM:

```
Developed by:KANISHKAR M
Register Number:22007816

num_words = 0
with open('data.txt','r') as f1:
     for i in f1:
        words=i.split()
        num_words+= len(words)
print("Number of words in the files = {}".format(num_words))

```

### OUTPUT:

![5a data](https://user-images.githubusercontent.com/118886772/214642975-c911c416-bf2a-43ac-ba2e-f60978eb4043.png)

![5A KANI](https://user-images.githubusercontent.com/118886772/214642945-2cd2eb56-48ce-49f2-b6a3-31667e8c0235.png)

## RESULT:

Thus the program is written to find the word count from a text.
