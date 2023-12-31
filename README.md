# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.

### Step 2: 
Open the existing file to read.
 
### Step 3: 
Open the new file to write.

### Step 4:  
Copy the contents from existing file to new file.

### Step 5: 
Get the inputs from the user for existing file and new file. Call the function.

### Step 6: 
End the program

## PROGRAM:
 # python program for copying the contents from one file to another file.
 # Developed by: SANJAI S
 # Register Number: 212223230185

~~~
def copy(fname,newfile):
  with open(fname,'r')as fp:
    with open(newfile,'w')as fp1:
      data1=fp.read()
      fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname,newfile)
~~~
### OUTPUT:

![Screenshot 2023-12-31 183600](https://github.com/Sanjaichitra/copy-file/assets/144870518/67e5994d-343b-4b6b-ad64-6e4fe9a2d68f)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
