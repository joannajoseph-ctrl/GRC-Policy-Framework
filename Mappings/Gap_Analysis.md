# Gap Analysis – Pura Health Cloud

This document identifies gaps between Pura Health Cloud’s current policies and the NIST Cybersecurity Framework (CSF) and ISO 27001 Annex controls.  
Each gap is assigned a risk rating and the recommended remediation.

---

## 📊 Summary Table

| Framework  | Control ID  | Control Requirement                                       | Current Status              | Gap Description                               | Risk Rating | Recommended Remediation                      |
|------------|-------------|-----------------------------------------------------------|-----------------------------|-----------------------------------------------|-------------|----------------------------------------------|
| NIST CSF   | PR.AC-3     | Remote access is managed securely                         | Policy covers MFA but no VPN policy | Remote workforce uses personal VPN solutions | High        | Implement a standardized VPN with MFA        |
| NIST CSF   | DE.CM-1     | Security continuous monitoring implemented                | Not addressed in policies   | No documented continuous monitoring practices | High        | Draft a logging & monitoring policy          |
| NIST CSF   | RS.MI-1     | Mitigation activities are performed to prevent expansion  | Policy states IR Plan exists but no playbooks | No step-by-step incident playbooks          | Medium      | Develop incident response playbooks           |
| ISO 27001  | A.5.34      | Privacy and protection of personally identifiable info    | General data policy exists  | No explicit PII handling procedures           | High        | Add a dedicated Data Privacy Policy           |
| ISO 27001  | A.8.9       | Backup and recovery requirements                          | Not documented              | No formal backup retention policy             | Medium      | Create a Backup & Recovery Policy             |
| ISO 27001  | A.6.1       | Roles and responsibilities for information security       | Roles loosely defined       | No RACI matrix for responsibilities           | Low         | Build a RACI chart and update policy docs     |

---

## 📌 Key Observations
- **High-risk gaps** exist around VPN usage, data privacy, and monitoring.  
- **Medium-risk gaps** include missing IR playbooks and backup policies.  
- **Low-risk gaps** are related to unclear accountability structures.  

---

## 🚀 Next Steps
1. Prioritize remediation of high-risk gaps (VPN, monitoring, PII).  
2. Assign ownership for drafting new policies.  
3. Re-run the compliance mapping once policies are updated.  
