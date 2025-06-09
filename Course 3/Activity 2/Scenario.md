Activity Overview

In this activity, you will consider a scenario involving a customer of the company that you work for who experiences a security issue when accessing the company’s website. You will  identify the likely cause of the service interruption. Then, you will explain how the attack occurred and the negative impact it had on the website. 

In this course, you have learned about several common network attacks. You have learned their names, how they are carried out, and the characteristics of each attack from the perspective of the target. Understanding how attacks impact a network will help you troubleshoot issues on your organization’s network. It will also help you take steps to mitigate damage and protect a network from future attacks. To review attacks, visit 
Identify: Network Attacks

Be sure to complete this activity before moving on. The next course item will provide you with a completed exemplar to compare to your own work. 

Scenario

Review the following scenario. Then complete the step-by-step instructions.

You work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, you receive an automated alert from your monitoring system indicating a problem with the web server. You attempt to visit the company’s website, but you receive a connection timeout error message in your browser.

You use a packet sniffer to capture data packets in transit to and from the web server. You notice a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. You suspect the server is under attack by a malicious actor. 

Cybersecurity Incident Report

Section 1: Identify the type of attack that may have caused this 
network interruption
One potential explanation for the website's connection timeout error message is: The attacker is sending several SYN requests every second. The rows highlighted and labeled yellow are failed communications between legitimate employee website visitors and the web server.

The logs show that: Only one IP address is attacking the web server by sending multiple Syn request every second. 
This event could be: DDOS SYN Flood Attack. 



Section 2: Explain how the attack is causing the website to malfunction
When website visitors try to establish a connection with the web server, a three-way handshake occurs using the TCP protocol. Explain the three steps of the handshake:
1. The [SYN] packet is the initial request from an employee visitor trying to connect to a
web page hosted on the web server. SYN stands for “synchronize.”

2. The [SYN, ACK] packet is the web server’s response to the visitor’s request agreeing to
the connection. The server will reserve system resources for the final step of the handshake. SYN, ACK stands for “synchronize acknowledge.”

3. The [ACK] packet is the visitor’s machine acknowledging the permission to connect.
This is the final step required to make a successful TCP connection. ACK stands for
“acknowledge.”

Explain what happens when a malicious actor sends a large number of SYN packets all at once: When the malicious actor send number of SYN packet, The server will become overwhelmed and unable to respond to the requests. The visitors receive more error messages indicating that they cannot establish or maintain a connection to the web server.

Explain what the logs indicate and how that affects the server: The logs indicate that the IP address 203.0.113.0 is sending multiple SYN request to the server which is most likely called DDOS SYN flood attack. The server at first was able to respond to the normal visitor traffic but after the attack, It got difficult which make it to crash out.

You take the server offline temporarily so that the machine can recover and return to a normal operating status. You also configure the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. You know that your IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. You need to alert your manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. You will need to be prepared to tell your boss about the type of attack you discovered and how it was affecting the web server and employees.
