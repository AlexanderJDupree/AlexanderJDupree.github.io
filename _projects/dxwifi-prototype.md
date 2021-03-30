---
title: "DxWiFi"
---

Skills Learned: **802.11 MAC**, **Atheros AR9271 Driver/Firmware Development**, **libpcap Packet capture library**, **Forward Error Correction**

Built With: **C**, **libpcap**, **Cmake5**<br/>

OreSat Live is tasked with the mission of streaming images of Oregon from
low earth orbit (~400km) to DIY Handheld ground stations built by high-school 
students with cheap, COTS WiFi adapters. The 802.11 WiFi standard was designed 
for reliability over a Local Area Network in mind, and has some significant 
shortcomings when it comes to long range transmission. 
DxWiFi attempts to surmount these shortcomings by leveraging packet injection 
and monitoring. Typically used by security researchers (or nefarious hackers), 
packet injection and monitoring has seen extensive use in the testing (and breaking)
of 802.11 protocols. With packet injection we can send custom raw data frames 
over the air without the need of a network connection or an expectation of a 
positive ACK from the receiver. Likewise, receivers enabled in monitor mode can
"promiscuously" scan and capture any packet regardless of destination. Combining 
injection and monitoring enables DxWiFi to achieve true unidirectional communication 
without the need for control packets or ACKs. 

Check out the full repository [here](https://github.com/AlexanderJDupree/dxwifi-prototype)

