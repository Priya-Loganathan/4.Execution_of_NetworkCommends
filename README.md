# 4.Execution_of_NetworkCommands

## Aim:
Use of Network commands in Real Time environment.

## Software:
Command Prompt And Network Protocol Analyzer.

## Procedure: 
To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
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
from scapy.all import *

target = "www.google.com"
result, _ = traceroute(target, maxttl=32)
print(result)
```
## Output:
![323205728-d5a38322-fb47-4aa2-935e-9481bcb561c9](https://github.com/Priya-Loganathan/4.Execution_of_NetworkCommends/assets/121166075/78500d0f-3a41-47c3-aae9-3c9afece6f33)

## Result:
Thus Execution of Network commands Performed.
