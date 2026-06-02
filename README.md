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

## Conclusion
Distance Vector Multicast Routing Protocol (DVMRP) is an important multicast routing protocol that enables efficient one-to-many communication in computer networks.
