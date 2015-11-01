L3-Static-Router 
================
#### ( A complete Router written in C for Linux )
#### Refer `router/sr_router.c[.h]` as a starting point for the Router's logic.
#### Problem Statement: https://github.com/mininet/mininet/wiki/Simple-Router
* This is a Router with a Static Routing table in Mininet
* It processes received Ethernet frames just like a real router with all the features, then forwards them to the correct outgoing interface. 
* It performs Longest Prefix Matching, ICMP packet handling for all types, ARP caching, ARP packet handling, TCP/IP handling according to the RFC requirements.


