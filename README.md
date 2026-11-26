# CCNA Labs

Cisco Packet Tracer labs I built while studying for the CCNA. Each lab has a topology and a configuration that I built and tested myself.

## Labs

1- configuration lab -> basic device configuration

- Set hostnames on the routers and switches
- Secured access with console, VTY and enable passwords
- Assigned IP addresses to PC and router interfaces
- Enabled interfaces (`no shutdown`) and added descriptions
- Connected the devices with the correct cable types (straight-through, crossover)
- Tested connectivity with `ping` and checked the setup with `show ip interface brief` and `show running-config`

  2- Lab on routing
  
- configurating ospf (Open Shortest Path First)
- Advertised the connected networks in area 0
- Verified neighbors and routes with `show ip ospf neighbor` and `show ip route`
- Tested connectivity between PCs with `ping`

  
  3- Spanning-tree
  
 - Built a switch topology with redundant links
- Observed how STP elects the root bridge
- Identified root, designated and blocked ports
- Verified with `show spanning-tree`



## Tools
- Cisco Packet Tracer


 Verification

Each lab can be checked with commands such as `show ip route`, `show spanning-tree`, `show running-config` and `ping`.


## Author

Moaz Mossad
