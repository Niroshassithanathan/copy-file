# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
Step 1:
Create two txt file.A file which has content [lines.txt] to be copied to the empty [text.txt]file.

Step 2: 
Using write() function to copy the content from line.txt to empty file,text.txt.

Step 3:
 Save and run the python program in terminal.

step 4:
 The text from the lines.txt file is copied to the empty file text.txt.

Step 5:
 Then the text is shown in empty file text.txt.

Step 6:
 Result is obtained.

## PROGRAM:
```
## Developed by:NIROSHA.S
## Reference number:22009078

with open('python.py','r') as file1:
    with open('text.txt','w') as file2:
        for line in file1:
            file2.write(line)
```
### OUTPUT:


![copy copy](https://user-images.githubusercontent.com/121418437/215252274-b2103aa2-add7-48f7-b2b4-3373d422da81.PNG)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
