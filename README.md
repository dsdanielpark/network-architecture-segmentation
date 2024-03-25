

# Please go to original repository, https://github.com/sergiomarotco/Network-segmentation-cheat-sheet
[Network-segmentation-cheat-sheet](https://github.com/sergiomarotco/Network-segmentation-cheat-sheet) Contributed by [@sergiomarotco](https://github.com/sergiomarotco) and [@eltociear](https://github.com/eltociear)





<br><br><br><br><br><br><br><br><br><br>


Do not use this repository, **you must go to** [Network-segmentation-cheat-sheet](https://github.com/sergiomarotco/Network-segmentation-cheat-sheet) and support them.

<br><br><br><br><br><br><br><br><br><br><br><br><br><br>




---

# Network Segmentation Levels

Network segmentation acts as a cornerstone in the architecture of cybersecurity, serving as a proactive measure against unauthorized access and attacks. By dividing a network into distinct segments, organizations can control the flow of traffic, enforce security policies more effectively, and limit the spread of potential threats. Below is a more detailed exploration of the four segmentation levels.

---

## Where can I find diagrams?
Graphic diagrams are available in the [Release page](https://github.com/sergiomarotco/Best-practice-for-network-segmentation/releases)</br>
The schema sources are located in the [repository](https://github.com/sergiomarotco/Best-practice-for-network-segmentation)

## Schematic symbols
Elements used in network diagrams:<br/>
![Schematic symbols](https://github.com/sergiomarotco/Best-practice-for-network-segmentation/blob/main/Schematic%20symbols/Schematic%20symbols.jpg)<br/>
Crossing the border of the rectangle means crossing the firewall.
To further enrich and elaborate on the provided information, let's delve deeper into each level of network segmentation, adding more detailed explanations and clarifications to better understand the significance and implementation nuances of each stage.

## Overview



| **Level** | **Segmentation** | **Advantages** | **Disadvantages** | **Key Notes** |
|-----------|------------------|----------------|-------------------|---------------|
| Level 1 | Basic Segmentation | - First line of defense against intrusions.<br/>- Isolates production from corporate environments. | - Corporate network's inherent vulnerabilities pose risks.<br/>- Potential compromise could lead to broader network access. | - Emphasizes basic protection and isolation.<br/>- Recommends upgrading to higher levels for improved security. |
| Level 2 | Adoption of Basic Security Practices | - More control over network traffic.<br/>- Duplication of essential services enhances resilience.<br/>- Integrates security in software development. | - Increased operational complexity and costs. | - Suggests a granular control and resilience approach.<br/>- Advocates for security integration in development processes. |
| Level 3 | High Adoption of Security Practices | - Comprehensive security ecosystem.<br/>- Cybersecurity becomes a part of company governance. | - High costs and need for specialized personnel. | - Focuses on establishing a robust security framework.<br/>- Stresses on strategic security governance. |
| Level 4 | Advanced Deployment of Security Practices at Scale | - Ultimate security with independent operation of segments.<br/>- Effectiveness of air-gapping sensitive environments. | - Requirement for dual workstations increases physical space and management complexity. | - Represents the pinnacle of security practices.<br/>- Dual workstations as a pivotal security measure. |


## Level 1: Basic Segmentation

![Level 1 Segmentation](https://github.com/sergiomarotco/Best-practice-for-network-segmentation/releases/download/4.1.1/Network.segmentation.Level.1.jpg)

### Advantages

- **Foundation for Security**: Establishes the groundwork for more advanced security measures by initially separating critical and non-critical network segments.
- **Environmental Isolation**: Clearly demarcates the boundary between production and corporate environments, thus minimizing the attack surface accessible to potential intruders.

### Disadvantages

- **Potential Weaknesses**: The presence of default network access rights, including administrative privileges from within the corporate segment to the production environment, can be exploited, highlighting the need for more stringent controls.

### Enhanced Protection Strategy

- **Layered Security Measures**: Emphasizes the importance of deploying a layered security approach, combining information protection tools with continuous monitoring and rapid incident response capabilities.
- **Progression to Higher Segmentation**: Acts as a stepping stone towards adopting more comprehensive segmentation strategies, underscoring the necessity for evolving network defenses in response to advanced threats.

---

## Level 2: Adoption of Basic Security Practices

![Level 2 Segmentation](https://github.com/sergiomarotco/Best-practice-for-network-segmentation/releases/download/4.1.1/Network.segmentation.Level.2.jpg)

### Advantages

- **Enhanced Segmentation Benefits**: Introduces additional layers of separation within the corporate network, further securing sensitive data and operations.
- **Infrastructure Duplication**: Ensures business continuity and resilience by duplicating key infrastructure components, thereby safeguarding against disruptions in the supporting systems.

### Disadvantages

- **Resource Intensive**: The added complexity and the requirement for duplicate infrastructure significantly increase operational costs and maintenance demands, challenging smaller organizations.

---

## Level 3: High Adoption of Security Practices

![Level 3 Segmentation](https://github.com/sergiomarotco/network-segmentation-cheet-sheet/releases/download/4.1.1/Network.segmentation.Level.3.jpg)

### Advantages

- **Comprehensive Security Posture**: Marks a strategic pivot towards a holistic security stance, integrating advanced tools and practices such as SIEM systems, DLP strategies, and proactive phishing defenses.
- **Organizational Commitment**: Reflects a mature understanding of cybersecurity's critical role, supported by a dedicated and sufficiently staffed information security unit.

### Disadvantages

- **Investment Implications**: The significant financial and human resource investments required for this level of security can be prohibitive, especially for entities with limited budgets.

---

## Level 4: Advanced Deployment of Security Practices at Scale

![Level 4 Segmentation](https://raw.githubusercontent.com/sergiomarotco/Network-segmentation-cheat-sheet/main/Network%20segmentation%20Level%204.jpg)

### Advantages

- **Air-Gap Strategy**: Embraces the pinnacle of isolation techniques, effectively neutralizing the threat of external attacks through strict access controls and physical separation.
- **Targeted Security Enhancements**: Focuses on fortifying the production environment with specialized security services and training, including sophisticated access management and compliance monitoring.

### Unique Challenge

- **Dual Workstation Deployment**: While significantly enhancing security, the requirement for multiple workstations introduces logistical and space considerations.
