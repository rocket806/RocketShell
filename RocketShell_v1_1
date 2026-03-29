import datetime
import random


print("Starting the program... If you want to start the program press y")
start = input(":  ")
if start == "y":
    active = True
else:
    active = False
#---- Main code ----#    
while active == True:
    command = input("")
    if command.startswith("echo "):
        echo_command = command[5:]
        print(echo_command)
    elif command == "exit":
        active = False
    elif command == "calculator":
        print("Enter the calculation:")
        calculation = input("")
        response = eval(calculation, {"__builtins__": None}, {})
        print(response)
    elif command == "time":
        now = datetime.datetime.now()
        print(now.strftime("%Y-%m-%d %H:%M:%S"))
    elif command == "about":
        print("RocketShell v1.1 \n made in python")
    elif command == "help":
        print("The commands are: \n echo \n exit \n calculator \n time \n about \n random \n help")
    elif command == "random":
        firstnum = int(input("From: "))
        lastnum = int(input("To: "))
        number = random.randint(firstnum, lastnum)
        print(number)
    else:
        print("Invalid command, try using help")
#---- Finish ----#        
       
       

