# **Virtualized Networking Modes**

Course: DevOps

Mod: Week 1

Topic: Virtualized Networking Modes

Amount of time: 1.5 hours

Author: Thomas Fowler

## **Lesson Objectives**

- List the various virtual networking modes and the use
case for each.

- Describe the virtual networking modes in detail and
how their implementation differs.

--------------------------------------------

### **Overview**

There are several different virtual networking modes in VirtualBox and
they are listed below. Each mode can be used for a variety of scenarios
for providing connectivity between the host machine and other guest
VMs.

### **Network Address Translation (NAT)**

NAT stands for Network Address Translation and is the simplest
and default form of virtual networking on VirtualBox. NAT
allows for external communication to the outside world but
does not allow for exteranl traffic to reach a virtual
machine.

--------------------------------------------

### **NAT Service**

NAT Service is the simplest form of virtual networking on
VirtualBox. NAT allows for external communication to the
outside world but does not allow for exteranl traffic to
reach a virtual machine.

--------------------------------------------

### **Bridged**

Bridged is the most advanced form of virtual networking on
VirtualBox. Bridged allows for external communication to the
outside world and does so by directly attaching to the
physical network card, thus bypassing the host OS's network
stack.

--------------------------------------------

### **Internal Networking**

Internal networking allows for a network in software that
can connect virtual machines together isolated from any
other host applications or external traffic.

--------------------------------------------

### **Host-Only Networking**

Host-Only networking allows guest virtual machines and the
host to communicate with one another. This virtual networking
mode does not use the host's physical network interface but
instead uses a software-based virtual network to establish
connectivity.
