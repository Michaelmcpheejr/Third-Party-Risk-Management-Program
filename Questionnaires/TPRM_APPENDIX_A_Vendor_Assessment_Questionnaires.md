# Third-Party Risk Management Program

## Appendix A: Vendor Assessment Questionnaires

**Purpose:** Provide reusable questionnaire templates for vendor security assessments

**Structure:**
1. Core Standard Questions (30-35 questions - same for ALL vendors)
2. Vendor-Type-Specific Question Banks (15-25 questions each by vendor type)
3. Guidance for customizing questions to your organization

---

## Part 1: Core Standard Questions (All Vendors)

**These 30-35 questions are baseline for every vendor assessment - CRITICAL, HIGH, and MEDIUM.**

Use all 30-35 for CRITICAL vendors. Use first 20-25 for HIGH vendors. Use first 12-15 for MEDIUM vendors.

---

### Section 1: Access Controls & Authentication (5 Questions)

**Q1:** Does your organization enforce multi-factor authentication (MFA) for all user access to systems and applications?
- [ ] Yes
- [ ] Partial (some systems, not all)
- [ ] No
- **If Yes, provide:** Evidence of MFA implementation (screenshot, policy, log sample)

**Q2:** Describe your approach to privileged access management (PAM). How do you control who has admin/root access to systems?
- Answer format: Open-ended text response
- **Request evidence:** PAM policy, list of privileged users, audit logs

**Q3:** Do you enforce the principle of least privilege (users have only the access they need for their job)?
- [ ] Yes, formally documented and enforced
- [ ] Partially - we review access annually
- [ ] No formal process
- **If Yes, provide:** Access control policy document

**Q4:** How often do you review and revoke access for terminated employees or contractors?
- [ ] Immediately upon termination
- [ ] Within 24 hours
- [ ] Within 1 week
- [ ] Monthly or less frequently
- **Provide:** Last 3 examples of access termination

**Q5:** Do you use role-based access control (RBAC) or similar model to manage access rights?
- [ ] Yes
- [ ] Partial
- [ ] No
- **If Yes, provide:** Documentation of roles and access levels

---

### Section 2: Data Protection & Encryption (5 Questions)

**Q6:** Describe your encryption approach for data at rest. What encryption standard and key length do you use?
- Answer format: Open-ended text
- **Request evidence:** Encryption policy, technical specifications

**Q7:** Describe your encryption approach for data in transit (between your systems and customer systems). What protocol/cipher do you use?
- Answer format: Open-ended text
- **Request evidence:** TLS version, cipher suite documentation

**Q8:** Who controls the encryption keys? (Your company, us, or shared?)
- [ ] We control all keys (you have no access)
- [ ] You control keys (we have no access)
- [ ] Shared control (you have some keys, we have some)
- **Explain:** Key management procedures

**Q9:** Do you encrypt customer data separately from other data in your environment?
- [ ] Yes, completely isolated and encrypted separately
- [ ] Partially isolated
- [ ] No, all data encrypted together
- **Provide:** Data isolation architecture diagram or description

**Q10:** Can you delete customer data upon request or contract termination?
- [ ] Yes, within [specify timeframe]
- [ ] Yes, but with limitations
- [ ] No, we retain data
- **Provide:** Data deletion procedure and timeline

---

### Section 3: Network Security & Infrastructure (5 Questions)

**Q11:** Describe your network security architecture. Do you use firewalls, intrusion detection/prevention systems (IDS/IPS), or similar controls?
- Answer format: Open-ended text
- **Request evidence:** Network diagram, security appliance list

**Q12:** How do you protect against Distributed Denial of Service (DDoS) attacks?
- [ ] DDoS mitigation service (e.g., Cloudflare, AWS Shield)
- [ ] On-premise DDoS detection/prevention
- [ ] Both
- [ ] No specific DDoS protection
- **If yes, provide:** Technical details of DDoS protection

**Q13:** Do you implement Web Application Firewall (WAF) protection?
- [ ] Yes
- [ ] Partial
- [ ] No
- **If yes, provide:** WAF configuration, rules list

**Q14:** How do you handle and protect API endpoints if you offer APIs to customers?
- Answer format: Open-ended text
- **Request evidence:** API security policy, authentication mechanisms, rate limiting, logging

**Q15:** Describe your approach to network segmentation. How do you isolate customer data/systems from each other and from internal systems?
- Answer format: Open-ended text
- **Request evidence:** Network diagram showing segmentation

---

### Section 4: Incident Response & Breach Notification (5 Questions)

**Q16:** Do you have a documented incident response plan? Provide a copy.
- [ ] Yes
- [ ] Partial plan exists
- [ ] No formal plan
- **Provide:** Current incident response plan document

**Q17:** What is your average time from security event detection to initial response/containment?
- Answer format: Specific timeframe (e.g., "2 hours")
- **Provide:** Examples of last 2-3 incidents with timeline documentation

**Q18:** What is your process for notifying customers of a security breach? What is the notification timeline?
- Answer format: Open-ended text
- **Request evidence:** Breach notification policy, examples of past notifications

**Q19:** Do you maintain an incident response team? Is it 24/7 available?
- [ ] Yes, 24/7 dedicated team
- [ ] Yes, on-call team
- [ ] Part-time incident response
- [ ] No dedicated team
- **Provide:** Incident response team structure, contact information

**Q20:** Have you experienced any security incidents in the last 24 months?
- [ ] Yes - provide details below
- [ ] No
- **If yes, provide:** Incident description, root cause, remediation taken, lessons learned

---

### Section 5: Business Continuity & Disaster Recovery (5 Questions)

**Q21:** Do you have a business continuity plan (BCP)? Provide a copy.
- [ ] Yes
- [ ] Partial
- [ ] No
- **Provide:** Current BCP document

**Q22:** Do you have a disaster recovery (DR) plan? Provide a copy.
- [ ] Yes
- [ ] Partial
- [ ] No
- **Provide:** Current DR plan document

**Q23:** What is your Recovery Time Objective (RTO) - how long to restore service after an outage?
- Answer format: Specific timeframe (e.g., "4 hours")
- **Provide:** SLA documentation, RTO guarantee

**Q24:** What is your Recovery Point Objective (RPO) - how much data loss is acceptable?
- Answer format: Specific timeframe (e.g., "1 hour")
- **Provide:** RPO documentation, backup schedule

**Q25:** How often do you test your disaster recovery procedures? When was your last test?
- [ ] Quarterly or more frequently
- [ ] Semi-annually
- [ ] Annually
- [ ] Never tested
- **Provide:** DR test results from last test (date, findings, remediation)

---

### Section 6: Vulnerability & Patch Management (4 Questions)

**Q26:** How frequently do you conduct vulnerability scans of your systems?
- [ ] Monthly or more frequently
- [ ] Quarterly
- [ ] Semi-annually
- [ ] Annually or less
- [ ] Never
- **Provide:** Last 3 months of vulnerability scan results

**Q27:** What is your process for prioritizing and remediating vulnerabilities?
- Answer format: Open-ended text
- **Request evidence:** Vulnerability management policy, prioritization matrix (CVSS score thresholds)

**Q28:** Do you conduct third-party penetration testing? How frequently?
- [ ] Yes, annually or more frequently
- [ ] Yes, every 2 years
- [ ] Yes, less frequently
- [ ] No
- **If yes, provide:** Last penetration test report (redacted for sensitive details if needed)

**Q29:** What is your patch management timeline? How quickly do you patch critical vulnerabilities?
- Answer format: Specific timeframes (e.g., "Critical: 48 hours, High: 7 days, Medium: 30 days")
- **Provide:** Patch management policy, recent patch examples

---

### Section 7: Personnel Security & Training (3 Questions)

**Q30:** Do you conduct background checks on employees with access to customer data?
- [ ] Yes, for all employees
- [ ] Yes, for select roles
- [ ] Limited background checks
- [ ] No
- **Provide:** Background check policy

**Q31:** Do you provide security awareness training to employees?
- [ ] Yes, annually or more frequently
- [ ] Yes, but less frequently
- [ ] No formal training
- **If yes, provide:** Training curriculum, attendance records

**Q32:** Do you have a policy regarding the use of customer data by employees? Is it restricted?
- [ ] Yes, strict access policy
- [ ] Partial restrictions
- [ ] No formal policy
- **Provide:** Data usage policy, access logging procedures

---

### Section 8: Compliance & Certifications (3 Questions)

**Q33:** What security certifications or compliance frameworks does your organization maintain?
- [ ] SOC 2 Type II
- [ ] ISO 27001
- [ ] FedRAMP
- [ ] PCI-DSS
- [ ] HIPAA
- [ ] Other: ___________
- **Provide:** Copy of current certification(s)

**Q34:** When was your last third-party security audit? What framework was used?
- Answer format: Date and framework (e.g., "SOC 2 Type II - Q4 2025")
- **Provide:** Most recent audit report (if allowed under NDA)

**Q35:** What is your information security governance structure? Who is accountable for security?
- Answer format: Open-ended text describing governance
- **Provide:** Organizational chart showing CISO/security leadership reporting

---

## Part 2: Vendor-Type-Specific Question Banks

**Use these in addition to Core Standard Questions (Q1-Q35).**

**Guidance:** Mix core questions + vendor-specific questions based on vendor type.

---

### Type 1: Cloud Infrastructure & SaaS Vendors

**Add these 15 questions to the core 35 for CRITICAL cloud vendors. Use top 8-10 for HIGH vendors.**

**Q36 (Multi-Tenancy & Data Isolation):**
How do you ensure that our data is isolated from other customers' data in your shared infrastructure?
- Answer format: Open-ended text
- **Request evidence:** Data isolation architecture, multi-tenant security procedures

**Q37 (Logging & Monitoring):**
Do you maintain comprehensive logs of all access to customer data? How long do you retain logs?
- Answer format: Log retention timeframe (e.g., "12 months")
- **Provide:** Sample logs showing data access, retention policy

**Q38 (Data Residency):**
Where is customer data stored geographically? Can we specify data residency requirements?
- Answer format: Geographic location(s)
- **Provide:** Data center locations, ability to restrict to specific regions

**Q39 (API Security):**
If you provide APIs, how do you secure them? Do you require authentication? Rate limiting?
- Answer format: Open-ended text
- **Request evidence:** API documentation, authentication requirements, rate limiting policies

**Q40 (Subprocessors/Vendors):**
What third-party vendors do you use to operate your service? How do you vet them?
- Answer format: List of subprocessors
- **Provide:** List of vendors with security requirements they must meet

**Q41 (Account Takeover Prevention):**
What controls do you have to prevent account takeover attacks?
- Answer format: Open-ended text
- Examples: Rate limiting failed logins, account lockout, CAPTCHA, velocity checks

**Q42 (Infrastructure Redundancy):**
Do you have redundant infrastructure across multiple regions/data centers?
- [ ] Yes, active-active across regions
- [ ] Yes, active-passive failover
- [ ] Single region with local redundancy
- [ ] No redundancy
- **Provide:** Redundancy architecture, failover testing results

**Q43 (Backup & Recovery):**
How frequently do you back up customer data? Can you recover from any point in time?
- Answer format: Backup frequency and recovery capabilities
- **Provide:** Backup procedures, recovery time objectives

**Q44 (Compliance with Data Protection Laws):**
How do you comply with GDPR, CCPA, or other data protection regulations?
- Answer format: Open-ended text
- **Provide:** Data deletion procedures, right-to-be-forgotten process

**Q45 (Change Management):**
How do you manage changes to your infrastructure without disrupting service?
- Answer format: Open-ended text
- **Request evidence:** Change management policy, recent change examples

**Q46 (Capacity & Performance):**
How do you ensure service performance and availability during peak usage?
- Answer format: Open-ended text
- **Provide:** Load testing results, capacity planning procedures

**Q47 (Security Updates & Patches):**
How do you deploy security patches without impacting customer service?
- Answer format: Open-ended text
- **Provide:** Patch deployment procedures, zero-downtime examples

**Q48 (Data Encryption in Transit):**
What TLS version and cipher suites do you use? Do you support only modern standards?
- Answer format: Specific TLS versions and ciphers
- **Provide:** SSL/TLS configuration details

**Q49 (OAuth/SSO Integration):**
If you support OAuth or SSO, how do you secure the integration?
- Answer format: Open-ended text
- **Provide:** OAuth implementation security measures

**Q50 (Incident Response to Customers):**
If there's a security incident affecting our data, what is your notification process and timeline?
- Answer format: Specific notification timeline
- **Provide:** Incident notification SLA, communication procedures

---

### Type 2: Managed Security & MSP Vendors

**Add these 18 questions to the core 35 for CRITICAL MSP vendors. Use top 10-12 for HIGH vendors.**

**Q51 (Employee Background Checks):**
Do all analysts with access to our systems pass background checks?
- [ ] Yes, all employees
- [ ] Yes, select roles
- [ ] Limited background checks
- [ ] No
- **Provide:** Background check policy, sample results (names redacted)

**Q52 (Access Logging for Analyst Activity):**
How do you log and monitor analyst access to our systems? Is it recorded?
- Answer format: Open-ended text
- **Request evidence:** Session recording procedures, access logs

**Q53 (Segregation of Duties):**
Do different analysts handle different customer environments to prevent one person from having too much access?
- [ ] Yes, strict segregation
- [ ] Partial segregation
- [ ] No segregation
- **Provide:** Access control procedures showing segregation

**Q54 (24/7 Monitoring Coverage):**
How do you maintain 24/7 monitoring of our systems? What is your staffing model?
- Answer format: Open-ended text
- **Provide:** Staffing schedule, escalation procedures, coverage guarantees

**Q55 (Alert Response Times):**
What is your average time to respond to security alerts?
- Answer format: Specific response times by severity level
- **Provide:** Examples of alerts and response times

**Q56 (Vendor Management):**
If you use tools or subcontractors, how do you vet them for security?
- Answer format: Open-ended text
- **Request evidence:** List of tools/subcontractors, vetting procedures

**Q57 (Incident Handling Process):**
Walk us through your process when you detect a potential security incident in our environment.
- Answer format: Step-by-step procedures
- **Provide:** Sample incident response procedures, examples

**Q58 (Communication & Escalation):**
How do you communicate with us during an incident? What's the escalation path?
- Answer format: Open-ended text
- **Provide:** Contact procedures, escalation matrix

**Q59 (Conflict of Interest Management):**
Do you have procedures to manage conflicts of interest (e.g., your analyst also works for a competitor)?
- [ ] Yes, strict conflict of interest policy
- [ ] Partial procedures
- [ ] No formal procedures
- **Provide:** Conflict of interest policy

**Q60 (Tool & Process Security):**
What tools do you use for remote access to our systems? How are they secured?
- Answer format: List of tools and security measures
- **Provide:** Remote access tool security specifications

**Q61 (Threat Intelligence):**
Do you provide threat intelligence insights or security recommendations?
- [ ] Yes, proactive recommendations
- [ ] Yes, reactive recommendations only
- [ ] Limited intelligence
- [ ] No
- **If yes, provide:** Examples of recommendations provided

**Q62 (Metrics & Reporting):**
What metrics and reports do you provide? How frequently?
- Answer format: List of metrics and reporting frequency
- **Provide:** Sample report

**Q63 (Service Level Agreement (SLA):**
What is your uptime SLA? What is your response time SLA?
- Answer format: Specific SLAs with percentages
- **Provide:** SLA document with penalties/credits

**Q64 (Vulnerability Scanning Frequency):**
How frequently do you scan our systems for vulnerabilities?
- [ ] Daily or more frequently
- [ ] Weekly
- [ ] Monthly
- [ ] Quarterly or less
- **Provide:** Last 3 months of scanning results

**Q65 (Patch Management):**
How quickly do you patch vulnerabilities in our environment?
- Answer format: Specific patch timelines by severity
- **Provide:** Recent patch examples with timelines

**Q66 (Backup & Recovery Testing):**
How frequently do you test backup and recovery procedures for our environment?
- [ ] Monthly or more
- [ ] Quarterly
- [ ] Annually
- [ ] Never
- **Provide:** Last backup recovery test results

**Q67 (Knowledge Transfer):**
Do you document your security procedures and transfer knowledge to our internal team?
- [ ] Yes, comprehensive documentation
- [ ] Partial documentation
- [ ] Minimal documentation
- [ ] No documentation
- **Provide:** Sample documentation

**Q68 (Termination & Data Return):**
Upon contract termination, how do you ensure all data and access is returned/removed?
- Answer format: Open-ended text with timeline
- **Provide:** Data return/destruction procedures

---

### Type 3: Infrastructure & Telecom Vendors

**Add these 12 questions to the core 35 for CRITICAL infrastructure vendors. Use top 7-8 for HIGH vendors.**

**Q69 (Network Redundancy & Failover):**
Do you have redundant network paths and automatic failover capabilities?
- [ ] Yes, geographic redundancy with automatic failover
- [ ] Yes, local redundancy
- [ ] Manual failover available
- [ ] No redundancy
- **Provide:** Network topology, failover procedures

**Q70 (Capacity & Performance):**
How do you ensure network capacity meets our growth needs? What is your capacity planning process?
- Answer format: Open-ended text
- **Provide:** Capacity planning procedures, recent upgrade examples

**Q71 (DDoS Protection):**
Do you offer DDoS protection? What mitigation techniques do you use?
- [ ] Yes, comprehensive DDoS service
- [ ] Yes, basic protection
- [ ] Limited protection
- [ ] No protection
- **If yes, provide:** DDoS protection details, mitigation procedures

**Q72 (BGP Hijacking Prevention):**
What measures do you take to prevent BGP route hijacking attacks?
- Answer format: Open-ended text
- **Provide:** BGP security procedures

**Q73 (Network Monitoring & Logging):**
How do you monitor network traffic? What traffic logging do you maintain?
- Answer format: Open-ended text
- **Provide:** Network monitoring procedures, log retention policies

**Q74 (Maintenance Windows):**
How frequently do you perform maintenance? What is your maintenance notification process?
- Answer format: Maintenance schedule
- **Provide:** Maintenance procedures, notification timelines

**Q75 (Service Level Agreement (SLA):**
What is your uptime SLA? What remedies apply if you miss the SLA?
- Answer format: SLA percentage with remedies
- **Provide:** SLA document

**Q76 (Incident Communication):**
How do you communicate network incidents to us? What is the notification timeline?
- Answer format: Open-ended text with specific timelines
- **Provide:** Incident notification procedures, example notifications

**Q77 (IPv6 Support):**
Do you support IPv6? Is IPv6 as secure as your IPv4 implementation?
- [ ] Yes, full IPv6 support
- [ ] Partial IPv6 support
- [ ] IPv6 available but not recommended
- [ ] No IPv6 support
- **If yes, provide:** IPv6 security procedures

**Q78 (Fiber Security):**
How do you secure the fiber optic cables and network infrastructure from physical tampering?
- Answer format: Open-ended text
- **Provide:** Physical security procedures

**Q79 (Vendor Transparency):**
Are you transparent about where your infrastructure is located? Any third-party routers or shared infrastructure?
- Answer format: Open-ended text
- **Provide:** Infrastructure location details, shared infrastructure disclosure

**Q80 (Incident History):**
Have you experienced any major outages or security incidents in the last 3 years?
- [ ] Yes - provide details
- [ ] No
- **If yes, provide:** Incident details, root cause, remediation, lessons learned

---

### Type 4: Professional Services Vendors (Consultants, Auditors, Law Firms)

**Add these 10 questions to the core 35 for CRITICAL professional services vendors. Use top 6-7 for HIGH vendors.**

**Q81 (Confidentiality Agreement):**
Do you have a non-disclosure/confidentiality agreement in place?
- [ ] Yes, current NDA on file
- [ ] Yes, signed for this engagement
- [ ] Not yet signed
- [ ] None
- **Provide:** Current NDA or proposed NDA

**Q82 (Data Handling Procedures):**
Describe your procedures for handling sensitive/confidential client information.
- Answer format: Open-ended text
- **Provide:** Data handling procedures document

**Q83 (Subcontractors):**
Do you use subcontractors or other vendors? How do you ensure they follow the same security standards?
- [ ] Yes - provide list
- [ ] No subcontractors
- **If yes, provide:** Subcontractor list, security agreements with each

**Q84 (Background Checks):**
Do your consultants/employees pass background checks?
- [ ] Yes, all employees
- [ ] Yes, select roles
- [ ] Limited background checks
- [ ] No
- **Provide:** Background check policy

**Q85 (Conflict of Interest):**
Do you screen for conflicts of interest (e.g., consultant also works for a competitor)?
- [ ] Yes, formal process
- [ ] Informal process
- [ ] Not screened
- **Provide:** Conflict of interest policy

**Q86 (Security Clearances):**
If this is sensitive work, do your consultants have security clearances?
- [ ] Yes
- [ ] Pending
- [ ] Not required
- [ ] No
- **If yes, provide:** Clearance evidence

**Q87 (Work Product Ownership):**
Who owns the intellectual property (IP) of the work delivered?
- [ ] We own it
- [ ] You own it
- [ ] Shared ownership
- **Provide:** IP ownership clause from contract

**Q88 (Insurance):**
Do you carry professional liability insurance?
- [ ] Yes - provide coverage details
- [ ] No
- **If yes, provide:** Insurance certificate, coverage amount

**Q89 (Communication & Access):**
How will you communicate with us? Will you need access to our systems/facilities?
- Answer format: Open-ended text
- **Provide:** Work approach, access requirements

**Q90 (Work Quality & Review):**
How do you ensure work quality? What review processes do you have?
- Answer format: Open-ended text
- **Provide:** Quality assurance procedures, examples of deliverables

---

### Type 5: Development & Deployment Vendors

**Add these 15 questions to the core 35 for CRITICAL dev vendors. Use top 9-10 for HIGH vendors.**

**Q91 (Secure Development Lifecycle):**
Describe your secure software development lifecycle (SDLC). Do you have security practices embedded?
- Answer format: Open-ended text
- **Provide:** SDLC documentation, security practices checklist

**Q92 (Code Review Process):**
Do you perform code reviews before deploying to production?
- [ ] Yes, every code change reviewed
- [ ] Partial code review
- [ ] Limited code review
- [ ] No code review
- **Provide:** Code review procedures, examples

**Q93 (Static Application Security Testing (SAST)):**
Do you use SAST tools to scan code for vulnerabilities?
- [ ] Yes, every build
- [ ] Yes, regular scans
- [ ] Yes, but infrequently
- [ ] No
- **If yes, provide:** SAST tool used, recent scan results

**Q94 (Dynamic Application Security Testing (DAST)):**
Do you use DAST tools to scan running applications?
- [ ] Yes, every build
- [ ] Yes, regular scans
- [ ] Yes, but infrequently
- [ ] No
- **If yes, provide:** DAST tool used, recent scan results

**Q95 (Dependency Management):**
How do you manage and track third-party libraries/dependencies?
- Answer format: Open-ended text
- **Provide:** Dependency management tool/process

**Q96 (Vulnerability Disclosure):**
If vulnerabilities are found in your software, how do you disclose and patch them?
- Answer format: Open-ended text with timelines
- **Provide:** Vulnerability disclosure procedures, recent examples

**Q97 (Build Integrity & Signing):**
How do you ensure code hasn't been tampered with during build/deployment?
- [ ] Code signing in place
- [ ] Hash verification
- [ ] Build artifacts secured
- [ ] No integrity checks
- **If yes, provide:** Code signing/verification procedures

**Q98 (Secrets Management):**
How do you handle API keys, database passwords, and other secrets in code?
- [ ] Secrets vault (e.g., AWS Secrets Manager)
- [ ] Environment variables
- [ ] Hardcoded (bad practice)
- [ ] Other: ___________
- **Provide:** Secrets management procedures

**Q99 (Infrastructure-as-Code (IaC) Security):**
If you use infrastructure-as-code, how do you ensure it's secure?
- Answer format: Open-ended text
- **Provide:** IaC practices, scanning tools used

**Q100 (CI/CD Pipeline Security):**
Describe your CI/CD pipeline. What security gates are in place?
- Answer format: Open-ended text
- **Provide:** CI/CD architecture, security scanning points

**Q101 (Production Access Control):**
Who has access to production systems? How is it controlled?
- Answer format: Open-ended text with access matrix
- **Provide:** Production access control procedures, privileged access procedures

**Q102 (Deployment Process & Rollback):**
How do you deploy code to production? What is your rollback procedure if something goes wrong?
- Answer format: Open-ended text
- **Provide:** Deployment procedures, rollback examples

**Q103 (Monitoring & Alerting):**
How do you monitor applications in production for security issues?
- Answer format: Open-ended text
- **Provide:** Monitoring tools, alert procedures

**Q104 (Configuration Management):**
How do you manage configuration changes to avoid security misconfigurations?
- Answer format: Open-ended text
- **Provide:** Configuration management procedures, change control

**Q105 (Third-Party Components):**
If you use open-source or third-party code, how do you vet it for security?
- Answer format: Open-ended text
- **Provide:** Third-party code vetting procedures, examples

---

### Type 6: Facilities & Physical Security Vendors

**Add these 8 questions to the core 35 for CRITICAL facilities vendors. Use top 5-6 for HIGH vendors.**

**Q106 (Physical Access Controls):**
How do you control access to the facility? What authentication is used?
- [ ] Badge/card access with logging
- [ ] Combination locks
- [ ] Manual sign-in
- [ ] No formal controls
- **If yes, provide:** Access control procedures, badge issuance process

**Q107 (Visitor Management):**
How do you manage visitors? Do they have escorts?
- [ ] All visitors logged and escorted
- [ ] Visitors logged but not always escorted
- [ ] Minimal visitor management
- [ ] No visitor control
- **Provide:** Visitor management procedures

**Q108 (Surveillance):**
Do you have CCTV surveillance? How long do you retain video?
- [ ] Yes, retention: ___________
- [ ] No
- **If yes, provide:** Surveillance system details, retention policy

**Q109 (Environmental Controls):**
How do you maintain environmental controls (temperature, humidity, power)?
- Answer format: Open-ended text
- **Provide:** Environmental control procedures, monitoring

**Q110 (Backup Power):**
Do you have backup power (UPS, generators) for critical systems?
- [ ] Yes, automatic failover
- [ ] Yes, manual backup
- [ ] No backup power
- **If yes, provide:** Backup power specifications, testing schedule

**Q111 (Fire Suppression):**
What fire suppression system do you use? When was it last tested?
- Answer format: Fire suppression type and test date
- **Provide:** Fire suppression system inspection records

**Q112 (Secure Disposal):**
How do you securely dispose of physical documents/equipment containing sensitive data?
- Answer format: Open-ended text
- **Provide:** Secure disposal procedures, vendor details

**Q113 (Emergency Procedures):**
What emergency procedures do you have (evacuation, business continuity, etc.)?
- Answer format: Open-ended text
- **Provide:** Emergency procedures document, evacuation plan

---

### Type 7: Hardware & Component Vendors

**Add these 10 questions to the core 35 for CRITICAL hardware vendors. Use top 6-7 for HIGH vendors.**

**Q114 (Supply Chain Visibility):**
How do you ensure hardware integrity from manufacturing to delivery?
- Answer format: Open-ended text
- **Provide:** Supply chain documentation, tamper detection procedures

**Q115 (Secure Boot & Firmware):**
Do you support secure boot? Can firmware be verified/signed?
- [ ] Yes, secure boot with signed firmware
- [ ] Partial support
- [ ] No secure boot
- **If yes, provide:** Secure boot specifications

**Q116 (Encryption Capabilities):**
Do the devices/components support hardware-based encryption?
- [ ] Yes
- [ ] Partial support
- [ ] Software encryption only
- [ ] No encryption
- **If yes, provide:** Encryption specifications

**Q117 (Vulnerability Disclosure):**
If vulnerabilities are found in hardware/firmware, how do you disclose and patch?
- Answer format: Open-ended text with timelines
- **Provide:** Vulnerability disclosure procedures, recent examples

**Q118 (Hardware Authentication):**
Can hardware be authenticated to ensure it's genuine and not counterfeit?
- [ ] Yes, authentication mechanism available
- [ ] No authentication
- **If yes, provide:** Authentication procedures

**Q119 (Secure End-of-Life):**
How do you handle secure destruction of hardware?
- Answer format: Open-ended text
- **Provide:** Hardware destruction procedures, certificates of destruction

**Q120 (Spare Parts & Repairs):**
How do you source spare parts? Can you ensure they're genuine?
- Answer format: Open-ended text
- **Provide:** Parts sourcing procedures, authenticity verification

**Q121 (Configuration Hardening):**
What hardening recommendations do you provide for secure deployment?
- Answer format: Open-ended text
- **Provide:** Hardening guides, configuration templates

**Q122 (Warranty & Support):**
What security support is included in warranty? Any security patches guaranteed?
- Answer format: Open-ended text
- **Provide:** Warranty terms, support SLA

**Q123 (Environmental Compliance):**
Are devices compliant with environmental standards (RoHS, WEEE)?
- [ ] Yes, compliant
- [ ] Partial compliance
- [ ] No
- **If yes, provide:** Compliance certificates

---

## Part 3: Custom Questions by Organization

**After using Core Standard Questions + Vendor-Type Questions, add 3-5 custom questions specific to your company.**

### Example Custom Questions

**For Federal Contractors (NIST 800-171 / CMMC Focus):**
- "How do you support our compliance with NIST 800-171 requirements? What controls do you implement?"
- "If we require CMMC Level 2 certification, are you willing to be assessed? When?"
- "How do you handle controlled unclassified information (CUI)? Describe your CUI procedures."

**For Healthcare Organizations (HIPAA Focus):**
- "Do you sign a Business Associate Agreement (BAA)? When was it last updated?"
- "How do you comply with HIPAA breach notification requirements?"
- "What is your approach to HIPAA audit readiness?"

**For Payment Card Industry (PCI-DSS Focus):**
- "Are you PCI-DSS compliant? What level?"
- "How do you handle credit card data? Do you store it, or does payment processing happen elsewhere?"
- "What is your approach to PCI audit readiness?"

**For Organizations with Specific Security Concerns:**
- "We require vendors to implement zero-trust architecture. Can you support this?"
- "How do you prevent data exfiltration from your service?"
- "What is your approach to insider threat prevention?"

---

## How to Use This Appendix

**Step 1: Select Vendor Type**
- Identify which type the vendor is (Cloud, MSP, Infrastructure, etc.)

**Step 2: Choose Question Set**
- For CRITICAL vendors: Use all 35 Core Questions + all vendor-type questions (40-50 total)
- For HIGH vendors: Use Core Questions 1-25 + top vendor-type questions (30-40 total)
- For MEDIUM vendors: Use Core Questions 1-12 + some vendor-type questions (15-20 total)
- For LOW vendors: Use Core Questions 1-5 only (5 questions)

**Step 3: Add Custom Questions**
- Add 3-5 organization-specific questions based on your compliance needs

**Step 4: Create Questionnaire**
- Compile into a document or online form
- Send to vendor with 2-week deadline for response
- Request evidence with each answer

**Step 5: Score Assessment**
- Review vendor responses against Phase 1 Risk Scoring framework
- Calculate Likelihood, Impact, Regulatory Exposure scores
- Generate risk score and assessment report

---

**Questions are organized by topic, making it easy to customize for your organization's needs. Feel free to modify, add, or remove questions as needed.**
