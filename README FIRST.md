# dc26
DEFCON 26 Workshop Securing Big Data in Hadoop
By: Mike Guirao (a.k.a. Chicolinux)
e-mail: dc26@futurasolucioneslibres.com
Twitter: @miguelguirao

ERRATA: As I'm writing this text, July 6th 2018, a new version of the HDP is available, version 2.6.5! I'm preparing the workshop around this version!

Welcome to this workshop! My name is Mike Guirao and I will be teaching this workshop at DEFCON 26. This is my third workshop at DC, my very first one was "Memory Forensics with Volatility" at DC24, "Secure Communications in Android with SSL/TLS" at the Crypto & Privacy Village DC25.

So, lets get ready for our workshop!!

First and foremost, you need to get up and running your Docker container. We will be working with Hortonworks Data Platform Sandbox, also known as HDP Sandbox, it is a very handy way of playing with Hadoop that you can run in your laptop.

Make sure to arrive to the workshop day with this container up & running! I will assume that you will arrive to the workshop day with the HDP up & running!

Please refer to the workshop.txt file, and follow the link to download the Docker image and create your container. You will be reading the: Sandbox Deployment and Install Guide - Deploying Hortonworks Sandbox on Docker.

If you are new to Hadoop and HDP, I advice you to read Learning the Ropes of the HDP Sandbox, at the Further Reading Section.

By the way, we are using HDP, we are NOT USING HDF!!!

* docker [start|stop] sandbox-hdp
* docker [start|stop] sandbox-proxy

[MORE HELP]
If you are new to Hadoop, there is a excelent free training "HDP Overview: Apache Hadoop Essentials - Self Paced Training", and you can find it here: http://learn.hortonworks.com/hdp-overview-apache-hadoop-essentials-self-paced-training

This is also a good one: https://github.com/HortonworksUniversity/Essentials

https://docs.hortonworks.com/HDPDocuments/HDP2/HDP-2.6.1/index.html

https://hortonworks.com/tutorial/learning-the-ropes-of-the-hortonworks-sandbox/