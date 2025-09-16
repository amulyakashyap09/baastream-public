# 📋 Complete Rule Catalog

## 🆓 Free Tier Rules (rules/free)

### Audit Logs (`audit_logs.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `AUDIT-001` | Audit Logs Enabled | High | API endpoints must have audit logging enabled with proper format validation |
| `AUDIT-002` | Log Retention Period | Medium | Audit logs must be retained for minimum required period with automated cleanup |
| `AUDIT-003` | Log Format Validation | Medium | Audit logs must include required fields with proper validation patterns |

### Unstructured Logs (`unstructured_logs.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `LOG-APACHE-001` | Apache Log Format Compliance | Medium | Apache logs must include required fields for compliance |
| `LOG-CUSTOM-001` | Custom Log Format Compliance | Medium | Custom logs must include essential fields for compliance |

## 💎 Pro Tier Rules (rules/pro)

### GDPR Security (`gdpr.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `GDPR-001` | Data Minimization | High | Only collect necessary personal data |
| `GDPR-002` | Consent Management | Critical | Implement proper consent mechanisms |
| `GDPR-003` | Right to Erasure | High | Support data deletion requests |
| `GDPR-004` | Data Portability | Medium | Enable data export functionality |
| `GDPR-005` | Privacy by Design | High | Implement privacy controls by default |
| `GDPR-006` | Data Breach Notification | Critical | Implement breach detection and notification |
| `GDPR-007` | Data Processing Records | Medium | Maintain processing activity records |
| `GDPR-008` | Cross-Border Transfers | High | Ensure adequate protection for transfers |

### SOC2 Security (`soc2.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `SOC2-001` | Access Controls | High | Implement proper access control mechanisms |
| `SOC2-002` | System Monitoring | Medium | Continuous system monitoring required |
| `SOC2-003` | Incident Response | High | Documented incident response procedures |
| `SOC2-004` | Change Management | Medium | Formal change management processes |
| `SOC2-005` | Risk Assessment | High | Regular risk assessments required |
| `SOC2-006` | Vendor Management | Medium | Third-party vendor risk management |
| `SOC2-007` | Data Classification | High | Classify and protect data appropriately |
| `SOC2-008` | Backup and Recovery | Medium | Regular backups and recovery testing |
| `SOC2-009` | Security Awareness | Low | Security awareness training programs |
| `SOC2-010` | Security Monitoring | High | Ongoing security monitoring |

### HITRUST Security (`hitrust.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `HITRUST-001` | PHI Protection | Critical | Protect Protected Health Information |
| `HITRUST-002` | Access Management | High | Comprehensive access management controls |
| `HITRUST-003` | Audit Controls | High | Comprehensive audit logging and monitoring |
| `HITRUST-004` | Integrity Controls | High | Data integrity protection mechanisms |
| `HITRUST-005` | Person Authentication | High | Strong user authentication requirements |
| `HITRUST-006` | Transmission Security | High | Secure data transmission protocols |
| `HITRUST-007` | Workforce Training | Medium | Healthcare-specific security training |
| `HITRUST-008` | Contingency Planning | High | Business continuity and disaster recovery |
| `HITRUST-009` | Risk Assessment | High | Healthcare-specific risk assessments |
| `HITRUST-010` | Policy Management | Medium | Comprehensive policy documentation |

### API Security (`api_security.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `API-001` | Authentication Required | Critical | All API endpoints must require authentication |
| `API-002` | HTTPS Enforcement | High | All API communications must use HTTPS |
| `API-003` | Rate Limiting | Medium | Implement API rate limiting controls |
| `API-004` | Input Validation | High | Validate all API input parameters |
| `API-005` | Output Sanitization | High | Sanitize all API output data |
| `API-006` | Error Handling | Medium | Secure error handling and logging |
| `API-007` | CORS Configuration | Medium | Proper Cross-Origin Resource Sharing |
| `API-008` | API Versioning | Low | Implement API versioning strategy |
| `API-009` | Documentation Security | Low | Secure API documentation practices |
| `API-010` | Monitoring and Alerting | High | Comprehensive API monitoring |

### Data Governance (`data_governance.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `DATA-001` | Data Classification | High | Classify data by sensitivity level |
| `DATA-002` | Data Retention | Medium | Implement data retention policies |
| `DATA-003` | Data Encryption | Critical | Encrypt sensitive data at rest |
| `DATA-004` | Data Backup | High | Regular automated data backups |
| `DATA-005` | Data Access Controls | High | Implement role-based access controls |
| `DATA-006` | Data Loss Prevention | High | Prevent unauthorized data exfiltration |
| `DATA-007` | Data Quality | Medium | Ensure data accuracy and completeness |
| `DATA-008` | Data Lineage | Low | Track data origin and transformations |
| `DATA-009` | Data Privacy | Critical | Protect personal and health information |
| `DATA-010` | Data Security | High | Ensure regulatory adherence |

### Cloud Security (`cloud_security.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `CLOUD-001` | Cloud Access Controls | High | Implement cloud access management |
| `CLOUD-002` | Network Security | High | Secure cloud network configurations |
| `CLOUD-003` | Container Security | Medium | Secure container deployments |
| `CLOUD-004` | Secrets Management | Critical | Secure cloud secrets and credentials |
| `CLOUD-005` | Security Monitoring | High | Monitor cloud security continuously |
| `CLOUD-006` | Data Residency | Medium | Ensure data residency requirements |
| `CLOUD-007` | Multi-Factor Authentication | High | Require MFA for cloud access |
| `CLOUD-008` | Logging and Monitoring | High | Comprehensive cloud logging |
| `CLOUD-009` | Incident Response | Medium | Cloud-specific incident procedures |
| `CLOUD-010` | Vendor Management | Medium | Cloud vendor risk assessment |

### Healthcare Specific (`healthcare_specific.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `HL7-001` | HL7 FHIR Security | High | Ensure HL7 FHIR standard security |
| `HL7-002` | Medical Device Security | Critical | Secure medical device integrations |
| `HL7-003` | Telemedicine Security | High | Secure telemedicine platform access |
| `HL7-004` | EHR Integration | High | Secure Electronic Health Record access |
| `HL7-005` | PHI Handling | Critical | Proper Protected Health Information handling |
| `HL7-006` | Consent Management | High | Healthcare-specific consent mechanisms |
| `HL7-007` | Breach Detection | Critical | Healthcare data breach detection |
| `HL7-008` | Clinical Workflow Security | Medium | Secure clinical workflow processes |
| `HL7-009` | Patient Data Access | High | Secure patient data access controls |

### Authentication Security (`authentication_security.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `AUTH-001` | Multi-Factor Authentication | High | Require MFA for all user accounts |
| `AUTH-002` | Emergency Access | Critical | Secure emergency access procedures |
| `AUTH-003` | Auto-Logoff | Medium | Implement automatic session termination |
| `AUTH-004` | Person Authentication | High | Strong person/entity authentication |
| `AUTH-005` | Session Management | High | Secure session management controls |
| `AUTH-006` | Password Policy | Medium | Enforce strong password requirements |
| `AUTH-007` | Single Sign-On | Low | Implement SSO where appropriate |
| `AUTH-008` | Access Control Matrix | High | Maintain comprehensive access matrix |

### Log Validation (`log_validation.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `LOG-001` | Log Format Validation | Medium | Ensure consistent log format standards |
| `LOG-002` | PHI Redaction | Critical | Redact PHI from log entries |
| `LOG-003` | FHIR Patient Access | High | Log FHIR patient data access |
| `LOG-004` | Authentication Events | High | Log all authentication events |
| `LOG-005` | Data Access Logging | Critical | Log all data access attempts |
| `LOG-006` | Error and Exception Logging | Medium | Comprehensive error logging |
| `LOG-007` | Session Management Logging | High | Log session management events |
| `LOG-008` | API Rate Limiting Logs | Medium | Log API rate limiting events |
| `LOG-009` | Data Breach Detection | Critical | Log patterns indicating breaches |
| `LOG-010` | Security Audit Trail | High | Maintain security audit trails |

### FHIR Compliance (`fhir_compliance.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `FHIR-001` | FHIR Resource Validation | Critical | FHIR resources must be valid according to FHIR specification |
| `FHIR-002` | FHIR Version Compliance | High | FHIR API must use supported FHIR version (R4, R5) |
| `FHIR-003` | FHIR Security Headers | High | FHIR API must include proper security headers |
| `FHIR-004` | FHIR Authentication | Critical | FHIR API must implement proper authentication (OAuth2, SMART on FHIR) |
| `FHIR-005` | FHIR Authorization Scopes | High | FHIR API must implement proper authorization scopes |
| `FHIR-006` | FHIR Audit Logging | High | FHIR API must implement comprehensive audit logging |
| `FHIR-007` | FHIR Data Encryption | Critical | FHIR data must be encrypted in transit and at rest |
| `FHIR-008` | FHIR Rate Limiting | Medium | FHIR API must implement rate limiting to prevent abuse |
| `FHIR-009` | FHIR CORS Configuration | Medium | FHIR API must have proper CORS configuration |
| `FHIR-010` | FHIR Content-Type Validation | High | FHIR API must validate Content-Type headers |
| `FHIR-011` | FHIR Error Handling | High | FHIR API must implement proper error handling with OperationOutcome |
| `FHIR-012` | FHIR Search Parameters | Medium | FHIR API must implement proper search parameters |
| `FHIR-013` | FHIR Bundle Validation | High | FHIR bundles must be properly validated |
| `FHIR-014` | FHIR Metadata Endpoint | High | FHIR API must expose proper metadata endpoint |
| `FHIR-015` | FHIR Conformance Statement | Medium | FHIR API must provide proper conformance statement |

### ISO 27001 (`iso27001.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `ISO-001` | Information Security Management System | Critical | ISMS must be established, implemented, maintained, and continually improved |
| `ISO-002` | Security Logging and Monitoring | Critical | Comprehensive security event logging and monitoring must be implemented |
| `ISO-003` | Access Control Management | Critical | Access to information and information processing facilities must be controlled |
| `ISO-004` | Information Classification and Handling | High | Information must be classified and handled according to its sensitivity |
| `ISO-005` | Cryptographic Controls | High | Cryptographic controls must be used to protect information confidentiality and integrity |
| `ISO-006` | Incident Management | High | Information security incidents must be managed effectively |
| `ISO-007` | Business Continuity Management | High | Business continuity and disaster recovery must be planned and tested |
| `ISO-008` | Risk Assessment and Treatment | Critical | Information security risks must be assessed and treated appropriately |
| `ISO-009` | Security Awareness and Training | Medium | Security awareness and training must be provided to all personnel |
| `ISO-010` | Physical and Environmental Security | High | Physical and environmental security controls must be implemented |
| `ISO-011` | Network Security Management | High | Network security must be managed to protect information in transit |
| `ISO-012` | System Acquisition and Development | High | Security requirements must be included in system acquisition and development |
| `ISO-013` | Supplier Relationships | Medium | Information security requirements must be included in supplier agreements |
| `ISO-014` | Compliance and Legal Requirements | Critical | Legal and regulatory compliance requirements must be met |
| `ISO-015` | Information Security Incident Management | High | Information security incidents must be reported and managed |

### Log Access Control (`log_access.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `LA-001` | IAM Role-Based Log Access | Critical | Log access must be controlled through IAM roles with specific permissions |
| `LA-002` | Principle of Least Privilege | Critical | Log access must follow principle of least privilege - minimum necessary permissions |
| `LA-003` | Log Access Audit Trail | High | All log access must be audited and logged for compliance |
| `LA-004` | Log Access Time Restrictions | High | Log access must have time-based restrictions for security |
| `LA-005` | Log Access IP Restrictions | High | Log access must be restricted to authorized IP addresses |
| `LA-006` | Log Access MFA Requirement | High | Log access must require multi-factor authentication |
| `LA-007` | Log Access Session Management | Medium | Log access sessions must be properly managed with timeouts |
| `LA-008` | Log Access Data Classification | High | Log access must be based on data classification levels |
| `LA-009` | Log Access Justification | Medium | Log access must require business justification and approval |
| `LA-010` | Log Access Monitoring | High | Log access must be continuously monitored for anomalies |
| `LA-011` | Log Access Encryption | High | Log access must be encrypted in transit and at rest |
| `LA-012` | Log Access Segregation | High | Log access must be segregated by function and responsibility |

### Log Integrity (`log_integrity.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `LI-001` | CloudTrail Log File Validation | Critical | CloudTrail log files must have validation enabled to detect tampering |
| `LI-002` | WORM Storage Configuration | Critical | Log storage must use WORM (Write Once, Read Many) to prevent modification |
| `LI-003` | Log Immutability Verification | High | Log files must be stored in immutable storage with verification |
| `LI-004` | Log Hash Verification | High | Log files must have cryptographic hashes for integrity verification |
| `LI-005` | Digital Signature Verification | High | Log files must be digitally signed for authenticity verification |
| `LI-006` | Log Chain of Custody | High | Log files must maintain chain of custody documentation |
| `LI-007` | Log Access Monitoring | High | All log access must be monitored and logged for audit purposes |
| `LI-008` | Log Retention Immutability | Medium | Log retention policies must be immutable and cannot be modified |
| `LI-009` | Log Backup Integrity | High | Log backups must maintain integrity and be tamper-evident |
| `LI-010` | Log Timestamp Integrity | Medium | Log timestamps must be tamper-evident and synchronized |
| `LI-011` | Log Encryption at Rest | High | Log files must be encrypted at rest with tamper-evident keys |
| `LI-012` | Log Integrity Monitoring | High | Continuous monitoring of log integrity must be implemented |

### PCI-DSS (`pci_dss.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `PCI-001` | Card Data Tokenization | Critical | Sensitive cardholder data must be tokenized or encrypted in API logs and responses |
| `PCI-002` | No PAN in Logs | Critical | Primary Account Numbers (PANs) must not appear in application logs |
| `PCI-003` | CVV/CVC Protection | Critical | Card Verification Values (CVV/CVC) must never be stored or logged |
| `PCI-004` | Payment Access Monitoring | High | All payment-related API access must be logged with user identity and timestamp |
| `PCI-005` | Payment Data Encryption | High | Payment data must be encrypted in transit and at rest |
| `PCI-006` | Payment Gateway Integration Security | High | Payment gateway integrations must use secure authentication and API keys |
| `PCI-007` | Payment Transaction Logging | High | Payment transactions must be logged with transaction ID and status |
| `PCI-008` | Payment Failure Handling | Medium | Payment failures must be logged securely without exposing sensitive data |
| `PCI-009` | Payment Data Retention | Medium | Payment data retention must comply with PCI-DSS requirements (max 1 year for transaction data) |
| `PCI-010` | Payment API Rate Limiting | Medium | Payment APIs must implement rate limiting to prevent abuse |
| `PCI-011` | Payment Webhook Security | High | Payment webhooks must be secured with signature verification |
| `PCI-012` | Payment Data Access Controls | High | Payment data access must be restricted to authorized personnel only |

### Encryption (`encryption.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `ENC-PRO-001` | End-to-End Encryption | Critical | All PHI data must be encrypted in transit and at rest |
| `ENC-PRO-002` | Key Management | High | Encryption keys must be managed securely with rotation |
| `ENC-PRO-003` | Algorithm Compliance | High | Only approved encryption algorithms must be used |
| `ENC-PRO-004` | Database Encryption | High | Database must be encrypted at rest |

### Data Redaction (`redaction.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `REDACT-PRO-001` | PHI Redaction | Critical | PHI data must be redacted in logs and non-production environments |
| `REDACT-PRO-002` | Data Anonymization | High | Personal identifiers must be anonymized in analytics |
| `REDACT-PRO-003` | Log Sanitization | High | Logs must be sanitized to remove sensitive data |
| `REDACT-PRO-004` | Access Control | Medium | Redacted data access must be controlled and logged |

### HealthLake Logs (`healthlake_logs.yaml`)
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `HL-001` | CloudTrail Enabled (Multi-Region) | Critical | Ensure AWS CloudTrail is enabled and configured for multi-region to capture HealthLake API events |
| `HL-002` | CloudTrail Management & Data Events Logging | High | CloudTrail should log management and data events (including Read/Write events) for HealthLake APIs |
| `HL-003` | CloudTrail S3 Delivery Bucket Encryption | High | CloudTrail logs stored in S3 should be encrypted (SSE-S3 or SSE-KMS) |
| `HL-004` | CloudTrail S3 Bucket Access Logging & Lockdown | High | S3 bucket used for CloudTrail should have access logging enabled and restrictive bucket policy to prevent public access |
| `HL-005` | CloudTrail S3 Bucket KMS Key Rotation | Medium | KMS CMKs used to encrypt CloudTrail logs should have automatic rotation enabled where applicable |
| `HL-006` | CloudWatch Logs Export / Aggregation for HealthLake | High | Ensure CloudWatch Logs for API Gateway / application logs are exported/aggregated and accessible for scan/reporting |
| `HL-007` | API Gateway Access Logging (FHIR Requests) | High | API Gateway (or ALB) must emit access logs that include requestTime, requestId, userIdentity, httpMethod, resourcePath for FHIR API requests |
| `HL-008` | FHIR Resource Pattern in Logs | Medium | Logged resource paths should follow FHIR resource patterns (e.g., /Patient/{id}, /Observation/{id}) |
| `HL-009` | User Identity in Logs | High | Log entries for HealthLake API calls should include a user identity (IAM principal or Cognito identity) to support traceability |
| `HL-010` | Log Retention Meets Minimum | High | Ensure audit logs (CloudTrail / CloudWatch) retention meets minimum policy (e.g., >= 365 days for HealthLake audit readiness) |
| `HL-011` | IAM Role Usage in API Calls | High | Detect anonymous or console-root usage in HealthLake API calls; prefer least-privilege IAM roles for service-to-service calls |

## 🔌 Plugin Architecture

BaaStream features a powerful plugin architecture that extends risk scanning to CI/CD pipelines and infrastructure as code.

### 🚀 CI/CD Plugins

### GitHub Actions Plugin (`github_actions`)
- **Purpose**: Validate GitHub Actions workflows for healthcare security
- **Rules**: 5 specialized rules for workflow security
- **Capabilities**:
  - Workflow validation
  - Secret management
  - Permission validation
  - Artifact security
  - Environment protection

**GitHub Actions Rules:**
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `GHA-001` | Workflow Security Permissions | High | Workflows must use minimal required permissions |
| `GHA-002` | Secret Management | Critical | Must use secrets for sensitive data |
| `GHA-003` | Environment Protection | High | Production environments must have protection rules |
| `GHA-004` | Artifact Security | Medium | Build artifacts must be properly secured |
| `GHA-005` | Workflow Validation | Medium | Workflows must validate inputs and outputs |

### Jenkins Plugin (`jenkins`)
- **Purpose**: Validate Jenkins pipelines for healthcare security
- **Rules**: 5 specialized rules for pipeline security
- **Capabilities**:
  - Pipeline validation
  - Credential management
  - Node security
  - Build artifacts
  - Environment isolation

**Jenkins Rules:**
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `JENKINS-001` | Pipeline Security | High | Pipelines must use secure practices |
| `JENKINS-002` | Credential Management | Critical | Must use credential store for sensitive data |
| `JENKINS-003` | Node Security | High | Nodes must be properly secured |
| `JENKINS-004` | Build Artifacts Security | Medium | Artifacts must be properly secured |
| `JENKINS-005` | Environment Isolation | High | Environments must be properly isolated |

### 🏗️ Infrastructure Plugins

### Terraform Plugin (`terraform`)
- **Purpose**: Validate Terraform Infrastructure as Code for healthcare security
- **Rules**: 5 specialized rules for infrastructure security
- **Capabilities**:
  - Resource validation
  - State security
  - Variable management
  - Provider security
  - Module validation

**Terraform Rules:**
| Rule ID | Name | Severity | Description |
|---------|------|----------|-------------|
| `TF-001` | Resource Security Configuration | High | Resources must have proper security configs |
| `TF-002` | State File Security | Critical | State files must be stored securely |
| `TF-003` | Variable Security | High | Variables must not contain sensitive data |
| `TF-004` | Provider Security | Medium | Providers must be properly configured |
| `TF-005` | Module Validation | Medium | Modules must be properly versioned |