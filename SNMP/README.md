<img src="assets/SNMP.wepb" alt="Captive Portal example screenshot" style="width: 380px;" align="right">

# <acronym title="Simple Network Management Protocol">SNMP</acronym> | Net | Quickstarts
- Allow devices to communicate management information to one another
- The dream: one admin can control an entire fleet (start process, close that interface, get rid of a user, see errors, deal with spammers, etc)

## Other Protocols
- IPX
- AppleTalk
- CLNS
- ...

## History
...

## System Components
- Similar to client-server model
- Diff to Secure Shell (SSH)
- Faster than SSH
- **SNMP** *manager* is the client software that issues requests
  - Named manager because (expected) it extracts management information from devices and also can issue commands to them
- **SNMP** *agent* is a server
  - Runs devices like: router, server, or workstation
  - More dynamic than most server software
  - Can help with confuguring the host
  - Gets information on the local system and sends back info to the *manager*
- <acronym title="Network Management System"><strong>NMS</strong></acronym> is for collecting data and issue commands to agents
  - It might run tools for managing systems via several other protocols
  - Transforms **SNMP** and other data into pretty human-readable graphs so you can make decisions
  - Sometimes refered as *monitoring systems*
  - Monitoring systems: 
    - Cacti
    - MRTG
    - Graphite
    - ...
  - Full-featured NMSes
    - OpenNMS
    - HP BTO/OpenView
  - Other NMSes (partial support for **NMS**): 
    - Zabbix
    - Nagios
    - Icinga
## How is SNMP Used
...
