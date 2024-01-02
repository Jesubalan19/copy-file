# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create the file.
### Step 2: 
Write some lines in that file. 
### Step 3: 
Create python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```
#Program to copy file
#Developed by : Jesubalan A
#Reference number : 23013427
def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
```
### OUTPUT:
![Ex 5c i](https://github.com/Jesubalan19/copy-file/assets/144979294/c3bf0361-8426-46a4-838d-919b4229cb95)

![Ex 5c ii](https://github.com/Jesubalan19/copy-file/assets/144979294/0387a677-e674-44a3-96b5-b8991257a158)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
