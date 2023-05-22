# Distributed-ticket-management-system
This is an assignment for comp 423: Distributed system

The goal of this distributed ticket management system is to create a system where a client interacts with a front end.
This front end would reliably unicast the user action(udp/ip message) to a sequencer. 
This sequencer would multicast the received message with total order to 3 distinctly programmed but functionally identical servers.
Each server would in turn have to execute the appropriate function that was given.

Each server would return their response to the front end and the end result of all servers would be compared to detect crash and software errors
