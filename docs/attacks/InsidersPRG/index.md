# Insiders attack - Tampering with PRG

### Formal incident response capability
Let us inspect the situation when one tampers with the device responsible for generating numbers for lottery games. In this situation we have three potential possibilities:
1. One can make it predictable only for him/her.
2. One can make it predictable for public.
3. One can make it predictable for personal time intervals.

As it comes to difficulty with assuming attacker's greediness in this case in some situations the reputation and reliability of the company is at risk of falling down, generating loss of interested users and later following to closing offices in different regions, bankruptcy.
### Incident Response Policy
In this case the statistical and probabilistic tests are being made. The test is to calculate number of people winning single play and winnings play in a row. In such situation the monitoring of effectiveness of PRG is made and in situations when the results are different than predicted the possibility of faulty PRG comes to be considered. In case of possible tampering the new PRG machine is generated and substituion process is performed. 
### Incident Response Plan
Given steps are taken to solve the problem:
1. Acrhitecture of new PRG is formed.
2. Development steps are taken to create new device.
3. Statistical tests are made to collect needed data. 
4. Replacing process is performed.
5. Gradually system's activity is restored.
6. Report after the incident is presented.
7. Security aspect of PRG is improved.

![Simple scheme of the PRG Tampering attack](https://raw.githubusercontent.com/CandOpSec/IncidentResponsePlan/master/docs/attacks/InsidersPRG/assets/InsidersPRG-Scheme.png)

### Policies and procedures regarding incident-related information sharing
Public Relation team is involved in the task. Their objective is to contact with the manufacturer of the PRG and form a dialogue channel to solve possible problems in the future. Chosen informations are also presented to players so that they are aware of possible fraudations that may happen during the lottery game.
### Providing information to the appropriate organization
+ In case of contacting the manufacturer of the device the knowledge of it as well as specifications are needed to be able to detect potential changes. If there exists an occurence of manufacturer's part in the attack thus the third party is chosen in secret and is also involved in the dialogue.
+ In case of communcating with the public the problem is presented. Awareness is spread so that users can avoid harm. After resolving the issue users are presented with the report of actions taken to stop the problem.

### Selecting response team model
1. Management
2. Core Architecture Team
3. Core Engineering Team
4. Core Development Team
5. Public Relation
6. External Audit Teams

If information of faulty PRG is received it shall be handled to the management. The team (1) performs a meeting with leaders of groups to introduce them to the problem and develop a solution minimizing potential impact. Teams (2), (3), (4) are responsible for replacing faulty PRG with a new one. Needed statistical tests are performed to assure that new device suffies given requirements. Team (5) is involved when it comes to communication with public and manufacturer of the device. In case of manufacturer's possible part in the attack team (6) is involved in the action plan. In the end a report for company branches is performed.
### Selecting people with skills for the incident response team
Each group posses a leader, who then chooses people that will be involved. Teams prepare the action plan together, so each member is aware of steps that are being taken. Leaders cooperate together to make smooth execution of the plan, avoiding taking backward steps as much as possible. Leader position is being assigned by management. 
### Identifying other groups for participating in incident handling
If for possibility of employee part in the attack three teams are involved:
1. Management
2. Human Resources
3. Internal Audit Teams

### Determining services the team should offer
An investigation process is being performed. During execution the business devices, data, informations will be checked to determine potential attacker. The investigation process does not break any of laws of work of employess as well as contracts signed by the both sides.

### Prevention steps
There are not many solutions that make it possible to fully prevent given attack. As well as recovery process is based on creating new device. To answer the question the answer is making small changes in PRG at random time moments can make it possible to disrupt and destroy attacker's plan.
