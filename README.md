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
