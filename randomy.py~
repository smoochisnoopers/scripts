import os
import random
import subprocess

command = []

for file_name in os.listdir("./"):
    if len(command) == 0:
        command.append(file_name)
    else:
        pos = random.randint(0,len(command))
        command.insert(pos,file_name)


command.insert(0,"audience")
subprocess.run(command)
