# Creating-a-Company-Culture-for-Security
**Overview:** Now that you’re super knowledgeable about security, let's put your newfound know-how to the test. You may find yourself in a tech role someday, where you need to design and influence a culture of security within an organization. This project is your opportunity to practice these important skillsets.

**Assignment:** *In this project, you’ll create a security infrastructure design document for a fictional organization. The security services and tools you describe in the document must be able to meet the needs of the organization. Your work will be evaluated according to how well you met the organization’s requirements.*

**About the organization:** This fictional organization has a small, but growing, employee base, with 50 employees in one small office. The company is an online retailer of the world's finest artisanal, hand-crafted widgets. They've hired you on as a security consultant to help bring their operations into better shape.

Organization requirements: As the security consultant, the company needs you to add security measures to the following systems:

 

 - An external website permitting users to browse and purchase widgets
 - An internal intranet website for employees to use

 

 - Secure remote access for engineering employees
 - Reasonable, basic firewall rules
 - Wireless coverage in the office
 - Reasonably secure configurations for laptops

Since this is a retail company that will be handling customer payment data, the organization would like to be extra cautious about privacy. They don't want customer information falling into the hands of an attacker due to malware infections or lost devices.

Engineers will require access to internal websites, along with remote, command line access to their workstations.

## Grading: This is a required assignment for the module.

**What you'll do: You’ll create a security infrastructure design document for a fictional organization. Your plan needs to meet the organization's requirements and the following elements should be incorporated into your plan:**

 - Authentication system
 - External website security
 - Internal website security
 - Remote access solution
 - Firewall and basic rules recommendations
 - Wireless security
 - VLAN configuration recommendations
 - Laptop security configuration
 - Application policy recommendations
 - Security and privacy policy recommendations
 - Intrusion detection or prevention for systems containing customer
   data

## Answer

**Introduction:** This document describes how the functional and nonfunctional requirements recorded in the Requirements Document and the preliminary user-oriented functional design based on the design specifications.

Furthermore, it describes the design goals in accordance with the requirements, by providing a high-level overview of the system architecture, and describes the data design associated with the system, as well as the human-machine scenarios in terms of interaction and operation. The high-level system design is further decomposed into low-level detailed design specifications including hardware, software, data storage and retrieval mechanisms and external interfaces.

Purpose of the Security Infrastructure Design Document

The Security Infrastructure Design Document helps to document and track the necessary information required to effectively define architecture and system design in order to give the guidance on the security architecture of the IT environment that is going to be established.

**2. General Overview and Design Approach**

***2.1 General Overview***

The client requires an IT infrastructure to perform their business activities that involve e-commerce applications and internal VPN access for their customers as well as employees with a high priority on the security and privacy of customer information and of the client’s as well

***2.2 Assumptions/Constraints/Risks***

**Assumptions**
It has been assumed that the employees are increased by 5% every year thereby reflecting the usage of the network bandwidth and increase of the devices that are connected to the enterprise network infrastructure.
**Constraints**
The following are the key considerations associated with the security of the infrastructure:

· Authentication system

· External website security

· Internal website security

· Remote access solution

· Firewall and basic rules recommendations

· Wireless security

· VLAN configuration recommendations

· Laptop security configuration

· Application policy recommendations

· Security and privacy policy recommendations

· Intrusion detection or prevention for systems containing customer data

**Risks**

Since the infrastructure is meant to carry out the e-commerce related transactions that may involve third party merchant authorizations and financial related issues, a strict security mechanism needs to be enforced so as to ensure that there is no such issue related in customers transactions as it may affect the reputation of the organization.

Additionally, there should be a backup mechanism to take the data backups at regular intervals to deal with any unwanted situations like system failures, attacks by intruders etc.,

**2.3 Alignment with Federal Enterprise Architecture**

The proposed architecture strictly complies with federal Enterprise architecture, All the protocols being used, and the hardware interfaces used compiles with the industry standards as specified so as to ensure compatibility of the networks as well as the security in compliance with CMS Enterprise Architecture (EA)

**3. Design considerations**

***3.1 Goals:***

The following are the desirable outcomes of the security infrastructure proposed to be implemented in the organization:

· An external website permitting users to browse and purchase widgets securely.

· An internal intranet website like that of a VPN for employees to use

· Secure remote access for engineering employees

· Reasonable, basic firewall rules

· Wireless coverage in the office

· Reasonably secure configurations for laptops

· Privacy of the user data

***3.2 Architectural Strategies***

For external website to perform purchase activity by customers:

In order to provide a secure e-commerce transaction, the following are the primary which security goals include:

· Protecting confidentiality of the data

· Making sure that unauthorized persons or systems cannot access the information of users;

· Making sure that the information accessed is genuine;

· Making the data accessible and usable;

· Logging the transactions for further reference and support activity

· Verifying the authenticity of a person to perform a transaction.

**1. For intranet website accessed by employees:**

Since the data is accessed by the company employees only it should be only available to company’s level of access making it private from other information being maintained on the infrastructure So,the following are the considerations in this case:

· Making sure that the access is within their intranet by implementing a firewall mechanism

· Specifying the authentication mechanism to access the website by the employees

· Supervising the activities and user management on the website by an administrator

***1. Secure remote access for engineering employees***

We can perform safe implementation of remote access control objectives based on the following security considerations:

 - Device type: What device types require remote access?
 - Role: What remote access is appropriate for that role given the
   device used?
 - Location. Is access from a public location, another company site,
   internal wireless, etc.?
 - Process and data: What processes and data are accessible given the
   first three access characteristics?
 - Authentication method: Does the need for strong authentication
   increase based on the device used, where it is used, and what it is
   allowed to access?
 
 **Basic firewall rules to be implemented:**
 - Block by default – to block all incoming and outgoing connections
 - Allow specific traffic – only allow specified IP addresses
 - Allow Inbound-only allowing intranet users
 
  Wireless coverage in the office Can be provided with an 802.11 WLAN adapter/router with PSK(pre-shared key) configuration or a login based limited access to company WIFI by the employees

**Security considerations: Should be Password protected and metered**

**1. V-LAN Configuration:**

VLAN network segmentation creates security zones that enables flexible and strong control of what a remote user can access. security zones separating incoming traffic from internal resources. Using dynamic VLAN assignments and access control lists, we can control user access based on the conditions

***1. Laptop Security configuration:***

One of the most vulnerable parts of the infrastructure is the laptop computers that employees use. These devices can be responsible for bringing in viruses or malware or causing the organization to lose sensitive data. This can be checked using the techniques such as:

· Encrypting the disks on the laptops

· Ensuring Antimalware/Antivirus are up to date in regular intervals

· White listing the devices on the network

· Running a product such as System Center Configuration Manager, LANDesk, Altiris, or some other systems management platform

**1. Application policy recommendations**

· Integrate secure coding principles in all software components of infrastructure.

· Perform automated application security testing as part of the overall application testing process.

· Development and testing environments should redact all sensitive data or use de-identified data.

· Compliance with industry standard data policies and protocols

**1. Security and privacy policy recommendations**

***Explain How the organization Collects and Use Personal Information***

· Cookie Policy – Cookies are used to store user preferences or shopping cart contents. Clearly explain your cookie practice.

· How organization will Share Customer Information – Customers need to know that their data will only be used to complete the transaction and that any further use of that data (including selling or distributing it) requires their consent.

· Contact Information – Make it easy for your customers to contact you or file a complaint.

 . Display Privacy Policy Make sure new customers or users have easy
   access to your policy mandatorily

. Publish Email Opt-Out Policies – Include opt-out options in your email marketing

. Get a Seal of Approval – Third party validation of your online privacy and security policy can enhance your credibility. And trust of security

. Intrusion detection or prevention for systems containing customer data

As the demand for E-Commerce grows on the Internet so will the increasing potential for E-Commerce sites to be attacked. Implementing security methodologies pertaining to an E-Commerce environment is not a simple thing. It should consider various threats and anomalies that can cause an attack. This can be achieved though penetration testing and reverse engineering to detect by signature or by an anomaly. This can be achieved by a third-party IDS system readily available in the market

**Summary**

Thus, we can conclude the report of the security infrastructure of the organization has been assessed and recommendations were made as required for the proposed environment as specified

***Key assets being protected:***

 1. Customer information, Company related information
 2. Key threats to protect against:
 3. Intrusion to website, Data Loss

**Key activities to protect against:**

Customer purchase of artifacts, payment transactions, employee data

Relative ranking of fundamental security goals:

*This is an important exercise for every organization as part of the risk mitigation planning process. For this project, the ranking came out like this:*

 1. **Confidentiality: high**
 2. **Integrity: high**
 3. **Availability: medium**
 4. **Auditability: medium**
 5. **Nonrepudiation: N/A**
