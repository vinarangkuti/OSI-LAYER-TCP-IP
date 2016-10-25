>**ARP SPOOFING**
----------------
ARP (address resolution protocol) operates by broadcasting a message across a network, to determine the Layer 2 address (MAC address) of a host with a predefined Layer 3 address (IP address). The host at the destination IP address sends a reply packet containing its MAC address. Once the initial ARP transaction is complete, the originating device then caches the ARP response, which is used within the Layer 2 header of packets that are sent to a specified IP address. 
An ARP Spoofing attack is the egression of unsolicited ARP messages. These ARP messages contain the IP address of a network resource, such as the default gateway, or a DNS server, and replaces the MAC address for the corresponding network resource with its own MAC address. Network devices, by design, overwrite any existing ARP information in conjunction with the IP address, with the new, counterfeit ARP information. The attacker then takes the role of man in the middle; any traffic destined for the legitimate resource is sent through the attacking system. As this attack occurs on the lower levels of the OSI model, the end-user is oblivious to the attack occurrence. 



