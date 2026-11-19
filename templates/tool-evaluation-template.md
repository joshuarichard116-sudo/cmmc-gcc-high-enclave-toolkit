# Tool Evaluation: <Tool name>

- **Evaluator:** 
- **Date:** 
- **Tool role in enclave:** (e.g. identity, endpoint, logging, backup, collaboration)
- **Will it store, process, or transmit CUI, or provide security protection for CUI assets?** Yes / No / Unsure
- **Sources used:** (official vendor docs, FedRAMP Marketplace, contract language; include links and dates)

Scoring: **Pass / Partial / Fail / Unknown**. Always note the evidence. "Unknown" is not "Pass".

| # | Criterion | What to check | Rating | Evidence / notes |
|---|---|---|---|---|
| 1 | FedRAMP authorization level | Authorization level and status for the exact offering/SKU in scope; or documented equivalency | | |
| 2 | GCC High availability | Is the offering available in GCC High / Azure Government? Feature gaps vs. commercial? | | |
| 3 | Data residency | Where is data stored, processed, backed up, and supported from? | | |
| 4 | FIPS 140 validated cryptography | Validated modules (certificate numbers) used for data in transit and at rest | | |
| 5 | US-persons support | Are support and administrative access limited to US persons where required? | | |
| 6 | Identity and access integration | SSO/MFA, role-based access, least privilege, admin separation | | |
| 7 | Logging and audit | Audit log content, retention, export to your SIEM | | |
| 8 | Shared responsibility | Documented split of responsibilities; customer responsibility matrix available? | | |
| 9 | SPRS / SSP evidence | Can the vendor provide artifacts you can cite in your SSP and assessment? | | |
| 10 | Incident response and reporting | Vendor notification process and timelines; support for your reporting obligations | | |
| 11 | Integration | Works with your existing enclave tooling and boundary design | | |
| 12 | Cost | Licensing model and total cost (record separately; do not publish quotes) | | |
| 13 | Exit / portability | Data export and deletion at termination | | |

## Decision

- **Outcome:** Approve / Approve with conditions / Reject / Needs more info
- **Conditions or compensating controls:** 
- **SSP sections to update:** 
- **Next review date:** 
