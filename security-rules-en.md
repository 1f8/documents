# DATA PROTECTION POLICY
We abide by this data protection policy for customer consent and data rights to access, rectify, erase, or stop sharing/processing their information where applicable or required by data privacy regulation.

1. NETWORK PROTECTION
Statlas.io is completely cloud-based and direct access is limited to only core engineers. All data requests are only available to authenticated users and each user's data is partitioned to prevent data leakage.

We will implement network protection controls (e.g. VPC subnet/Security Groups, Virtual Networks, network firewalls) to deny access to unauthorized IP addresses.

2. ACCESS MANAGEMENT
We will not create or use generic, shared, or default login credentials or user accounts, and will implement baselining mechanisms to ensure that at all times only the required user accounts access private information. We will regularly review the list of people and services with access to private information on a regular basis (at least quarterly), and remove accounts that no longer require access.

We do not store any user passwords on our server. All passwords are handled directly through AWS, so you're passwords will never be exposed via our servers.

3. ENCRYPTION IN TRANSIT
All data in transit must be accomplished over TLS/HTTPS. In the case we are working with legacy systems, we highly recommend converting to HTTPS, as we must enforce this security control on all applicable external endpoints used by customers as well as internal communication channels and operational tooling. Unsecured communication channels will be disabled.

4. INCIDENT RESPONSE PLAN
Plans and Tooling will be in place to detect and handle security incidents, which identify the incident response roles and responsibilities, define incident types that may impact third-parties, define incident response procedures for defined incident types, and define an escalation path and procedures to escalate Security Incidents to respective parties. Such Plans and Tooling will be reviewed and verify the plan every 6 months.

Data breaches require the client (customer), users, third-party APIs and all other parties to be notified within 72 hours, unless otherwise specified by the parties rules and regulations (e.g. Amazon requires 24 hour notice).

5. REQUEST FOR DELETION AND RETURN
We will respond with data requests within 72 hours and you may ask for data to be permanently deleted, with written confirmation after it is completed.

6. DATA GOVERNANCE
We will create, document, and abide by a privacy and data handling policy for their Applications or services which govern the appropriate conduct and technical controls to be applied in managing and protecting information assets.

7. ENCRYPTION AND STORAGE
All data at rest must be encrypted. The cryptographic materials and cryptographic capabilities used for encryption will only accessible to the our processes and services, and will never be shared. Data will never be persisted using removable media (e.g., USB) or unsecured public cloud applications (e.g., public links made available through Google Drive) unless their is written consent via the client.

API Secrets have an added layer of encryption which falls under very strong encryption and are only accessible by principle developers of the application. Any secret that is exposed must be regenerated and the owner must be prompted to immediately delete the exposed secret.

8. LEAST PRIVILEGE PRINCIPLE
We implement fine-grained access control mechanisms to allow granting rights to any party using the Application and the Application’s operators following the principle of least privilege, which means data is protected under a unique access role, and access should be granted on a “need-to-know” basis.

9. LOGGING AND MONITORING
We have our own proprietary logging and monitoring system which gathers logs to detect security-related events to Applications and systems. All logs are only accessible privately by us and we prevent any unauthorized access and tampering throughout their lifecycle. Our internal system contains mechanisms to monitor the logs and all system activities to trigger investigative alarms on suspicious actions. In case their is an incident, it will be dealt with in accordance with our Incident Response Plan.

10. AUDIT
We audit our data policies and security best practices regularly, as well as follow updates on Amazon, Google, and Azure’s best practices.

11. COMMUNICATION
Communication will come through our email address or community forums. We will never ask for your password, API key, or any personal information through email. We will also never send attachments with an executable program. If you get an email from us that is suspicious, please contact us immediately as it may affect other users.

CONTACT US
For more information of if you have questions contact us at:

Email: hello@1f8.dev
1F8, LLC
4-29-4-315 Nishishinjyuku Shinjyuku-ku
Tokyo, Japan 160-0023
Last Updated: March 24, 2022