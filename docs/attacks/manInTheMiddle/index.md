# Man in the middle attack: 
MITM between any of our servers and Salesmen endpoints. This attack is based on tampering with the encrypted data sent over the network. We are not able to predict how the attacker can tamper with it.
## Delineation of the incident:
### Analysis (How big is the impact?)
Impact of this attack can be devastating for the legitimate users/buyers of the tickets at given Salesmen point. This way it can bring our business down due to loss of reliability.
### Detection (How do you detect?)
We can detect the attack by sending remote group of guards to gather data collected by Salesmen endpoint devices for further comparison of data on our servers.
### How to recover (How to make the system usable/safe again?)
First step to recover from such attack we have to buy an insurance protocols.
Second step is to pay the prizes to our users/ buyers of the tickets if they have something to prove their rights to the prize.
Third step is to change the connection which was the most likely affected.
### What is the cost of recovery?
The cost of recovery is cost of the insurances and loss of reliability.
### How to stop the attack?
To stop the attack we change as many parts of the inter-network as possible to minimize chances of the attacker’s exploit to succeed.
### How to return to the previous status of the machine?
The reinforcement of the network connections are irreversible for our business.
### How to prevent from Future same/similar incidents
Reinforcing the network connections are at the same time prevention from future similar attacks.
### What was the cost of the attack?
The cost of the attack may vary on number of users affected.
### What is the cost of prevention?
The cost of the prevention is included in cost of the recovery.
### Cost/Feasibility difference between Recovery and Prevention (Which is more worth it?)
As we are not able to predict future vectors of attack we assume that recovery of incidents that occurred is more feasible for us.

## Quality steps
### Formal incident response capability
That type of incidents could cause non fatal direct loss, but indirect impact could damage our reputation and become deciding factor of our incomes. Response to that type of incident requires our teams to understand connections between end-users and our servers. Detection of such incident without knowing where malevolent tricks were applied is unserviceable for us. We have to locate exact vector of attack between any nodes in the connection the attack was mounted.

### Incident response policy
The incident response policy in case of man in the middle type of attacks forces every team selected by Incident Response Team to act accordingly to the plan.

### Incident response plan based on the incident response policy
The plan to respond to Man in the Middle attacks is to stop malicious user of taking advantage of servers he has successfuly mounted the attack and inform affected user that his account is under investigation. In case of irreversible changes to the affected user's account - refund any active game he has started during the attack.

### Incident response procedures
1. Any intelligence about MITM attack should be reported to any Incident Response Team.
2. Incident Response Team evaluates impact of the attack:
    - a) the attack successfuly prevents users from winning any game
    - b) the attack hijacks all the games users have won
    - c) the attack randomly dismisses any game (lost or won)
3. Incident Response Team informs other remote Incident Response Teams
4. Incident Response Team delegates the job to locate vector of attack to External Audit Teams
5. External Audit Teams reports back to Incident Response Team
6. Incident Response Teams orders a fixture to the unit responsible for patching vulnerability:
    - a) Engineering Team in case of hardware vulnerability
    - b) Development Team in case of software malfunction
7. Selected Teams (Engineering or Development) report back to Incident Response with Estimated Remaining Time to fix and costs
8. Incident Response Team informs Business Continuity Planning Management about expenses
9. Business Continuity Planning Management decides if teams should fix immediatelly or replace parts for temporary patching and informs Incident Response Team.
10. Incident Response Team delegates the work that has to be done.
11. Selected Teams work on solutions to stop the attack and reverse losses if possible.
12. Selected Teams inform Incident Response Team about progress and point out when the attack is safely removed from the games.
13. Incident Response Teams are informing Public Relations about the end of attack.
14. Selected Teams prepare extensive documentations how to prevent or immediatelly stop future MITM type attacks with the same vector of attacks.

![Simple scheme of the MITM ATTACK](https://raw.githubusercontent.com/CandOpSec/IncidentResponsePlan/master/docs/attacks/manInTheMiddle/assets/MITM-SCHEME.png)

### Policies and procedures regarding incident-related information sharing
The company partners should be informed about the incident's occurence only if the incident could make loss to their politics or budgets. In case of making bigger losses to our company than we value our partners we are not informing any third parties.
We share status of the incident to every internal team involved directly to preventing or responding to the attack.

### Provision of pertinent information on incidents to the appropriate organization
Information about the incident should be provided only to organizations that bound us with law which may cause financial problems.

### Determine which services the team should offer
- Network Analysts:
    * to determine vector of attack from small amount of network requests
    * to calculate amount of users capable of being affected
- Network Engineers:
    * to establish alternate paths avoiding current vector of attack
- Incident Response Teams:
    * to delegate work and evaluate the incident's aspects
- External Audit Units:
    * to find the problem in parts of the system available to the public
    * to find possible solutions for other teams
- Business Continuity Planning Management:
    * to calculate losses and gains
- Public Relations:
    * to share the information about the attack in a way that will not cause losses indirectly


