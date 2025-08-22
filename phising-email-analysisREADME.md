# Incident Response Simulation 🔐

## Background
In this scenario, I walked through how I would handle a situation where a workstation started sending out suspicious traffic. My goal was to think like a security analyst — spot the problem, dig into it, and figure out what actions to take.  

## Tools I Used
- Linux command line (to check the system and logs)  
- Wireshark (to capture and analyze network traffic)  
- Splunk (to search and review log data)  

## What I Did
1. First, I imagined isolating the machine from the network to stop the suspicious traffic from spreading or causing more harm.  
2. Next, I went through the logs to look for unusual IP addresses and connections that stood out.  
3. I then used Wireshark to dig deeper into the network traffic and see exactly what kind of data was being sent out.  
4. Finally, I wrote down my findings and tried to piece together what might have caused the issue.  

## What I Found
- The machine was sending traffic out to a suspicious external IP address.  
- The behavior looked like there could have been some kind of malware infection.  

## What I Learned
This exercise gave me good practice in thinking through an incident step by step. It reminded me how important it is to **act quickly to contain a threat** and also how powerful tools like logs and packet captures can be when you need to figure out what’s really going on. Most of all, it showed me that good documentation and a clear process make incident response a lot more manageable.
