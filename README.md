# GRC Policy Framework
This repository houses security policies with the addition of mapping to controls, and a gap analysis. For these policies, I have created the ficitional org 'Pura Health Cloud.' This company has about 100 employees and is a SaaS that stores PHI. The regulatory standard for this organization is HIPAA.

## Compliance Mappings

This repository includes mappings of Pura Health Cloud’s policies to industry frameworks.

- [NIST CSF Mapping](./mappings/nist_csf_mapping.csv)  
- [ISO 27001 Mapping](./mappings/iso27001_mapping.csv)

### Example (NIST CSF extract)

| Policy          | Statement ID | Control Text                                 | Function | Category | Subcategory |
|-----------------|--------------|----------------------------------------------|----------|----------|-------------|
| Access Control  | AC-1         | MFA required for all production access       | PROTECT  | PR.AC    | PR.AC-7     |
| Access Control  | AC-2         | Passwords must be at least 12 characters     | PROTECT  | PR.AC    | PR.AC-1     |
| Incident Resp.  | IR-1         | IR Plan with roles and responsibilities      | RESPOND  | RS.RP    | RS.RP-1     |


