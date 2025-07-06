# DNS_configuration
This repository documents the setup and configuration of a DNS server using BIND9 on an Ubuntu system. The goal of this project was to create a functional DNS server with both forward and reverse lookup capabilities for a custom domain.


📝 Project Overview
This project demonstrates a standard BIND9 configuration for a local network. The server is configured to handle DNS queries for the domain prabhath.com and perform reverse lookups for the 192.168.64.0/24 network.

Key Features:
Forward DNS Zone: Resolves prabhath.com and www.prabhath.com to the IP address 192.168.64.3.

Reverse DNS Zone: Performs reverse lookups, mapping 192.168.64.10 and 192.168.64.20 back to their respective hostnames.

DNS Forwarding: Unresolved queries are forwarded to Google's public DNS servers (8.8.8.8 and 8.8.4.4).

Recursion: Enabled to allow the server to perform lookups on behalf of clients.
