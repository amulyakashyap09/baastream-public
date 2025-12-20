# BaaStream ⚕️ — Healthcare API Risk & Compliance Scanner

Transform reactive compliance into proactive risk prevention. BaaStream continuously scans your APIs, infrastructure-as-code, and logs against healthcare-grade controls (HIPAA, HITRUST, SOC 2, ISO 27001, GDPR, FHIR, PCI-DSS) to catch issues before they become costly incidents or failed audits.

> Legal note: BaaStream identifies technical risks and control gaps. It does not provide legal advice or guarantee compliance outcomes. More information read: www.baastream.com/legal

---

## 💼 Executive Summary
- Reduce breach and audit failure risk with automated scanning and clear remediation.
- Shorten audits from weeks to days with evidence-ready reporting (JSON, CSV, PDF, summaries).
- Integrate in hours, not months: CLI-first, CI/CD plugins, and dashboard upload-ready.
- Outcome-focused: fewer incidents, faster audits, lower compliance cost.

---

## 🧰 What BaaStream Does
- Scans infrastructure configs, CI/CD workflows, and logs for misconfigurations, missing controls, and PHI/PII exposure risks.
- Maps findings to frameworks (HIPAA, HITRUST, SOC 2, ISO 27001, GDPR, FHIR, PCI-DSS) with remediation guidance.
- Generates executive-friendly reports and engineering-ready action lists.
- Extensible via plugins (GitHub Actions, Jenkins, Terraform) and custom rules.

Who it’s for: CTO/CISO/VP Eng at healthtech, payors/providers, digital health, and any API-driven product handling PHI/PII or payment data.

---

## 💰 Business Outcomes & Savings

### The cost of not knowing
- HIPAA breach penalties and settlement costs: $4.2M average major event
- SOC 2 failures and remediation: $2.1M average per cycle
- Infra misconfig incidents (secrets exposure, logging gaps): $2.4M average
- Incident response & downtime: $2.5M average per severe incident

### How BaaStream creates value
- Early detection of control gaps (before audit) → avoid rework and delays
- Continuous scanning in CI/CD → prevent risky changes from shipping
- Evidence-ready reporting → shorter audits, fewer external consulting hours
- PHI/PII redaction and logging validation → reduce exposure and breach scope

### Illustrative annual savings

<table>
  <thead>
    <tr>
      <th>Category</th>
      <th>Without BaaStream</th>
      <th>With BaaStream</th>
      <th>Estimated Savings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>HIPAA breach exposure</td>
      <td>$4.2M average</td>
      <td>Early detection, redaction, logging</td>
      <td>$3.8M+</td>
    </tr>
    <tr>
      <td>SOC 2 remediation</td>
      <td>$2.1M</td>
      <td>Proactive control checks</td>
      <td>$1.9M+</td>
    </tr>
    <tr>
      <td>Misconfig incidents</td>
      <td>$2.4M</td>
      <td>Automated validation</td>
      <td>$2.2M+</td>
    </tr>
    <tr>
      <td>Logging/audit gaps</td>
      <td>$1.8M</td>
      <td>Complete audit trail</td>
      <td>$1.6M+</td>
    </tr>
  </tbody>
  
</table>

Conservative outcome for a mid-size org: $1.0M–$3.0M avoided costs/year. For startups: faster enterprise sales and reduced audit lift.

### Quick ROI calculator
- Inputs: Annual audits (n), external audit hours (h), rate ($/hr), avg incidents avoided (k), incident cost ($)
- ROI ≈ [ (h × rate × n) + (k × incident cost) + (engineering hours saved) ] − BaaStream subscription
- Typical teams see payback in 1–3 months.

---

## ✨ Why BaaStream (Differentiators)
- Healthcare-grade rules out of the box: HIPAA, HITRUST, FHIR, PCI-DSS (in addition to SOC 2/ISO/GDPR)
- Deep log validation: PHI redaction checks, FHIR access patterns, audit trail completeness
- CI/CD and IaC coverage: GitHub Actions, Jenkins, Terraform
- Multi-output reports (JSON, CSV, PDF, executive summary) for auditors and engineers
- Extensible rules and plugins; easy custom rules for your environment
- Developer-first CLI with dashboard upload capability

See `docs/README.md` in the repository root for the complete rule catalog and examples.

---

## 📦 What’s Included (at a glance)
- 150+ rules across HIPAA, HITRUST, SOC 2, ISO 27001, GDPR, FHIR, PCI-DSS, API Security, Cloud Security, Log Access/Integrity, Data Governance, Encryption, Redaction
- Plugins: GitHub Actions, Jenkins, Terraform (more planned)
- Formats: JSON, CSV, PDF, human-readable summaries
- Filters: by severity, framework, tags, rule IDs
- Example datasets and sample configs for quick validation (see `examples/`)

---

## ⚙️ How It Works
1. Point BaaStream at your config/logs/IaC
2. Select rule sets (e.g., HIPAA + SOC 2 + PCI) and severity filters
3. Run locally or in CI/CD; optionally upload results to the dashboard
4. Get prioritized findings, remediation, and framework mapping

---

## 🔌 Integrations
- CI/CD: GitHub Actions, Jenkins (pipeline checks, secrets, permissions)
- IaC: Terraform (resource, state, variable, provider security)
- Cloud/Healthcare APIs: AWS HealthLake, Azure Health Data Services, Google Cloud Healthcare API (log requirements, identity, retention, private connectivity)

---

## 🔒 Security & Privacy
- No production traffic interception; scan artifacts you choose (configs, logs)
- PHI/PII redaction checks and secure handling guidance
- Evidence export for auditors without exposing sensitive data (CSV/PDF with selective fields)
- Supports least-privilege operational models

Note: Always review outputs before sharing with external parties. See `docs/legal.md`.

---

## 📜 Compliance Coverage (Selected)
- HIPAA/HITRUST: audit logging, access controls, transmission security, PHI handling
- SOC 2/ISO 27001: logging/monitoring, change management, backups, business continuity
- GDPR: data minimization, breach detection, consent, cross-border controls
- FHIR: resource validation, authentication, scopes, headers, audit logging
- PCI-DSS: PAN/CVV protections, encryption, webhook security, rate limiting

Refer to `rules/*.yaml` for full details.

---

## 🚀 Key Features

- 🔍 Rule Engine: 150+ rules for infrastructure and log pattern validation across HIPAA, GDPR, SOC 2, HITRUST, ISO 27001, FHIR, PCI-DSS, and security best practices
- 🔌 Plugin Architecture: Extensible CI/CD and infrastructure integrations
- 📊 Multiple Output Formats: JSON, CSV, PDF, and human-readable summaries
- 🎯 Targeted Scanning: Scan specific rules by ID or category
- 📝 Log Analysis: Advanced log pattern validation for potential technical risks
- 🏗️ Infrastructure Scanning: Terraform, GitHub Actions, and Jenkins support
- ⚡ Developer-First: CLI tool with CI/CD integration

---

## 📊 Infrastructure & Log Scanning Coverage

| Framework | Rules | Scope | Key Areas |
|-----------|-------|-------|-----------|
| **HIPAA** | 8 rules | Infrastructure & Logs | PHI protection patterns, access control configs, audit logging patterns |
| **GDPR** | 8 rules | Infrastructure & Logs | Data minimization configs, consent patterns, breach detection logs |
| **SOC 2** | 10 rules | Infrastructure & Logs | Access control configs, monitoring setup, incident response logs |
| **HITRUST** | 10 rules | Infrastructure & Logs | PHI protection configs, authentication setup, transmission security |
| **ISO 27001** | 15 rules | Infrastructure & Logs | ISMS governance, security controls, risk management, compliance |
| **FHIR** | 15 rules | Infrastructure & Logs | FHIR resource validation, authentication, encryption, audit logging |
| **PCI-DSS** | 12 rules | Infrastructure & Logs | Payment data protection, tokenization, access controls, encryption |
| **API Security** | 10 rules | Infrastructure & Logs | Authentication configs, encryption setup, rate limiting patterns |
| **Data Governance** | 10 rules | Infrastructure & Logs | Classification configs, encryption setup, access control patterns |
| **Cloud Security** | 10 rules | Infrastructure & Logs | Access management configs, network security, secrets management |
| **Log Access Control** | 12 rules | Infrastructure & Logs | IAM roles, least privilege, access monitoring, time restrictions |
| **Log Integrity** | 12 rules | Infrastructure & Logs | WORM storage, hash verification, digital signatures, tamper detection |
| **HealthLake** | 11 rules | Infrastructure & Logs | CloudTrail configuration, FHIR logging, user identity, retention policies |
| **Google Cloud Healthcare** | 13 rules | Infrastructure & Logs | Cloud Audit Logs, KMS encryption, VPC Service Controls, FHIR patterns |
| **Azure Health Data Services** | 12 rules | Infrastructure & Logs | Activity Logs, Diagnostic Settings, Private Endpoints, Managed Identity |
| **Authentication Security** | 8 rules | Infrastructure & Logs | Multi-factor auth, session management, identity verification patterns |
| **Audit Logs** | 7 rules | Infrastructure & Logs | Comprehensive audit logging, event capture, compliance reporting |
| **Log Validation** | 10 rules | Infrastructure & Logs | Log format validation, completeness checks, integrity verification |
| **Unstructured Logs** | 2 rules | Infrastructure & Logs | Apache logs, custom log formats, legacy system compatibility |
| **Healthcare Specific** | 8 rules | Infrastructure & Logs | Healthcare-specific compliance patterns, PHI handling, clinical workflows |
| **Encryption** | 4 rules | Infrastructure & Logs | End-to-end encryption, key management, algorithm compliance |
| **Data Redaction** | 4 rules | Infrastructure & Logs | PHI redaction, anonymization, log sanitization, access control |

---

## ⏱️ Implementation & Timeline
- Time-to-value: 30–90 minutes for initial CLI scans; 0.5–1 day for CI/CD rollout
- Typical steps:
  - Build CLI and run first scans on sample data (`examples/`)
  - Choose frameworks and severity filters
  - Enable relevant plugins (GitHub Actions/Terraform)
  - Integrate into CI/CD with pass/fail thresholds
  - Export reports for audit readiness

---

## 💳 Pricing & Plans
Tiered subscriptions from Community (free) to Healthcare Enterprise, covering users, scans, plugins, analytics, and support SLAs. See pricing and tiers in the repository root `README.md` or contact us.

For procurement or volume licensing, contact `support@baastream.com`.

---

## 🏥 Case Studies (Illustrative)
- Healthcare startup (50 employees): avoided SOC 2 remediation delay; saved ~$450K and 6 months
- Mid-size health system: early PHI exposure detection; saved ~$2.7M and avoided sanctions
- API platform (200 employees): PCI checks maintained enterprise deals; saved ~$1.1M

---

## 🆚 Competitive Landscape (High-Level)
| Option | Pros | Cons |
| --- | --- | --- |
| Generic open-source scanners | Free; basic checks | Limited healthcare depth; no audit-ready outputs |
| Traditional GRC suites | Governance workflows | Slow to implement; weak code/log-level checks |
| BaaStream | Healthcare rules + CI/CD + logs + reports | Purpose-built; complements (not replaces) GRC |

BaaStream often runs alongside your SIEM and GRC to close the technical control gap.

---

## ➡️ Next Steps
- Review the root `README.md` → rule catalog and examples
- Try local scan: see `USAGE.md`
- Add CI/CD checks via plugins: see `plugins/README.md`
- Talk to us for a tailored ROI model: `support@baastream.com`

BaaStream — catch issues early, prove compliance faster, and protect patient trust.

---

## 🧪 End-to-End Workflow (Under the Hood)

- **1) CLI parses inputs and flags**
  - Reads flags like `-rules`, `-format`, `-severity`, `-tags`, `-type`, `-log-format`, `-custom-rules`, `-historical`, `-login`, `-setup-dashboard`, etc.
  - Supports listing rules and plugins, showing help/version, and authentication commands.

- **2) Engine initialization**
  - Creates the compliance engine (`engine.NewEngine()`), which instantiates the rule engine, scanner, and loads built-in plugins.
  - Plugins are loaded and available for info/extension; scanning uses the rule engine as the primary path.

- **3) Rules loading and selection**
  - If `-rules` is a directory/file: loads YAML rules via `LoadRules`.
  - If `-rules` is a specific ID (e.g., `AUDIT-001`): loads all, then selects only that rule.
  - Optional filters:
    - `-severity` to include only rules of that severity.
    - `-tags` to include only rules matching tags (e.g., `hipaa,gdpr`).

- **4) Input discovery and scan type detection**
  - Determines scan type: `auto|config|logs`. Auto uses extension heuristics.
  - If a directory: walks files matching extensions for the scan type.
  - If a single file: proceeds directly.

- **5) Log parsing (for -type logs)**
  - Detects format automatically (Apache, Nginx, JSON, structured, mixed, or custom).
  - Parses into structured entries; if parsing fails or no fields extracted, falls back to scanning raw text content.

- **6) Scanning and rule evaluation**
  - For each data item, builds a `ScanContext` and evaluates every loaded rule.
  - Rich condition operators supported: `equals`, `contains`, `in`, `regex`, comparison ops, `exists/not_exists`, nested fields via dot notation, and `and/or` logical groups.
  - Produces `pass/fail/error` results with severity, category, message, remediation, and data context.

- **7) Output generation**
  - Formats: `json`, `csv`, `pdf` (text-style summary currently), or `summary`.
  - Summary/analytics can incorporate `-historical` data for trend analysis.

- **8) Analytics and dashboards (when summary/analytics)**
  - Computes risk scores (overall, by severity/category/framework) and recommendations.
  - Generates a compliance dashboard object with top risks, quick wins, compliance rate, next scan suggestion, and trends.

- **9) Dashboard authentication and upload (optional)**
  - If not disabled (`-disable-upload` absent), validates authentication and plan limits.
  - Authentication options:
    - Firebase (browser PKCE or device code fallback; refresh tokens supported; mock mode for testing).
    - Legacy email/password (deprecated path retained for compatibility).
  - If valid and plan allows uploads, sends results + metadata to the dashboard API.
  - Graceful degradation: scan never fails solely due to auth/upload issues.

- **10) Exit codes**
  - `0`: all checks passed
  - `1`: one or more checks failed
  - `2`: an error occurred during scanning

### Typical Run (Putting it Together)
1) Load rules (or a specific rule ID), apply optional filters.
2) Detect scan type and enumerate inputs.
3) Parse logs (if applicable), with automatic format detection and fallback.
4) Evaluate all rules against each input; collect results.
5) Generate desired output format; optionally compute analytics and trends.
6) Validate auth and plan; if eligible, upload results to the dashboard.
7) Return appropriate exit code for CI/CD gating.

## 📞 Contact For Demo
- **Contact Us**: support@baastream.com
- **Website**: [https://baastream.com](https://baastream.com)
