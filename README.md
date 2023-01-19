# NEURALNETWORKASSIGNMENT2

First_name=input("enter first name") #taking first name from user
last_name=input("enter last name") #taking last name from user
Full_name=First_name+last_name #concatenating two strings using + symbol
print("Full name is :", Full_name)  #printing full name

in the above code we want to input first name and last name and want to prin out the full name using last name and first name


tr1=input("enter string")
def string_alternative(str1):  #defining string alternative function
    final_String=(str1[::2])   #using slicing retrieving alternate characters in the string and assigning to final string
    return print(final_String)        #returning and printing final string
string_alternative(str1)  #calling function string_alternative

in the above program we wanted to give input string and it should print the alternate letters of that string

f=open("input.txt","w")  #opening file with write mode
f.write("Python Course\n")  #writing first line 
f.write(" Deep Learning Course") #writing secomd line into file
f.close() #closing file after writing
f=open("input.txt","r") #opening file with read mode
print(f.read()) #reading that file
f.close()  # closing file after freading

from collections import Counter  #importing Counter from collections library
def count_words(filename):   #defining count_words function by taking file as argument
    with open(filename) as f: 
        return Counter(f.read().split())  #reading the input file and split every word in file and count words

with open("output.txt","a") as f:  #opening new outputfile and sending output of returned function to output file
    print("Number of words in the file:\n", count_words("input.txt"))     #printing output
    
    
    in this following code we want to print the number of string in given file
    
    data = input("enter customer heights : ")

def inchToCent(value):
    return value*2.54

heights = data.split()

new_list = []

for x in heights:
    value = int(x)
    new_list.append(inchToCent(value))
    
print("show list : ",new_list)

in this code wanted to take height of customers in inches andconvert them into inches
