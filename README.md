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
Use write function to copy the read file that has been stored in the variable

### Step 5: 
The content in the original file will be copied in the new file.

### Step 6:
End the program.

## PROGRAM:


'''

Developed by: NATHIN R

Register Number:22008510

'''


with open('text.txt','r') as firstfile:

    with open('text2.txt','a') as secondfile:
    
        for line in firstfile:
        
            secondfile.write(line)


### OUTPUT:

![image](https://user-images.githubusercontent.com/118679646/214835436-f3a96a58-ba65-4345-afe9-def9ab764c1b.png)


![image](https://user-images.githubusercontent.com/118679646/214836006-faa5a2a8-33bd-403f-b50c-611cb7fcb38d.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
