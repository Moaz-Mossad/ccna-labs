# CCNA Labs

Cisco Packet Tracer labs I built while studying for the CCNA (200-301). Each lab has a topology screenshot and the original `.pkt` file.

To open the `.pkt` files you need [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (free).


| Lab | Topic | File |
| --- | --- | --- |
| 1 | Basic device configuration | [Configuration lab.pkt](<Labs (.pkt)/Configuration lab.pkt>) |
| 2 | OSPF routing | [Routing Lab.pkt](<Labs (.pkt)/Routing Lab.pkt>) |
| 3 | Spanning Tree Protocol | [Spanning-tree.pkt](<Labs (.pkt)/Spanning-tree.pkt>) |
| 4 | Layer 3 EtherChannel (LACP) | [Layer 3 Switch Routing with LACP EtherChannel.pkt](<Labs (.pkt)/Layer 3 Switch Routing with LACP EtherChannel.pkt>) |
| 5 | HSRP | [HSRP.pkt](<Labs (.pkt)/HSRP.pkt>) |
## 1. Basic device configuration

![Configuration lab topology](<Pictures of labs/Configuration Lab.png>)

- Set hostnames on the routers and switches
- Secured access with console, VTY and enable passwords
- Assigned IP addresses to PC and router interfaces
- Enabled interfaces (`no shutdown`) and added descriptions
- Connected the devices with the correct cable types
- Verified with `ping`, `show ip interface brief` and `show running-config`

## 2. OSPF (Open Shortest Path First)

![Routing lab topology](<Pictures of labs/Routing lab.png>)

- Configured OSPF on the routers and advertised the connected networks in area 0
- Verified with `show ip ospf neighbor` and `show ip route`

## 3. Spanning Tree Protocol

![Spanning tree topology](<Pictures of labs/Spanning-tree.png>)

- Built a switch topology with redundant links
- Observed the root bridge election and the root, designated and blocked ports
- Verified with `show spanning-tree`

## 4. Layer 3 EtherChannel (LACP)

![Layer 3 EtherChannel topology](<Pictures of labs/Switch routing with LACP.png>)

- Bundled two Gigabit links between a 2960 and a 3560 Layer 3 switch into one LACP port-channel
- Made the port-channel and the PC1 port routed ports (`no switchport`) with IP addresses
- Enabled `ip routing` so the core switch routes between 10.1.1.0/24 and 10.1.2.0/24
- Verified with `show etherchannel summary`, `show ip route` and `ping`

## 5. HSRP

![HSRP topology](<Pictures of labs/HSRP Lab.png>)

- Configured HSRP for first hop redundancy
- Verified with `show standby`

## Author

**Moaz Mossad**, IT student at Tanta University
