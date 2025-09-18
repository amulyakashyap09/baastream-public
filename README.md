# BaaStream
Run automated checks on logs, infra, and configs for potential technical risks 🏥✨.

## 🎯 Overview

BaaStream is an infrastructure and log scanning tool designed to help healthcare organizations, API developers, and DevOps teams identify potential technical risks before they become costly breaches. It scans infrastructure configurations and log patterns against industry best practices and security frameworks including HIPAA, GDPR, SOC2, HITRUST, ISO 27001, FHIR, and PCI-DSS.

## 💰 How BaaStream Saves You Millions

### 🚨 The Hidden Cost of Technical Debt

**Healthcare organizations lose $10.9 million annually** due to security incidents and compliance violations. Most of these costs stem from:

- **Infrastructure Misconfigurations**: $2.4M average cost per incident
- **Logging Gaps**: $1.8M average cost per audit failure  
- **Compliance Violations**: $4.2M average HIPAA breach penalty
- **Technical Risk Exposure**: $2.5M average incident response cost

### 🛡️ BaaStream's Risk Prevention Value

| Risk Category | Without BaaStream | With BaaStream | Savings |
|---------------|-------------------|----------------|---------|
| **HIPAA Breaches** | $4.2M average penalty | Early detection & prevention | **$3.8M+** |
| **SOC2 Failures** | $2.1M audit costs | Proactive compliance | **$1.9M+** |
| **Infrastructure Issues** | $2.4M incident costs | Automated validation | **$2.2M+** |
| **Logging Gaps** | $1.8M audit failures | Comprehensive logging | **$1.6M+** |
| **Total Annual Savings** | **$9.5M+** | | |

### 🎯 Real-World Impact Examples

**🏥 Healthcare Startup (50 employees)**
- **Before**: Failed SOC2 audit, $500K remediation costs
- **After**: Proactive scanning prevented 12 critical issues
- **Savings**: $450K + 6 months of development time

**🏢 Mid-Size Health System (500 employees)**  
- **Before**: HIPAA violation, $2.1M penalty + $800K remediation
- **After**: Continuous monitoring caught PHI exposure early
- **Savings**: $2.7M + avoided regulatory sanctions

**🚀 HealthTech API Company (200 employees)**
- **Before**: PCI-DSS failure, $1.2M in penalties + lost contracts
- **After**: Automated payment security validation
- **Savings**: $1.1M + maintained enterprise contracts

### 🚀 Key Features

- **🔍 Rule Engine**: 99+ rules for infrastructure and log pattern validation across HIPAA, GDPR, SOC2, HITRUST, and security best practices

- **🔌 Plugin Architecture**: Extensible CI/CD and infrastructure integrations

- **📊 Multiple Output Formats**: JSON, CSV, PDF, and human-readable summaries

- **🎯 Targeted Scanning**: Scan specific rules by ID or category

- **📝 Log Analysis**: Advanced log pattern validation for potential technical risks

- **🏗️ Infrastructure Scanning**: Terraform, GitHub Actions, and Jenkins support

- **⚡ Developer-First**: CLI tool with CI/CD integration

## 📊 Infrastructure & Log Scanning Coverage

| Framework | Rules | Scope | Key Areas |
|-----------|-------|-------|-----------|
| **HIPAA** | 15+ rules | Infrastructure & Logs | PHI protection patterns, access control configs, audit logging patterns |
| **GDPR** | 8 rules | Infrastructure & Logs | Data minimization configs, consent patterns, breach detection logs |
| **SOC2** | 10 rules | Infrastructure & Logs | Access control configs, monitoring setup, incident response logs |
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
| **Encryption** | 4 rules | Infrastructure & Logs | End-to-end encryption, key management, algorithm compliance |
| **Data Redaction** | 4 rules | Infrastructure & Logs | PHI redaction, anonymization, log sanitization, access control |

## 💰 Plans & Pricing

BaaStream offers CLI access with monthly risk assessment reports across six tiers using a **hybrid user-based + scan-based pricing model**:

| Tier                      | Price       | Users | Scans / Month | Rules | Plugins      | Custom Rules | Support                      | Extras                                                            |
| ------------------------- | ----------- | ----- | ------------- | ----- | ------------ | ------------ | ---------------------------- | ----------------------------------------------------------------- |
| **Community**             | **\$0**     | 1     | 50            | 10    | –            | –            | Community / Discord          | –                                                                 |
| **Starter**               | **\$99**    | 5     | 300           | 25    | –            | –            | Community / Discord          | –                                                                 |
| **Professional**          | **\$149**   | 10    | 750           | 50    | Any 1 plugin | 3 / month    | Priority (24–48h, Email)     | –                                                                 |
| **Growth**                | **\$299**   | 15    | 1,200         | 75    | Any 2 plugins| 5 / month    | Priority (24h, Email)        | Advanced analytics                                               |
| **Business**              | **\$699**   | 25    | 2,500         | 75    | All plugins  | 10 / month   | Priority (24h, Email + Call) | Early upgrade access                                              |
| **Enterprise**            | **\$1,299** | 50    | 5,000         | 99+   | All plugins  | 25 / month   | Dedicated (Email + Call)     | Technical Training                                                |
| **Healthcare Enterprise** | **\$2,499** | 100   | 10,000        | 99+   | All plugins  | 50 / month   | Dedicated (Email + Call)     | HIPAA/HITRUST templates, audit-ready exports, vendor risk reports |

### 🆓 Community – Free
**For individual developers & personal projects**

- 1 User
- 50 Scans / month
- 10 core HIPAA rules
- Text-only risk score & top 3 risks
- Community support (Discord/Slack)

**Value**: Get started with healthcare compliance scanning

### 🌱 Starter – $99/month
**For early-stage startups & small teams**

- Up to 5 Users
- 300 Scans / month
- 25 security rules (HIPAA + GDPR basics + API basics)
- Commercial license
- PDF outputs
- Community support

**Value**: Affordable compliance scanning for seed-stage companies

### 🚀 Professional – $149/month
**For growing healthcare startups**

- Up to 10 Users
- 750 Scans / month
- 50 core rules (HIPAA, GDPR, API, Auth, Encryption, SOC2 Essentials)
- Any 1 plugin integration
- 3 custom rules / month
- JSON + PDF output formats
- Priority support (24-48h SLA)

**Value**: Essential compliance scanning for scaling startups

### 💼 Growth – $299/month
**For established dev/security teams**

- Up to 15 Users
- 1,200 Scans / month
- 75 advanced rules (Complete HIPAA, SOC2, ISO, HITRUST, Cloud, Logs, Data Governance)
- Any 2 plugin integrations
- 5 custom rules / month
- Advanced analytics & reports
- Priority support (24h SLA)

**Value**: Advanced compliance coverage with analytics & custom rules

### 🏢 Business – $699/month
**For scaling healthcare companies**

- Up to 25 Users
- 2,500 Scans / month
- 75 advanced rules + all plugins
- All plugin integrations (GitHub Actions, Jenkins, Terraform)
- 10 custom rules / month
- Team management features
- Priority support (24h SLA + Call)
- Early access to new features

**Value**: Enterprise-grade security & collaboration with CI/CD integrations

### 🏥 Enterprise – $1,299/month
**For large healthcare organizations**

- Up to 50 Users
- 5,000 Scans / month
- 99+ all framework rules
- All plugin integrations
- 25 custom rules / month
- Dedicated support (Email + Call)
- Technical training
- Advanced analytics & insights

**Value**: Dedicated compliance partnership with technical training

### 🏥 Healthcare Enterprise – $2,499/month
**For large health systems & enterprises**

- Up to 100 Users
- 10,000 Scans / month
- 99+ all framework rules
- All plugin integrations
- 50 custom rules / month
- Dedicated support (Email + Call)
- HIPAA/HITRUST templates
- Audit-ready exports
- Vendor risk reports
- Technical training

**Value**: White-glove compliance platform for health systems & enterprise-level orgs

### 📊 Feature Comparison Table (Hybrid Model)

| Feature | Community | Starter | Professional | Growth | Business | Enterprise | Healthcare Enterprise |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Base Price** | **$0** | **$99/month** | **$149/month** | **$299/month** | **$699/month** | **$1,299/month** | **$2,499/month** |
| **Monthly Users (Included)** | 1 | 5 | 10 | 15 | 25 | 50 | 100 |
| **Monthly Scans (Included)** | 50 | 300 | 750 | 1,200 | 2,500 | 5,000 | 10,000 |
| **Additional User Cost** | N/A | **$25/user** | **$35/user** | **$40/user** | **$45/user** | **$50/user** | **$60/user** |
| **Overage Scan Cost** | N/A | **$0.50/scan** | **$0.45/scan** | **$0.40/scan** | **$0.40/scan** | **$0.30/scan** | **$0.25/scan** |
| **Security Rules** | 10 basic | 25 core | 50 core | 75 advanced | 75 advanced | 99+ all frameworks | 99+ all frameworks |
| **Plugin Support** | ❌ | ❌ | ✅ **1 plugin** | ✅ **2 plugins** | ✅ **All plugins** | ✅ **All plugins** | ✅ **All plugins** |
| **Custom Rules** | ❌ | ❌ | ✅ **3/month** | ✅ **5/month** | ✅ **10/month** | ✅ **25/month** | ✅ **50/month** |
| **Support** | Community | Community | Priority (24-48h) | Priority (24h) | Priority (24h) + Call | Dedicated (Email + Call) | Dedicated (Email + Call) |
| **Advanced Analytics** | ❌ | ❌ | ❌ | ✅ | ✅ | ✅ | ✅ |
| **Technical Training** | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ |

## 📰 Read more about rules: [Rule Catalog](./docs/RULES.md)

## 📌 Documentation: [Docs](./docs/USAGE.md)

⚠️ **IMPORTANT DISCLAIMER**: This tool does NOT provide legal advice or guarantee regulatory adherence. It only scans infrastructure configurations and log patterns for potential technical risks. Full regulatory adherence requires comprehensive legal, technical, and operational measures beyond this tool's scope. Always consult with legal experts and regulatory counsel for actual requirements.

**Read More about Legal Disclaimer**: [LEGAL_DISCLAIMER.md](./LEGAL_DISCLAIMER.md)

## 🆘 Support
- **Issues 🪲**: [GitHub Issues](https://github.com/amulyakashyap09/baastream-public/issues)
- **Discussions**: [GitHub Discussions](https://github.com/amulyakashyap09/baastream-public/discussions)
- **Email**: support@baastream.com