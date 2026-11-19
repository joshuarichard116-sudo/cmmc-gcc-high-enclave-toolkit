# Decision Matrix: Evaluation Criteria to NIST SP 800-171 Control Families

A starting-point mapping of the criteria in `tool-evaluation-template.md` to the 14 NIST SP 800-171 Rev. 2 requirement families. It is author-written and **not authoritative**. Verify against NIST SP 800-171 Rev. 2 and the CMMC Assessment Guide Level 2.

## NIST SP 800-171 Rev. 2 families

| ID | Family |
|---|---|
| 3.1 | Access Control |
| 3.2 | Awareness and Training |
| 3.3 | Audit and Accountability |
| 3.4 | Configuration Management |
| 3.5 | Identification and Authentication |
| 3.6 | Incident Response |
| 3.7 | Maintenance |
| 3.8 | Media Protection |
| 3.9 | Personnel Security |
| 3.10 | Physical Protection |
| 3.11 | Risk Assessment |
| 3.12 | Security Assessment |
| 3.13 | System and Communications Protection |
| 3.14 | System and Information Integrity |

## Criteria mapping

Mark each tool's rating for each criterion in your own copy. "Primary" families are where the criterion most directly produces evidence.

| Criterion | Primary families | Notes |
|---|---|---|
| FedRAMP authorization level / equivalency | 3.13, 3.12 | Supports external service/boundary decisions and assessment evidence |
| GCC High availability | 3.13 | Confirm the exact offering is available in the target environment |
| Data residency | 3.13, 3.8 | Where CUI is stored, processed, and backed up |
| FIPS 140 validated cryptography | 3.13, 3.1 | Cryptography protecting CUI in transit and at rest |
| US-persons support | 3.9, 3.1 | Who can access the service and its administration |
| Identity and access integration | 3.1, 3.5 | MFA, least privilege, account management |
| Logging and audit | 3.3 | Content, retention, protection of audit records |
| Shared responsibility | 3.12 | Documented in the SSP |
| SPRS / SSP evidence | 3.12 | Artifacts for assessment |
| Incident response and reporting | 3.6 | Vendor notification and your reporting path |
| Integration (boundary and configuration) | 3.4, 3.13 | Baselines, change control, boundary protection |
| Exit / portability | 3.8 | Export and sanitization at termination |
| Cost | n/a | Business input; not a control criterion |

The same mapping is in `decision-matrix.csv`.

## Scoring worksheet (copy per tool)

| Criterion | Rating (Pass / Partial / Fail / Unknown) | Evidence link or note |
|---|---|---|
| FedRAMP authorization level / equivalency | | |
| GCC High availability | | |
| Data residency | | |
| FIPS 140 validated cryptography | | |
| US-persons support | | |
| Identity and access integration | | |
| Logging and audit | | |
| Shared responsibility | | |
| SPRS / SSP evidence | | |
| Incident response and reporting | | |
| Integration | | |
| Exit / portability | | |
| Cost | | |
