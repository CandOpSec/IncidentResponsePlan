# DDOS
## Description of an incident (What is the attack?)
Distributed Denial of Service - blocks any legitimate traffic to our servers.
## Analysis (How big is the impact?)
Impact of this attack can be fatal if the malevolent users can block multiple servers at the same time or negligible if DDOSes only part of them.
## Detection (How do you detect?)
To detect the attack we monitor traffic’s IP origins and we delegate detection to third parties (CloudFlare).
IPS, IDS
## How to recover (How to make the system usable/safe again?)
In case of fatal DDOS attack (multiple servers down) we deploy new instances of the servers in another regions of the world with shrinking the malicious traffic bandwidth.
## What is the cost of recovery?
The cost of recovery is a time of workhours of our Development Teams and rent cost of new servers.
## How to stop the attack?
To stop the attack we migrate main server to another region of the world to make the attacker’s traffic go through smaller bandwidths networks to reach.
## How to return to the previous status of the machine?
The new region for the server is going to stay as the main one until some requirements make us change the decision.
How to prevent from Future same/similar incidents
The DDOS attacks are hard to avoid or prevent, but we have developed a system to quickly respond to those attacks.
## How to avoid similar events in the future?
To avoid similar events in the future we stay as long as the new bandwidth allows us to carry current amount of users, so the attacker is not able to deploy new DDOS from the same origins.
## What was the cost of the attack?
The cost of the attack is the time to deploy new servers and time to broadcast new IP/Domains for all main DNS servers.
## What is the cost of prevention?
The cost of prevention is amount of lost users due to website load time from remote regions of the world.
Cost/Feasibility difference between Recovery and Prevention
## Conclusion (Which is more worth it?)
It is more feasible to Recover from the incident than to Prevent the DDOS attack, because of really important for the user Website Load Time.
