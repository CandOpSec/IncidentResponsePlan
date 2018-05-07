# E-lottery
<!-- {% include_relative intro.md %} -->

# Incident response plan in general

## What is a Security Incident?
A security incident in the context of this MSSEI requirement is an event that compromises or has the potential to compromise:
- the operation of covered core systems
- confidentiality or integrity of covered data assets
A security incident may involve any or all of the following:
- a violation of campus computer security policies and standards
- unauthorized computer or data access
- presence of a malicious application, such as a virus
- presence of unexpected/unusual programs
- a denial of service condition against data, network or computer
- misuse of service, systems or information
- physical or logical damage to systems
- computer theft

## Components of an Incident Response Plan
Should contain the following:
- Names, contact information and responsibilities of the local incident response team
- System details, or reference to the location of such information
- Procedures for reporting and handling a suspected incident
- Report security incident to ISP and include the intake report
- Respond to the security incident in a timely fashion based on the incident prioritization guideline

## Security Incident Prioritization
To help prioritize the timing and resources needed to deploy corrective action, resource proprietors and resource custodians must assess the impact of a security incident based on the following factors:
- How the incident will impact existing functionality of the affected systems
- Whether the incident breaches the confidentiality or integrity of covered data (Protection Level 2) or non-covered data
- How much of the user population is affected by the security incident
- What’s the reputational/financial impact to campus


# Plan for our large scale e-lottery system

## Mission
Our company's mission is to allow every user of our platform to have equal chances of winning the e-lottery.
Our incident response plan is about protecting availability and preventing random numbers prediction.

## Strategies and goals
Our strategy to protect availability is through mirroring servers and frequent staff or system parts changes.
Our goal is to sustain profitability from every single e-lottery game and stopping any fraudulent action inside the system.

## Senior management approval
Incidents selected in this document are approved by senior management and are considered crucial for existence of our e-lottery system.

## How the incident response team will communicate with the rest of the organization and with other organizations
In case of large scale e-lottery served via complex networks, we are assuming that every action should be taken automatically in a way that applies to given incident.
Each incident description contains both general view, impact and post-incident steps to follow.

## Metrics for measuring the incident response capability and its effectiveness
Every incident's impact is measured from a point of view of a potential money loss.
We distinguish three types of potential money loss:
- unavailability
- too many winning players
- lack of players

## Roadmap for maturing the incident response capability
After each incident response that has been done in any way, the successful or failed one, management will have to accept next iterations of our forged/improved response plan.

## How the program fits into the overall organization
As our organization is imaginary, we try to ensure the management that given incidents are close to fatal and those incidents are highly probable to occur. We must focus on incidents that may bring huge loss to our company and there is no insurance that may cover the damage.

# Our incident response plan
## Communication
Chain of communication is recommended to follow, but in special cases when time is main factor of defending our system from total failure we encourage to broadcast the messages to all internal entities at once.

### The media - internal and external communication
In case of internal communication of any incident we should follow rules of informing everyone on company's general chat so everyone will know that they have to swap parts of the system that they are responsible for.
In case of external communication with the public - it is prohibited with exception for Public Relations staff members who are in charge of reporting. Company may lose liability and we may lose players that are our only income.

### The law enforcement
We consider contacting with law enforcements high probability of compromising that our system has been attacked and losing liability.

### Incident reporting organizations
Our company has primary and secondary Point Of Contact to report to organizations that our company have to stay in touch in case of any incident that we are obliged to inform about.

### Other outside parties
We consider any leakage of any incident as a damage to our profits, but in case of our suppliers and service providers we stay in confidential contact to support each other.

##### Internet Service Providers
Our system's architecture is distributed across the world so we have multiple ISPs.
Our company have designated people to constantly stay in contact with theirs people in case of any problems. We consider high network loads or denials of service.

##### Software vendors
Servers and end-point machines software vendors are contacted only in case of a malfunction or vulnerability.

##### Other incident response teams
As a world wide distributed system we have few incident response teams on each continent to prevent low availability and hold high focus on our systems security.
Every team reports to other teams about any suspicious action in our system and is constantly training in search for new potential attacks.

##### Affected external parties
In our case affection may touch salesmen with end-points machines to sell tickets.
We contact them only by our servers - disconnecting devices in case of compromisation or detection of any tamper on the devices.

## Incident response team structure
### Brief description
Our teams are distributed world wide, at least one team per continent. Every team reports to other teams through secure channels.
We have one coordinating team which is one of the distributed teams. The coordinating team is a team which's region has the highest risk of being attacked and actually has the biggest number of potentially available players.

### Structures
Each of below structures should contain exact personal details for easier contact.
- Management (John Doe, mail@mail.net, phone number, ...)
- Public Relations
- Human Resources
- Incident Response Teams
- Internal Audit Teams
- External Audit Teams
- Core Development Team
- Core Architecture Team
- Core Engineering Team
- Accountancy department
- Advertisement department
- SOC-SIEM department


## Dependencies within organization
- Managements stands above all of the entities from our e-lottery system structures and all of them respond to their commands and suffice their needs, as it's success is entire system's success.
    - Business Continuity Planning Management
    - Legal Department Management
    - Information Assurance Management
    - Physical Security and Facilities Management
- Public Relations takes care of good visage of the company and is reporting only to FM.
- Human Resources takes care of hiring people and is responsible for all the resources they hire.
- Incident Response Team is responsible for splitting tasks between all the structures in case of an incident.
- Internal Audit Teams are responsible for checking for vulnerabilities of entire system that is accessible by company members (staff) and proofing the system from insider attacks.
- External Audit Teams are responsible for checking and securing the system from outsider attacks and proving system is secure in a way that public may accept as legitimate.
- Core Architecture Team is responsible for planning how the system should work and what parts are next in queue for securing. This team calculates real costs of the system to upgrade.
- Core Development Team is responsible for developing features and system's parts for exchange or updates.
- Core Engineering Team is responsible for designing and building (if possible) devices for external usage. Those devices are used by salesmen remotely to sell e-lottery tickets.
- Accountancy department are responsible on keeping track of entrance and exit of money, are required on estimating money loss in case of critical incidents.
- Advertisement department, they are subset of the public relation department. They are needed to recreate trust towards the company after a critical attack.
- SOC-SIEM department, composed of security engineers and analysts, they work on monitoring the system and finding vulnerabilities to patch.


## Incident response team services
### Intrusion Detection
Incident detection is possible by means of three main team types and outside sources such as outsourced informators or anonymous sources.
Three main team types:

- Engineering Teams
    - Systems
    - Networks
    - Hardwares
    - Architectures
- Development Teams
    - Kernels
    - Features
    - Softwares
    - Extensions
- Internal and External Audit Teams

### Advisory Distribution
Our company outsources most of the advisories, such as legal department advisors.

### Education and Awareness
Our company extensive researches on subjects of information security and cyber security are sufficient to stay up-to-date with bleeding edge technologies and vulnerabilities. We use that knowledge to spread between our structures durin comprehensive lectures and technical workshops for our Engineers, Developers, Audit Teams and ordinary employees.

### Information Sharing
Sharing of the information inside of our company is possible by any secure channel. We are global e-lottery system and it is feasible to use secured network connections to communicate and share information about current system's state.

### Impact criteria
As a company we value profit and system traffic over stagnation. Our system earns from number of users playing games and lack of system failures or unexpected incidents which require us to interact and spend resources. We distinguish three main types of criteria for classification of the incidents, which may require slight interpretation depending on context of an incident:
- critical - stake of our system is endangered and there is huge probability of losing more money or public respect than we can gather in a month of no-disturbance.
- average/moderate - the probability of losing money is enough to start considering change of main components in advance as an investment
- low/non-negligible - the probability of money loss is too small to recover from single incident with high priority. Instead we recognise that types of incidents better for insurance companies to pay off or our teams to consider next occurences of that type of incident defensible with prevention stage (small system changes).
- negligible - incidents not worth applying any resources to respond or build prevention steps for further usage.

## Quality steps
### Establish a formal incident response capability
### Create an incident response policy
### Develop an incident response plan based on the incident response policy
### Develop incident response procedures
### Establish policies and procedures regarding incident-related information sharing
### Provide pertinent information on incidents to the appropriate organization
### Consider the relevant factors when selecting an incident response team model
### Select people with appropriate skills for the incident response team
### Identify other groups within the organization that may need to participate in incident handling
### Determine which services the team should offer

{% include_relative attacks.md %}
