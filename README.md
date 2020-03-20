# Modules
Modules in python
import time
import os

while True:
    if os.path.exists("D:\Desktop\python\Basic Practice\some\some.txt"):
        with open("D:\Desktop\python\Basic Practice\some\some.txt") as file:
            print(file.read())
    else:
        print("File doesnot exist")
    time.sleep(5)

#Pandas
import time    #builtin library
import os      #written in python
import pandas  #installed 3rd party library 

while True:
    if os.path.exists("D:\Desktop\python\Basic Practice\original.csv"):
        data = pandas.read_csv("D:\Desktop\python\Basic Practice\original.csv")
        print(data.mean())  #"st1" between big paranthesis for taking the mean of only one
    else:
        print("File doesnot exist")
    time.sleep(5)
