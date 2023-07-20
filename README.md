# DHCP-PROTOCOL
DHCP:

Dynamic Host Configuration Protocol (DHCP) is a client/server protocol that automatically provides an Internet Protocol (IP) host with its IP address and other related configuration information such as the subnet mask and default gateway.
DHCP represents Dynamic Host Configuration Protocol. It is a network management protocol that can dynamically assign an IP address to a denial device, or node, on a network so they can connect using IP (Internet Protocol).

DHCP automates and centrally handles these configurations. There is no requirement to manually assign IP addresses to new devices. Thus, there is no need for any user configuration to connect to a DHCP-based network.

In distance-vector routing (DVR), each router is required to inform the topology changes to its neighboring routers periodically. Historically it is known as the old ARPNET routing algorithm or Bellman-Ford algorithm.

How the DVR Protocol Works
In DVR, each router maintains a routing table. It contains only one entry for each router. It contains two parts − a preferred outgoing line to use for that destination and an estimate of time (delay). Tables are updated by exchanging the information with the neighbor’s nodes.
Each router knows the delay in reaching its neighbors (Ex − send echo request).
Routers periodically exchange routing tables with each of their neighbors.
It compares the delay in its local table with the delay in the neighbor’s table and the cost of reaching that neighbor.
If the path via the neighbor has a lower cost, then the router updates its local table to forward packets to the neighbor.
