---
title: "Ultra Low Power Connectivity and Sensing"
layout: single-portfolio
excerpt: "<img src='/images/research/map.png' alt=''>"
collection: research
order_number: 60
header: 
  og_image: "research/map.png"
---


Scalable and Ultra-low-power WiFi connectivity for IoT [WCSNG](https://wcsng.ucsd.edu/ubiquitousIoT/)


IoT devices need very low power connectivity to the Internet so they can be deployed for years without having to replace batteries. Further, IoT adoption can be accelerated if IoT devices can connect to widely used infrastructure such as WiFi access points, in other words, if connectivity is via a standard WiFi AP and yet consume just tens of microwatts of power for IoT communication. My research tackled this problem via multiple systems, including designing RFIC systems. For example, my work was the first to enable long range high-data-rate connectivity via backscattering existing WiFi signals from the WiFi APs, which are already deployed and can be readily used for backscattering. We showed that with a meager budget of a few micro-watts, backscatter devices could achieve 5 Mbps of connectivity. This work leveraged the concept of Code-Word translation allowing the IoT device to encode information in the reflections (backscatter). These reflections are received by another WiFi device, decoding the reflections to decode the IoT device data. This work created the first benchmark for achieving WiFi backscattering-based connectivity.

To eliminate the need for full-duplex, I invented the concept of code-word translation, that encodes the information from IoT devices on an existing ambient WiFi signal by backscattering it while changing the underlying information in the ambient WiFi signals [Fig. 6]. Any WiFi receiver can decode the WiFi complaint backscatter signals, thus enabling for the first time a true existing infrastructure-based connectivity while achieving a high data-rate like WiFi transmission (Mbps) for IoT devices, providing secure and backscatter-based WiFi connectivity to IoT devices [IV.A.9]. I generalized the code-word translation concept to work for all ISM band transmissions like WiFi, Zigbee or Bluetooth [IV.A.11]. This work enabled for the first time a network coding concept with a practical application.

Next, we developed an RFIC in collaboration with my colleague Mercier, which enhanced the range of the WiFi backscatter and reduced the power consumption achieving a world record. Since the IoT devices only reflect the information, they have a limited range. With RFIC, we developed the world's lowest power WiFi, which uses just 28 micro-watts of peak power to send the information, which is 5000x more efficient, achieving 13 meters of range. Next, we designed a hierarchical wake-up receiver that enables world-first synchronized WiFi backscatter. Most prior systems lacked high-quality synchronization and limited throughput performance, all the while improving idle power consumption to 3 microwatts which are 10000x more efficient than current IoT devices. To further improve the range and require a single AP, we developed the world’s first retro-reflective MIMO WiFi backscatter connectivity. We enhanced the van-atta array concept to perform the code-word translation, improving the range to 23meters. Recently, we demonstrated by designing a MIMO re-directive tag that would improve the range up to 50 meters. Furthermore, even current BLE devices used in healthcare devices are bulky and power-hungry. My research solves this problem by developing such a connectivity paradigm for BLE devices and reducing power consumption by 1000x. 

This work would have a ground-breaking implication for both the circuits and networking communities, wherein extensive work has been undertaken to provide ultra-low-power connectivity with existing infrastructure. Our work promises that this could be a feasible and practical solution. The above technology has been translated into a commercial product at Haila, where I serve as a technical adviser, which has demonstrated this solution working in greenhouses in Europe. In the next few years, our goal is to increase the range of WiFi-backscatter connectivity to 100 meters, support self-localization, support the latest 11ax connectivity, and develop self-sustainable tags, which can be used for all wearables, wearables, and other IoT devices. 

