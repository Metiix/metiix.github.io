---
layout: post
published: false
title: HA Cluster
---
A high availability cluster is a group of hosts that act like a single system and provide continuous service when certain system component fails. They are often used for failover and backup purposes.

 High availability clusters, also known as HA clusters or fail-over clusters operate using high availability software.  Most systems usually have redundant soft and hardware that makes this system available.

High Availability implementations consist of multiple servers composed together into a single cluster.  HA cluster implementations attempt to build redundancy into a cluster to eliminate failure, including network connections and data storage which is redundantly connected via storage networks.  These clusters consist of multiple nodes that share information with each other through shared data memory grids.  HA clusters usually use a heartbeat private network connection which is used to monitor the health and status of each node in the cluster.  The servers communicate with each other to update and maintain a heartbeat.

When a failure does occur, the process is able to recover and restore the system to normal within a matter of microseconds.  HA clustering detects software and hardware faults, then instantly restarts the application on another system without admin help. Without clustering, if your server application were to crash, the application would be unavailable until the server was fixed. 

HA clusters are commonly uses for file sharing and critical databases. This is a great option to ensure reliability, scalability and high system availability. 