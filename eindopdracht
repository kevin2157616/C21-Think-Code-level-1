from tkinker import Tk
from tkinker import Label
import time
import sys

master = Tk()
master.title("Digitale klok")

def get_time():
    timeVar = time.striftime("%I:%M:%S %p")
clock.config(text=timeVar)
clock.after(200,get_time)


clock = Label(master, front=("Calibri",90),bg="grey",fg="white")
clock.pack()

get_time()

 master.mainloop()
