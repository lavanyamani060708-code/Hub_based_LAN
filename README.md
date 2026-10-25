# Hub-Based LAN Using Cisco Packet Tracer

## Aim
To create a Hub-Based Local Area Network (LAN) using Cisco Packet Tracer and test communication between four computers.

## Software Required
- Cisco Packet Tracer

## Devices Used
- 4 PCs
- 1 Hub-PT
- Copper Straight-Through cables

## Network Topology
In this project, four computers are connected to a central hub. The hub forwards network signals to the connected devices, allowing communication within the local area network.

## IP Address Configuration

| Device | IP Address | Subnet Mask |
|---|---|---|
| PC0 | 192.168.1.1 | 255.255.255.0 |
| PC1 | 192.168.1.2 | 255.255.255.0 |
| PC2 | 192.168.1.3 | 255.255.255.0 |
| PC3 | 192.168.1.4 | 255.255.255.0 |

## Procedure
1. Open Cisco Packet Tracer.
2. Place four PCs and one Hub-PT in the workspace.
3. Connect each PC to a separate hub port using Copper Straight-Through cables.
4. Configure a unique IP address and subnet mask for each PC.
5. Open the Command Prompt on PC0.
6. Use the ping command to test communication with the other computers.

## Testing

Use the following commands from PC0:

```text
ping 192.168.1.2
ping 192.168.1.3
ping 192.168.1.4
```

Successful replies indicate that the computers can communicate over the LAN.

## Advantages
- Simple to set up.
- Suitable for demonstrating basic LAN communication.
- Easy to understand for networking beginners.

## Result
A Hub-Based LAN was configured using Cisco Packet Tracer. Network connectivity can be verified using the ping command.

## Project File
`Hub_Based_LAN.pkt`

## Author
GitHub: [lavanyamani060708-code](https://github.com/lavanyamani060708-code)
