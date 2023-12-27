# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file
### Step 2: 
 Open the required file by using the function "with".
### Step 3: 
Then use the laptop to assign the i value in the file.
### Step 4:  
Using split function to spilt the words
### Step 5: 
Finding the given length of the words by using len() fuction.
### Step 6: 
Calling the function and Printing the number of words.
## PROGRAM:
Program to find the word count.
#Developed by: YENUGANTI PRATHYUSHA
#RegisterNumber:23009045
num_word=0
with open ("sample.txt",'r') as f:
for i in f:
word=i.split()
num_word+=len(word)
print("number of words ={}".format(num_word)


### OUTPUT:
![image](https://github.com/prathyusharavi/Word-count/assets/147474424/ac095217-ea6c-4adc-a362-f1d848950c34)
![image](https://github.com/prathyusharavi/Word-count/assets/147474424/185f65bf-9eaf-478b-94fd-4ecac6d6fa04)



## RESULT:
Thus the program is written to find the word count from a text.
