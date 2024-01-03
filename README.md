# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Get the file name from the user.
## Step 2:
Assign num_words equal to 0.
## Step 3:
open the file by with open(fname,"r") as f: for handling.
## Step 4:
Iterate through each line in the file and separate them into words using space('')
## Step 5:
Find the number of words using num_words+=len(words)
## Step 6:
End the program by orinting the output.

## PROGRAM:
\*
# program to find the word count using command line argument
# Developed by: VIGNESH M
# register number: 212223240176
\*
fname=input("Enter the file name: ")
num_words=0
with open(fname,"r") as f:
for line in f:
words=line.split()
num_words+=len(words)
print("Number of words: ",num_words

### OUTPUT:
![image](https://github.com/vigneshvickyu/command-line-arguments-to-count-word/assets/151948835/9bb254bb-b478-4c39-ad28-ace60219da54)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
