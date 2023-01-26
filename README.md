# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## ALGORITHM: 
### Step 1:
Open vscode.

### Step 2:
Type the program.

### Step 3:
save the python file.

### Step 4:
create a text file .

### Step 5:
Run the program in the vscode, in the terminal type the following commands.

### Step 6:
End the program.
## PROGRAM:

#Developed by: SABARI S
#Reference no: 22008698
import sys
count={}
a=sys.argv[1]
with open(a,'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word]=1
            else:
                count[word]+=1
print(count)
f.close()

### OUTPUT:

![WhatsApp Image 2023-01-26 at 16 54 54](https://user-images.githubusercontent.com/118660461/214827232-38e8ed3c-3472-4e6c-a54c-c17e38c61fa5.jpg)
![WhatsApp Image 2023-01-26 at 16 54 54](https://user-images.githubusercontent.com/118660461/214827249-c9c6a3ef-8f6e-4d00-9b32-b4166a238d02.jpg)

##RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
