This is a current, as of October 13, 2025, lab setup to the objectives in Cisco's 200-301 CCNA v1.1 Exam Topics. The purpose of these labs are to:
  1) Give a free alternative to paid resources
  2) To give a framework for people to work off of which allowed me to succeed
  3) To combat against braindumping and actually give a concise idea of what you need for the CCNA itself
  4) To serve as a more difficult lab series where most other material is lacking or beyond the scope of the CCNA exam topics
  6) To document my studies and serve as a resource in the future

 Each lab has a Packet Tracer lab, an answer key with explanations, and a .png diagram. 
 All of these labs are based off of the posted exam topics wherever "Configure" is listed on Cisco's learning network webpage: https://learningnetwork.cisco.com/s/ccna-exam-topics

  1.0 NETWORK FUNDAMENTALS
  
    1.6 Configure and verify IPv4 addressing and subnetting
    1.8 Configure and verify IPv6 addressing and prefix

  2.0 NETWORK ACCESS
  
    2.1 Configure and verify VLANs (normal range) spanning multiple switches
      2.1.a Access ports (data and voice)
      2.1.b Default VLAN
      2.1.c InterVLAN connectivity
    2.2 Configure and verify interswitch connectivity
      2.2.a Trunk ports
      2.2.b 802.1Q
      2.2.c Native VLAN
    2.3 Configure and verify Layer 2 discovery protocols (Cisco Discovery Protocol and LLDP)
    2.4 Configure and verify (Layer 2/Layer 3) EtherChannel (LACP)

  3.0 NETWORK CONNECTIVITY
  
    3.3 Configure and verify IPv4 and IPv6 static routing
    3.3.a Default route
    3.3.b Network route
    3.3.c Host route
    3.3.d Floating static
    3.4 Configure and verify single area OSPFv2
    3.4.a Neighbor adjacencies
    3.4.b Point-to-point
    3.4.c Broadcast (DR/BDR selection)
    3.4.d Router ID
    
  4.0 IP SERVICES
  
    4.1 Configure and verify inside source NAT using static and pools
    4.2 Configure and verify NTP operating in a client and server mode
    4.6 Configure and verify DHCP client and relay
    4.8 Configure network devices for remote access using SSH

  5.0 SECURITY FUNDAMENTALS
  
    5.3 Configure and verify device access control using local passwords
    5.6 Configure and verify access control lists
    5.7 Configure and verify Layer 2 security features (DHCP snooping, dynamic ARP inspection, and port security)
    5.10 Configure and verify WLAN within the GUI using WPA2 PSK



These labs are built to be more comprehensive than what I experienced on the exam to reinforce these configurations to memory. None of these labs 
are a copy of the lab exams. *These are not braindumps!* These labs were built in an attempt to emulate closer to the complexity of Boson's netsim labs 
while retaining more pointed directions reflecting the requirements of the exam topics.

My recommendation is that the labs here should serve as a first-time reference on what you should expect when configuring the exam topic lobs and then build your own 
labs while using mine as templates. An example would be:

    Use Lab 2.1 PART 2 and apply extended ACL's to block incoming Echo requests to the 
    SVI's while still allowing Echo reply requests from the administration SVI.

  Another example would be:
  
    Use lab 3.4 OSPF to configure IPv6 routes on all of the routers forwarding to the edge router
    
This is what I did for roughly a month, 6-8 hours a day preparing for my third attempt and pass on the CCNA and I truly felt that gave me the capabilities to pass.


As for the labs themselves, feel free to use them for anything. Share them. Sell them. Claim them as your own. Put more garbage on Udemy. Whatever. I received a lot of free 
information (thanks, Jeremy's IT Lab) so I feel it's only appropriate to give freely as well.
