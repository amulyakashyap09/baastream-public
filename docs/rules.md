# 📋 BaaStream Rules Documentation

**Complete Reference Guide for All 100+ Compliance Rules Across 15+ Frameworks**

---

## 🎯 **Overview**

BaaStream provides comprehensive compliance scanning with **100+ rules** across **15+ frameworks** covering healthcare, security, and global compliance requirements. This document provides a complete reference for all available rules, their categories, and descriptions.

---

## 📊 **Rule Categories Summary**

| Category | Rules | Frameworks | Description |
|----------|-------|------------|-------------|
| **🏥 Healthcare-Specific** | 36 | HIPAA, HITRUST, FHIR, AWS HealthLake, Azure Health, Google Health | Healthcare industry compliance and interoperability |
| **🌐 Global Compliance** | 32 | GDPR, SOC2, ISO 27001, PCI DSS | International compliance frameworks |
| **🔒 Security & Infrastructure** | 32 | API Security, Authentication, Cloud Security, Data Governance, Encryption | Core security and infrastructure controls |

---

## 🏥 **Healthcare-Specific Rules (36 rules)**

### **Healthcare-Specific Compliance Rules (8 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **HL7-001** | HL7 FHIR API Compliance | FHIR API endpoints must follow HL7 FHIR R4 specification with proper resource validation |
| **HL7-002** | FHIR Resource Validation | All FHIR resources must be validated against their respective profiles and schemas |
| **HL7-003** | FHIR Audit Logging | Comprehensive audit logging for all FHIR resource access and modifications |
| **HL7-004** | FHIR Security Headers | Proper security headers implementation for FHIR endpoints |
| **HL7-005** | FHIR Error Handling | Standardized error responses following FHIR OperationOutcome specification |
| **HL7-006** | FHIR Versioning | Proper API versioning and backward compatibility for FHIR endpoints |
| **HL7-007** | FHIR Search Parameters | Validated search parameters with proper filtering and pagination |
| **HL7-008** | FHIR Bundle Processing | Secure processing of FHIR bundles with transaction support |

### **FHIR Compliance Rules (8 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **FHIR-001** | FHIR R4 Compliance | Ensure FHIR server implements R4 specification correctly |
| **FHIR-002** | FHIR Resource Validation | Validate FHIR resources against profiles and schemas |
| **FHIR-003** | FHIR Audit Logging | Comprehensive audit logging for FHIR operations |
| **FHIR-004** | FHIR Security Implementation | Implement FHIR security requirements including SMART on FHIR |
| **FHIR-005** | FHIR Error Handling | Proper error responses using OperationOutcome |
| **FHIR-006** | FHIR Versioning Support | Support for FHIR versioning and history |
| **FHIR-007** | FHIR Search Implementation | Implement FHIR search with proper parameters |
| **FHIR-008** | FHIR Bundle Processing | Secure processing of FHIR bundles and transactions |

### **AWS HealthLake Rules (11 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **HL-001** | CloudTrail Enabled (Multi-Region) | Ensure AWS CloudTrail is enabled and configured for multi-region to capture HealthLake API events |
| **HL-002** | CloudTrail Data Events | Enable CloudTrail data events for HealthLake S3 buckets to track data access |
| **HL-003** | S3 Bucket Encryption | Ensure HealthLake S3 buckets use KMS encryption for data at rest |
| **HL-004** | S3 Bucket Versioning | Enable S3 bucket versioning for HealthLake data protection |
| **HL-005** | S3 Bucket MFA Delete | Enable MFA delete protection for HealthLake S3 buckets |
| **HL-006** | KMS Key Rotation | Enable automatic key rotation for HealthLake KMS keys |
| **HL-007** | CloudWatch Logging | Enable CloudWatch logging for HealthLake operations |
| **HL-008** | CloudWatch Log Retention | Configure appropriate log retention for HealthLake CloudWatch logs |
| **HL-009** | API Gateway Access Logging | Enable access logging for HealthLake API Gateway |
| **HL-010** | API Gateway Request Validation | Enable request validation for HealthLake API Gateway |
| **HL-011** | HealthLake Data Export | Ensure HealthLake data export follows security best practices |

### **Azure Health Data Services Rules (12 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **AZ-HDS-001** | Activity Log Enabled | Ensure Azure Activity Log is enabled for Health Data Services |
| **AZ-HDS-002** | Diagnostic Settings | Configure diagnostic settings for Health Data Services resources |
| **AZ-HDS-003** | Storage Account Encryption | Ensure Health Data Services storage accounts use encryption |
| **AZ-HDS-004** | Key Vault Access Policies | Configure proper access policies for Health Data Services Key Vault |
| **AZ-HDS-005** | Key Vault Key Rotation | Enable automatic key rotation for Health Data Services keys |
| **AZ-HDS-006** | Log Analytics Workspace | Configure Log Analytics workspace for Health Data Services |
| **AZ-HDS-007** | Application Gateway Access Logging | Enable access logging for Health Data Services Application Gateway |
| **AZ-HDS-008** | Application Gateway WAF | Enable Web Application Firewall for Health Data Services |
| **AZ-HDS-009** | Network Security Groups | Configure Network Security Groups for Health Data Services |
| **AZ-HDS-010** | Private Endpoint Configuration | Configure private endpoints for Health Data Services |
| **AZ-HDS-011** | RBAC Configuration | Configure Role-Based Access Control for Health Data Services |
| **AZ-HDS-012** | Private Endpoint Configuration | Ensure private endpoints are properly configured for Health Data Services |

### **Google Cloud Healthcare API Rules (13 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **GCH-001** | Cloud Audit Logs Enabled | Ensure Cloud Audit Logs are enabled for Healthcare API |
| **GCH-002** | Cloud Audit Logs Data Access Logging | Enable data access logging for Healthcare API operations |
| **GCH-003** | Cloud Storage Encryption | Ensure Healthcare API Cloud Storage uses encryption |
| **GCH-004** | Cloud KMS Key Management | Configure proper key management for Healthcare API |
| **GCH-005** | Cloud KMS Key Rotation | Enable automatic key rotation for Healthcare API keys |
| **GCH-006** | Cloud Logging Configuration | Configure Cloud Logging for Healthcare API |
| **GCH-007** | Cloud Load Balancer Access Logging | Enable access logging for Healthcare API load balancer |
| **GCH-008** | Cloud Load Balancer SSL Policy | Configure SSL policy for Healthcare API load balancer |
| **GCH-009** | VPC Service Controls | Configure VPC Service Controls for Healthcare API |
| **GCH-010** | IAM Policy Configuration | Configure IAM policies for Healthcare API access |
| **GCH-011** | Healthcare API Dataset Configuration | Configure Healthcare API dataset with proper permissions |
| **GCH-012** | VPC Service Controls Configuration | Ensure VPC Service Controls are properly configured |
| **GCH-013** | Healthcare API FHIR Store Configuration | Configure FHIR store with proper security settings |

---

## 🌐 **Global Compliance Rules (32 rules)**

### **GDPR Rules (8 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **GDPR-001** | Data Minimization | Implement data minimization principles to collect only necessary data |
| **GDPR-002** | Consent Management | Implement comprehensive consent management with explicit consent tracking |
| **GDPR-003** | Data Subject Rights | Implement data subject rights including access, rectification, and erasure |
| **GDPR-004** | Data Protection by Design | Implement data protection by design and by default principles |
| **GDPR-005** | Data Protection Officer | Appoint and maintain a Data Protection Officer (DPO) |
| **GDPR-006** | Breach Notification | Implement data breach notification procedures within 72 hours |
| **GDPR-007** | Data Processing Records | Maintain records of data processing activities |
| **GDPR-008** | Privacy Impact Assessment | Conduct Privacy Impact Assessments for high-risk processing |

### **SOC2 Rules (10 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **SOC2-001** | Security Controls | Implement comprehensive security controls for system protection |
| **SOC2-002** | Availability Controls | Ensure system availability and uptime monitoring |
| **SOC2-003** | Processing Integrity | Implement controls to ensure processing integrity |
| **SOC2-004** | Confidentiality Controls | Implement confidentiality controls for sensitive data |
| **SOC2-005** | Privacy Controls | Implement privacy controls for personal information |
| **SOC2-006** | Access Controls | Implement proper access controls and user management |
| **SOC2-007** | Monitoring Controls | Implement continuous monitoring and alerting |
| **SOC2-008** | Incident Response | Implement incident response procedures and capabilities |
| **SOC2-009** | Change Management | Implement change management controls and procedures |
| **SOC2-010** | Vendor Management | Implement vendor management controls and oversight |

### **ISO 27001 Rules (12 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **ISO-001** | Information Security Policy | Establish and maintain information security policies |
| **ISO-002** | Organization of Information Security | Define roles and responsibilities for information security |
| **ISO-003** | Human Resource Security | Implement security controls for human resources |
| **ISO-004** | Asset Management | Implement asset management and classification |
| **ISO-005** | Access Control | Implement comprehensive access control measures |
| **ISO-006** | Cryptography | Implement cryptographic controls for data protection |
| **ISO-007** | Physical and Environmental Security | Implement physical security controls |
| **ISO-008** | Operations Security | Implement operational security controls |
| **ISO-009** | Communications Security | Implement network and communications security |
| **ISO-010** | System Acquisition and Development | Implement secure system development lifecycle |
| **ISO-011** | Supplier Relationships | Implement supplier security management |
| **ISO-012** | Information Security Incident Management | Implement incident management procedures |

### **PCI DSS Rules (6 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **PCI-001** | Secure Network and Systems | Implement secure network and systems architecture |
| **PCI-002** | Cardholder Data Protection | Protect stored cardholder data with encryption |
| **PCI-003** | Vulnerability Management | Implement vulnerability management program |
| **PCI-004** | Access Control Measures | Implement strong access control measures |
| **PCI-005** | Network Monitoring | Implement network monitoring and testing |
| **PCI-006** | Information Security Policy | Maintain information security policy |

---

## 🔒 **Security & Infrastructure Rules (32 rules)**

### **API Security Rules (10 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **API-001** | API Authentication | Strong API authentication prioritizing OAuth 2.0 with MFA for human-involved flows |
| **API-002** | API Rate Limiting | Comprehensive API rate limiting with adaptive behavior and quota enforcement |
| **API-003** | API Input Validation | Comprehensive input validation with sanitization and type checking |
| **API-004** | API Output Sanitization | Comprehensive output sanitization to prevent data leakage |
| **API-005** | API Error Handling | Secure error handling with proper logging and user feedback |
| **API-006** | API CORS Configuration | Proper CORS configuration for cross-origin resource sharing |
| **API-007** | API Versioning | Proper API versioning with backward compatibility |
| **API-008** | API Documentation | Comprehensive API documentation with security requirements |
| **API-009** | API Monitoring | Comprehensive API monitoring with performance and security metrics |
| **API-010** | API Dependency Management | Secure dependency management with vulnerability scanning |

### **Authentication Security Rules (8 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **AUTH-001** | Multi-Factor Authentication Validation | All healthcare API access must require phishing-resistant MFA with adaptive risk-based prompts |
| **AUTH-002** | Emergency Access Procedures | Emergency access to healthcare systems must be properly logged, monitored, and include post-access review |
| **AUTH-003** | Automatic Logoff Detection | Healthcare systems must implement adaptive session timeout with pre-logoff warnings |
| **AUTH-004** | Person/Entity Authentication Patterns | Implement distinct authentication patterns for person and entity access with device attestation |
| **AUTH-005** | Session Management Security | Implement secure session management with encryption, concurrent session limits, and token revocation |
| **AUTH-006** | Password Policy Enforcement | Implement modern password policies focusing on length and MFA with passwordless alternatives |
| **AUTH-007** | Single Sign-On Integration | Implement secure SSO integration with proper token validation and revocation capabilities |
| **AUTH-008** | Access Control Matrix | Implement comprehensive access control matrix with role-based permissions and ABAC |

### **Cloud Security Rules (10 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **CLOUD-001** | Cloud Access Controls | Implement comprehensive cloud access controls and identity management |
| **CLOUD-002** | Network Security | Implement network security controls including VPCs, subnets, and security groups |
| **CLOUD-003** | Container Security | Implement container security controls including image scanning and runtime protection |
| **CLOUD-004** | Secrets Management | Implement secure secrets management with encryption and rotation |
| **CLOUD-005** | Security Monitoring | Implement comprehensive security monitoring and alerting |
| **CLOUD-006** | Data Residency | Ensure data residency compliance with geographic restrictions |
| **CLOUD-007** | Multi-Factor Authentication | Implement MFA for all cloud service access |
| **CLOUD-008** | Logging and Monitoring | Implement comprehensive logging and monitoring for cloud resources |
| **CLOUD-009** | Incident Response | Implement cloud-specific incident response procedures |
| **CLOUD-010** | Vendor Management | Implement vendor management controls for cloud services |

### **Data Governance Rules (10 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **DATA-001** | Data Classification | Implement comprehensive data classification and labeling |
| **DATA-002** | Data Retention | Implement data retention policies with automated lifecycle management |
| **DATA-003** | Data Quality | Implement data quality controls and validation |
| **DATA-004** | Data Lineage | Implement data lineage tracking and documentation |
| **DATA-005** | Data Privacy | Implement privacy controls and data protection measures |
| **DATA-006** | Data Security | Implement data security controls and encryption |
| **DATA-007** | Data Compliance | Implement compliance monitoring and reporting |
| **DATA-008** | Data Audit | Implement data audit trails and logging |
| **DATA-009** | Data Governance Policy | Establish and maintain data governance policies |
| **DATA-010** | Data Access Controls | Implement data access controls and permissions |

### **Encryption Rules (4 rules)**

| Rule ID | Name | Description |
|---------|------|-------------|
| **ENC-001** | End-to-End Encryption | Implement end-to-end encryption for data in transit |
| **ENC-002** | Key Management | Implement secure key management with rotation and escrow |
| **ENC-003** | Algorithm Compliance | Use approved encryption algorithms and key lengths |
| **ENC-004** | Encryption at Rest | Implement encryption at rest for all sensitive data |

---

## 📝 **Additional Rule Categories**

### **Audit Logs Rules**

| Rule ID | Name | Description |
|---------|------|-------------|
| **AUDIT-001** | Audit Logging Enabled | Ensure comprehensive audit logging is enabled for all system activities |
| **AUDIT-002** | Log Retention | Configure appropriate log retention periods for compliance requirements |
| **AUDIT-003** | Log Integrity | Implement log integrity protection and tamper detection |
| **AUDIT-004** | Log Access Control | Implement proper access controls for audit logs |

### **Log Access Rules**

| Rule ID | Name | Description |
|---------|------|-------------|
| **LOG-001** | Log Access Control | Implement proper access controls for log data |
| **LOG-002** | Log Monitoring | Implement log monitoring and alerting |
| **LOG-003** | Log Analysis | Implement log analysis and correlation |
| **LOG-004** | Log Storage Security | Implement secure log storage and archival |

### **Log Integrity Rules**

| Rule ID | Name | Description |
|---------|------|-------------|
| **INTEGRITY-001** | Log Tamper Detection | Implement log tamper detection and prevention |
| **INTEGRITY-002** | Log Signing | Implement digital signing for log entries |
| **INTEGRITY-003** | Log Chain of Custody | Implement chain of custody for log data |
| **INTEGRITY-004** | Log Validation | Implement log validation and verification |

### **Log Validation Rules**

| Rule ID | Name | Description |
|---------|------|-------------|
| **VALID-001** | Log Format Validation | Validate log format and structure |
| **VALID-002** | Log Content Validation | Validate log content and data integrity |
| **VALID-003** | Log Schema Validation | Validate log schema and metadata |
| **VALID-004** | Log Timestamp Validation | Validate log timestamps and sequencing |

### **Redaction Rules**

| Rule ID | Name | Description |
|---------|------|-------------|
| **REDACT-001** | PHI Redaction | Implement PHI redaction in logs and data |
| **REDACT-002** | Data Anonymization | Implement data anonymization techniques |
| **REDACT-003** | Log Sanitization | Implement log sanitization and filtering |
| **REDACT-004** | Access Control Redaction | Implement access control redaction |

### **Unstructured Logs Rules**

| Rule ID | Name | Description |
|---------|------|-------------|
| **UNSTRUCT-001** | Unstructured Log Parsing | Implement parsing for unstructured log formats |
| **UNSTRUCT-002** | Log Format Detection | Implement automatic log format detection |
| **UNSTRUCT-003** | Log Normalization | Implement log normalization and standardization |
| **UNSTRUCT-004** | Log Enrichment | Implement log enrichment and correlation |

---

## 🎯 **Rule Severity Levels**

| Severity | Description | Impact |
|----------|-------------|---------|
| **Critical** | Immediate compliance violation | High risk of regulatory penalties |
| **High** | Significant compliance gap | Moderate risk of regulatory issues |
| **Medium** | Minor compliance issue | Low risk but should be addressed |
| **Low** | Best practice recommendation | Improvement opportunity |

---

## 🏷️ **Rule Tags**

Rules are tagged with relevant categories for easy filtering and organization:

- **Framework Tags**: `hipaa`, `hitrust`, `gdpr`, `soc2`, `iso27001`, `pci_dss`, `fhir`
- **Platform Tags**: `aws`, `azure`, `google`, `cloud`
- **Category Tags**: `security`, `authentication`, `encryption`, `logging`, `compliance`
- **Type Tags**: `api`, `data`, `network`, `access`, `monitoring`

---

## 🚀 **Usage Examples**

### **Test Specific Framework**
```bash
go run cmd/scan/main.go cmd/scan/output.go \
  -rules rules \
  -tags "hipaa" \
  your_data.json
```

### **Test Multiple Frameworks**
```bash
go run cmd/scan/main.go cmd/scan/output.go \
  -rules rules \
  -tags "hipaa,gdpr,soc2" \
  your_data.json
```

### **Test Specific Rule Category**
```bash
go run cmd/scan/main.go cmd/scan/output.go \
  -rules rules/api_security.yaml \
  your_data.json
```

### **Test Cloud Platform**
```bash
go run cmd/scan/main.go cmd/scan/output.go \
  -rules rules \
  -tags "aws" \
  your_data.json
```

---

## 🔄 **Rule Updates**

Rules are regularly updated to reflect:
- New compliance requirements
- Updated best practices
- Security threat landscape changes
- Framework specification updates

For the latest rule updates, check the `rules/` directory and rule file headers for version information.

---

**Total Rules**: 203 rules across 15+ compliance frameworks  
**Last Updated**: September 2025 
**Version**: 1.0.0
