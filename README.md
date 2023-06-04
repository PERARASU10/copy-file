# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Create a text1.txt with some content in it

Step 2:
Open the text1.txt file in read mode

Step 3:
Create a copy.txt file using write mode

Step 4:
Copy the content of text1.txt file to copy.txt using write function
## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Developed by: PERARASU M
RegisterNumber: 212222100033
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:

![image](https://github.com/PERARASU10/copy-file/assets/118348589/1aeb24a8-57ae-4614-a8d6-e2d4482f215f)

![image](https://github.com/PERARASU10/copy-file/assets/118348589/a2b8dd99-6d7b-468b-b682-11eba330d15b)

![image](https://github.com/PERARASU10/copy-file/assets/118348589/098758ac-b3b9-4bfb-9058-2d4306d61e9d)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
