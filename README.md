# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 

Read the file and store in a variable.
### Step 3:

Now create a new file in which we want to paste the content using write access mode.

### Step 4: 
Use write function to copy the read file that has been stored in the variable.

### Step 5:
The content in the original file will be copied in the new file.

### Step 6:
End the program.

## PROGRAM:
```
# program for copying the contents from one file to another file.
# Developed by: MS Dharanish
# Reference number:212223240027
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
# File:
![Screenshot 2024-01-02 142024](https://github.com/MSDharanish-23011819/copy-file/assets/147139454/07997678-2f8f-4b36-af96-eb479d545023)



### OUTPUT:

![Screenshot 2024-01-02 142059](https://github.com/MSDharanish-23011819/copy-file/assets/147139454/2915194b-703f-4307-bdc8-f0afb41938b5)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
