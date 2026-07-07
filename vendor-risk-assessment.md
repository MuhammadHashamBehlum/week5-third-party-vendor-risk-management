
Summer Training Program 2026

Third-Party & Vendor Risk Management — Assessing the Supply Chain

Prepared By:
Mohammad Hesham Wazir Ali Behlum
Bachelor of Science in Cybersecurity
Rochester Institute of Technology (RIT) Dubai
Final-Year Student

Submission Date: 07 July 2026

Introduction
As organizations continue to adapt to cloud computing and outsourced IT services, as well as digital business platforms, they increasingly tend to rely on third-party vendors to be able to support daily operations. While these partnerships do improve efficiency and reduce operational costs, they are also able to introduce additional cybersecurity risks that extend beyond the organization's direct control. A single weakness in a vendor's security practices can expose sensitive information, along with interrupting the business operations, or even lead to regulatory and financial consequences.

For EduTrack Learning Solutions, which to reiterate, is a fictional mid-sized educational technology company that used throughout this internship, managing the third-party risk is an important part of maintaining a strong security posture. The organization depends on several external service providers to be able to host applications and process payments, as well as support communication, and even manage the technical infrastructure. Since these vendors have different levels of access to the company systems and data, each of the relationships must be evaluated before onboarding, as well as monitored throughout the partnership.

This report is able to extend the Governance, Risk, and Compliance (GRC) work that was completed during previous weeks by focusing on the supply chain security, along with the  vendor risk management. It is able to identify the organization's primary third-party vendors, as well as evaluates the level of risk associated with each one, and recommends appropriate security controls, along with developing a vendor security questionnaire that can be used during the onboarding process. The assessment is able to align with the ISO/IEC 27001:2022 supplier relationship controls and is able to demonstrate how vendor governance contributes to a stronger overall security program.

Why Third-Party and Supply Chain Risk Matters
Many organizations invest significant resources in protecting their own networks, but the attackers often target suppliers, as well as service providers instead because they can provide an indirect path into multiple organizations. Modern cyber incidents have shown that weaknesses within a trusted vendor can tend to affect thousands of customers at the same time. This makes third-party risk management one of the most important responsibilities within Governance, Risk, and Compliance.

Several well-known incidents are able to demonstrate the impact of supply chain attacks. The SolarWinds compromise had affected thousands of organizations after the attackers had inserted malicious code into trusted software updates. Similarly, the MOVEit Transfer vulnerability had exposed sensitive information across numerous organizations because many businesses relied on the same file transfer platform. These examples are able to highlight that an organization's security is closely connected to the security practices of its vendors.

For EduTrack Learning Solutions, the third-party vendors are able to provide essential services including cloud infrastructure, payment processing, email communication, and even outsourced IT support. These providers may be able to process confidential student information, along with employee records and payment details, or even business documents. If one of the vendors experiences a security breach, the organization could face data loss and operational disruption, along with reputational damage, regulatory penalties, and even reduced customer trust.

Effective vendor risk management therefore tends to focus on understanding the level of risk before establishing a business relationship, which is able to ensure that the appropriate contractual security requirements are in place, along with continuously monitoring the vendor performance, and even securely ending the relationship when services are no longer required.

Vendor Risk Management Lifecycle
Vendor risk management is an ongoing process rather than a one-time assessment. Throughout the vendor relationship, organizations should continuously evaluate whether suppliers continue to meet security expectations.
1. Vendor Onboarding and Due Diligence
Before selecting a vendor, the organization tends to perform a due diligence to be able to  understand the supplier's security maturity. This includes reviewing the certifications such as ISO/IEC 27001, along with evaluating the previous audit reports and completing security questionnaires such as the Standardized Information Gathering (SIG) Questionnaire or the Consensus Assessments Initiative Questionnaire (CAIQ), as well as reviewing privacy practices, and even assessing the compliance with relevant regulations.

The goal is to be able to ensure that the vendor can adequately protect organizational information before any sensitive data is shared.

2. Vendor Risk Assessment
After onboarding, the organization evaluates the vendor based on several factors, including:
Type of services provided
Sensitivity of accessible information
Level of system access
Potential business impact if compromised
Compliance obligations
History of security incidents
Technical and administrative security controls

Each vendor is assigned a risk rating such as Low, Medium, High, or even Critical, which allows the security teams to be able to prioritize monitoring and remediation efforts.

3. Continuous Observation
Vendor security should not be assessed only once. Continuous monitoring is able to help ensure that the suppliers continue meeting security expectations throughout the contract period.

Monitoring activities may include:
Annual security reviews
Updated compliance certifications
Vulnerability assessments
Security performance reports
Incident notifications
Contract reviews
Audit evidence requests

Regular monitoring helps identify new risks before they are able to significantly affect the business operations.

4. Vendor Offboarding
When a vendor relationship ends, the organizations must ensure that the access to the systems is removed promptly, as well as securely. Offboarding activities tend to include revoking the user accounts, recovering the organizational assets, confirming the secure deletion of organizational data, terminating the remote access, updating the asset inventories, and even documenting contract closure. Proper offboarding is able to reduce the risk of unauthorized access after the services have ended.

ISO/IEC 27001:2022 Supplier Relationship Controls
The assessment follows the supplier relationship controls defined within ISO/IEC 27001:2022 Annex A, particularly controls A.5.19 through A.5.22, which focus on managing risks associated with external suppliers.

Annex A Control
Purpose
Application within EduTrack Learning Solutions
A.5.19 – Information Security in Supplier Relationships
Establish the security requirements before engaging suppliers.
Security clauses are included in contracts, and the vendors undergo security due diligence before onboarding.
A.5.20 – Addressing Information Security Within Supplier Agreements
Ensure the contracts are able to clearly define the security responsibilities and compliance expectations.
Service agreements include confidentiality obligations, incident reporting timelines, encryption requirements, as well as data protection responsibilities.
A.5.21 – Managing Information Security in the ICT Supply Chain
Monitor the technology suppliers throughout the relationship to be able to reduce the supply chain risks.
Annual vendor reviews, security questionnaires, compliance verification, and even risk reassessments are conducted for the critical suppliers.
A.5.22 – Monitoring, Review, and Change Management of Supplier Services
Continuously evaluate the supplier performance, as well as manage the changes that may affect security.
Security teams review the vendor performance regularly and reassess risks whenever any significant service or infrastructure changes occur.


These controls are able to support the organization's overall Information Security Management System (ISMS) by ensuring that the external suppliers maintain security standards that are comparable to those expected internally. Implementing these controls is able to strengthen governance, as well as improve compliance, and even reduce the likelihood of supply chain-related security incidents.

Vendor Risk Management
The following assessment is able to identify the primary third-party vendors that are currently supporting EduTrack Learning Solutions. Each vendor was evaluated based on the type of service provided, along with the sensitivity of the information it can access and the potential business impact if the service is disrupted, as well as the security controls required to be able to reduce the risk. The risk ratings follow the same qualitative approach used throughout previous GRC activities (Low, Medium, and High) to be able to maintain consistency across the organization's overall risk management process.

Vendor
Service Provided
Data Accessed
Risk Level
Key Security Controls Required
Monitoring Frequency
Microsoft Azure
Cloud hosting and infrastructure
Student records, application databases, employee information, backups
High
Multi-factor authentication (MFA), encryption at rest and in transit, network segmentation, continuous vulnerability management, backup verification
Quarterly security review and annual reassessment
Stripe
Online payment processing
Payment transactions, customer billing information, transaction history
High
PCI DSS compliance, encryption, fraud monitoring, strong authentication, continuous transaction monitoring
Quarterly review and compliance verification
Microsoft 365
Email, file storage, and collaboration
Internal emails, documents, calendars, shared files
Medium
MFA, email filtering, data loss prevention (DLP), secure configuration, audit logging
Quarterly review
Managed IT Support Provider
Endpoint management, remote administration, technical support
Administrative accounts, user devices, system configurations
High
Privileged Access Management (PAM), least privilege, endpoint protection, session logging, regular access reviews
Monthly monitoring and annual audit


Vendor Assessment Analysis
Microsoft Azure – Cloud Infrastructure Provider (High Risk)
Microsoft Azure is able to host the organization's learning platform and databases, as well as application infrastructure. Because nearly all of the business operations rely on the availability and security of this environment, Azure is able to represent one of the organization's most critical suppliers.

A compromise affecting the cloud environment could result in unauthorized access to student information, as well as service interruptions, or even the loss of important business data. Although Microsoft is able to maintain a mature security program, EduTrack Learning Solutions tends to remain responsible for configuring the cloud resources securely under the shared responsibility model.

To reduce risk, the organization should enforce the multi-factor authentication for all the administrative accounts, as well as encrypt sensitive information both during storage and transmission, along with regularly reviewing the access permissions and performing vulnerability assessments, and lastly, continuously monitoring the cloud activity through logging and security alerts.

Stripe – Payment Processing Provider (High Risk)
Stripe manages all online payment transactions made through the learning platform. While the payment card information is largely processed within Stripe's environment, the transaction records and customer billing details remain valuable information that requires protection.

The organization should verify that Stripe maintains PCI DSS compliance, as well as provides encryption for all payment data and supports fraud detection mechanisms, and has well-defined incident response procedures. Since payment processing directly affects revenue generation and customer confidence, periodic reviews of compliance reports and security documentation should form part of the vendor monitoring process.
Microsoft 365 – Communication and Collaboration Platform (Medium Risk)
Microsoft 365 is able to support daily communication between the employees through email, document sharing, and even the collaboration tools. Although it does not host the organization's primary application, it does contain confidential business discussions, internal documentation, contracts, and even employee information.

Security controls should include mandatory MFA, anti-phishing protection, email filtering, Data Loss Prevention (DLP) policies, and even audit logging. User awareness training should also complement these technical controls because phishing tends to remain one of the most common attack methods which are targeting the email services.

Managed IT Support Provider – Technical Support Services (High Risk)
The outsourced IT support provider is able to perform endpoint management and software deployment, along with troubleshooting, and even remote administration across organizational devices. Because support engineers may tend to receive privileged administrative access, this vendor is able to present a significant operational risk.

The organization should require the vendor to be able to implement Privileged Access Management (PAM), as well as enforce the principle of least privilege, and maintain detailed administrative logs, along with conducting background checks for privileged personnel and immediately report any security incidents. Regular access reviews should ensure that the  remote administrative privileges remain limited to authorized personnel only.


Vendor Security Questionnaire
Before onboarding any third-party vendor, EduTrack Learning Solutions should require the supplier to complete the following security assessment questionnaire. The purpose of these questions is to be able to evaluate the vendor's security maturity, as well as identify the potential risks early, and even determine whether additional controls are necessary before sharing organizational information.

Is your organization certified against ISO/IEC 27001 or another recognized information security standard? If yes, please provide evidence of certification.
How do you protect sensitive customer information during storage and transmission? Please describe your encryption methods.
Is Multi-Factor Authentication (MFA) required for privileged or administrative accounts?
How often do you perform vulnerability assessments and penetration testing on your systems?
What is your incident response process, and within what timeframe will customers be notified following a confirmed security incident?
Do you perform employee background checks for personnel who have access to customer systems or sensitive information?
How do you manage software updates, security patches, and vulnerability remediation within your environment?
Do you use subcontractors or fourth-party suppliers to deliver any part of your services? If yes, how are their security practices assessed?
What procedures are followed to securely return or permanently delete customer information when a contract or service agreement ends?
Can you provide recent audit reports, compliance certifications, penetration testing summaries, or other evidence demonstrating the effectiveness of your security controls?


Conclusion
Third-party risk management has become an essential component of modern Governance, Risk, and Compliance because organizations increasingly depend on external suppliers to deliver critical business services. As consistently proven, this assessment, as well as vendors can introduce cybersecurity risks that directly affect confidentiality, integrity, and even availability, even when an organization's internal security controls are strong.

For EduTrack Learning Solutions, applying a structured vendor risk management process strengthens the organization's overall security posture by ensuring that suppliers are evaluated before onboarding, as well as monitored throughout the business relationship, and even securely offboarded when services end. The Vendor Risk Assessment identified the Microsoft Azure, Stripe, Microsoft 365, as well as the Managed IT Support Provider as key suppliers, each requiring the security controls appropriate to the level of risk they introduce.

The vendor security questionnaire is able to complement this assessment by providing a consistent method for evaluating prospective suppliers before they are able to receive access to the organizational information or systems. Combined with ISO/IEC 27001 Annex A.5.19 through A.5.22 supplier relationship controls, these practices are able to support continuous compliance, as well as improve operational resilience, and even reduce the likelihood of supply chain attacks.

Overall, this assessment is able to demonstrate that effective vendor governance extends security beyond organizational boundaries. By integrating due diligence and contractual security requirements, along with continuous observing, and periodic reassessment into the Information Security Management System (ISMS), EduTrack Learning Solutions is better positioned to be able to protect its information assets, as well as maintain customer trust, and even achieve a long-term compliance with ISO/IEC 27001 requirements.
