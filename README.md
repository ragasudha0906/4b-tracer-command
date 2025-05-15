# 4b-Tracer-command

4.Execution_of_NetworkCommands

## AIM :
Use of Network commands in Real Time environment
## Software :
Command Prompt And Network Protocol Analyzer
## Procedure: 
<BR>
To do this EXPERIMENT- follows these steps:
<BR>
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer
<BR>
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
and normal mode and how to configure router interface and how to save this configuration to
flash memory or permanent memory.
<BR>
<BR>
This commands includes
<BR>
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Program:

```
from scapy.all import* 
target = ["www.google.com"] 
result, unans = traceroute(target,maxttl=32) 
print(result,unans)
```

## Output:

![image](https://github.com/user-attachments/assets/bf66a212-6456-467b-a640-f95acbadc68d)


## Result:
Thus Execution of Network commands Performed
