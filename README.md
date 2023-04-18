# TP3_Sec_Reseaux
![LOGO](https://user-images.githubusercontent.com/99618982/225015198-317d743a-74b9-44ad-a13b-7e698620b346.jpeg)
Realisé Par : Adil Erraad

# Sommaire:

 1. **Introduction:**
 
    1. *Objectifs de ce TP :*
    
    2. *Outils logiciels :*
    
 2. **Network Topology:**
 
 3. **Conclusion:**


## 1. **Introduction:**
  1. *Objectifs de ce TP :*
  
  2. *Outils logiciels :*
  
    Cisco Packet tracer
  
## 2. **Network Topology:**
 1. *Topology 1*
 
 ![2023-04-18 14_10_38-Cisco Packet Tracer - C__Users_adilraad2001_Cisco Packet Tracer 8 2 0_saves_tp3](https://user-images.githubusercontent.com/99618982/232805592-3e4481ee-3675-4e4e-ae7d-0fa36d789253.png)
 
 1.1. Advantage:
 
    - Cost-effective:Using a single switch to link three machines can be less expensive than using numerous switches. This is especially effective in small-scale or low-budget networks.
    
    - Simple management:Managing a single switch is often easier than managing numerous switches. Because there is only one device to manage, tasks like as configuration, monitoring, and troubleshooting are simpler.

    - Reduce network complexity:The entire network topology is simpler with only one switch, which can lead to easier troubleshooting and maintenance. It may also necessitate less network cabling, resulting in less clutter and easier cable management.
    
    - easier surveillance:Because there are fewer ports and connections to monitor with a single switch, it may be easier to monitor network traffic and discover any security threats or anomalies.
    
 1.2. disadvantage:
 
    - Small-scale segmentation:It may be difficult to establish adequate network segmentation for security purposes in a network with only one switch. Segmentation aids in the isolation of different areas of the network in order to contain potential security breaches. An attack or breach in one computer may have a greater impact on the rest of the network if it is not properly segmented.
    
    - One point to failure:If a single switch fails, the entire network may go down, impacting all machines connected to it. Redundancy and fault tolerance may be jeopardized, affecting total network availability and resilience.
    
    - Security features are limited:Some advanced security features, such as VLANs, access control lists (ACLs), and network segmentation, may necessitate more complex configurations that are difficult to achieve with a single switch. This may hinder the network's capacity to apply comprehensive security measures.

 2. *Topology 2*
 
 ![2023-04-18 14_20_15-Cisco Packet Tracer - C__Users_adilraad2001_Cisco Packet Tracer 8 2 0_saves_tp3](https://user-images.githubusercontent.com/99618982/232806735-975c5ad4-d79d-47de-a13a-da6e147caae9.png)
 
  2.1. Advantage:
  
   - Segmentation:Multiple switches enable greater network segmentation, which can assist separate different areas of the network and reduce the impact of security breaches or attacks. This can aid in containing any security events and preventing them from propagating throughout the network.
   
   - Access control:Access control mechanisms such as VLANs and ACLs can be used with multiple switches to regulate traffic between distinct network segments. This can aid in the enforcement of security regulations and the restriction of illegal access to critical resources.
   
   - Flexibility:More advanced security features, such as VLANs (Virtual LANs), access control lists (ACLs), and other security measures, can be implemented with numerous switches to regulate and secure traffic between separate network segments.
   
   - Monitoring and detection:Multiple switches can help detect and mitigate potential security risks or abnormalities by providing more visibility into network traffic and activity. On switches, monitoring tools and security protocols can be used to monitor traffic and identify any security breaches or malicious activity.
  
  2.2. disadvantage:
  
  - Configuration difficulties:To enable effective communication between switches and machines, additional setup chores such as inter-switch links (ISLs) or trunking may be required when configuring and administering several switches. This can make network design and administration more difficult.
  
  - Enhanced attack surface:With several switches, there may be additional potential entry points for attackers to exploit, thereby increasing the network's overall attack surface. To prevent this danger, proper security measures, such as securing switch configurations and installing tight access controls, are required.
  
  - Cost:When opposed to having only one switch, implementing numerous switches may incur higher expenditures, including the cost of procuring and maintaining additional network devices.
  
  - Complexity:The overall network architecture may be more difficult to configure, administer, and troubleshoot with several switches. This may necessitate greater effort and knowledge of network architecture and administration.

 3. *Topology 3*
 
 ![2023-04-18 14_21_09-Cisco Packet Tracer - C__Users_adilraad2001_Cisco Packet Tracer 8 2 0_saves_tp3](https://user-images.githubusercontent.com/99618982/232806900-a6e6aa2c-2bfb-463a-9859-34fd5b464c8e.png)
 
  3.1. Advantage:
   
   - Segmentation:VLANs can offer logical network segmentation, allowing different types of traffic to be isolated. As an attacker getting access to one VLAN may have limited or no view into other VLANs, this can help restrict the potential impact of security breaches or assaults.
   
   - Access control:To restrict traffic between separate VLANs, VLANs can be used to establish access control measures such as VLAN-based ACLs. This can help to enforce security policies and limit network connectivity, lowering the danger of unauthorized access or data breaches.
   
   - Least privilege:The idea of least privilege can be enforced by grouping machines into distinct VLANs based on their responsibilities or permissions. This means that each computer will only have access to the resources and services required for its specialized role, lowering the possible attack surface and reducing the danger of lateral movement by attackers.
   
   - Monitoring and detection:VLANs can be used to improve security threat monitoring and detection. Having separate VLANs for different types of traffic makes it easier to monitor and analyze data inside each VLAN, which can help spot potential security issues, abnormalities, or malicious activity.
   
  3.2. disadvantage:
  
   - Misconfiguration risk:VLAN misconfigurations, such as erroneous VLAN assignments or misconfigured trunk lines, can lead to security flaws. For example, if a machine is allocated to the wrong VLAN by mistake, it may acquire illegal access to resources in other VLANs. To mitigate this risk, proper configuration management techniques should be used.
   
   - VLAN hopping:VLAN hopping is a security flaw in which an attacker gains unauthorized access to a VLAN by taking advantage of misconfigured or unprotected trunk lines. An attacker may be able to obtain access to critical resources in other VLANs as a result of this. Proper security measures, like as protecting trunk lines and employing VLAN pruning, can assist limit this risk.
   
   - Insider threats:While VLANs can enable segmentation and access control, authorized users within the same VLAN can still represent a risk. To reduce the danger of insider threats, proper user access control, authentication, and authorisation methods should be adopted.
   
   - Single point of failure:If the switch linking the machines to the VLANs fails, the entire network may go down because all machines in various VLANs rely on the same switch for connectivity. This danger can be mitigated by implementing redundant switches and network resilience solutions.

 
## 3. **Conclusion:**

When using different Topology to build a network, the benefits and disavantage depend on the quality, shape, and tools used in it, as each part or tool can increase the effectiveness of the network, but it will affect another part, and the least part is the cost each time it increases in order to make the network safe. Through multiple monitoring methods and bypassing common errors and dangers
So the network topology can be built in different ways for several reasons


   
