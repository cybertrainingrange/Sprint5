# Industry Tools for SIEM

SIEM (Security Information and Event Management) platforms play a crucial role in modern cybersecurity strategies by providing organizations with the ability to effectively manage and analyze security event data from various sources. These platforms integrate essential features such as event correlation, log management, threat intelligence, and incident response to provide comprehensive security monitoring and threat detection capabilities.


<table>
   <tr>
    <td><img src="https://drive.google.com/uc?export=view&id=1JpefoiTCX-YzQSHn_WGvT0X35Xa38qAl"> </td>
    <td align="top">Splunk: Splunk is a leading commercial SIEM platform known for its powerful log management and data analytics capabilities. It offers real-time monitoring, event correlation, and a wide range of prebuilt security use cases. Splunk supports integration with various data sources and has a large ecosystem of apps and add-ons.</td>
  </tr>
    <tr>
    <td align="top">IBM QRadar: IBM QRadar is another popular commercial SIEM solution that provides real-time monitoring, threat detection, and incident response capabilities. It offers advanced analytics, behavior profiling, and supports a wide range of data sources. QRadar also includes features like vulnerability management and network flow analysis. </td>
    <td><img src="https://drive.google.com/uc?export=view&id=1UcgGOd5AMFmnqK8JyM8aD6BTobST2YoX"></td>
    <tr>
    <td class="tg-0lax">![SIEM](https://drive.google.com/uc?export=view&id=1VQ2qgGrCqM2Bkqw7ccnSJpTAU8UdbYth)</td>
    <td class="tg-0lax"></td>
  </tr>
    <tr>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">![SIEM](https://drive.google.com/uc?export=view&id=1VQ2qgGrCqM2Bkqw7ccnSJpTAU8UdbYth)</td>
  </tr>
    <tr>
    <td class="tg-0lax">![SIEM](https://drive.google.com/uc?export=view&id=1VQ2qgGrCqM2Bkqw7ccnSJpTAU8UdbYth)</td>
    <td class="tg-0lax"></td>
  </tr>
    <tr>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">![SIEM](https://drive.google.com/uc?export=view&id=1VQ2qgGrCqM2Bkqw7ccnSJpTAU8UdbYth)</td>
  </tr>
</table>

|  ![SIEM](https://drive.google.com/uc?export=view&id=1VQ2qgGrCqM2Bkqw7ccnSJpTAU8UdbYth)  |
| ----------------------- |




**There are several SIEM platforms available in the market today, both commercial and open source, each offering different features and capabilities. Here are some notable SIEM tools:**



| Analyzing network protocols is a crucial aspect of network troubleshooting, security analysis, and performance optimization. Network protocols govern the rules and procedures for data communication between devices in a network. To analyze network protocols effectively, professionals often rely on tools like Wireshark or other neutral vendor tools, which provide detailed insights into the traffic flowing through the network. |
| Network protocol analysis is the process of examining the data packets that are transmitted over a network. This can be done for a variety of purposes, including troubleshooting network problems, detecting security threats, and analyzing network traffic. |

**There are a number of tools that can be used for network protocol analysis. Some of the most popular tools include.**

- Wireshark: Wireshark is a free and open-source network protocol analyzer. It is one of the most powerful tools available for network protocol analysis.
- NetworkMiner: Network Miner is a commercial network protocol analyzer. It offers a number of features that are not available in Wireshark, such as the ability to decode encrypted traffic.
- tcpdump: tcpdump is a command-line network protocol analyzer. It is a powerful tool, but it can be difficult to use.
- ngrep: ngrep is a command-line network protocol analyzer that is similar to tcpdump. It is easier to use than tcpdump, but it does not offer as many features.
- Microsoft Network Monitor: Microsoft Network Monitor is a commercial network protocol analyzer that is included with Windows Server. It is a powerful tool, but it is not as widely used as Wireshark or Network Miner.

When analyzing network protocols, two widely used models come into play: **the OSI model and the TCP/IP model.** These models serve as frameworks for understanding and dissecting the different layers of network communication.




![OSI Model](https://drive.google.com/uc?export=view&id=1JfZIN75hzjLyZ4HIb0uwXdTCAa9xUdoP) 




**The OSI (Open Systems Interconnection) model is a conceptual framework that defines seven layers, each responsible for a specific aspect of network communication. These layers include:** 

1. Physical Layer: Deals with the electrical and physical properties of data transmission, such as cables and network interfaces.
2. Data Link Layer: Manages the reliable transmission of data across a physical link, addressing errors and controlling flow.
3. Network Layer: Handles logical addressing and routing of data packets across different networks.
4. Transport Layer: Provides end-to-end communication between source and destination hosts, ensuring reliable data delivery and flow control.
5. Session Layer: Establishes, manages, and terminates connections between applications.
6. Presentation Layer: Translates data between the application layer and the network format, handling data encryption, compression, and formatting.
7. Application Layer: Represents the interface between the network and the end-user applications, facilitating communication between them. 



| ![App Screenshot](https://drive.google.com/uc?export=view&id=1AN0_tMVUvTzAzP_injeJbkcG5y2myzy8) |
| ----------------------- |


**The TCP/IP (Transmission Control Protocol/Internet Protocol) model is a simplified version of the OSI model, widely used in today's internet communication. It consists of four layers:**

1. Network Interface Layer: Equivalent to the combination of the physical and data link layers in the OSI model.
2. Internet Layer: Corresponds to the network layer in the OSI model, handling IP addressing, routing, and fragmentation.
3. Transport Layer: Combines the functions of the transport and session layers in the OSI model, with TCP and UDP protocols responsible for reliable data delivery and connection management.
4. Application Layer: Similar to the OSI model's application layer, it includes protocols like HTTP, SMTP, FTP, etc., that enable application-level communication.

When using tools like Wireshark or neutral vendor tools, the network traffic is captured at various layers of the OSI or TCP/IP model, depending on the tool's capabilities and configuration. These tools provide detailed packet-level analysis, allowing professionals to examine the headers, payload, and other relevant information for each captured packet.


**By analyzing network protocols using such tools, experts can:**

1. Identify and troubleshoot network issues: Analyzing protocol-level data helps pinpoint problems such as packet loss, latency, or misconfigurations at different layers.
2. Monitor network performance: By examining protocol-specific metrics, professionals can assess the performance of individual protocols, identify bottlenecks, and optimize network resources.
3. Ensure network security: Analyzing protocols allows for the detection of malicious or abnormal traffic patterns, helping to identify potential security threats and vulnerabilities.
4. Validate compliance and standards: By comparing captured network traffic against established protocols and standards, professionals can ensure compliance and identify any deviations or non-standard behavior.

Analyzing network protocols using tools like Wireshark or neutral vendor tools allows professionals to gain insights into the intricacies of network communication. The OSI and TCP/IP models provide a framework for understanding the different layers involved in this communication, enabling effective troubleshooting, performance optimization, security analysis, and compliance validation.

## Technical Documentation 🤖

[Analyzing Network Protocols](https://docs.google.com/document/d/19xuaboWqPuh2xHv4bwEWp6eR3k2f7zS9hQ9Nw0aDXqE/edit?usp=share_link)


## 🔗 Authors: 👐

### Emilie Dionisio👩‍
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emdionisio/)
- [@Emilie Dionisio](https://github.com/emiliedionisio)


### Ameha Zewde Lemma 👨
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ameha-lemma/)
- [@Ameha Zewde Lemma](https://github.com/orgs/cybertrainingrange/people/ameha01)

### Mayra Castillo👩‍
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayra-castillo-barrios/)
- [@Mayra Castillo](https://github.com/mbarri0s)
