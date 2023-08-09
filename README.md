<h1>Using NIST CSF to Respond to a Security Incident</h1>



<h2>Description</h2>
Project consists of using the NIST cybersecurity framework to analyze a network Incident . The National Institue od Standards and Technology Cybersecurity framework is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. There are five core functions of the NIST CSF framework: identify, protect, detect, respond, and recover.These core functions help organizations manage cybersecurity risks, implement risk management strategies, and learn from previous mistakes. Plans based on this framework should be continuously updated to stay ahead of the latest security threats. The core functions help ensure organizations are protected against potential threats, risks, and vulnerabilities.
<br />


<h2>Scenario:</h2>

<p>
I am a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.<br/>
During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 
<br/>
The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 
<br/>
To address this security event, the network security team implemented: <br/>
<ul>
  <li>A new firewall rule to limit the rate of incoming ICMP packets</li>
  <li>Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets</li>
  <li>Network monitoring software to detect abnormal traffic patterns</li>
  <li>An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics</li>
</ul>
<br/>
</p>
<h2>Applying the Framework:</h2>
<p>
Based on this security event, we are going to create a plan to improve our company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF), we will use the CSF to help us navigate through the different steps of analyzing this cybersecurity incident and integrate our analysis into a general security strategy:
<br/>
<img src="https://i.imgur.com/RlLex0P.png" height="80%" width="80%" alt="The first 3 cores of the Framework"/>
<br />
<br />

<img src="https://i.imgur.com/HNfrOsg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
