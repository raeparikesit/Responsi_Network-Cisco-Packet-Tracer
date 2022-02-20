# Responsi_Network-Simulation-Cisco-Packet-Tracer
I designed this network configuration to meet the practical exam (response) for computer networking courses. This is honestly an interesting problem to work on which demonstrates the concept of IP Subnetting and using the RIPv2 Protocol.what I learned in studying these concepts can be realized in the practical real world.

## CASE STUDY

In an office building there are 4 main rooms, namely Kumulo Artifact, Trans Artifact, Kana Tiger, and Titan Brave. Each room has the following conditions:

1. Kumulo Artifact

    a) Divided into 2 parts VLAN, namely:
     VLAN 10, with description
      - VLAN name is Dis
      - Number of hosts 60
      - Dynamic IP (DHCP)
 
     VLAN 20, with description
      - VLAN name is Dat
      - Number of hosts 60
      - Dynamic IP (DHCP)

    b) RIP Routing Protocol v2

2. Trans Artifact
    a) Access Point, with configuration:
     - SSID: Artifact Trans Hotspot
     - Number of devices 125
     - Dynamic IP (DHCP)

    b) RIP Routing Protocol v2

3. Kana Tiger
  a) Dynamic IP (DHCP)
  b) Number of devices 24 pieces
  c) Static Routing Protocol

4. Titan Brave
  a) Contains a laptop connected to an Access Point
  b) Number of laptops 88 pieces
  c) Static Routing Protocol

5. Between routers connected by serial cable

## DESIGN NETWORK
![Network-Responsi_screenshot](https://user-images.githubusercontent.com/93896646/154805654-d20f69cd-e910-40b2-b662-bd3bddbc5c7a.png)

## SUBNETTING TABLE
![Screenshot (1489)](https://user-images.githubusercontent.com/93896646/154806445-b0915f65-dd38-491a-8482-384a2ab6c2c6.png)

## NOTE 
the .pkt file is in the main file
### How to run
Install Cisco Packet Tracer and then simply open the main file.pkt. The whole network is in working condition. You can check it by sending a packet from one system to another or through using the PING command in the Cisco Packet Tracer.

This solution works for version 6.2 or above of Cisco Packet Tracer.

