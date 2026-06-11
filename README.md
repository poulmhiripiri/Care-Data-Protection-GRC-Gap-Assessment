# Care Provider Data Protection & GRC Gap Assessment Toolkit

A practical Governance, Risk and Compliance (GRC) project demonstrating how a UK care company can assess its data protection maturity, identify gaps, prioritise risks, and produce a remediation roadmap aligned to ICO guidance, UK GDPR principles, CQC governance expectations and NHS Data Security and Protection Toolkit (DSPT) concepts.

> **Portfolio purpose:** This project is designed to demonstrate GRC analyst, compliance analyst, vulnerability analyst and GRC engineer capability through evidence-led assessment, risk scoring, control mapping, policy review, DPIA triggers, data sharing review and security improvement planning.

---

## 1. Scenario

A small-to-medium UK care provider handles resident/service-user records, staff records, medication records, safeguarding notes, emergency contacts, incident reports, rota data, payroll data, supplier contracts, CCTV footage, emails and digital care planning systems.

The organisation wants to know:

- Are we compliant with UK GDPR and ICO expectations?
- Are we handling special category data safely?
- Do we have proper data sharing agreements with councils, NHS bodies, IT suppliers and payroll providers?
- Do we know where personal data is stored and who can access it?
- Do we need DPIAs for digital care records, monitoring technology, CCTV, remote access or new systems?
- What are the highest-risk gaps and what should we fix first?

---

## 2. Project objectives

1. Build a care-sector data protection gap assessment framework.
2. Map controls to ICO accountability, DPIA, transparency, data sharing and information security guidance.
3. Include practical templates for evidence collection, risk rating and remediation tracking.
4. Demonstrate recruiter-relevant GRC skills: control assessment, risk register management, stakeholder reporting, policy review, third-party risk, vulnerability and security governance.

---

## 3. Frameworks and guidance used

This toolkit is based on publicly available UK guidance, including:

- ICO accountability and governance guidance
- ICO data protection audit framework
- ICO DPIA guidance
- ICO special category data guidance
- ICO transparency in health and social care guidance
- ICO data sharing code of practice
- CQC Regulation 17 good governance expectations
- CQC guidance on handling personal information
- NHS Digital Data Security and Protection Toolkit concepts

See: [`docs/reference-guidance.md`](docs/reference-guidance.md)

---

## 4. Repository structure

```text
care-data-protection-grc-gap-assessment/
├── README.md
├── docs/
│   ├── reference-guidance.md
│   ├── methodology.md
│   ├── control-domains.md
│   ├── data-flow-examples.md
│   └── recruiter-positioning.md
├── assessment/
│   ├── care-provider-gap-assessment.csv
│   ├── control-mapping.csv
│   ├── maturity-scoring-model.md
│   └── remediation-roadmap.md
├── templates/
│   ├── evidence-request-list.md
│   ├── risk-register-template.csv
│   ├── dpia-screening-template.md
│   ├── data-sharing-review-template.md
│   ├── supplier-due-diligence-template.md
│   ├── breach-response-checklist.md
│   └── management-report-template.md
├── examples/
│   ├── sample-gap-assessment-summary.md
│   ├── sample-risk-register.csv
│   └── sample-management-report.md
├── policies/
│   ├── data-protection-policy-outline.md
│   ├── retention-policy-outline.md
│   ├── access-control-policy-outline.md
│   └── incident-management-policy-outline.md
└── evidence-register/
    └── evidence-index-template.csv
```

---

## 5. Assessment domains

The gap assessment covers 12 domains:

| # | Domain | What is assessed |
|---|--------|------------------|
| 1 | Governance & Accountability | Ownership, DPO/lead role, policies, audit trail, senior oversight |
| 2 | Records of Processing | Data inventory, lawful basis, Article 9 condition, data flows |
| 3 | Special Category Data | Health/care records, safeguarding data, medication records, worker health data |
| 4 | Transparency & Privacy Notices | Clear notices for service users, families, staff and website visitors |
| 5 | Individual Rights | SAR process, rectification, erasure, restriction, objection, complaints |
| 6 | DPIA & Privacy by Design | DPIA screening, new systems, CCTV, monitoring, digital care records |
| 7 | Data Sharing | Sharing with councils, NHS, GPs, pharmacies, emergency services, suppliers |
| 8 | Supplier & Processor Management | Contracts, due diligence, processor clauses, exit controls |
| 9 | Information Security | MFA, access control, encryption, patching, backups, endpoint security |
| 10 | Vulnerability & Patch Governance | Asset register, vulnerability scanning, risk acceptance, remediation SLA |
| 11 | Breach & Incident Response | Detection, escalation, 72-hour assessment, lessons learned |
| 12 | Retention & Disposal | Retention schedule, secure deletion, archive controls, paper records |

---

## 6. Maturity scoring

| Score | Rating | Meaning |
|------:|--------|---------|
| 0 | Not in place | No evidence or informal practice only |
| 1 | Initial | Basic activity exists but undocumented/inconsistent |
| 2 | Defined | Documented process exists but not fully embedded |
| 3 | Managed | Process is implemented, evidenced and reviewed |
| 4 | Optimised | Process is measured, improved and integrated into governance reporting |

Risk priority is calculated using:

```text
Risk Priority = Likelihood x Impact
```

Recommended rating:

| Score | Priority |
|------:|----------|
| 1-4 | Low |
| 5-9 | Medium |
| 10-15 | High |
| 16-25 | Critical |

---

## 7. Example outputs

This project produces the following deliverables:

- Gap assessment workbook-style CSV
- Control mapping register
- Evidence request list
- DPIA screening template
- Data sharing review template
- Supplier due diligence checklist
- Risk register
- Remediation roadmap
- Management report
- Policy outline pack

---

## 8. Skills demonstrated

This repository demonstrates:

- UK GDPR and ICO control interpretation
- GRC control assessment
- Risk register development
- Compliance evidence collection
- Third-party and supplier risk review
- DPIA screening
- Data sharing governance
- Vulnerability management governance
- Security control improvement planning
- Audit-ready reporting for senior management

---

## 9. Disclaimer

This project is for portfolio and educational purposes. It is not legal advice. Care providers should seek professional legal, data protection or information governance advice before relying on any template for live compliance decisions.
