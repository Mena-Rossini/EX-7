# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND

## DATE : 17-04-2023

## AIM :
To write the python program for simulating Traceroute command
## ALGORITHM:
1. Start the program.
2. Get the frame size from the user.
3. To create the frame based on the user request.
4. To send frames to server from the client side.
5. If your frames reach the server, it will send ACK signal to client
otherwise it will sendNACK signal to client.
6. Stop the program
## PROGRAM :
```
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
## OUTPUT:

![241380866-8d3fcaf3-f270-4a86-bf6f-38905453fa6f](https://github.com/Mena-Rossini/EX-7/assets/102855266/c75252d5-ba3e-47e0-acde-c068e8fa4c39)

## RESULT:
Thus, the python program for simulating Traceroute command was successfully executed.
