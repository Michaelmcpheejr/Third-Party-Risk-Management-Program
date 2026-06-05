# Third-Party Risk Management & Vendor Governance Program

## Phase 4: Vendor Monitoring & Ongoing Oversight

**Organization:** [Client Enterprise / Federal Contractor]  
**Program Owner:** Chief Risk Officer & Procurement Director  
**Phase Duration:** Ongoing (Month 6+)  
**Key Outcome:** Continuous vendor risk monitoring with automated alerts and escalation  

---

## Executive Summary

Phase 4 operationalizes continuous monitoring of vendors after initial assessment. Rather than assessing vendors once and forgetting about them, Phase 4 establishes automated, risk-based monitoring to catch issues early and track vendor performance over time.

**Key Objectives:**
1. Establish automated monitoring procedures by vendor criticality
2. Detect vendor security incidents and breaches early
3. Track vendor certification status and compliance
4. Monitor vendor performance against SLAs
5. Identify when re-assessment is needed
6. Escalate issues through appropriate channels
7. Track remediation and vendor improvements

**Key Outcomes:**
- Automated monitoring system (alerts, dashboards, escalations)
- Vendor monitoring schedule (quarterly, semi-annual, annual, biennial)
- Breach database monitoring (Dark Web, public breaches)
- Certification tracking (SOC 2 expiration, ISO 27001 renewal)
- Performance dashboards (SLA compliance, incident response time)
- Escalation procedures with clear ownership
- Executive reporting on vendor risk portfolio

---

## Part 1: Monitoring Strategy by Vendor Criticality

### CRITICAL Vendors - Quarterly Monitoring

**Monitoring Frequency:** Every quarter (4x per year)

**Monitoring Methods:**

**Method 1: Automated Vulnerability Scanning (Monthly)**
- Frequency: Monthly scans of vendor infrastructure (if allowed by contract)
- Scope: External vulnerability scan for known exposures
- Tools: Qualys, Rapid7, Nessus, or similar
- Acceptance: Vendor should allow scanning as part of contract
- Action on findings: Report vulnerability within 48 hours, request vendor remediation plan

**Method 2: Breach Database Monitoring (Continuous)**
- Check if vendor appears in breach databases (monthly)
- Sources: Have I Been Pwned, Breach Directory, Dark Web monitoring services
- Tools: Automated monitoring services or manual checks
- Action on findings: Immediate escalation if breach detected involving our data

**Method 3: Certification Status Tracking (Quarterly)**
- Verify SOC 2 Type II certification is current
- Check expiration dates (notify 60 days before expiration)
- Request updated reports as they're released
- Tools: Certification tracking spreadsheet + automated calendar alerts
- Action: Escalate if vendor lets certification lapse

**Method 4: Incident Monitoring (Ongoing)**
- Monitor public news/announcements for vendor incidents
- Subscribe to vendor's security announcements
- Track vendor's incident response time and communication
- Action: Follow up on any public incidents to understand scope

**Method 5: Performance Metrics Tracking (Quarterly)**
- Track vendor SLA compliance (uptime, response time)
- Monitor mean time to respond (MTTR) to security issues
- Track number of vulnerabilities found and time to remediate
- Tools: Vendor performance dashboard, automated metrics collection

**Method 6: Quarterly Business Review (QBR)**
- Schedule quarterly meeting with vendor security leadership
- Review: Recent incidents, vulnerabilities, certifications, improvements
- Discuss: Changes in architecture, new services, risk changes
- Document: Meeting notes and any action items

**Escalation Threshold:**
- Any security issue detected → escalate immediately to CISO
- SLA miss → escalate to vendor management team
- Certification lapse → escalate to steering committee

---

### HIGH Vendors - Semi-Annual Monitoring

**Monitoring Frequency:** Every 6 months (2x per year)

**Monitoring Methods:**

**Method 1: Vulnerability Assessment (Semi-Annual)**
- Frequency: Twice per year
- Scope: External vulnerability assessment (similar to CRITICAL)
- Tools: Automated vulnerability scanning
- Action: Track and remediation follow-up

**Method 2: Breach Database Monitoring (Quarterly)**
- Check for vendor in breach databases quarterly
- Tools: Automated monitoring or manual checks
- Action: Escalate if breach detected

**Method 3: Certification Verification (Semi-Annual)**
- Verify certifications are current (SOC 2, ISO 27001, etc.)
- Request updated reports when available
- Action: Notify if renewal approaching

**Method 4: Performance Review (Semi-Annual)**
- Review SLA compliance and incident response times
- Conduct semi-annual business review
- Discuss: Performance, any incidents, changes

**Escalation Threshold:**
- Security incident or data breach → immediate escalation
- SLA miss (repeated) → escalate to steering committee
- Certification issues → escalate to vendor management

---

### MEDIUM Vendors - Annual Monitoring

**Monitoring Frequency:** Once per year

**Monitoring Methods:**

**Method 1: Annual Assessment (Full Assessment)**
- Conduct abbreviated questionnaire reassessment (same as initial)
- Request updated certifications
- Review performance over past year
- Tools: Streamlined questionnaire (15-20 questions)

**Method 2: Breach Database Check (Annual)**
- Check if vendor appears in breach databases
- Action: Escalate if breach detected

**Method 3: SLA Compliance Review (Annual)**
- Review performance metrics for the year
- Document any SLA misses or incidents
- Provide feedback to vendor

**Escalation Threshold:**
- Data breach → immediate escalation
- Multiple SLA misses → escalate to vendor management
- Significant control gaps in reassessment → escalate for remediation

---

### LOW Vendors - Biennial Monitoring

**Monitoring Frequency:** Every 2 years

**Monitoring Methods:**

**Method 1: Basic Verification (Biennial)**
- Verify vendor is still in business (check website, financials)
- Confirm contact information is current
- Tools: Simple vendor status check

**Method 2: Breach Database Check (Annual)**
- Check if vendor appears in breach databases
- Action: Escalate if breach detected

**Escalation Threshold:**
- Data breach (rare for LOW vendors) → escalate
- Vendor out of business → remove from vendor list

---

## Part 2: Automated Monitoring Tools & Setup

### Tool 1: Vulnerability Scanning Service

**What It Does:** Automatically scans vendor infrastructure for known vulnerabilities

**Setup:**
1. Identify vendor IP ranges or domains to scan
2. Get approval from vendor (must be in contract)
3. Set up monthly automated scans
4. Configure alerts for Critical/High findings

**Tools Options:**
- Qualys Cloud Platform
- Rapid7 InsightVM
- Tenable Nessus
- AWS Inspector (if vendor uses AWS)

**Cost:** $500-$5,000/month depending on scope

**Actions on Findings:**
- Critical: Contact vendor within 24 hours
- High: Within 1 week
- Medium: Within 30 days

---

### Tool 2: Breach Database Monitoring

**What It Does:** Monitors if vendor email/data appears in public breach databases

**Setup:**
1. Identify vendor contact emails (security team, key executives)
2. Subscribe to breach monitoring service
3. Receive alerts if emails appear in breaches
4. Follow up with vendor for details

**Tools Options:**
- Have I Been Pwned (HIBP)
- Breach Directory
- Dark Web monitoring services (Flashpoint, Digital Shadows)
- Automated email monitoring (integrated into security platform)

**Cost:** Free to $10,000+/year depending on service level

**Actions on Detection:**
- Confirm what was exposed
- Ask vendor for incident response details
- Assess impact to your organization

---

### Tool 3: Certification Tracking System

**What It Does:** Tracks expiration dates of vendor certifications

**Setup:**
1. Create spreadsheet or database with vendor certifications
2. Record certification type (SOC 2 Type II, ISO 27001, etc.)
3. Record expiration date
4. Set up calendar alerts for 60 days before expiration

**Data Points:**
- Vendor name
- Certification type
- Date obtained
- Date expires
- Renewal status
- Report location/access

**Manual Process:**
- Monthly: Check expiring certifications
- 90 days before expiration: Contact vendor for renewal
- 30 days before expiration: Escalate if not renewed
- Upon renewal: Update tracking system with new report

**Automated Tools:**
- Jira/ServiceNow for ticket tracking
- Excel with conditional formatting
- Dedicated vendor management platform

---

### Tool 4: Vendor Performance Dashboard

**What It Does:** Tracks vendor SLA compliance and incident metrics

**Metrics to Track:**

| Metric | Target | Frequency |
|--------|--------|-----------|
| Uptime SLA Compliance | 99.95%+ | Monthly |
| Mean Time to Respond (MTTR) | <1 hour (CRITICAL alerts) | Per incident |
| Mean Time to Detect (MTTD) | <24 hours | Monthly |
| Incident frequency | <1 incident/month (for CRITICAL vendors) | Monthly |
| Vulnerability remediation time | <30 days for High vulns | Monthly |
| Patch deployment time | Per SLA | Monthly |

**Data Sources:**
- Vendor status pages
- Incident tickets
- Vulnerability scan results
- Vendor reports

**Dashboard Visualization:**
- Green: Vendor meeting all targets
- Yellow: Vendor missing some targets (monitor)
- Red: Vendor failing to meet SLA (escalate)

---

### Tool 5: Incident Tracking & Response

**What It Does:** Tracks vendor security incidents and our response

**Setup:**
1. Create incident record when vendor announces incident
2. Document: What happened, what data affected, timeline, vendor's response
3. Track: Timeline of vendor's incident response (detection → response → remediation)
4. Assess: Impact to your organization
5. Close: Once resolved and lessons learned documented

**Data Points Per Incident:**
- Incident date & discovery date
- Vendor name & affected service
- Type of incident (breach, outage, malware, etc.)
- Data affected (your data? customer data? internal only?)
- Timeline: Detection → first response → containment → resolution
- Root cause
- Vendor's remediation steps
- Your assessment: Impact to you, lessons learned
- Follow-up actions

**Escalation:**
- Any incident involving your data → immediate escalation to CISO
- Incident affecting service availability → escalate to business owner
- Repeated incidents from same vendor → escalate to steering committee

---

## Part 3: Monitoring Procedures by Scenario

### Scenario 1: Vendor Vulnerability Found During Scan

**Situation:** Monthly vulnerability scan finds a High-severity vulnerability in CRITICAL vendor's infrastructure

**Procedure:**

**Step 1: Document (Same Day)**
- Record vulnerability details (CVE, CVSS score, description)
- Determine if it affects your data/systems
- Check if vendor is aware of vulnerability

**Step 2: Contact Vendor (24 Hours)**
- Email or call vendor security contact
- Describe vulnerability
- Request remediation timeline
- Ask for updates on remediation status

**Step 3: Track Remediation (Ongoing)**
- Set follow-up date (e.g., 7 days later)
- Re-scan to confirm remediation
- Document closure

**Step 4: Escalate if Needed (If Not Resolved)**
- If no response in 24 hours → escalate to vendor CISO
- If no remediation plan in 48 hours → escalate to steering committee
- If not remediated in agreed timeline → contract review/termination consideration

**Example Record:**
```
Vendor: AWS
Finding: CVE-2024-XXXXX (SQL Injection, CVSS 8.5)
Date Detected: Jan 15, 2026
Affected: Possibly our data (in RDS database)
Action Taken: Contacted AWS security team Jan 15
AWS Response: Acknowledged, patch deployed Jan 18
Re-scan Confirmed: Remediated Jan 19
Status: CLOSED
```

---

### Scenario 2: Vendor Appears in Breach Database

**Situation:** Breach monitoring service alerts that vendor (Slack) appears in a data breach database

**Procedure:**

**Step 1: Verify (Same Day)**
- Confirm what data was exposed
- Determine if it includes your data or customer data
- Check vendor's official announcement

**Step 2: Contact Vendor (24 Hours)**
- Ask vendor for official incident details
- Understand scope: Who was affected? What data?
- Ask for timeline: When discovered? When disclosed?

**Step 3: Assess Impact (24-48 Hours)**
- Does the breach affect your data?
- If yes, what data was exposed?
- Customer impact? Regulatory impact?

**Step 4: Notify Stakeholders (If Needed)**
- If your data affected: Notify CISO, steering committee
- If customer data affected: Notify customers per SLA
- Document notification timeline and recipients

**Step 5: Close Incident (Once Resolved)**
- Document vendor's remediation steps
- Record impact assessment
- Update vendor risk score if needed

**Escalation:**
- Breach involving your data → CISO immediately
- Breach involving customer data → Legal/Compliance immediately
- Repeated breaches from same vendor → Consider replacement

---

### Scenario 3: Vendor Certification Expires

**Situation:** SOC 2 Type II certification for CRITICAL cloud vendor (AWS) expires in 30 days

**Procedure:**

**Step 1: Alert (60 Days Before Expiration)**
- Calendar alert triggers
- Contact vendor: "Your SOC 2 report expires on [date]. Please provide renewal."

**Step 2: Follow-Up (30 Days Before Expiration)**
- If no new report received: Send second request
- Escalate to vendor management team

**Step 3: Escalate (At Expiration)**
- If certification not renewed: Escalate to steering committee
- May require:
  - Contract amendment
  - Risk acceptance decision
  - Vendor termination

**Step 4: Update (Upon Renewal)**
- Receive new certification report
- Verify it's current
- Update certification tracking
- Review for any control changes

**Example Timeline:**
```
April 1: SOC 2 expires (60 days = Feb 1)
Feb 1: Send request for renewal
Feb 28: Follow-up if not received (30 days remaining)
March 31: Escalate if still not provided
April 1: Certification expired - escalate to board
April 15: New report received, crisis averted
```

---

### Scenario 4: Vendor SLA Miss

**Situation:** CRITICAL vendor's uptime SLA is 99.95%, but they had 3 hours downtime (99.83% that month)

**Procedure:**

**Step 1: Document (Upon Detection)**
- Record downtime incident
- Calculate impact: hours down × users/services affected
- Cost of downtime (business impact)

**Step 2: Contact Vendor (Within 24 Hours)**
- Ask about incident
- Request post-mortem/root cause analysis
- Understand steps to prevent recurrence

**Step 3: Review SLA Credits (If Applicable)**
- Most contracts include SLA credits for misses
- Calculate credit owed (often 5-10% of monthly fee)
- Request vendor apply credit to next invoice

**Step 4: Track Trends (Monthly)**
- Month 1: 99.83% (0.12% miss) - Monitor
- Month 2: 99.90% (0.05% miss) - Improving, still monitor
- Month 3: 99.95% (on target) - Acceptable

**Step 5: Escalate if Pattern (If Multiple Misses)**
- If vendor misses SLA in 3+ months: Escalate to steering committee
- May require:
  - Formal improvement plan
  - Increased monitoring
  - Vendor replacement consideration

---

## Part 4: Re-Assessment Schedule

### When to Re-Assess Vendors

**CRITICAL Vendors:**
- **Annual full reassessment** (update questionnaire, verify controls)
- Plus **quarterly monitoring** (see Part 1)
- Trigger for emergency re-assessment: Any security incident, major architecture change, failed audit

**HIGH Vendors:**
- **Biennial reassessment** (every 2 years)
- Plus **semi-annual monitoring** (see Part 1)
- Trigger for emergency re-assessment: Security incident, failed certification renewal

**MEDIUM Vendors:**
- **Biennial reassessment** (every 2 years)
- Plus **annual monitoring** (see Part 1)

**LOW Vendors:**
- **Triennial reassessment** (every 3 years)
- Plus **biennial monitoring** (see Part 1)

### Re-Assessment Process

**Step 1: Schedule (60 Days in Advance)**
- Contact vendor
- Propose reassessment date
- Request questionnaire completion within 2 weeks

**Step 2: Conduct (Similar to Initial Assessment)**
- Send questionnaire
- Collect evidence
- Schedule interviews if needed
- Document findings

**Step 3: Score (Apply Phase 1 Risk Framework)**
- Calculate new risk score (Likelihood, Impact, Regulatory Exposure)
- Compare to previous score
- Note improvements or deterioration

**Step 4: Report (Generate Reassessment Report)**
- Executive summary: Risk score change
- Key improvements noted
- New findings/gaps identified
- Updated remediation plan if needed

**Step 5: Update (Document in Tracking System)**
- Update vendor risk score
- Update next reassessment date
- Update monitoring procedures if risk level changed

---

## Part 5: Escalation Procedures

### Escalation Levels & Decision Authority

**Level 1: Operational (Vendor Manager)**

| Finding | Action | Timeline |
|---------|--------|----------|
| Low-severity vulnerability found | Contact vendor, request remediation plan | 48 hours |
| Minor SLA miss (1-2 times/year) | Discuss with vendor, track trend | Ongoing |
| Certification expiring (>90 days) | Send renewal request | 60 days before expiration |
| Certification update received | Review and update records | Upon receipt |

**Authority:** Vendor Manager can approve remediation timelines up to 30 days

---

**Level 2: Steering Committee (CISO, Procurement, CRO)**

| Finding | Action | Timeline |
|---------|--------|----------|
| High-severity vulnerability (not remediated in 7 days) | Escalate, demand remediation plan | 7 days |
| Repeated SLA misses (3+ in 6 months) | Formal improvement plan required | 14 days |
| Certification lapse (expired) | Review contract terms, risk acceptance | Immediate |
| Security incident involving vendor | Full investigation, impact assessment | 24-48 hours |
| Vendor data breach affecting your data | CISO leads response, notify customers if needed | Immediate |

**Authority:** Steering Committee can approve remediation up to 90 days, require vendor improvements, consider contract renegotiation

---

**Level 3: Board / Executive (Board Risk Committee)**

| Finding | Action | Timeline |
|---------|--------|----------|
| Critical security incident affecting business | Board notification, executive response | Immediate |
| Vendor with repeated critical failures | Contract termination decision | Emergency meeting |
| Vendor loss of critical certification | Risk acceptance decision | Within 48 hours |
| Supply chain attack via vendor | Full escalation, business continuity activation | Immediate |

**Authority:** Board approves vendor termination, major contract changes, business continuity activations

---

### Escalation Path Example

```
SCENARIO: CRITICAL vendor's SOC 2 certification expires, no renewal

Day 1 (Expiration): Vendor Manager notifies CISO
    ↓
Day 2: CISO contacts vendor demanding renewal within 7 days
    ↓
Day 9 (No renewal): Escalate to Steering Committee
    ↓
Steering Committee decides:
  Option A: Risk acceptance (temporary, with mitigation)
  Option B: Require interim audit before expiration
  Option C: Initiate vendor replacement process
    ↓
Day 15: Board notified of decision
    ↓
Day 30+: Execute decision (new cert obtained OR vendor replaced)
```

---

## Part 6: Vendor Relationship Management

### Quarterly Business Review (QBR) - CRITICAL Vendors

**Frequency:** Quarterly (4 times per year)

**Participants (From Your Side):**
- CISO or Security Lead
- Vendor Manager
- Key business owner (procurement, operations)

**Participants (From Vendor):**
- Vendor CISO or Security Lead
- Vendor account manager
- Vendor technical lead

**Meeting Duration:** 1-2 hours

**Agenda:**

| Topic | Discussion | Duration |
|-------|-----------|----------|
| Security Incidents | Any incidents in past quarter? How responded? Lessons learned? | 15 min |
| Vulnerabilities | Any vulnerabilities found? Remediation status? | 10 min |
| Certifications | SOC 2 status? Any upcoming expirations? | 5 min |
| Performance | SLA compliance? MTTR/MTTD metrics? | 10 min |
| Roadmap | Any architecture changes? New services? Security updates planned? | 10 min |
| Escalations | Any outstanding issues from previous quarter? | 10 min |

**Deliverables:**
- Meeting notes documented
- Action items assigned with owners and due dates
- Issues log updated

**Example Output:**
```
QBR - AWS - Q2 2026

Incidents: 1 minor outage (30 min), quickly resolved
Vulnerabilities: 2 High found and patched, 0 Critical
Certifications: SOC 2 Type II current through 2027
Performance: 99.98% uptime (exceeds 99.95%), avg MTTR 2 hours
Roadmap: Migrating to new region, security review in progress
Action Items:
  - AWS to provide new region security assessment by Q3
  - Our team to review and approve by Q3 end
```

---

### Semi-Annual Business Review (SBR) - HIGH Vendors

**Frequency:** Twice per year

**Similar to QBR but less frequent**

**Focus:** Performance review, any escalations, upcoming changes

---

### Annual Review - MEDIUM Vendors

**Frequency:** Once per year

**Format:** Less formal than QBR, primarily focused on reassessment

---

## Part 7: Executive Reporting & KPIs

### Monthly Dashboard (Risk Operations)

**Key Metrics:**

| Metric | Status | Trend |
|--------|--------|-------|
| Total vendors monitored | 287 | ↑ +5 new vendors |
| Vendors with current certifications | 278 (97%) | ↔ Stable |
| Monitoring findings this month | 8 | ↑ +2 from last month |
| Critical findings open | 1 | ↓ (resolved 2) |
| High findings open | 3 | ↔ Stable |
| SLA misses this month | 2 | ↔ Historical average |
| Breaches affecting us | 0 | ✓ Clean |

**Actions Needed:**
- 1 Critical vulnerability (Payment Processor) - Escalate
- 3 High findings - Monitor remediation

---

### Quarterly Executive Report (Board/Steering Committee)

**Format:** 1-2 page executive summary

**Contents:**

**Section 1: Vendor Risk Portfolio (Current State)**
- Total vendors: 287
- Risk distribution: 12 CRITICAL, 35 HIGH, 85 MEDIUM, 155 LOW
- Vendors in acceptable risk state: 282 (98%)
- Vendors with findings requiring remediation: 5 (2%)

**Section 2: Key Incidents & Escalations**
- Any breaches affecting your data: 0
- Certification lapses: 0
- Repeated SLA misses: 1 vendor (plan to address in Q3)
- Critical vulnerabilities found: 2 (both remediated)

**Section 3: Program Health**
- Assessments completed this quarter: 21
- Monitoring findings resolved: 34
- On schedule to complete all HIGH vendor assessments by end of Q2

**Section 4: Risk Trends**
- Vendor security posture: Improving (fewer findings, better SLA compliance)
- Certification compliance: 97% of vendors current on certifications
- Incident trend: Down 15% from Q1

**Section 5: Recommendations & Actions**
- Continue current monitoring procedures
- Address 1 HIGH vendor's repeated SLA misses with improvement plan
- Approve budget for breach database monitoring expansion

---

### Annual Vendor Risk Portfolio Report

**Comprehensive annual review for board & executive leadership**

**Contents:**

1. **Program Overview**
   - Program maturity progress
   - Assessment completion rate
   - Monitoring effectiveness

2. **Vendor Risk by Criticality**
   - CRITICAL vendors: Status, incidents, certifications
   - HIGH vendors: Status, findings, remediation
   - MEDIUM & LOW: Summary stats

3. **Key Metrics**
   - Vendor SLA compliance trends
   - Incident frequency & response times
   - Vulnerability findings & remediation rates
   - Certification renewal success rate

4. **Major Events**
   - Any significant breaches or incidents
   - Vendor changes (additions, terminations)
   - Certification lapses (if any)
   - Notable improvements or concerns

5. **Lessons Learned**
   - What worked well
   - What could improve
   - Process improvements planned for next year

6. **Budget & Resource Needs**
   - Current monitoring tool costs
   - Recommended budget for next year
   - Resource needs (staffing, tools)

---

## Part 8: Monitoring Metrics & KPIs

### Program Health Metrics

| KPI | Target | Frequency | Owner |
|-----|--------|-----------|-------|
| Assessment completion rate | 100% on schedule | Monthly | Vendor Manager |
| Monitoring findings response time (Critical) | <24 hours | Per finding | CISO |
| Monitoring findings response time (High) | <7 days | Per finding | Vendor Manager |
| SLA compliance rate | 95%+ vendors meeting SLA | Monthly | Operations |
| Certification currency | 98%+ vendors with current certs | Monthly | Risk Operations |
| Remediation closure rate | 100% of findings tracked to closure | Quarterly | Vendor Manager |
| Escalation accuracy | 100% of critical issues escalated | Ongoing | CISO |

### Vendor Performance Metrics

| Metric | Target | Measurement |
|--------|--------|-------------|
| Mean Time to Detect (MTTD) | <24 hours | Per incident |
| Mean Time to Respond (MTTR) | <1 hour (CRITICAL) | Per incident |
| Uptime SLA | 99.95%+ | Monthly |
| Vulnerability remediation time | <30 days for High | Per vulnerability |
| Patch deployment time | Per SLA | Per patch |
| Certification renewal rate | 100% on schedule | Annual |
| Breach notification compliance | 100% compliance | Per breach |

---

## Part 9: Monitoring Tools Procurement

### Recommended Tools by Function

**Vulnerability Scanning:** Qualys, Rapid7, Tenable - $3K-$10K/month

**Breach Monitoring:** Have I Been Pwned, Flashpoint, Digital Shadows - $500-$5K/month

**Certification Tracking:** Custom spreadsheet (free) or Jira/ServiceNow ($2-5K/month)

**Performance Monitoring:** Vendor dashboards (many included free), custom dashboards - $0-$3K/month

**Incident Management:** Jira, ServiceNow - $2-5K/month

**Total Annual Cost (Estimate):** $15K-$60K/year depending on organization size and tool selection

---

**Phase 4 Complete. This concludes the 4-phase TPRM program.**
