<h1>Hotel Network Design and Implementation</h1>
<h2>Technology use: VLAN, Switching, DCHP, Routing Protocol (OSPF) </h2>
<h2>Case Study</h2>
<p>
  As a part of your end year networking project, you are required to design and implement Vic Modern Hotel network. The hotel has three floors; in the first floor there are three departments (Reception, Store and Logistics), in the second floor there are three departments (Finance, HR and Sales/Marketing), while the third floor hosts the IT and Admin. Therefore, the following are part of the considerations during the design and implementation.
  <ol>1.	There should be three routers connecting each floor (all placed in the server room in IT department). </ol>
  <ol>2.	All routers should be connected to each other using serial DCE cable</ol>
  <ol>3.	The network between the routers should be: 
<l>10.10.10.0/30, </l>
<l>10.10.10.4/30, </l>
<l>10.10.10.8/30. </l>
</ol>
<ol>4.	Each floor is expected to have one switch (placed in the respective floor).</ol>
<ol>5.	Each floor is expected to have different VLANs with the following details: 
<li type="square">1st Floor
•	Reception – VLAN 80, Network of 192.168.8.0/24 
•	Store – VLAN 70, Network of 192.168.7.0/24 
•	Logistics – VLAN 60, Network of 192.168.6.0/24 </li>
  <li type="square">
2nd Floor
•	Finance – VLAN 50, Network of 192.168.5.0/24 
•	HR – VLAN 40, Network of 192.168.4.0/24 
•	Sales – VLAN 30, Network of 192.168.3.0/24 </li>
   <li type="square">
3rd Floor
•	Admin – VLAN 20, Network of 192.168.2.0/24 
•	IT – VLAN 10, Network of 192.168.1.0/24 </li>
</ol>
<ol>6. All devices in the network are expected to obtain IP addresses dynamically with their respective router configured as the DHCP server. </ol>
</p>
  <h4>Topology</h4>
  <img src="images\ping and dhcp.png" alt="ping">
  <p> 
