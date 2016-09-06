---
layout: post
published: false
title: Virtualization
---
Virtualization is the creation of a virtual version such as an operating system, a server, a storage device or other network resources.
 
Operating system virtualization or OS virtualization is a server virtualization technology.  This technology involves tailoring a standard operating system so it can run multiple applications handled by several users on a single computer.  The operating systems do not interfere with each other and the users and requests are handled separately by the virtualized operating system.
 
There are three ways to create virtual servers which include full virtualization, para-virtualization and OS-level virtualization.  The three share very little in common, but all have a physical server called the host and the virtual server called the guest.
 
Full Virtualization is where the guest operating system is unaware that it is in the virtualized state and hardware is virtualized by the host operating system. Each guest server can run on its own operating system.
 
OS level virtualization does not use a hypervisor, but instead, this allows the host to perform all aspects of a fully virtualized hypervisor. Each virtual server is independent of one another, but can have mixed operating systems.
 
Paravirtualization is a virtualization technique that presents a software interface to virtual machines that is similar, but not identical to that of the underlying hardware.