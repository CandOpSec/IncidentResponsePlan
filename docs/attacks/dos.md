# DOS
## Description of an incident
Denial of Service - blocks any legitimate traffic to our servers.
### Analysis
Impact of this attack can be critical if the malevolent user can block multiple servers at the same time or negligible if DOSes only part of them.
## Establish a formal incident response capability
The most critical outcome the attack could generate is to stop the possibility to generate the lottery numbers.
Therefore the compensation of the sold ticket, which is a big cost, with after the likely event of loss in trust from our customers to our company, moving the customers to competitors and obliging the company the face a bigger cost in advertisement in a more aggressive advertisement campaign to regain the trust from our customers.
Additional cost is the hardware, this type of attack can cause breaking of server and a general equipment for the network. This will take to company to purchase, set up or worse design new machines which will may lead to additional loss for not having the system at its fully potential.
In case of a missing plan for both a successful and unsuccessful attack we could risk to remain off-line throughout multiple lotteries, making the company face immense money loss.
## Create an incident response policy
The policy is to keep the company going, which means that the most critical mission is to move the jobs executed on the attacked network or machines to external(intercontinental) ones. In such a way we can keep the company activities going while one of the subsidiary is under attack.
## Develop an incident response plan based on the incident response policy
In case of DOS, the most critical mission, is to make possible that the incident response team will move the jobs performed on the attacked machines/network to externals (different continent) backup machines. In this way, the company can still perform its activity while one of the subsidiary gets attacked.
In parallel a team of analyst (externals or internals) can analyze the traffic to understand the origin/pattern of the traffic to understand what to block and limit the impact of the attack onto the system.
Network engineers will redirect part of the traffic directed to the attacked machines to other dummy machine (external and internals) to distribute more evenly the attack and decrease its damage.
## Develop incident response procedures
### Critical
1. Network engineers/analyst detects which part of the network is under attack and the source of it.
2. Is checked what this machine performed and which of the machines performs the job with the higher priority.
    * In parallel is checked if the other subsidiary are also under attack, we prepare, in the one that are not, the machine that will start to perform the jobs that our attacked machines should perform. If all subsidiary are under attack, we contact a third party company that offers the service renting servers to prepare servers for us, at least of the quantity necessary to perform the most critical jobs.
3. In order of critical relevance we move the jobs to the external servers
4. Once the most critical jobs are moved the priority moves to restore a previous healthy status of the system.
5. Analyst must understand the source of the attack to know what traffic to block and check if during the DOS attack some additional attack was performed hidden by the DOS. If so, report it and follow the policy for that additional attack.
6. The traffic can be decreased by increasing the standards of acceptance by the IPS and firewall, so to filter more traffic.
6. Once the traffic is blocked and the compromised machines and the one dependent to them are checked we can move back our traffic to its original source.
## Establish policies and procedures regarding incident-related information sharing
1. First of all it is needed to inform all subsidiary that an attack is going on and that it could spread.
2. In case that the engineers will not manage to move the jobs to external servers on time and the company will not manage to perform its activity then the customers must be informed the compromised activity will not be available. In that case the accountant department must prepare a cost perspective for the refund of the sold tickets.
## Provide pertinent information on incidents to the appropriate organization
In case the attack was performed due to some new bug in the system. Then, as soon as the exploit will be fixed on our machines, the security engineers will prepare a report and publish the used exploit.
Insurance companies with which we have a contract must be informed in detail for the attack.
## Consider the relevant factors when selecting an incident response team model
1. What is the most efficient way to ask
## Select people with appropriate skills for the incident response team
The incident response team will be responsible to orchestrate the above and below explained policies. Therefore they will be people with excellent communication skill, capable to take fast decision and moreover responsibility for it. These people will be the main responsible in both case of failure and success the below mentioned departments have to respond directly to them in case of attack.
The team must monitor that all the involved departments follow the described policy. After the recovery from the attack they must make a report about what/why has happened and how to prevent it and if it can happen again and if needed they have to update this policy.
## Identify other groups within the organization that may need to participate in incident handling
In case that we cannot recover on time from the attack to perform our usual activities, then the public relation department must prepare the best way to inform the customers that the compromised activities will not be available until the time estimated by the engineers working on it will be reached. In parallel also the accountants department must work on understanding the possible money loss and how to refund the unhappy customers.
## Determine which services the team should offer
- Analyst:
  * understand the source/pattern of the attack, so to block that type of traffic
  * check if other attacks or suspicious activity are happening hidden under the chaos of the DOS
- Network engineers:
  * try to distributed the attack as evenly as possible without compromising the other machines
  * estimate how much time to recover from the attack is needed and inform PR department about it
  * if needed move the compromised jobs to external servers
- Server engineers
  * check if any hardware got compromised during the attack
- Accountant:
  * estimate possible money loss
  * plan to refund the money without ending in negative
- Advertisement department:
  * prepare campaign to recreate trust into the company
- Public relation:
  * Inform the investors and customers about the attack
## Attack prevention
* Having updated routers IPS, IDS and firewall with the latest info about traffic to block, like famous IP used in botnets or DOS in other systems
* Analyst have to monitor the system and in case of suspicious activities, inform the incident response team so that they can prevent the attack before it is too late, or at least reduce its impact.
