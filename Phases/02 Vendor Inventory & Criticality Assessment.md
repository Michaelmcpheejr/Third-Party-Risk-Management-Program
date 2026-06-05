# Third-Party Risk Management & Vendor Governance Program

## Phase 2: Vendor Inventory & Criticality Assessment

**Organization:** [Client Enterprise / Federal Contractor]  
**Program Owner:** Chief Risk Officer & Procurement Director  
**Phase Duration:** Month 3-5  
**Key Outcome:** Complete vendor inventory with criticality scoring and portfolio analysis  

---

## Executive Summary

Phase 2 establishes a comprehensive vendor inventory and applies the criticality assessment framework from Phase 1. This phase answers critical questions:

- **How many vendors do we have?**
- **Who has access to what?**
- **Which vendors are CRITICAL vs. LOW-risk?**
- **Where are our biggest risks?**
- **How should we prioritize assessment efforts?**

**Key Objectives:**
1. Complete vendor discovery across the enterprise
2. Classify vendors by type and function
3. Apply multi-dimensional criticality assessment
4. Create vendor risk portfolio view
5. Develop executive dashboard for vendor risk oversight
6. Prioritize assessment and monitoring activities

**Key Outcomes:**
- Master vendor inventory (100-300+ vendors depending on organization size)
- Vendor criticality scoring (each vendor scored 1.0-3.0)
- Vendor risk portfolio analysis (distribution across criticality levels)
- Executive dashboard and reporting
- Assessment prioritization roadmap (which vendors to assess first)
- Data quality assessment (gaps in vendor information)

---

## Part 1: Vendor Discovery Process

### Step 1: Multi-Source Vendor Identification

**Source 1: Procurement System**
- Active contracts in procurement/finance system
- Vendor names, contract values, contract dates
- Procurement contact information
- Service descriptions

**Source 2: IT Asset Inventory**
- SaaS subscriptions (often scattered across departments)
- Cloud services (AWS accounts, Azure subscriptions)
- On-premise software licenses
- Infrastructure providers

**Source 3: Finance & Accounting**
- Vendor payments (accounts payable)
- Budget allocations
- Service contracts
- Master vendor list

**Source 4: Department Interviews**
- Business owners / department heads
- IT operations
- Security team
- HR / facilities
- Sales / customer success

**Source 5: Active Directory & Network**
- Connected vendors (VPN access, API integrations)
- Service accounts (technical integrations)
- Cloud provider identity (SSO, API keys)

**Source 6: Insurance & Legal**
- Insurance providers
- Legal vendors (law firms, paralegals)
- Audit firms
- Consultants

**Source 7: Existing Risk Registers**
- Known high-risk vendors
- Vendors flagged in audits
- Incident history
- Compliance assessments

### Step 2: Vendor Consolidation & Deduplication

**Challenge:** Same vendor appears under multiple names
- "Microsoft" vs. "Microsoft Corporation" vs. "Azure"
- "AWS" vs. "Amazon Web Services" vs. "Amazon Cloud"

**Process:**
1. Consolidate duplicate entries
2. Identify parent companies
3. Link related vendors
4. Create master vendor record with all aliases

### Step 3: Vendor Master Data Collection

**Core Information to Collect:**

| Field | Description | Source | Required |
|-------|-------------|--------|----------|
| Vendor ID | Unique identifier | Generated | Yes |
| Vendor Name | Official company name | Procurement | Yes |
| Primary Contact | Main business contact | Procurement | Yes |
| Technical Contact | Primary IT/security contact | IT ops | For critical |
| Service Type | What service does vendor provide? | Various | Yes |

---

## Part 2: Multi-Dimensional Criticality Scoring

### Dimension 1: Data Access Level (1-3 Scale)

| Score | Level | Criteria |
|-------|-------|----------|
| 3 | CUI/Sensitive | Access to CUI, PII, financial data |
| 2 | Internal Data | Access to internal emails, documents |
| 1 | No Data Access | No access to company data |

### Dimension 2: System Integration & Criticality (1-3 Scale)

| Score | Level | Criteria |
|-------|-------|----------|
| 3 | Critical Infrastructure | Essential to operations; systems down = business impact |
| 2 | Important Systems | Important but workarounds exist |
| 1 | Non-Critical | Not essential; easy to replace |

### Dimension 3: Strategic Value / Business Dependency (1-3 Scale)

| Score | Level | Criteria |
|-------|-------|----------|
| 3 | Strategic / Sole-Source | Only vendor for critical function; high switching costs |
| 2 | Important / Few Alternatives | Important but alternatives exist |
| 1 | Commodity / Easy Replace | Easy to replace |

### Criticality Score Calculation

**Formula:** (Data Access + Integration + Strategic Value) / 3

**Scale: 1.0 - 3.0**

| Score Range | Classification | Oversight Level |
|-------------|-----------------|-----------------|
| 2.7-3.0 | CRITICAL | Deep assessment, quarterly monitoring |
| 2.0-2.6 | HIGH | Comprehensive assessment, semi-annual monitoring |
| 1.4-1.9 | MEDIUM | Standard assessment, annual monitoring |
| 1.0-1.3 | LOW | Lightweight assessment, biennial review |

---

## Part 3: Sample Vendor Portfolio (Example Organization)

**Example Organization:** TechSecure Inc. (Federal Contractor, 500 employees, handles CUI)

**Total Vendors: 287**

| Criticality | Count | % |
|-------------|-------|---|
| CRITICAL | 12 | 4% |
| HIGH | 35 | 12% |
| MEDIUM | 85 | 30% |
| LOW | 155 | 54% |

### CRITICAL Vendors (Sample)

**CRIT-001: Amazon Web Services (AWS)**
- Data Access: 3 | Integration: 3 | Strategic Value: 3
- **Score: 3.0 (CRITICAL)**
- Assessment: Quarterly, SOC 2 Type II certified

**CRIT-002: Managed SOC Provider**
- Data Access: 3 | Integration: 3 | Strategic Value: 3
- **Score: 3.0 (CRITICAL)**
- Assessment: Quarterly, on-site audit required

**CRIT-003: Okta (Identity Provider)**
- Data Access: 3 | Integration: 3 | Strategic Value: 3
- **Score: 3.0 (CRITICAL)**
- Assessment: Quarterly, SOC 2 Type II certified

**CRIT-004: Salesforce**
- Data Access: 3 | Integration: 3 | Strategic Value: 3
- **Score: 3.0 (CRITICAL)**
- Assessment: Quarterly, SOC 2 Type II certified

**CRIT-005: GitHub Enterprise**
- Data Access: 3 | Integration: 3 | Strategic Value: 3
- **Score: 3.0 (CRITICAL)**
- Assessment: Quarterly, SOC 2 Type II certified

*(7 more CRITICAL vendors not listed)*

### HIGH Vendors (Sample)

**HIGH-001: Secondary Cloud Provider (Google Cloud)**
- Data Access: 2 | Integration: 2 | Strategic Value: 2
- **Score: 2.0 (HIGH)**
- Assessment: Semi-annual

**HIGH-002: Slack**
- Data Access: 2 | Integration: 2 | Strategic Value: 2
- **Score: 2.0 (HIGH)**
- Assessment: Semi-annual

**HIGH-003: Atlassian (Jira)**
- Data Access: 2 | Integration: 2 | Strategic Value: 2
- **Score: 2.0 (HIGH)**
- Assessment: Semi-annual

*(32 more HIGH vendors not listed)*

---

## Part 4: Assessment Prioritization Roadmap

### Phase 1: CRITICAL Vendors (Months 1-3)

**Priority:** Immediate

**Vendors:** 12 total

**Assessment Type:** Comprehensive
- Extended questionnaire (50+ questions)
- Evidence review
- Executive interviews
- Site assessment (for MSP, data center)

**Timeline:** 8 weeks

### Phase 2: HIGH Vendors (Months 4-6)

**Priority:** High

**Vendors:** 35 total

**Assessment Type:** Comprehensive
- 40-50 question questionnaire
- Evidence review
- Phone/video interviews (not on-site)

**Timeline:** 10 weeks

### Phase 3: MEDIUM Vendors (Months 7-12)

**Priority:** Medium

**Vendors:** 85 total

**Assessment Type:** Streamlined
- 15-20 question questionnaire
- Certification check only
- 1-2 page assessment per vendor

**Timeline:** 6 months

### Phase 4: LOW Vendors (Ongoing)

**Priority:** Low

**Vendors:** 155 total

**Assessment Type:** Lightweight
- Background check
- Certification check (if any)
- Annual review

---

## Part 5: Executive Dashboard & Reporting

### Dashboard 1: Vendor Risk Portfolio

**Key Metrics:**
- Total vendors: 287
- Vendors assessed: 45 (16%)
- CRITICAL vendors with SOC 2: 10/12 (83%)
- Vendors in acceptable risk state: 240 (84%)

**Visualization:**
- Pie chart: Criticality distribution
- Progress bar: Assessment completion
- Heat map: Vendor risk by type

### Dashboard 2: Assessment Progress

**Key Metrics:**
- CRITICAL vendors completed: 8/12 (67%)
- Average assessment time: 3 weeks
- Vendor response rate: 92%
- Outstanding follow-ups: 4

### Dashboard 3: Vendor Risk Heatmap

**Key Metrics:**
- Vendors in RED (unacceptable): 3
- Vendors in YELLOW (remediating): 8
- Vendors in GREEN (acceptable): 34

---

## Part 6: Success Metrics

### Phase 2 Completion Metrics

| Metric | Target |
|--------|--------|
| Vendor inventory complete | 100% identified |
| Criticality scoring complete | 100% of vendors |
| Assessment roadmap defined | Yes |
| Executive dashboards created | Yes |

### Ongoing Metrics

| Metric | Target | Owner |
|--------|--------|-------|
| Vendor master record accuracy | 98%+ | Vendor Manager |
| Assessment completion on schedule | 100% | Risk Operations |
| Dashboard currency | 100% current | Risk Operations |

---

**Phase 2 Complete. Ready for Phase 3: Vendor Assessment & Risk Scoring?**

> **"LOCK PHASE 2 AND PROCEED WITH PHASE 3"**
