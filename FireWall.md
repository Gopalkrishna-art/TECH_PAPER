# Firewall Description

![alt text](https://media.istockphoto.com/photos/cybersecurity-and-secure-nerwork-concept-data-protection-gdrp-glowing-picture-id1197780051)

**Firewalls** have existed since the late 1980s and started as [**Packet filters**](https://www.google.com/search?q=packet+filtering+firewall&oq=packet+filters&aqs=chrome.1.69i57j0i10i131i433j0j0i10l7.5568j0j7&sourceid=chrome&ie=UTF-8), which were networks set up to examine [packets](https://www.google.com/search?q=packets+in+a+firewall&oq=packets+in+fire&aqs=chrome.2.69i57j0i22i30l5j0i390l3.9585j0j9&sourceid=chrome&ie=UTF-8), or [bytes](https://www.google.com/search?q=bytes+in+firewall&oq=bytes+in+fire&aqs=chrome.1.69i57j33i22i29i30l4.5712j0j9&sourceid=chrome&ie=UTF-8), transferred between computers. It is a software program that helps to screen out the hackers that try to reach your computer from the Internet.
 ## Introduction
A **Firewall** is a necessary part of any [security architecture](https://www.google.com/search?q=security+architecture&sxsrf=ALeKk0397W6T4AvTO0P5s2FVuTA6BqqMRA%3A1620447007741&ei=Hw-WYPfXLIzYz7sP2OCr2Ao&oq=security+architecture&gs_lcp=Cgdnd3Mtd2l6EAMyCAgAELEDEIMBMgIIADICCAAyAggAMgIIADICCAAyAggAMgIIADICCAAyAggAOgcIIxCwAxAnOgcIABBHELADUMrWE1jK1hNg4OkTaAFwAngAgAHSAYgBiAOSAQUwLjEuMZgBAKABAqABAaoBB2d3cy13aXrIAQnAAQE&sclient=gws-wiz&ved=0ahUKEwi345fCm7nwAhUM7HMBHVjwCqsQ4dUDCA4&uact=5) and  lies in between your Internet and untrusted Internet. **Firewalls**, and especially NextGeneration **Firewalls**, focus on blocking malware and application-layer attacks, along with an integrated [intrusion prevention system (IPS)](https://www.google.com/search?q=intrusion+prevention+system&oq=intrusion+prevention+system&aqs=chrome..69i57j0l9.597j0j7&sourceid=chrome&ie=UTF-8). These would react very quickly and provide security. It is used to defend your network and carry suspicious activity by using software, like [malware](https://www.google.com/search?q=malware&oq=malware&aqs=chrome.0.69i59j0i433l2j0j0i433l2j0j0i433j0l2.413j0j9&sourceid=chrome&ie=UTF-8), and shut it down.

## There are 5 Generations

- ### `Gen 1 Virus`
- ### `Gen 2 Networks`
- ### `Gen 3 Applications`
- ### `Gen 4 Payload`
- ### `Gen 5 Mega`


 
## Types of Firewalls

### **1. Packet filtering**
### **2. Proxy service**
 ### **3. stateful inspection**
 ### **4. Next-Generation Firewall(NGFW)**
 ### **5. Software filtering**
 ### **6. Hardware service**
 ### **7. cloud filtering**

  


## **1. Packet filtering**

A small amount of data is analyzed and distributed according to the filter’s standards. Generation Firewalls inspect packets at the application level of the **[TCP/IP stack](https://www.google.com/search?q=tcp%2Fip+stack+layers&oq=TCP%2FIP&aqs=chrome.1.69i57j69i59j0l4j0i131i433j69i58.1896j0j9&sourceid=chrome&ie=UTF-8)**. In packet filtering, an IP address of both the sender and receiver will be maintained and along with the port numbers. This is how it protects our computer from a hacker. 
### **Syntax in Packet filter:**
```    
   #include "sys/io-pkt.h"
#include "nw_datastruct.h"

int mod_entry( void *dll_hdl, struct _iopkt_self *iopkt,
               char *options)
{

}
```
In the above syntax we used `include` for adding the required files. `int` for the declaration of variables. `mod_entry` as method name.

## **2. Proxy service**
In Proxy services, the Ip address of the end-user will be hidden. The Network security system protects while filtering messages at the application layer. Similarly, a [virtual private network (VPN)](https://www.google.com/search?q=virtual+private+network&oq=virtual+private+network&aqs=chrome..69i57j0l9.476j0j9&sourceid=chrome&ie=UTF-8) extends a private network across a public network within a tunnel that is often encrypted where the contents of the packets are protected while traversing the Internet.


## **3. Stateful inspection**
[Dynamic packet filtering](https://www.google.com/search?q=Dynamic+packet+filtering&oq=Dynamic+packet+filtering&aqs=chrome..69i57.453j0j9&sourceid=chrome&ie=UTF-8) that monitors active connections to determine which network packets to allow through the Firewall. Network maintaining the access and conversation list to maintain the stateful inspection. Thus the security will be flexible.\
> **Run the user-space minifirewall program after compiling it. Follow the steps >given below to test it.**
```
  gcc -o -Wall minifirewall minifirewall.c
    sudo ./minifirewall --in --proto ALL --action BLOCK
    ping www.google.com
```

The above code pings to `Google.com`.

## **4. Next-Generation Firewall (NGFW)**
[Deep packet inspection](https://www.google.com/search?q=Deep+packet+inspection+Firewall&oq=Deep+packet+inspection+Firewall&aqs=chrome..69i57.1012j0j9&sourceid=chrome&ie=UTF-8) Firewall with the application-level inspection. The downside is that unwanted applications or malware can pass over allowed ports, e.g. outbound Internet traffic over web protocols HTTP and HTTPS, port 80 and 443 respectively.

## **5.Software filtering**
A Firewall that is present in your computer is the Software firewall that is installed on a PC. As it is stored in a pc it is called a Host firewall. It will consume computer resources like CPU, RAM, etc. used to protect only one computer which has a software firewall installed in it.





## **6.Hardware service**

The firewall that is present in between two networks is called Hardware Firewall. Your home router itself acts as a Hardware firewall. It is a separate piece that has its software running on it. It is also called an Appliance Firewall. It is having its software and doesn't use CPU, RAM, etc. It can protect all the computers present in the network.






## **7.cloud filtering**

The Cloud is like a bank scattered resources. It blocks the cyberattacks directed at these cloud assets. It is hosted in the cloud. It acts as a physical security guard with a global 24/7 security center that has centralized staff.



## Why Do We Need Firewalls?
**Firewalls**, especially Next-Generation Firewalls, focus on blocking malware and application-layer attacks. Firewalls, especially [Next-Generation Firewalls](https://www.google.com/search?q=Next+Generation+Firewall&oq=Next+Generation+Firewall&aqs=chrome..69i57j69i59.369j0j9&sourceid=chrome&ie=UTF-8), focus on blocking malware and application-layer attacks. Task regulate the flow of traffic bypassing the secure data. Without a firewall, hackers can hack that is why you should never shut your firewall. Also, we need to maintain the malware for better performance.


Nowadays all the types of windows starting from Windows XP sp2 to windows 10, all are having an inbuilt software **firewall**. This is used to regulate the flow of traffic and permits secure data. In the absence of a **firewall**, hackers can hack easily. It is better, download the [Next-Generation Firewall (NGFW)](https://www.google.com/search?q=Next+Generation+Firewall&oq=Next+Generation+Firewall&aqs=chrome..69i57j69i59.369j0j9&sourceid=chrome&ie=UTF-8) Buyer’s Guide today. Today’s **firewalls**, including Next-Generation **Firewalls** and Network **Firewalls**, support a wide variety of functions and capabilities with built-in features, including:
* **[*Network Threat Prevention*](https://www.google.com/search?q=Network+Threat+Prevention&oq=Network+Threat+Prevention&aqs=chrome..69i57.839j0j9&sourceid=chrome&ie=UTF-8)**
* **[*Application and Identity-Based Control*](https://www.google.com/search?q=application+and+identity-based+control&oq=Application+and+Identity-Based+Control&aqs=chrome.0.0.1063j0j9&sourceid=chrome&ie=UTF-8)**
* **[*Hybrid Cloud Support*](https://www.google.com/search?q=hybrid+cloud+support&oq=Hybrid+Cloud+Support&aqs=chrome.0.0.509j0j9&sourceid=chrome&ie=UTF-8)**
* **[*Scalable Performance*](https://www.google.com/search?q=scale+performance&oq=scale+perfo&aqs=chrome.0.0l2j69i57j0i22i30l7.7096j1j9&sourceid=chrome&ie=UTF-8)**

## Conclusion
As the cybersecurity landscape continues to evolve and attacks become more sophisticated, Next-Generation Firewalls will continue to be an essential component of any organization’s security solution. Today you might be a billionaire but without a firewall, will lead you to zero. Maintaining proper security that can be done by the firewall is mandatory.
## References

https://www.youtube.com/watch?v=eO6QKDL3p1I&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6

https://www.youtube.com/watch?v=KZc1KaE1OKU&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6&index=2

https://www.youtube.com/watch?v=aUPoA3MSajU&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6&index=3

https://www.youtube.com/watch?v=Xj654WUdDFE&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6&index=4

https://www.checkpoint.com/cyber-hub/network-security/what-is-firewall/#:~:text=A%20Firewall%20is%20a%20network,network%20and%20the%20public%20Internet.

https://github.com/ashishraste/minifirewall#:~:text=minifirewall%20is%20a%20simple%20packet,a%20computer%20in%20a%20network.
 

