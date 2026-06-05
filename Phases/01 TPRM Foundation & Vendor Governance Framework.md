# Third-Party Risk Management & Vendor Governance Program

## Phase 1: TPRM Foundation & Vendor Governance Framework

**Organization:** [Client Enterprise / Federal Contractor]  
**Program Owner:** Chief Risk Officer & Procurement Director  
**Implementation Date:** Month 1-3  
**Program Scope:** Comprehensive vendor governance across entire enterprise vendor ecosystem  
**Key Outcome:** Enterprise-wide vendor risk visibility and management capability  

---

## Executive Summary

Phase 1 establishes the foundation for a comprehensive Third-Party Risk Management (TPRM) program aligned to Rasner's vendor governance model and enterprise risk management principles. The program addresses vendor risk across the complete vendor lifecycle: intake → assessment → ongoing monitoring → offboarding.

**Key Objectives:**
1. Define vendor governance framework and decision authority
2. Establish vendor criticality assessment methodology
3. Create risk scoring model aligned to enterprise risk appetite
4. Map compliance requirements across vendor types
5. Establish vendor categorization and tiering structure
6. Define roles, responsibilities, and governance committees

**Key Outcomes:**
- Comprehensive vendor governance charter
- Vendor criticality matrix (3-dimensional: data access, integration, strategic value)
- Risk scoring methodology (Likelihood × Impact × Regulatory Exposure)
- Vendor categorization framework (SaaS, Infrastructure, Services, Consultants, etc.)
- Governance structure (Board/Steering/Operational committees)
- Compliance framework mapping (SOC 2, FedRAMP, ISO 27001, NIST, etc.)

---

## Part 1: The Vendor Risk Challenge

### Why Vendor Risk Matters

**Statistics:**
- 60%+ of security breaches involve third parties
- Average vendor breach impact: $4M-$8M per incident
- Regulatory fines for vendor-caused breaches: $500K-$50M+ (depends on data exposed)
- Compliance failures due to vendor issues: Leading cause of audit findings

**Federal Contractor Context:**
- CUI handling requires vendor security oversight (NIST 800-171, CMMC)
- Supply chain compromises are primary nation-state attack vector
- Vendor assessment failures have led to loss of federal contracts
- Third-party risk is top audit finding for federal contractors

### The Gap Most Organizations Face

**Current State (Typical):**
- Vendors assessed once at contract signing
- Minimal ongoing oversight
- No formal risk tiering (all vendors treated equally)
- Ad-hoc questionnaires with no standardization
- No executive visibility into vendor risk portfolio
- Reactive response to vendor breaches

**Desired State:**
- Continuous vendor risk assessment
- Risk-based tiering (critical vendors get deeper oversight)
- Standardized assessment across all vendors
- Executive dashboards showing vendor risk portfolio
- Proactive monitoring and incident coordination
- Strategic vendor management aligned to enterprise risk appetite

---

## Part 2: Vendor Governance Framework (Rasner Model)

### Three-Layer Vendor Governance Structure

**Layer 1: Board / Executive Oversight (Quarterly)**

| Decision | Authority | Frequency |
|----------|-----------|-----------|
| Vendor strategy & risk appetite | Board / Executive Committee | Quarterly |
| High-risk vendor approval | CISO + CFO + Business Owner | As needed |
| Major vendor incidents | Board notification | Immediate |
| Compliance certifications (SOC 2, FedRAMP) | Steering Committee | Annually |
| Vendor contract terms | Procurement + Legal + Risk | Per procurement |

**Layer 2: Steering Committee (Monthly)**

| Function | Owner | Frequency |
|----------|-------|-----------|
| Vendor risk assessment review | Chief Risk Officer | Monthly |
| Incident status updates | CISO | Monthly |
| Remediation tracking | Procurement Director | Monthly |
| Compliance audit prep | Compliance Officer | Monthly |
| New vendor approvals | Cross-functional | Per procurement |

**Layer 3: Operational (Ongoing)**

| Function | Owner | Frequency |
|----------|-------|-----------|
| Vendor intake processing | Vendor Management Team | Per procurement |
| Questionnaire administration | Risk Assessment Team | Per vendor |
| Evidence collection | Vendor / Risk Team | Per assessment |
| Continuous monitoring | Risk Operations | Monthly/Quarterly |
| Breach response coordination | CISO + Vendor Manager | As needed |

### Vendor Governance Charter

**Purpose:** Establish clear governance for third-party risk management across the enterprise

**Scope:** All vendors with access to systems, data, or facilities

**Key Principles:**
1. **Risk-based approach:** Oversight proportional to risk level
2. **Shared responsibility:** Vendor responsible for controls, enterprise for oversight
3. **Transparency:** Vendor risk visible to all stakeholders
4. **Continuous improvement:** Assessment and monitoring evolve with threat landscape
5. **Compliance:** All vendor oversight meets regulatory requirements (NIST 800-171, CMMC, etc.)

**Governance Authority:**
- **CISO:** Vendor security requirements and assessment methodology
- **Procurement Director:** Vendor selection and contract execution
- **Chief Risk Officer:** Overall vendor risk portfolio and risk appetite
- **Business Owner:** Vendor performance and business continuity
- **Compliance Officer:** Regulatory requirements and audit readiness

---

## Part 3: Vendor Criticality Assessment

### Multi-Dimensional Vendor Criticality Matrix

Unlike simple tiering (High/Medium/Low), this framework scores vendors across **three dimensions**, providing more granular risk assessment.

### Dimension 1: Data Access Level

**What data does the vendor access?**

| Score | Level | Description | Example Vendors |
|-------|-------|-------------|-----------------|
| 3 | CUI/Sensitive | Access to CUI, PII, financial data, confidential IP | Cloud storage (AWS, Azure), SaaS CRM systems, payment processors |
| 2 | Internal Data | Access to internal emails, documents, non-sensitive data | Email providers, collaboration tools, file sharing |
| 1 | No Data Access | No access to company data (facility services, office supplies) | Office supplies vendor, janitorial services |

### Dimension 2: System Integration & Criticality

**How integrated is the vendor with critical systems?**

| Score | Level | Description | Example Vendors |
|-------|-------|-------------|-----------------|
| 3 | Critical Infrastructure | Essential to operations; systems down = business impact | Cloud infrastructure, DNS providers, VPN services |
| 2 | Important Systems | Important but not immediately critical; workarounds exist | Backup vendors, email filtering, collaboration tools |
| 1 | Non-Critical | Not essential; easy to replace or work around | Consulting services, training, advisory |

### Dimension 3: Strategic Value / Business Dependency

**How dependent is the business on this vendor?**

| Score | Level | Description | Example Vendors |
|-------|-------|-------------|-----------------|
| 3 | Strategic / Sole-Source | Only vendor for critical function; high switching costs | Primary cloud provider, MSP, managed security vendor |
| 2 | Important / Few Alternatives | Important but alternatives exist | Backup cloud provider, secondary SaaS tool |
| 1 | Commodity / Easy Replace | Easy to replace; low switching costs | Single-use tools, specialized contractors |

### Combined Criticality Scoring

**Criticality Score = (Data Access + Integration + Strategic Value) / 3**

**Scale: 1.0 - 3.0**

| Score Range | Vendor Classification | Oversight Level |
|-------------|----------------------|-----------------|
| 2.7-3.0 | CRITICAL | Deep assessment, quarterly monitoring, board visibility |
| 2.0-2.6 | HIGH | Comprehensive assessment, semi-annual monitoring, steering committee visibility |
| 1.4-1.9 | MEDIUM | Standard assessment, annual monitoring, operational visibility |
| 1.0-1.3 | LOW | Lightweight assessment, biennial review, basic documentation |

### Vendor Criticality Examples

**Example 1: Cloud Infrastructure Provider (AWS/Azure)**
- Data Access: 3 (CUI/sensitive data)
- Integration: 3 (critical infrastructure)
- Strategic Value: 3 (sole-source for cloud)
- **Criticality Score: 3.0 (CRITICAL)**
- **Oversight:** Deep quarterly assessment, board reporting

**Example 2: Email SaaS Provider (Microsoft 365)**
- Data Access: 2 (internal data, some sensitive)
- Integration: 3 (critical for communications)
- Strategic Value: 3 (sole-source)
- **Criticality Score: 2.67 (HIGH)**
- **Oversight:** Comprehensive annual assessment, steering committee visibility

**Example 3: Backup Vendor**
- Data Access: 3 (all data for backups)
- Integration: 2 (important but has workaround)
- Strategic Value: 2 (secondary backup exists)
- **Criticality Score: 2.33 (HIGH)**
- **Oversight:** Comprehensive assessment, semi-annual monitoring

**Example 4: Office Supplies Vendor**
- Data Access: 1 (no data access)
- Integration: 1 (non-critical)
- Strategic Value: 1 (easy to replace)
- **Criticality Score: 1.0 (LOW)**
- **Oversight:** Basic questionnaire, biennial review

---

## Part 4: Vendor Risk Scoring Methodology

### Risk = Likelihood × Impact × Regulatory Exposure

Aligned to IRM scoring methodology from Phase 1 of Threat Modeling program.

### Component 1: Likelihood (Probability of Breach)

**Scale: 1 (Unlikely) to 3 (Highly Likely)**

| Score | Likelihood | Assessment Criteria |
|-------|-----------|-------------------|
| 3 | Highly Likely | Vendor has had prior breach, weak security posture, critical controls missing |
| 2 | Possible | Vendor has average security posture, some control gaps, history of minor issues |
| 1 | Unlikely | Vendor has strong security posture, controls in place, no history of issues |

**Factors that increase likelihood:**
- No SOC 2 Type II certification
- Weak access controls (no MFA)
- No encryption of data at rest/in transit
- Inadequate incident response procedures
- Prior security incidents
- Unsupported/outdated software

### Component 2: Impact (Business Consequence of Breach)

**Scale: 1 (Low) to 3 (Severe)**

| Score | Impact | Assessment Criteria |
|-------|--------|-------------------|
| 3 | Severe | Data breach affects >1,000 customers/employees, CUI exposed, >$5M recovery cost, regulatory fines |
| 2 | Moderate | Data breach affects 100-1,000 people, internal data exposed, $500K-$5M recovery, audit findings |
| 1 | Low | Data breach affects <100 people, non-sensitive data, <$500K recovery cost, no regulatory impact |

**Factors that increase impact:**
- Vendor handles CUI or PII
- Vendor is critical to operations (business downtime impact)
- Vendor has access to customer data
- Vendor stores data long-term
- Vendor is in supply chain (can affect customers)

### Component 3: Regulatory Exposure (Compliance Risk)

**Scale: 1 (None) to 3 (Severe)**

| Score | Exposure | Assessment Criteria |
|-------|----------|-------------------|
| 3 | Severe | NIST 800-171 requirement, federal contract dependent on vendor, breach = loss of federal contracts, CMMC certification at risk |
| 2 | Moderate | HIPAA/PCI requirement, audit finding likely, regulatory fine possible |
| 1 | None | No direct regulatory requirement, compliance impact minimal |

**Factors that increase exposure:**
- Vendor handles CUI (NIST 800-171, CMMC requirement)
- Vendor is federal contractor (subject to audit)
- Vendor impacts customer compliance (e.g., payment processor for PCI-DSS)
- Vendor has regulatory oversight (healthcare, finance)
- Vendor breach could affect government contracting status

### Risk Score Calculation

**Formula:**
```
Risk Score = (Likelihood × 0.33) + (Impact × 0.33) + (Regulatory Exposure × 0.33)
Scale: 1.0 - 3.0
```

**Severity Bands:**

| Score Range | Classification | Remediation Timeline | Actions |
|-------------|-----------------|----------------------|---------|
| 2.67-3.0 | CRITICAL | 0-30 days | Immediate: Board notification, interim controls, risk acceptance decision |
| 2.33-2.66 | HIGH | 30-60 days | Assess: Root cause analysis, control improvement plan, executive reporting |
| 1.68-2.32 | MODERATE | 60-90 days | Plan: Remediation roadmap, quarterly monitoring, steering committee visibility |
| 1.0-1.67 | LOW | 90+ days | Monitor: Annual assessment, standard ongoing monitoring |

### Vendor Risk Score Examples

**Example 1: Critical Cloud Provider with Security Gap**

Vendor: AWS (data storage provider)
- Likelihood: 1 (strong security, no history of breaches, SOC 2 certified) = 1
- Impact: 3 (handles all CUI, breach = business shutdown, $50M+ impact) = 3
- Regulatory Exposure: 3 (NIST 800-171 requirement, CMMC dependent) = 3

**Risk Score = (1×0.33) + (3×0.33) + (3×0.33) = 2.33 (HIGH)**
**Action:** Comprehensive annual assessment, quarterly monitoring, steering committee visibility

**Example 2: Backup Vendor with Weak Controls**

Vendor: Third-party backup provider
- Likelihood: 2 (average controls, no MFA, some audit findings) = 2
- Impact: 3 (stores all backups = recovery capability at risk) = 3
- Regulatory Exposure: 2 (impacts NIST 800-171 backup requirements) = 2

**Risk Score = (2×0.33) + (3×0.33) + (2×0.33) = 2.33 (HIGH)**
**Action:** Immediate remediation plan (MFA, encryption), monthly monitoring until fixed

**Example 3: Email Service with Adequate Controls**

Vendor: Microsoft 365 (email provider)
- Likelihood: 1 (SOC 2 certified, strong controls, history of good security) = 1
- Impact: 2 (email data sensitive but not CUI, some internal info) = 2
- Regulatory Exposure: 2 (email subject to audit, but not critical for CMMC) = 2

**Risk Score = (1×0.33) + (2×0.33) + (2×0.33) = 1.67 (LOW)**
**Action:** Annual assessment, standard ongoing monitoring

---

## Part 5: Vendor Categorization Framework

### Vendor Types (Based on Function)

**Category 1: Cloud Infrastructure & SaaS Vendors**
- Examples: AWS, Azure, Salesforce, Microsoft 365, ServiceNow
- Typical Criticality: HIGH to CRITICAL
- Key Risks: Data breach, service outage, supply chain compromise
- Required Controls: SOC 2 Type II, encryption, access controls, incident response

**Category 2: Managed Security & MSP Vendors**
- Examples: Managed SOC, MSSP, managed firewall provider
- Typical Criticality: CRITICAL
- Key Risks: Breach of breach (attacker via MSP), insider threat, misconfiguration
- Required Controls: SOC 2 Type II, background checks, privileged access monitoring, detailed contracts

**Category 3: Infrastructure & Telecom Vendors**
- Examples: ISP, data center provider, telecom vendor
- Typical Criticality: CRITICAL
- Key Risks: Service outage, nation-state interception, supply chain attack
- Required Controls: Service level agreements, redundancy, encryption support, incident notification

**Category 4: Professional Services Vendors**
- Examples: Consultants, auditors, law firms, accountants
- Typical Criticality: MEDIUM to HIGH (depends on access to sensitive data)
- Key Risks: Data breach, insider threat, conflicts of interest
- Required Controls: NDA, background checks, limited access, data handling procedures

**Category 5: Development & Deployment Vendors**
- Examples: Software development firms, DevOps consultants, code repository providers
- Typical Criticality: HIGH to CRITICAL (code access = supply chain risk)
- Key Risks: Malicious code injection, supply chain compromise, insider threat
- Required Controls: Code review, access controls, secure SDLC practices, background checks

**Category 6: Facilities & Physical Security Vendors**
- Examples: Data center, facilities management, security guards, janitorial services
- Typical Criticality: LOW to MEDIUM (depends on facility criticality)
- Key Risks: Physical breach, data theft, social engineering
- Required Controls: Background checks, security protocols, visitor management

**Category 7: Hardware & Software Vendors**
- Examples: Hardware manufacturers, software vendors, component suppliers
- Typical Criticality: MEDIUM to CRITICAL (supply chain risk)
- Key Risks: Supply chain compromise, hardware backdoors, software vulnerabilities
- Required Controls: Vendor security assessments, code signing, supply chain transparency

---

## Part 6: Compliance Framework Mapping

### Which Compliance Frameworks Apply to Which Vendor Types?

| Framework | Applies To | Key Requirement |
|-----------|-----------|-----------------|
| **SOC 2 Type II** | Cloud, SaaS, MSP, Infrastructure | Security controls independently audited & tested |
| **ISO 27001** | All vendors handling sensitive data | Information security management system certified |
| **FedRAMP** | Cloud vendors (federal customers) | Federal cloud security certification |
| **NIST 800-171** | All vendors handling CUI | Specific technical controls for CUI protection |
| **PCI-DSS** | Payment processors, vendors with card data | Payment card data security requirements |
| **HIPAA** | Healthcare vendors, health data processors | Healthcare privacy & security requirements |
| **GDPR** | Vendors handling EU citizen data | European data privacy requirements |
| **CMMC** | Federal contractor vendors | Cybersecurity Maturity Model Certification |

### Vendor Assessment Framework by Type

**CRITICAL Vendors (Risk Score 2.67-3.0):**
- ✅ SOC 2 Type II certification (required)
- ✅ Risk assessment questionnaire (comprehensive)
- ✅ Site assessment/on-site audit (for critical vendors)
- ✅ Executive interviews
- ✅ Evidence review (security policies, logs, test results)
- ✅ Contract terms review (liability, breach notification, indemnification)
- ✅ Quarterly monitoring & re-assessment
- ✅ Incident notification SLA
- ✅ Business continuity & disaster recovery testing

**HIGH Vendors (Risk Score 2.33-2.66):**
- ✅ SOC 2 Type II certification (preferred) or equivalent
- ✅ Risk assessment questionnaire (standard)
- ✅ Evidence review (security controls, certifications)
- ✅ Contract terms review
- ✅ Semi-annual monitoring & re-assessment
- ✅ Incident notification SLA
- ✅ Disaster recovery capability confirmation

**MEDIUM Vendors (Risk Score 1.68-2.32):**
- ✅ Risk assessment questionnaire (abbreviated)
- ✅ Certification check (SOC 2, ISO 27001, or equivalent)
- ✅ Annual monitoring & re-assessment
- ✅ Incident notification clause in contract

**LOW Vendors (Risk Score 1.0-1.67):**
- ✅ Basic information collection
- ✅ Background check (if accessing facilities)
- ✅ Biennial or as-needed review
- ✅ Standard contract terms

---

## Part 7: Vendor Governance Committees & Decision Authority

### Committee 1: Vendor Risk Steering Committee

**Frequency:** Monthly (1 hour)

**Members:**
- Chief Risk Officer (chair)
- CISO
- Procurement Director
- Compliance Officer
- Key Business Owner (rotates)

**Responsibilities:**
- Review new vendor risk assessments
- Approve HIGH and CRITICAL vendor risk scores
- Track remediation status for at-risk vendors
- Discuss vendor incidents and mitigation
- Ensure compliance with vendor governance policy

**Agenda:**
1. New vendor approvals (5 min)
2. Risk assessment review (HIGH/CRITICAL only) (10 min)
3. Vendor incident updates (5 min)
4. Remediation tracking (10 min)
5. Compliance status (5 min)

### Committee 2: Vendor Management Operational Team

**Frequency:** Bi-weekly (1 hour)

**Members:**
- Vendor Manager (chair)
- Risk Assessment Analyst
- Procurement Specialist
- Security Analyst
- Compliance Analyst

**Responsibilities:**
- Process vendor intake forms
- Schedule and conduct assessments
- Collect evidence and questionnaire responses
- Track remediation activities
- Coordinate monitoring activities
- Process vendor offboarding

**Agenda:**
1. Vendor intake status (5 min)
2. Active assessments (10 min)
3. Remediation tracking (10 min)
4. Monitoring & monitoring results (5 min)
5. Issues & escalations (5 min)

### Committee 3: Board Executive Oversight

**Frequency:** Quarterly (15 min)

**Members:**
- Board Risk Committee
- CEO
- CISO
- Chief Risk Officer

**Responsibilities:**
- Oversight of vendor risk strategy
- Approval of vendor risk appetite
- Review of CRITICAL vendor incidents
- Assessment of overall vendor risk portfolio
- Approval of major vendor contract terms

**Agenda:**
1. Vendor risk dashboard review (5 min)
2. Critical incidents (if any) (5 min)
3. Compliance status (3 min)
4. Strategic vendor decisions (2 min)

---

## Part 8: Vendor Risk Policy Framework

### Core TPRM Policy Components

**Policy 1: Vendor Selection & Intake**
- Requirement for vendor security assessment before contract signing
- Risk-based assessment approach (criticality determines depth)
- Risk approval authority (who can approve HIGH/CRITICAL vendors)
- Timeline for assessment (should not delay procurement more than 2 weeks)

**Policy 2: Vendor Assessment**
- Mandatory questionnaire completion (tailored by vendor type)
- Evidence submission requirements
- Interview requirements for CRITICAL vendors
- Site assessment eligibility (for highest-risk vendors)

**Policy 3: Vendor Contract Terms**
- Required security clauses (breach notification, access control, data handling)
- Liability and indemnification requirements
- Service level agreements (SLAs) for critical vendors
- Termination & data return procedures
- Audit rights (ability to audit vendor security)

**Policy 4: Vendor Monitoring & Oversight**
- Frequency of monitoring by risk level (quarterly, semi-annual, annual, biennial)
- Monitoring methods (vulnerability scanning, breach database checks, recertification)
- Incident notification requirements (timeline, escalation)
- Remediation requirements (how quickly vendor must fix identified issues)

**Policy 5: Vendor Offboarding**
- Data return & destruction procedures
- Access revocation timeline
- Final compliance verification
- Contract closeout procedures

**Policy 6: Vendor Incident Response**
- Notification procedures (how vendor informs of breach)
- Investigation procedures (how company assesses impact)
- Customer notification (if customer data exposed)
- Recovery procedures (restoration, forensics, etc.)

---

## Part 9: Key Governance Decisions

### Decision 1: Vendor Risk Appetite

**Question:** How much vendor risk is acceptable?

**Options:**
1. **Conservative:** No CRITICAL vendors; only SOC 2 Type II certified vendors
2. **Balanced:** CRITICAL vendors acceptable with deep monitoring; most vendors SOC 2 certified
3. **Aggressive:** Accept higher risk for business agility; risk mitigation through contracts/insurance

**Recommendation:** Balanced approach
- CRITICAL vendors acceptable (but with quarterly monitoring)
- HIGH vendors require semi-annual assessment
- Risk acceptance authority tied to business impact
- CMMC/NIST 800-171 requirements for federal contractors

### Decision 2: Assessment Depth by Risk Level

**Question:** How much rigor in assessment by vendor type?

**Recommended Matrix:**
- CRITICAL: Comprehensive (questionnaire + evidence review + executive interview)
- HIGH: Standard (questionnaire + evidence review)
- MEDIUM: Streamlined (questionnaire only)
- LOW: Basic (background check + NDA)

### Decision 3: Ongoing Monitoring Approach

**Question:** How frequently to re-assess vendors?

**Recommended Frequency:**
- CRITICAL: Quarterly (automated monitoring) + annual full re-assessment
- HIGH: Semi-annual monitoring + every 2 years full re-assessment
- MEDIUM: Annual review
- LOW: Biennial review

---

## Part 10: Success Metrics

### Phase 1 Completion Metrics

| Metric | Target | Evidence |
|--------|--------|----------|
| Governance charter approved | 100% | Signed charter document |
| Steering committee established | Yes | Committee charter + meeting cadence |
| Assessment methodology documented | Yes | TPRM policy & procedures document |
| Vendor categorization complete | 100% of vendors | Vendor database with categories |
| Risk scores calculated | 100% of vendors | Risk register with scores |
| Board approval of risk appetite | Yes | Board decision minutes |

### Program Health Metrics (Ongoing)

| Metric | Target | Owner |
|--------|--------|-------|
| Assessment completion rate | 100% within 30 days of intake | Vendor Manager |
| Remediation tracking | 100% of issues tracked | Risk Operations |
| CRITICAL vendor monitoring | 100% on schedule | Risk Operations |
| Steering committee attendance | 80%+ | Chief Risk Officer |
| Board escalation accuracy | All CRITICAL incidents reported | CISO |

---

## Document Control

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2026-Q1 | Security & Risk Team | Initial release - TPRM Phase 1 foundation |

**Document Classification:** Confidential - Executive/Board Use

**Next Review Date:** Upon completion of Phase 1; then quarterly

---

**Phase 1 Complete. Ready for Phase 2: Vendor Inventory & Criticality Assessment?**

> **"LOCK PHASE 1 AND PROCEED WITH PHASE 2"**
