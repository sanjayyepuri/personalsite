---
layout: post
title: "Building the Raspberry Pi Cluster"
description: ""
category: 
tags: ["pi cluster"]
---

Hey everyone, welcome to my blog. I’ll be writing about things that I found interesting related to computer science and other related topics.  To start things out I’m going to set up a cluster of Pis, and create an infrastructure similar to high performance computing center to perform calculations and run other tasks.

This project was inspired by a demo at School’s Out Hackathon by an engineer at Rackspace. Dale (the engineer) had created a cluster of  7 PIs and had used them to deploy an OpenStack Cluster. He called it “The Cloud” on your desk. The idea was extremely enticing but then it was not clear to me how beneficial the experience would be. The problem is that solutions have come out that made it simple to deploy a Kubernetes or Docker swarm to a group of pis; if the goal was to build a personal Cloud, it was easily attainable.  Later that weekend, I read an article about how Los Alamos National Laboratory had used an obscenely large pi cluster to simulate a super computer in order to test their software before they bought the actual computers. I am going to try to build a desktop supercomputer; a simple platform that I could use to test simple distributed algorithms or other problems related to distributed systems. The following posts, I hope, will document the process that I go through. 

## Figuring out what to get
This was a last minute effort during spring break to do something fun. Late Friday afternoon I remembered this project that I’ve been interested in. So that night right after my tax refund was deposited into my bank account, I drove to Micro-center and bought the following: 
	* 5x Raspberry Pi 3 B 
	* 1x Anker 7 port USB Charging Hub 
	* 1x Netgear FS108 8-port Network Switch
	* 5x 6in Ethernet cables 
	* 5x 6in MicroUSB cables 
	* 5x 16gb micro-sd cards 
	
Dale had created a device that was extremely compact and took very little space; perfect for my dorm room.  Unfortunately I had trouble finding the GitHub page where he described the project so I had to go off of what others did. On Thingiverse I found a nice model that had stackable cases that could house the 5 pis.  I also had an extremely strong 3M tape that i’ve dubbed “the superglue tape” that I used to attach everything together. I ended up with this: 

… picture of pis…

If you are observant, you’ll have noticed that there are only 4 pis; unfortunately, I had run out filament as I was printing out the 5th chassis.

