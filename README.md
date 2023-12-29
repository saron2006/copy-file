# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
### Step 1: 
Get the file name and location from the user.
### Step 2: 
Give a new file name to create a copy of a file content.
### Step 3:
 Read the file and close the file.
### Step 4: 
Now write the content in the new file.
### Step 5:
 When done print"File copied successfully".
### Step 6: 
End of the program
## PROGRAM:
```
# To write a program for coping the contents from one to another file.
# Developed by : SARON XAVIER .A
#RegisterNumber:23005103
with open("file.txt","r") as f:
    x=f.read()
with open("file1.txt","w") as f1:
    f1.write(x)
```

### OUTPUT:
![image](https://github.com/saron2006/copy-file/assets/138849343/07926172-f635-4f12-82e7-6f250863184c)
![image](https://github.com/saron2006/copy-file/assets/138849343/b785a367-3a4b-4c1a-a443-480562b599d4)
![image](https://github.com/saron2006/copy-file/assets/138849343/3afa312f-387b-4ef6-a0fd-0ac8ed1a6ff4)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
