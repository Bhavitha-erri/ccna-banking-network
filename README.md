                                                   ENTERPRISE NETWORKING PROJECT

This is the requirnent;

 Radeon company Ltd. is a US owned company that deals with Banking and Insurance the company is intending to expand its services across the African continent having the first
 branch to  be located in Nairobi,Kenya.The company has secured a four-story building to operate within the kenyan capital city.Therefore,the company would like to allow sourcing
 the knowledge froma group of final-year students from the local university to design and implement their company network .Assume you are among the students to take over this role.
 Carefully read down the requirements then model the design and implement the network based on the company needs.Each floor has departments as provided in the table below.
 FIRST FLOOR
 Management      20 pc 4 printers
 Research        20 pc 4 printers
 Human resource  20 pc 4 printers
          SECOND FLOOR
  marketing     20 pc  4 printers
  Accounting    20 pc  4 printers
  Finance       20 pc  4 printers
          THIRD FLOOR
Logistics and store  20 pc  4 printers
customer care        20 pc  4 printers
Guest area           40 pc  2 printers
          FOURTH FLOOR
Admin  20 pc 2 printers
ICT    20 pc 2 printers
server room  2 admin pcs and 3 DHCP,HTTP AND EMMAIL

1.--There should be one router on each floor.The router should be connecting switches on that floor.
--Use OSPF as the routing protocol to advertise routers
--Each departent is required to have a wireless network for the users.
--Each departent except the server room will be anticipated to have around 60 users both wired and wireless users.
--Host devices in the network are required to obtain IPV4 addresses automatically.
--Devices in all the departents are required to communicate with each other.
-- All devices in the network are expected to obtain an IP address dynamically fro the dedicated DHCP servers located at the server room.
--create HTTP,and E-ail servers.
--configure SSH in all the routers for remote login.

2.Use hierarchical network design with redundancy included:
 -- Having core,distribution and access layers
3.configure the basic configuration of the devices
 -- Hostnames
 -- Line console and VTY passwoards
 --Banner messages
 --Disable domain ip lookup
4.Each departent should be in a different VLAN
  --create VLAN in every department
  --VLANs you will use in your case ,including VLAN1 also eg.10,20,30...etc
  --each VLAN should be a different subnetwork
5.Planning of IP addresses
  --you have been given 192.168.10.0 as the base address for this network.
  --Do subnetting based on the nuber of hosts in every department as provided above
  --identify subnet mask,useable IP  address range and broadcast address for each subnet
6.End device configurations:
  --configure all the end devices in the network with the appropriate IP address based on the calculations above.
7.End device configuration
   --use sticky caand to obtain AC address
   --violation ode of the shutdown
8.Test communication
  --Do device in the sae VLAN communicate
  
