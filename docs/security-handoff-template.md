# Security Handoff Template

Use this template whenever a feature requires review by the Security Champion or central security team.

## 🔍 Feature Overview
- **Feature name:** 
- **Summary of functionality:** 
- **Primary owners:** 
- **Linked tickets/design docs:**

## 🔐 Data & Access Review
- [ ] Identified any new data being collected or stored
- [ ] Classified data risk level (Low/Medium/High)
- [ ] Checked for proper authentication requirements
- [ ] Verified authorization logic and permission boundaries
- [ ] Validated data validation and sanitization needs

## 🛡️ Security Controls
- [ ] Encryption requirements addressed (in transit + at rest)
- [ ] Logging requirements validated (PII not exposed)
- [ ] Secrets handling follows secure storage guidelines
- [ ] Input/output validation reviewed

## ⚠️ Threat Modeling
- [ ] Identified key attack surfaces
- [ ] Considered abuse cases and misuse scenarios
- [ ] Potential vulnerabilities documented
- [ ] Mitigation strategies proposed

## 🧪 Testing Requirements
- [ ] Security testing scenarios added to test plan
- [ ] Automated security tools (SAST/DAST) run if applicable
- [ ] Manual penetration test needed? (Yes/No)

## ✔️ Security Sign‑off
- **Security Champion:** (Approved / Needs Fixes)
- **Central Security Team (if required):** (Approved / Needs Fixes)
