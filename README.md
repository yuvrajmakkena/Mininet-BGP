## Folder structure

![image](https://github.com/yuvrajmakkena/Mininet-BGP/assets/40199249/51cbb304-d213-458b-8262-f27c14d2e302)

 

## Topology

   ![image](Topology.png)

## Simulate the Network
     
       sudo python bgp.py


## Network IPs

### AS1

| Host | Interface | IP       |
|------|-----------|----------|
| R1   | R1-eth1   | 11.0.1.254 |
| R1   | R1-eth2   | 11.0.2.254 |
| R1   | R1-eth3   | 11.0.3.254 |
| R1   | R1-eth4   | 9.0.0.1   |
| R1   | R1-eth5   | 9.0.4.1   |
| h1-1 | eth0      | 11.0.1.1  |
| h1-2 | eth0      | 11.0.2.1  |
| h1-3 | eth0      | 11.0.3.1  |

### AS2

| Host | Interface    | IP        |
|------|--------------|-----------|
| R2   | R2-eth1      | 12.0.1.254 |
| R2   | R2-eth2      | 12.0.2.254 |
| R2   | R2-eth3      | 12.0.3.254 |
| R2   | R2-eth4      | 9.0.0.2   |
| R2   | R2-eth5      | 9.0.1.1   |
| h2-1 | h2-1-eth0    | 12.0.1.1  |
| h2-2 | h2-2-eth0    | 12.0.2.1  |
| h2-3 | h2-3-eth0    | 12.0.3.1  |


### AS3

| Host | Interface   | IP        |
|------|------------|-----------|
| R3   | R3-eth1    | 13.0.1.254|
| R3   | R3-eth2    | 13.0.2.254|
| R3   | R3-eth3    | 13.0.3.254|
| R3   | R3-eth4    | 9.0.1.2   |
| h3-1 | h3-1-eth0  | 13.0.1.1  |
| h3-2 | h3-2-eth0  | 13.0.2.1  |
| h3-3 | h3-3-eth0  | 13.0.3.1  |

### AS4

| Host | Interface  | IP       |
|------|------------|----------|
| h4-1 | h4-1-eth0  | 13.0.1.1 |
| h4-2 | h4-2-eth0  | 13.0.2.1 |
| h4-3 | h4-3-eth0  | 13.0.3.1 |


## Start a Host Console 

       xterm <host> (host = h1-1,h2-2,R1 e.t.c)
 
## Get BGP Table
     
       sh ip bgp

## Start Rouge AS

     
       ./start_rogue.sh

## To Stop Rogue AS

       ./stop_rogue.sh

## Get Forwarding/Routing Table
     
       sh ip bgp

## To Open Wireshark
     
       sudo wireshark &

      


      


   
       
 
