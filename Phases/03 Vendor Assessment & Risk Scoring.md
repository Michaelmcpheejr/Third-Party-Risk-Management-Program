# Third-Party Risk Management & Vendor Governance Program

## Phase 3: Vendor Assessment & Risk Scoring

**Organization:** [Client Enterprise / Federal Contractor]  
**Program Owner:** Chief Risk Officer & Procurement Director  
**Phase Duration:** Month 6-18 (ongoing)  
**Key Outcome:** Complete vendor risk assessments with remediation plans  

---

## Executive Summary

Phase 3 operationalizes vendor assessment. This phase takes the prioritization from Phase 2 and conducts actual risk assessments, applying the risk scoring methodology from Phase 1 to determine which vendors need remediation and how urgent.

**Key Objectives:**
1. Conduct risk-based assessments for all vendors (CRITICAL first)
2. Collect evidence of vendor security controls
3. Score vendor risk using Phase 1 methodology
4. Identify control gaps and remediation needs
5. Track remediation through completion
6. Report assessment results to stakeholders

**Key Outcomes:**
- Completed assessment reports for 100% of vendors
- Risk scores for each vendor (1.0-3.0)
- Remediation plans for at-risk vendors
- Evidence repository (controls documentation)
- Assessment tracking dashboard
- Escalation procedures for high-risk findings

---

## Part 1: Assessment Methodology by Vendor Criticality

### CRITICAL Vendor Assessment (Deep Dive)

**Timeline:** 6-8 weeks per vendor (or batch 2-3 at a time)

**Assessment Components:**

#### Component 1: Security Questionnaire (Extended)

**Length:** 50-75 questions

**Topics Covered:**
- Access controls & authentication (10 questions)
- Data protection & encryption (10 questions)
- Network security & infrastructure (10 questions)
- Incident response & breach notification (8 questions)
- Business continuity & disaster recovery (8 questions)
- Compliance & certifications (8 questions)
- Personnel & physical security (8 questions)
- Vulnerability management & patching (5 questions)

**Question Types:**

**Yes/No Questions (Baseline Controls):**
- "Does your organization enforce multi-factor authentication (MFA) for all user access?"
- "Do you encrypt data at rest using AES-256 or equivalent?"
- "Do you maintain and test disaster recovery procedures annually?"

**Evidence-Based Questions (Require Proof):**
- "What is your incident response time from detection to containment? Provide evidence of your last 3 incidents and response times."
- "Provide your SOC 2 Type II audit report covering the last 12 months."
- "Provide your business continuity test results from the last 12 months."

**Open-Ended Questions (Deep Dive):**
- "Describe your approach to managing privileged access. Who has admin access and how is it monitored?"
- "Walk us through your most recent security incident. What happened, how did you detect it, and what did you do?"

#### Component 2: Evidence Collection & Review

**Required Evidence Documents:**

| Evidence Type | Acceptance | Timeline |
|---------------|-----------|----------|
| SOC 2 Type II Report | Most recent 12-month report | Required for CRITICAL |
| ISO 27001 Certificate | Current year certificate | Preferred |
| Security Policy | Latest version, specific to data handling | Required |
| Incident Response Plan | Documented and current | Required |
| Business Continuity Plan | Documented, tested | Required |
| Vulnerability Scan Results | Last 90 days | Required |
| Penetration Test Results | Last 12 months | Preferred for CRITICAL |
| Access Control Procedures | MFA, privileged access, least privilege | Required |
| Encryption Standards | Data at rest and in transit | Required |
| Disaster Recovery Test Results | Last 12 months, documented | Required |

**Evidence Review Process:**
1. Request documents (via email with deadline)
2. Vendor submits evidence
3. Security team reviews completeness & authenticity
4. Score each control area (Implemented / Partial / Missing)
5. Identify gaps & remediation needs

#### Component 3: Executive/Technical Interviews

**Participants (From Vendor):**
- Chief Information Security Officer (CISO) or Chief Security Officer
- Chief Technology Officer or VP Engineering
- Incident Response Lead
- Compliance Officer (if applicable)

**Interview Duration:** 2-3 hours

**Interview Topics:**

**Security Leadership (30 min):**
- How is security governance structured?
- Who is accountable for security?
- How is security budget determined?
- What are your top security priorities?

**Incident Response (30 min):**
- Walk us through your incident response process
- How long does it take to detect/respond/contain?
- How do you notify customers of breaches?
- Show us examples of recent incidents

**Technical Controls (30 min):**
- How do you manage access to customer data?
- What encryption standards do you use?
- How do you handle patches and updates?
- How do you test security controls?

**Compliance & Risk (30 min):**
- What compliance frameworks do you follow?
- How do you manage vendor risk (if you're an MSSP)?
- What is your disaster recovery capability?
- How do you stay current with emerging threats?

**Documentation:** Record interview notes, ask permission to record

#### Component 4: Site Assessment (For Select CRITICAL Vendors)

**Who Gets Site Assessment:**
- MSPs (Managed Security Providers)
- Data center providers
- Vendors with physical access to your systems
- Vendors handling CUI with direct facility access

**What's Evaluated:**
- Physical security controls (badge access, visitor logs, cameras)
- Data center conditions (temperature, humidity, backup power)
- Server room security (locked, limited access, logging)
- Incident response capability (SOC walkthrough)
- Continuity procedures (backup site, failover testing)

**Assessment Duration:** 1-2 days on-site

**Deliverable:** Site assessment report with photos/evidence

---

### HIGH Vendor Assessment (Comprehensive)

**Timeline:** 2-4 weeks per vendor

**Assessment Components:**

#### Component 1: Security Questionnaire (Standard)

**Length:** 40-50 questions

**Topics Covered:**
- Access controls (8 questions)
- Data protection (8 questions)
- Network security (8 questions)
- Incident response (6 questions)
- Business continuity (6 questions)
- Compliance (6 questions)

**Question Types:** Mix of yes/no + evidence-based + some open-ended

#### Component 2: Evidence Collection & Review

**Required Evidence:**

| Evidence Type | Acceptance |
|---------------|-----------|
| SOC 2 Type II Report | Preferred (or equivalent) |
| ISO 27001 Certificate | Preferred |
| Security Policy | Required |
| Incident Response Plan | Required |
| Business Continuity Plan | Required |
| Vulnerability Scan Results | Last 6 months |

#### Component 3: Technical Interview

**Duration:** 1-2 hours

**Participants:** CISO or Security Lead + Technical Lead

**Topics:** Security architecture, controls, incident response, compliance

#### Component 4: Site Assessment

**Not typically required** - only if:
- Vendor handles CUI
- Vendor has critical infrastructure access
- Previous assessments flagged concerns

---

### MEDIUM Vendor Assessment (Streamlined)

**Timeline:** 1-2 weeks per vendor

**Assessment Components:**

#### Component 1: Security Questionnaire (Abbreviated)

**Length:** 15-20 questions

**Topics:** Key areas only
- Access controls (3-4 questions)
- Data protection (3-4 questions)
- Incident response (2-3 questions)
- Compliance certifications (2-3 questions)

#### Component 2: Certification Verification

**Required:** At least one of:
- SOC 2 Type II certification
- ISO 27001 certification
- Industry-specific (PCI-DSS, HIPAA, FedRAMP)

**Verification Process:**
1. Vendor provides certification document
2. Verify certificate is current
3. Check issuing body is reputable
4. Document certification in vendor file

#### Component 3: Document Review

**Required Documents:**
- Security policy (high-level)
- Incident response procedure (summary)
- Data handling agreement

**No interviews required** - information gathering only

---

### LOW Vendor Assessment (Lightweight)

**Timeline:** 1 week per vendor

**Assessment Components:**

#### Component 1: Background Check

**Standard commercial background check:**
- Company history
- Ownership/principals
- Litigation history (any lawsuits?)
- Financial stability (is company solvent?)

**Sources:**
- Dun & Bradstreet report
- SEC filings (if public company)
- Court records
- Business registry

#### Component 2: Certification Check

**If applicable:**
- Does vendor claim to have SOC 2, ISO 27001?
- If yes, request copy and verify

#### Component 3: Basic Contract Review

**Ensure contract includes:**
- Data handling clause
- Breach notification requirement
- Data deletion clause (after contract ends)

**No questionnaire required** - too low-risk for detailed assessment

---

## Part 2: Risk Scoring During Assessment

### Scoring Inputs

During assessment, you gather information to score three dimensions:

**Dimension 1: Likelihood (Probability of Breach)**

**Based on Assessment Findings:**

| Finding | Likelihood Score | Reason |
|---------|-----------------|--------|
| SOC 2 certified, strong controls documented, no prior breaches | 1 | Low probability of breach |
| Adequate controls, some gaps, no prior breaches | 2 | Possible breach risk |
| Weak controls, significant gaps, prior breach history | 3 | High probability of breach |

**Assessment Evidence:**
- Controls documented? → Strong controls = lower likelihood
- Evidence of testing? → Regular testing = lower likelihood
- Prior incidents? → History of incidents = higher likelihood
- Certifications? → SOC 2/ISO 27001 = lower likelihood

**Dimension 2: Impact (Business Consequence if Breach Occurs)**

**Based on Vendor Criticality:**

| Impact Type | Score | Example |
|-------------|-------|---------|
| CUI exposed, customer PII affected, >1,000 people impacted | 3 | Salesforce breach exposes 10,000 customer records |
| Internal data exposed, 100-1,000 people impacted | 2 | Email vendor breach exposes internal communications |
| Non-sensitive data, <100 people impacted | 1 | Office supplies vendor breach (minimal data) |

**Assessment Consideration:**
- What data does vendor access? (From Phase 1 criticality scoring)
- How many people affected if breached? (Multiply by data access level)
- Business impact if vendor goes down? (Service outage cost)

**Dimension 3: Regulatory Exposure (Compliance Risk)**

**Based on Data Type & Requirements:**

| Exposure | Score | Example |
|----------|-------|---------|
| CUI handling (NIST 800-171 required), federal contract risk | 3 | AWS breach of CUI = loss of federal contracts |
| PCI-DSS or HIPAA data | 2 | Payment processor breach = regulatory fine |
| No regulatory requirement | 1 | Office supplies vendor = no compliance impact |

**Assessment Question:**
- Does vendor handle CUI? → Score 3
- Does vendor handle regulated data (PCI, HIPAA)? → Score 2
- No regulated data? → Score 1

---

### Risk Score Calculation (Applied During Assessment)

**Formula:**
```
Risk Score = (Likelihood × 0.33) + (Impact × 0.33) + (Regulatory Exposure × 0.33)
```

**Example 1: CRITICAL Vendor (AWS) with Strong Controls**

**Assessment Findings:**
- Likelihood: 1 (SOC 2 certified, no breaches, strong controls)
- Impact: 3 (handles CUI, if breached = business shutdown)
- Regulatory Exposure: 3 (NIST 800-171 requirement, federal contract risk)

**Risk Score = (1×0.33) + (3×0.33) + (3×0.33) = 2.33 (HIGH)**

**Interpretation:** Even though AWS has strong controls (low likelihood), the impact and regulatory exposure are high. Result: HIGH risk score requiring quarterly monitoring.

**Example 2: HIGH Vendor (Slack) with Average Controls**

**Assessment Findings:**
- Likelihood: 2 (SOC 2 certified, but some communication gaps in incident response plan)
- Impact: 2 (internal data, important but not CUI)
- Regulatory Exposure: 1 (no regulatory requirement for Slack)

**Risk Score = (2×0.33) + (2×0.33) + (1×0.33) = 1.67 (LOW/MEDIUM)**

**Interpretation:** Slack has moderate risk. Impact is internal data only, no regulatory exposure. Result: MEDIUM risk requiring annual monitoring, no immediate remediation needed.

**Example 3: CRITICAL Vendor (Payment Processor) with Gaps**

**Assessment Findings:**
- Likelihood: 2 (SOC 2 certified but missing vulnerability scanning evidence)
- Impact: 3 (payment card data, PCI-DSS regulated, customer breach = liability)
- Regulatory Exposure: 3 (PCI-DSS compliance requirement, customer trust impact)

**Risk Score = (2×0.33) + (3×0.33) + (3×0.33) = 2.67 (CRITICAL)**

**Interpretation:** Payment processor has control gaps (missing vulnerability scans). High impact + regulatory exposure = CRITICAL risk. Action: Require vendor to implement vulnerability scanning within 30 days.

---

## Part 3: Assessment Report Structure

### Report Template (For Each Vendor)

**Section 1: Executive Summary**

| Field | Example |
|-------|---------|
| Vendor Name | Salesforce |
| Assessment Date | Q2 2026 |
| Risk Score | 3.0 (CRITICAL) |
| Risk Status | GREEN (Acceptable) |
| Recommendation | Continue monitoring quarterly. No remediation required. |

**Section 2: Vendor Information**

| Field | Value |
|-------|-------|
| Vendor ID | CRIT-005 |
| Service Type | Cloud SaaS (CRM) |
| Data Access Level | 3 (CUI/PII/Financial) |
| Integration Level | 3 (Critical infrastructure) |
| Strategic Value | 3 (Sole-source) |
| Criticality Score | 3.0 (CRITICAL) |

**Section 3: Assessment Summary**

- Assessment Type: Comprehensive questionnaire + evidence review + executive interview
- Assessment Period: Jan 15 - Feb 28, 2026
- Vendors Interviewed: Sarah Chen (CISO), Mike Torres (Engineering Lead)
- Evidence Reviewed: SOC 2 report, incident response plan, security policy
- Assessment Status: COMPLETE

**Section 4: Risk Scoring**

| Dimension | Score | Justification |
|-----------|-------|---------------|
| Likelihood | 1 | SOC 2 Type II certified, strong controls, no prior breaches |
| Impact | 3 | Handles CUI, customer PII, financial data |
| Regulatory Exposure | 3 | NIST 800-171 requirement, CMMC dependent |
| **Overall Risk Score** | **3.0 (CRITICAL)** | **Acceptable risk with monitoring** |

**Section 5: Control Assessment**

| Control Area | Status | Evidence | Score |
|--------------|--------|----------|-------|
| Access Controls | IMPLEMENTED | MFA enabled, SSO via Okta, role-based access | PASS |
| Data Encryption | IMPLEMENTED | AES-256 at rest, TLS 1.2+ in transit | PASS |
| Incident Response | IMPLEMENTED | IR plan documented, avg response time 2 hours | PASS |
| Business Continuity | IMPLEMENTED | DR tested quarterly, RTO <4 hours | PASS |
| Vulnerability Management | IMPLEMENTED | Monthly scanning, pen test annually | PASS |
| Network Security | IMPLEMENTED | DDoS protection, WAF, IDS/IPS | PASS |
| Personnel Security | IMPLEMENTED | Background checks, training, least privilege | PASS |
| Compliance | IMPLEMENTED | SOC 2 Type II, FedRAMP authorized | PASS |

**Section 6: Findings & Remediation**

**Finding 1: Minor**
- Issue: Documentation of latest penetration test not provided during assessment
- Severity: LOW
- Remediation: Vendor to provide most recent penetration test report by [date]
- Timeline: 30 days
- Owner: Vendor CISO

**Finding 2:** None - all controls are implemented and documented

**Section 7: Monitoring Plan**

- Frequency: Quarterly
- Type: Automated vulnerability scanning + annual full reassessment
- Next Assessment: Q3 2026
- Monitoring Contact: Sarah Chen (Salesforce CISO)
- Escalation Contact: [Your CISO]

**Section 8: Contract Review**

| Clause | Status | Details |
|--------|--------|---------|
| Data Handling Agreement | PRESENT | Current, covers CUI handling |
| Breach Notification SLA | PRESENT | 24-hour notification requirement |
| Audit Rights | PRESENT | Right to audit quarterly |
| Liability & Indemnification | PRESENT | Covers data breach liability |
| Termination & Data Return | PRESENT | 30-day data return after contract end |
| Business Continuity SLA | PRESENT | 99.95% uptime SLA |

**Section 9: Conclusion & Recommendation**

Salesforce demonstrates strong security posture with comprehensive controls, SOC 2 Type II certification, and proactive incident response. Overall risk is ACCEPTABLE. 

Recommend: Continue quarterly monitoring. No immediate remediation required. Annual reassessment recommended.

**Approved by:** [Your CISO]  
**Date:** [Assessment Date]

---

## Part 4: Remediation Tracking

### When Vendor Gets a "Red Flag" Finding

**Example Scenario:**
Assessment finds: "Vendor does not have documented incident response procedure"

**Remediation Process:**

**Step 1: Document the Issue**
- Finding: No incident response procedure
- Severity: HIGH
- Risk Impact: If vendor is breached, response will be chaotic; detection/containment time unknown
- Deadline: 30 days to provide documented procedure

**Step 2: Vendor Remediation**
- Vendor develops incident response plan
- Vendor submits to you for review (within 30 days)

**Step 3: Review & Acceptance**
- You review vendor's IR plan
- Accept (if adequate) OR reject (if inadequate) and ask for revisions

**Step 4: Close-Out**
- Once accepted, mark finding as RESOLVED in tracking system
- Schedule follow-up verification in 90 days

**Step 5: Escalation (If Needed)**
- If vendor misses deadline → escalate to vendor CISO
- If vendor's remediation is inadequate → escalate to steering committee
- If vendor refuses to remediate → escalation path leads to contract renegotiation or termination

### Remediation Tracking Dashboard

| Vendor | Finding | Severity | Due Date | Status | Owner | Days Remaining |
|--------|---------|----------|----------|--------|-------|-----------------|
| Payment Processor | Missing vulnerability scans | HIGH | 3/15/26 | IN PROGRESS | Vendor CISO | 14 days |
| Backup Vendor | No MFA for admin access | CRITICAL | 2/28/26 | OVERDUE | Your CISO | -7 days |
| SaaS Vendor #3 | Outdated encryption standard | MEDIUM | 4/30/26 | NOT STARTED | Vendor CTO | 45 days |
| MSP Vendor | Documentation gap in IR plan | LOW | 5/31/26 | NOT STARTED | Vendor CISO | 76 days |

**Actions on Dashboard:**
- OVERDUE findings: Escalate immediately
- IN PROGRESS (nearing deadline): Follow up with vendor
- NOT STARTED (due within 30 days): Send reminder

---

## Part 5: Evidence Management & Compliance Mapping

### Evidence Repository

**Location:** Secure shared folder (Box, SharePoint, or similar)

**Structure:**
```
/Vendors/
  /VENDOR_ID-VENDOR_NAME/
    /Assessments/
      /2026_Q2_Assessment_Report.pdf
      /Questionnaire_Responses.xlsx
      /Interview_Notes.docx
    /Certifications/
      /SOC2_Type2_Report_2026.pdf
      /ISO27001_Certificate_2026.pdf
    /Policies/
      /Security_Policy.pdf
      /Incident_Response_Plan.pdf
      /Data_Handling_Procedures.pdf
    /Compliance/
      /NIST_800171_Mapping.xlsx
      /CMMC_Alignment.xlsx
    /Monitoring/
      /Vulnerability_Scan_Results_2026_Q2.pdf
      /Annual_Reassessment_2026.pdf
```

### Compliance Framework Mapping

**What It Is:** Document which vendor controls map to compliance requirements

**Example: Payment Processor Vendor**

| NIST Requirement | PCI-DSS Requirement | Vendor Control | Evidence |
|------------------|-------------------|-----------------|----------|
| Access Control (AC-2) | Requirement 8: User access | MFA for all admin access | SOC 2 Type II section 5.3 |
| Encryption (SC-7) | Requirement 3: Data encryption | AES-256 encryption at rest, TLS 1.2+ in transit | SOC 2 Type II section 4.2 |
| Incident Response (IR-4) | Requirement 12: Security incidents | Documented IR plan, <2 hour detection/response | Incident Response Plan document |
| Vulnerability Mgmt (SI-2) | Requirement 11: Vulnerability scanning | Monthly vulnerability scans, annual pen test | Vulnerability scan results, pen test report |

**Use Case:** 
When auditor asks "How do we know Payment Processor meets PCI-DSS requirement 8 (access control)?", you show: "See this mapping - they use MFA, which is documented in their SOC 2 Type II report section 5.3."

---

## Part 6: Assessment Metrics & KPIs

### Completion Metrics

| Metric | Target | Owner |
|--------|--------|-------|
| CRITICAL vendor assessments completed | 100% within 3 months | Vendor Manager |
| HIGH vendor assessments completed | 100% within 6 months | Vendor Manager |
| MEDIUM assessments completed | 100% within 12 months | Vendor Manager |
| Assessment quality (no rework needed) | 95%+ first-time | Risk Analyst |
| Average assessment time (CRITICAL) | 6 weeks | Vendor Manager |
| Vendor response rate to questionnaire | 90%+ within 2 weeks | Vendor Manager |

### Risk Metrics

| Metric | Target | Owner |
|--------|--------|-------|
| Vendors with acceptable risk score | 95%+ | Chief Risk Officer |
| Findings closed within SLA | 100% | Risk Operations |
| CRITICAL findings remediated within 30 days | 100% | Vendor Manager |
| HIGH findings remediated within 60 days | 95%+ | Vendor Manager |
| Repeat findings (same issue twice) | <5% | Risk Analyst |

---

**Ready to proceed with Phase 4: Vendor Monitoring & Ongoing Oversight?**
