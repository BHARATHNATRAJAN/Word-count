# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file with .txt file extension
### Step 2: 
 add some text in that file
### Step 3: 
create a python file
### Step 4:  
write a code to count the number of words in that file
### Step 5: 
run the program
### Step 6: 
display the output
## PROGRAM:
```
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Ttotal number of words:",count)
program()
```
### OUTPUT:
![image](https://github.com/BHARATHNATRAJAN/Word-count/assets/147473529/6df19517-4ec3-4285-883b-2bbdb5d148a8)
![image](https://github.com/BHARATHNATRAJAN/Word-count/assets/147473529/5f71bad2-b374-4b0e-9212-0a332a5c1183)
![image](https://github.com/BHARATHNATRAJAN/Word-count/assets/147473529/9719f825-e09c-4312-8284-e5357f8590ee)

## RESULT:
Thus the program is written to find the word count from a text.
