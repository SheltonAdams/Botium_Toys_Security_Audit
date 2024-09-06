<h1 align="center"><strong> 🔒Botium Toys Security Audit</strong></h1>
<h3 align="center"><strong>This is a fictional security audit based on the fictional company Botium Toys in the Google Cybersecurity Professional Certification. </strong></h3>


---

<h3 align="center"><strong>Scope of The Audit:</strong></h3>

The audit covered key systems like accounting, endpoint detection, firewalls, intrusion detection, and SIEM tools. It evaluated user permissions, controls, and procedures to ensure compliance with PCI DSS and GDPR requirements.

**Goals:**

- Ensure compliance with NIST Cybersecurity Framework.
- Strengthen system controls.
- Implement least privilege for user access.
- Develop policies, procedures, and playbooks to maintain security.
---
**Findings:**

- Lacking disaster recovery plans and access controls.
- Policies for encryption, password management, and system monitoring need to be developed.
- Legacy systems require manual monitoring.
- Physical security measures like CCTV, locks, and fire prevention systems are needed.
- The following controls should be implemented when possible:
- Time-controlled safe
- Adequate lighting
- Locking cabinets
- Signage indicating alarm service provider
---
**Recommendations:**

Botium Toys is facing significant risks due to inadequate management of its assets and a lack of necessary controls and compliance practices. The company's current risk score of 8 out of 10 indicates a high level of vulnerability, primarily because of the absence of strong security measures and adherence to regulatory standards. To mitigate these risks, Botium Toys needs to prioritize the identification and classification of its assets, ensuring that the impact of losing any critical asset is fully understood and managed.

One of the most pressing issues is the company's failure to implement encryption for customer credit card information. This lack of encryption exposes sensitive data to potential breaches, which could lead to severe financial and reputational damage. Additionally, the absence of access controls, such as least privilege and separation of duties, further increases the risk of unauthorized access to sensitive information, including cardholder data and customers' personally identifiable information (PII).

Another critical area of concern is Botium Toys' lack of disaster recovery plans and data backups. Without these, the company is ill-prepared to handle data loss or system failures, which could disrupt business operations and lead to significant financial losses. Implementing regular backups and a robust disaster recovery plan is essential to ensure business continuity in the event of a crisis.

The company also needs to address its outdated password policies and the lack of a centralized password management system. Current password requirements are minimal and do not meet industry standards, leaving systems vulnerable to unauthorized access. By enforcing stronger password policies and implementing a centralized management system, Botium Toys can significantly reduce the risk of password-related security breaches.

In conclusion, Botium Toys must take immediate action to improve its security posture by addressing the gaps identified in the risk assessment. This includes implementing encryption, establishing access controls, creating disaster recovery plans, and updating password policies. By doing so, the company can reduce its risk score and better protect its assets, customer data, and overall business operations.

---
<h3 align="center"><strong> WALKTHROUGH </strong></h3>

**Current Assets Managed by IT:**

- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Vendor access management
- Data center hosting services
- Data retention and storage
- Badge readers
- Legacy system maintenance: end-of-life systems that require human monitoring

**Risks:**

- Assets are being inadequately managed.
- There are no proper controls in place.
- May not be compliant with U.S. international regulations and standards.
- Risk score is 8.
- Medium potential impact from asset loss (IT dept does not know which assets would be lost.
- High likelihood of a lost asset or fines from governing bodies (no necessary controls in place; not adhering to required regulations and standards related to keeping customer data private.)

**Internal IT Audit Goals:**

- To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)
- Establish a better process for their systems to ensure they are compliant
- Fortify system controls
- Implement the concept of least permissions when it comes to user credential management
- Establish their policies and procedures, which includes their playbooks
- Ensure they are meeting compliance requirements
---
<h3 align="center"><strong>Control categories</strong></h3>

**The Three Main Categories:**

- Administrative/Managerial controls: policies and procedures (how an organization manages data; employee responsibilities)
  
![image](https://github.com/user-attachments/assets/f847957a-fc9e-49e2-8af8-1c1d8008c008)

- **Technical Controls:** Firewalls, Intrusion Detection Systems (IDS), Instrustion Prevention Systems (IPS), Audio Visual (AV), Encryption

![image](https://github.com/user-attachments/assets/71402941-05dd-4a36-8be6-4c289afff202)

- **Physical controls:** door locks, cabinet locks, surveillance cameras, badge readers

![image](https://github.com/user-attachments/assets/ae4322d3-b471-4383-9c75-8c2e9e7ea599)

**The Five Security Control Types:**
- Preventative: prevent an incident from occurring
- Corrective: restore an asset after an incident
- Detective: whether an incident has occurred or is in progress
- Deterrent: discourage attacks
- Compensating: fortify the security of an asset
  
---
<h3 align="center"><strong>Controls Assessment</strong></h3>

![image](https://github.com/user-attachments/assets/9df6f383-0eca-4d26-a356-9b5211d69dbd)

![image](https://github.com/user-attachments/assets/5faa1758-d34e-4f96-b41d-c12c802cf7cd)

![image](https://github.com/user-attachments/assets/b57bc219-09e6-468a-8ec1-3d661ed837e8)

---
<h3 align="center"><strong>Compliance</strong></h3>

**General Data Protection Regulation (GDPR)**

GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens’ data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen’s data is compromised, they must be informed within 72 hours of the incident.

Why?: Botium Toys conduct business and collect personal information from people worldwide, including the E.U.

**Payment Card Industry Data Security Standard (PCI DSS)**

PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment.

Why?: Botium Toys store, accept, process, and transmit credit card information in person and online.

**System and Organizations Controls (SOC type 1, SOC type 2)**

The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

Why?: Botium Toys needs to establish and enforce appropriate user access for internal and external (third-party vendor) personnel to mitigate risk and ensure data safety.



