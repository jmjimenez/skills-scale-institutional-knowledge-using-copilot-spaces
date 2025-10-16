# OctoAcme — Security Risk Assessment Template

## Purpose
Provide Security Leads with a structured approach to identify, assess, and mitigate security risks in projects and features.

## Assessment Overview

### Project/Feature Information
- **Project Name:**
- **Assessment Date:**
- **Security Lead:**
- **Project Team:**
- **Target Release Date:**
- **Classification Level:** (Public / Internal / Confidential / Restricted)

### Scope
- **Systems/Components in Scope:**
- **Data Types Handled:**
- **External Dependencies:**
- **Third-party Integrations:**

## Threat Modeling

### Assets to Protect
List critical assets (data, systems, credentials, etc.):
1.
2.
3.

### Attack Surface Analysis
- **Entry Points:**
  - [ ] Web interfaces
  - [ ] APIs
  - [ ] Mobile apps
  - [ ] Third-party integrations
  - [ ] Database connections
  - [ ] File uploads
  - [ ] Other: ___________

- **Authentication/Authorization:**
  - [ ] User authentication mechanisms identified
  - [ ] Authorization controls reviewed
  - [ ] Session management evaluated
  - [ ] Multi-factor authentication considered

### Threat Categories (STRIDE)
Check applicable threats:
- [ ] **Spoofing:** Identity spoofing or impersonation risks
- [ ] **Tampering:** Data modification or integrity risks
- [ ] **Repudiation:** Lack of proof or audit trail
- [ ] **Information Disclosure:** Unauthorized data access
- [ ] **Denial of Service:** Availability risks
- [ ] **Elevation of Privilege:** Unauthorized access escalation

## Security Risk Assessment

### Identified Risks

#### Risk #1
- **Description:**
- **Threat Category:**
- **Affected Component:**
- **Likelihood:** (Low / Medium / High)
- **Impact:** (Low / Medium / High)
- **Risk Level:** (Low / Medium / High / Critical)
- **Mitigation Strategy:**
- **Owner:**
- **Target Date:**

#### Risk #2
- **Description:**
- **Threat Category:**
- **Affected Component:**
- **Likelihood:** (Low / Medium / High)
- **Impact:** (Low / Medium / High)
- **Risk Level:** (Low / Medium / High / Critical)
- **Mitigation Strategy:**
- **Owner:**
- **Target Date:**

#### Risk #3
- **Description:**
- **Threat Category:**
- **Affected Component:**
- **Likelihood:** (Low / Medium / High)
- **Impact:** (Low / Medium / High)
- **Risk Level:** (Low / Medium / High / Critical)
- **Mitigation Strategy:**
- **Owner:**
- **Target Date:**

## Security Requirements Checklist

### Input Validation & Data Handling
- [ ] Input validation on all user inputs
- [ ] Output encoding to prevent XSS
- [ ] SQL injection prevention measures
- [ ] File upload restrictions and scanning
- [ ] Data sanitization implemented

### Authentication & Authorization
- [ ] Strong password requirements
- [ ] Multi-factor authentication available
- [ ] Session timeout configured
- [ ] Secure password storage (hashing)
- [ ] Role-based access control (RBAC)
- [ ] Principle of least privilege applied

### Data Protection
- [ ] Encryption at rest for sensitive data
- [ ] Encryption in transit (TLS/SSL)
- [ ] Secure key management
- [ ] Data retention policies defined
- [ ] PII/sensitive data handling compliant

### API Security
- [ ] API authentication required
- [ ] Rate limiting implemented
- [ ] API versioning strategy
- [ ] Input validation on API requests
- [ ] Secure API keys/tokens management

### Infrastructure Security
- [ ] Network segmentation
- [ ] Firewall rules configured
- [ ] Security groups/ACLs reviewed
- [ ] Patch management process
- [ ] Secure configuration baselines

### Logging & Monitoring
- [ ] Security event logging enabled
- [ ] Audit trails for sensitive operations
- [ ] Log retention policy defined
- [ ] Security monitoring alerts configured
- [ ] Incident response procedures documented

### Third-party & Dependencies
- [ ] Third-party libraries scanned for vulnerabilities
- [ ] Dependency versions up to date
- [ ] Vendor security assessments completed
- [ ] Third-party data handling reviewed
- [ ] Supply chain security considered

### Compliance & Privacy
- [ ] Regulatory requirements identified (GDPR, HIPAA, etc.)
- [ ] Privacy impact assessment completed
- [ ] Data processing agreements in place
- [ ] Consent mechanisms implemented (if needed)
- [ ] Data breach notification procedures

## Security Testing Plan

### Testing Activities
- [ ] Static Application Security Testing (SAST)
- [ ] Dynamic Application Security Testing (DAST)
- [ ] Dependency scanning
- [ ] Container/infrastructure scanning
- [ ] Penetration testing (if applicable)
- [ ] Security code review

### Testing Schedule
- **SAST:** Continuous in CI/CD
- **DAST:** Before each release
- **Dependency Scan:** Weekly
- **Penetration Testing:** Annually or for major releases
- **Code Review:** For all security-sensitive changes

## Incident Response Readiness

### Preparation
- [ ] Incident response plan documented
- [ ] Security incident contacts identified
- [ ] Escalation procedures defined
- [ ] Communication templates prepared
- [ ] Post-incident review process established

## Sign-off

### Security Review
- **Security Lead Approval:**
- **Date:**
- **Residual Risk Acceptance:**
- **Accepted By:**
- **Date:**

### Follow-up
- **Next Review Date:**
- **Periodic Re-assessment:** (Quarterly / Semi-annually / Annually)

## Notes & Additional Context
