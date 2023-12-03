## Folder structure

|-- bgp.py
|-- conf
|   |-- bgpd-R1.conf
|   |-- bgpd-R2.conf
|   |-- bgpd-R3.conf
|   |-- bgpd-R4.conf
|   |-- bgpd-R4-modified.conf (Replace 10.0.0.0/8 to 10.1.0.0/24) 
|   |-- zebra-R1.conf
|   |-- zebra-R2.conf
|   |-- zebra-R3.conf
|   `-- zebra-R4.conf
|-- connect.sh
|-- install.sh
|-- logs
|   `-- README
|-- run.py
|-- start_rogue.sh
|-- stop_rogue.sh
|-- webserver.py
`-- website.sh
 

## Topology

   ![image](Topology.png)

## Simulate the Network
     
       sudo python bgp.py

## Get BGP Table

     
       sh ip bgp

## Start Rougue AS

     
       ./start_rogue.sh

### To Stop Rogue

       ./stop_rogue.sh

## Get Forwarding/Routing Table
     
       sh ip bgp

## To Open Wireshark
     
       sudo wireshark &

      


      


   
       
 
