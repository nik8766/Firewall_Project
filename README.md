# Firewall_Project: Configuring iptables on a Linux Server

# Introduction
This project demonstrates the configuration of iptables firewall rules on a Linux server to manage incoming, outgoing, and forwarded network traffic. It includes setting up a client-server network with a gateway, enabling IP forwarding, and implementing DNAT and SNAT for routing SSH and Telnet traffic.

# Purpose
The goal of this lab is to provide practical experience with configuring iptables to secure network communications, manage traffic flow, and enable secure routing between client and server systems through a gateway.

# Features
iptables configuration: Setup and apply rules for INPUT, OUTPUT, and FORWARD chains to control network traffic.

Client-server network: Configure a gateway to forward traffic between the client and server networks.

IP forwarding: Enable packet forwarding between network interfaces on the gateway.

Routing with DNAT/SNAT: Route SSH and Telnet traffic through the gateway using Destination NAT and Source NAT.

# Setup and Configuration
Flushing firewall rules: Scripts are used to flush existing iptables rules and set default policies for INPUT, OUTPUT, and FORWARD chains.

Allowing specific traffic: Custom rules were created to allow Telnet (port 23) and SSH (port 22) traffic.

IP forwarding: Enabled on the gateway to forward packets between networks.

DNAT/SNAT setup: Forward incoming SSH and Telnet traffic to the server using DNAT, and SNAT for outgoing traffic.

# How to Use
To replicate this lab:
1.Configure iptables on your Linux server using the provided scripts.
2.Set up a client-server environment with a gateway in between.
3.Enable IP forwarding on the gateway.
4.Use netcat or other tools to test SSH and Telnet connections.

# Conclusion
This lab provided valuable hands-on experience with iptables, routing, and managing network traffic in a secure environment. It is a practical demonstration of firewall rules, IP forwarding, and the use of NAT for secure network communication.

# Author
Nikhil Makwana
