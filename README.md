# Handling-Loopy-Topology-in-RYU-SDN
The goal of this project is to install flow rules in switches in such a way that proper communication happens even if a loop exists in the network. This has been done as an excercise to learn about the inner workings of the simple_switch_13.py and the topology api provided by the RYU Controller, therefore, I haven't used STP, and created a kind of my own STP here.

This works on all kind of loopy topologies, except for the assumption that a switch is connected to a single host only. In future updates, multiple hosts on a single switch would work. 

How to run:

just run this file as the controller. store it in ryu/ryu/app .
install the dependencies which arise. 
