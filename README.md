# Minimalist-Portscanner

This python code sets up a function to scan a given target (IP or address) for open ports. It takes two arguments, the target and the number of ports to scan. It then prints a message and loops through the ports, attempting to connect with each one. If the connection is successful, it will print a message. Finally, it takes the target(s) and port number from the user and runs the scan function.

This python script is use to scan a target (or multiple targets) for open ports. It begins by importing the socket and termcolor modules to use for the script. It then defines two functions, scan() and scan_port(). The scan() function takes two arguments, target and ports. 

It then uses a for loop to iterate through the ports and call the scan_port() function. The scan_port() function takes two arguments, ipaddress and port. It then tries to create a socket and connect to the target ipaddress and port. 

If the connection is successful, it prints out a success message. If it is unsuccessful, it does nothing. 

Finally, the code prompts for a target (or multiple targets) to scan and the number of ports to scan. It then checks to see if multiple targets were entered, and if so, uses a for loop to iterate through each target and call the scan() function. If only one target was entered, it calls the scan() function.

# Wath I learn in the process

This project has helped to strengthen my Python coding abilities.

Consolidate my knowledge about ports and how to detect open ports in a network.

Create an automation in Python to help me run a quick scan for open ports on a target network.
