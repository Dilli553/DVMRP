# DVMRP
## DVMRP (Distance Vector Multicast Routing Protocol)

DVMRP is a multicast routing protocol that uses the distance-vector routing algorithm to distribute multicast packets from one sender to multiple receivers. It employs a Flood-and-Prune mechanism

•	Packets are initially flooded to all routers. 

•	Routers without interested receivers send prune messages.

•	A multicast delivery tree is formed, reducing unnecessary traffic.

 <img width="489" height="432" alt="image" src="https://github.com/user-attachments/assets/e91982a1-f5bc-4d37-9e16-59c18e2aff86" />

  
## Real-Time Applications of DVMRP

1.	Live Video Streaming
2.	Video Conferencing
3.	IPTV (Internet Protocol Television)
4.	Stock Market Information Systems
5.	Distance Learning and E-Learning
6.	Military Communication Networks

## Live Video Streaming

Used to distribute live events (sports, webinars, online classes) to many users simultaneously without sending separate streams to each user.

<img width="501" height="254" alt="image" src="https://github.com/user-attachments/assets/4ab3eb03-8347-432e-93e3-9c8e63928623" />


## Video Conferencing

Supports group communication in conferencing systems where the same audio/video data must reach multiple participants.

		 
<img width="411" height="266" alt="image" src="https://github.com/user-attachments/assets/fc58a0d3-09a1-4dc0-9961-e42bbc131d3f" />




## IP Television (IPTV)

Television content can be multicast to thousands of subscribers efficiently.
		 
<img width="408" height="224" alt="image" src="https://github.com/user-attachments/assets/e7d6c262-8aad-4028-a9cb-67a5685d8bbf" />


## Stock Market Data Distribution

Real-time stock updates can be sent simultaneously to many trading terminals.

<img width="1289" height="860" alt="image" src="https://github.com/user-attachments/assets/08e72adb-8d6b-497c-9e7c-cc65b6740843" />


## Network Announcements

Routers can multicast routing updates or network status information to multiple devices.

<img width="389" height="302" alt="image" src="https://github.com/user-attachments/assets/2463cb30-e1d5-4576-bb21-3a763e6f5fc6" />
		 

## Military Communication Networks

Used for distributing command and control information to multiple units at the same time.

<img width="389" height="302" alt="image" src="https://github.com/user-attachments/assets/e932cd02-6971-4d16-a940-3cd48ac7dceb" />


## Example Scenario

Imagine a university broadcasting a live lecture to 100 classrooms:

•	Without multicast: 100 separate streams are sent, consuming high bandwidth. 

•	With DVMRP multicast: One stream is transmitted, and routers replicate packets only where needed. 

This significantly reduces network bandwidth usage and improves efficiency.

## Advantages

•	Efficient bandwidth utilization 

•	Supports one-to-many communication 

•	Simple multicast tree construction

## Disadvantages

•	Initial flooding causes overhead 

•	Not scalable for sparse networks 

•	Largely replaced by more modern protocols such as PIM in modern networks.

## Assessment Questions and Answers

## Part A — Fill in the Blanks
#	Question	Answer
1	DVMRP stands for __________.	Distance Vector Multicast Routing Protocol
2	DVMRP is used for __________ communication.	multicast
3	DVMRP is based on the __________ routing algorithm.	distance vector
4	The technique used to verify the shortest path to the source is called __________.	Reverse Path Forwarding (RPF)
5	DVMRP initially sends packets using __________.	flooding
6	Unwanted multicast traffic is removed using __________.	pruning
7	A previously pruned branch can rejoin using __________.	grafting
8	DVMRP creates a __________ multicast tree.	source-based
9	DVMRP works efficiently in __________ networks.	dense
10	Live video streaming is a __________ application of DVMRP.	real-time

## Part B — Match the Following

Column A	Column B	Answer Key
1. DVMRP	a. Removes unwanted branches	1→f
2. RPF	b. Rejoin multicast tree	2→e
3. Pruning	c. One-to-many communication	3→a
4. Grafting	d. Initial packet distribution	4→b
5. Flooding	e. Shortest path verification	5→d
6. Multicast	f. Multicast routing protocol	6→c
7. IPTV	g. Dense-mode network	7→h
8. Dense Mode	h. Real-time application	8→g

## Part C — True or False

#	Statement	Answer
1	DVMRP is a multicast routing protocol.	True

2	DVMRP uses flooding and pruning mechanisms.	True

3	DVMRP is designed for unicast communication only.	False

4	RPF stands for Reverse Path Forwarding.	True

5	Pruning adds new branches to the multicast tree.	False

6	DVMRP works best in dense multicast environments.	True

7	Grafting reconnects a previously pruned branch.	True

8	IPTV is a common application of DVMRP.	True

## Part D — Multiple Choice Questions (MCQs)

1. What is the primary purpose of DVMRP?

To compress files

To provide multicast routing ✓

To encrypt data

To increase storage

2. DVMRP is based on which routing algorithm?

Link State

Distance Vector ✓

Hybrid

Path Vector

3. What does RPF stand for?

Reverse Packet Filtering

Reverse Path Forwarding ✓

Routing Path Function

Reliable Packet Forwarding

4. Which mechanism removes unnecessary multicast traffic?

Flooding

Routing

Pruning ✓

Broadcasting

5. Which mechanism reconnects a pruned branch?

ACK

Grafting ✓

CRC

Framing

6. DVMRP works best in which type of network?

Sparse Network

Dense Network ✓

Wireless Network

Mobile Network

7. Which of the following is a real-time application of DVMRP?

Word Processing

IPTV ✓

Image Editing

Spreadsheet Calculation

8. What type of communication does DVMRP support?

One-to-One

One-to-Many ✓

Many-to-One

Point-to-Point

## Part E — Short Answer Questions
## Q1. Define DVMRP Protocol.

Answer:

DVMRP (Distance Vector Multicast Routing Protocol) is a multicast routing protocol used to deliver data from one sender to multiple receivers efficiently. It uses distance-vector routing, Reverse Path Forwarding (RPF), flooding, and pruning mechanisms to create multicast distribution trees.

## Q2. What is the role of RPF in DVMRP?

Answer:
RPF (Reverse Path Forwarding) ensures that multicast packets arrive through the shortest path from the source. It prevents routing loops and unnecessary packet forwarding.

## Q3. What is pruning in DVMRP?

Answer:

Pruning is the process by which routers inform upstream routers that they do not have any interested multicast receivers. This prevents unnecessary multicast traffic from being forwarded.

## Q4. Why is DVMRP called a multicast routing protocol?

Answer:

DVMRP is called a multicast routing protocol because it allows a single source to send data simultaneously to multiple receivers, reducing bandwidth consumption compared to multiple unicast transmissions.

## Q5. Explain one real-time application of DVMRP.

Answer:

One real-time application of DVMRP is IPTV (Internet Protocol Television). DVMRP helps distribute television channels and multimedia content from a server to multiple subscribers simultaneously, making efficient use of network bandwidth.

## Conclusion

Distance Vector Multicast Routing Protocol (DVMRP) is an important multicast routing protocol that enables efficient one-to-many communication in computer networks.
