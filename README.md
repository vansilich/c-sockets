# Internet sockets on C
This is code from Beej\`s guide:  
https://beej.us/guide/bgnet

## How to
Code was written for Unix/Linux systems.

compile:  
```bash
gcc -Wall main.c utils.c listener.c -o main
```
launch:  
```bash
./main
```
then you can open multiple windows in terminal
and in every window launch:
```bash
telnet localhost 9034
```

Then you can write comething short on random window 
and see this message in other windows