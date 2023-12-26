# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.

### Step 2: 
Enter a new file name to create a copy of a file content.
 
### Step 3: 
Read the file and close te file.

### Step 4:
Now write te content in the new file.

### Step 5:
Print "File copied successfully" when code is completed

### Step 6:
End of the program.

## PROGRAM:
```
#Program to copy the contents of one file to another
#Developed by: R.SANJANA
#Register Number:23008112

fileHandle = open("Sample.txt", "r")
texts = fileHandle.readlines()
fileHandle.close()
fileHandle = open("New.txt", "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!")
```

### OUTPUT:



## RESULT:
Thus the program is written to copy the contents from one file to another file.