<div align="center">

![Mayur Agnihotri — Agentic AI Security and Decision-Rights](banner.png)

[![OWASP](https://img.shields.io/badge/OWASP-AISVS%20Contributor-1d4ed8?style=flat-square&logo=owasp&logoColor=white)](https://github.com/OWASP/AISVS)
[![Standards](https://img.shields.io/badge/Standards--Track-Active-f59e0b?style=flat-square)](https://github.com/Mayur021/writings)
[![License](https://img.shields.io/badge/Content-CC--BY--4.0-10b981?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)
[![Experience](https://img.shields.io/badge/Experience-12%2B%20Years-64748b?style=flat-square)]()
[![Lane](https://img.shields.io/badge/Lane-Vendor%20Neutral-4dd0e1?style=flat-square)]()

**Head of Threat Research** · Agentic AI Security & Decision-Rights · AI SOC + OT/ICS · SecOps · Board Member

</div>

---

## 🎯 Focus

Working on the architectural floor for AI agents that take irreversible actions. The thesis in one line: **investigation is reversible, actuation is not — and the gate for the write side has to be code the agent cannot reach, evaluating a manifest the agent cannot rewrite.**

Three primitives carry the architecture:

```
manifest.action_class    = "irreversible"   // declared upstream by publisher
deterministic.gate       = outside_loop      // code the agent cannot reach
worst_case.chain_rule    = governs_chain     // composed actions inherit the worst class
```

Twelve-plus years across threat research, AI-driven SOC detection and response, OT/ICS security, cyber-range exercise design, cyber-crime investigation, and web/mobile/application security.

---

## 🛡 Standards-Track Contributions

| Project | Status | Scope |
|---|---|---|
| **OWASP AISVS** | ![Named in v1.0](https://img.shields.io/badge/-Named%20in%20v1.0-10b981?style=flat-square) | Named in the published v1.0 contributor list. Reversibility-graded action controls in C09: C9.2.3 (reversibility classification), C9.2.4 (enforce by class), C9.2.10 (worst-case reachable across chains) |
| **OWASP SPVS** | ![Active](https://img.shields.io/badge/-Active%20Work-f59e0b?style=flat-square) | V5.6.5 IR decision-rights ([PR #14](https://github.com/OWASP/www-project-spvs/pull/14)), V1.3.7 NHI runtime decision-rights ([PR #15](https://github.com/OWASP/www-project-spvs/pull/15)), supply-chain ([Issue #13](https://github.com/OWASP/www-project-spvs/issues/13)) |
| **OWASP Cornucopia (Agentic AI)** | ![Merged](https://img.shields.io/badge/-Merged-10b981?style=flat-square) | Per-action-class decision-rights and reversibility mapping into the AAI suit ([Issue #3018](https://github.com/OWASP/cornucopia/issues/3018), merged in [PR #3233](https://github.com/OWASP/cornucopia/pull/3233)). Listed on the project tribute page |
| **OWASP GenAI Security Project** | ![Active](https://img.shields.io/badge/-Active%20Work-f59e0b?style=flat-square) | Reversibility-graded authority into Agentic AI Threats & Mitigations v1.1 ([Issue #13](https://github.com/GenAI-Security-Project/GenAI-Agent-Security-Initiative/issues/13)) |
| **OWASP Agentic Skills Top 10 (AST09)** | ![Contributor](https://img.shields.io/badge/-Contributor-10b981?style=flat-square) | Cross-execution chain linkage (`parent_action_ref` + fan-in) accepted into the AST09 execution-receipt proposal ([Issue #44](https://github.com/OWASP/www-project-agentic-skills-top-10/issues/44)) |
| **Creduent** (open agent identity standard) | ![Merged](https://img.shields.io/badge/-Merged-10b981?style=flat-square) | Reversibility classification in the signed Execution Receipt schema: design-time conformance gate plus runtime fail-closed on unclassified tools, anchored to AISVS C9.2.3 ([PR #8](https://github.com/Idevsec/creduent/pull/8)) |
| **Agent Evidence Levels (AEL)** | ![Merged](https://img.shields.io/badge/-Merged-10b981?style=flat-square) | Governability extension: reversibility-class provenance on evidence records, fail-closed on unclassified or unverifiable policy ([PR #2](https://github.com/luckyPipewrench/agent-evidence-levels/pull/2)) |
| **Microsoft Agent Governance Toolkit** | ![Merged](https://img.shields.io/badge/-Merged-10b981?style=flat-square) | India regulatory policy pack as Rego policy-as-code: DPDP, CERT-In, RBI, SEBI, Aadhaar ([PR #3123](https://github.com/microsoft/agent-governance-toolkit/pull/3123), 12 files) |
| **OWASP Agent Control Standard** | ![Tracked](https://img.shields.io/badge/-Tracked%20for%20v0.2.0-4dd0e1?style=flat-square) | Tool declarations carry no integrity binding, so a same-version redefinition is invisible to Inspect-Dynamic ([Issue #38](https://github.com/GenAI-Security-Project/agent-control-standard/issues/38)). Deferred to the v0.2.0 window; named in the project's Strategic Adoption Plan as the strongest technical contribution received from outside |
| **CSA NHI v1.0** | ![Reviewer](https://img.shields.io/badge/-Reviewer-4dd0e1?style=flat-square) | Peer review June 2026 |

**Prior OWASP leadership**: AppSec India Co-Leader (2016–2020) · OWASP Indore Chapter Leader (2017–2018)

---

## ⚙️ Reference Implementations

<table>
<tr>
<td width="50%" valign="top">

### ✅ [aisvs-c9-action-class-conformance](https://github.com/Mayur021/aisvs-c9-action-class-conformance)

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Apache 2.0](https://img.shields.io/badge/-Apache%202.0-green?style=flat-square)
![70 tests](https://img.shields.io/badge/-70%20tests-10b981?style=flat-square)

Independent, vendor-neutral conformance scenarios for the action-class and reversibility controls in **OWASP AISVS C09**. Real-data fixtures generated from a published MCP registry corpus, three binding states in the record against two outcomes at the gate, and a supersession event channel so an implementation cannot pass every scenario while emitting nothing. Cited as the executable form of the argument in [10.5281/zenodo.22649163](https://doi.org/10.5281/zenodo.22649163).

</td>
<td width="50%" valign="top">

### 🔒 [aisvs-action-class-reference](https://github.com/Mayur021/aisvs-action-class-reference)

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JSON Schema](https://img.shields.io/badge/-JSON%20Schema-grey?style=flat-square)
![CC BY 4.0](https://img.shields.io/badge/-CC%20BY%204.0-green?style=flat-square)

Reference implementation of **OWASP AISVS C9.2.3 / C9.2.4 / C9.2.10**: reversibility classification, enforce-by-class gate, worst-case reachable across chains. JSON schema + Python.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🆔 [nhi-runtime-decision-rights](https://github.com/Mayur021/nhi-runtime-decision-rights)

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SPIFFE](https://img.shields.io/badge/-SPIFFE-grey?style=flat-square)
![CC BY 4.0](https://img.shields.io/badge/-CC%20BY%204.0-green?style=flat-square)

NHI runtime decision-rights companion to **OWASP SPVS V1.3.7**. Identity provenance verification, token freshness, action-class authorization.

</td>
<td width="50%" valign="top">

### 🧭 [agentic-standards-cross-walk](https://github.com/Mayur021/agentic-standards-cross-walk)

![Research](https://img.shields.io/badge/-Research-6366f1?style=flat-square)
![CC BY 4.0](https://img.shields.io/badge/-CC%20BY%204.0-green?style=flat-square)

Research lens cross-walking agentic AI standards across CSA, NIST, OWASP and others, mapping where the same control is named differently and where a control exists in one body and nowhere else.

</td>
</tr>
</table>

---
## 📄 Whitepaper

  [![Whitepaper](https://img.shields.io/badge/Whitepaper-v1.0%20%E2%80%94%20Action--Class%20Authority-1d4ed8?style=flat-square&logo=github&logoColor=white)](https://github.com/Mayur021/action-class-authority)
  [![Pages](https://img.shields.io/badge/Length-~28%20pages-64748b?style=flat-square)]()
  [![Chapters](https://img.shields.io/badge/Chapters-18-64748b?style=flat-square)]()
  [![License](https://img.shields.io/badge/-CC%20BY%204.0-10b981?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

  ### [Action-Class Authority for AI Agents: A Verification-Side Reference](https://github.com/Mayur021/action-class-authority)

  The full architectural reference. 18 chapters across 5 parts (Problem / Architecture / Standards Anchor / Applied Patterns / Implementation) + closing. Develops the four-class reversibility taxonomy (read-only / reversible / external-reversible / irreversible), manifest-declared classification, worst-case chain rule, and the architectural floor that makes the gate resistant to prompt injection. Anchored in **OWASP AISVS C9.2.3 / C9.2.4 / C9.2.10** (reversibility classification, enforce-by-class, and worst-case reachable across chains; AISVS v1.0).

  **Cross-substrate convergence catalog (10 substrates):** OWASP AISVS · CSA IAM WG · PieterKas/agent2agent-auth-framework · SANS AI Security Maturity Model · CSA AARM · Identient AuthR · Digital Identity Forum · CSA NHI · James A Bex AI Engineering Handbook · Riddhi Mohan Sharma EHV.

  ---
## 📜 Writings

[![Writings](https://img.shields.io/badge/Repository-Mayur021%2Fwritings-1d4ed8?style=flat-square&logo=github&logoColor=white)](https://github.com/Mayur021/writings)

Long-form essays on AI agent security, decision-rights, reversibility-graded authority, and contribution methodology. Three essays published June 2026 (~9,900 words + 7 figures):

- **[The Decision-Rights Plane: An Architectural Gap in AI Security](https://github.com/Mayur021/writings/tree/main/2026-06-02-decision-rights-plane)** — the missing primitive at layers 4 and 5
- **[Investigation Is Reversible. Actuation Is Not.](https://github.com/Mayur021/writings/tree/main/2026-06-02-investigation-vs-actuation)** — the read/write architectural fold as design primitive
- **[What I Learned Contributing Across Five Standards Surfaces](https://github.com/Mayur021/writings/tree/main/2026-06-02-contributing-across-standards-surfaces)** — the cross-surface contributor method

### Magazine Publications

- *Action-Class Authority When AI Agents Do the Triage* — eForensics Magazine, *AI in Forensics: The Age of Autonomy* (Jun 2026)
- *Interview with Mayur Agnihotri* — Science Of Cyber Security (Oct 2017)
- *Conviction Of Digital Crime* — National Cyber Defence eMagazine (Aug 2016)
- *PenTest: Penetration Testing in Linux* — PenTest Magazine (Mar 2016)
- *PowerShell For Penetration Testing* — PenTest Magazine (Jan 2016)
- *Predictions For Cyber Security in 2016* — eForensics and Hakin9 (Dec 2015)

---

## 🏆 Responsible Disclosure Recognition

[![CVE-2026-90572](https://img.shields.io/badge/CVE--2026--90572-Finder-b91c1c?style=flat-square)](https://www.cve.org/CVERecord?id=CVE-2026-90572)

**[CVE-2026-90572](https://www.cve.org/CVERecord?id=CVE-2026-90572)** — memory corruption in `TSnap7MicroClient::opUpload`, snap7 1.4.0 to 1.4.3, the Siemens S7 client library vendored by a good deal of SCADA and HMI code. A length field the server declares, copied without checking it against what actually arrived. Credited as **finder** on the CVE record. Published 13 September 2026, CVSS v4.0 5.1, v3.1 4.7.

[![GHSA-wcqx-x7x9-c8rm](https://img.shields.io/badge/GHSA--wcqx--x7x9--c8rm-Reporter-b45309?style=flat-square)](https://github.com/mz-automation/libiec61850/security/advisories/GHSA-wcqx-x7x9-c8rm)

**[GHSA-wcqx-x7x9-c8rm](https://github.com/mz-automation/libiec61850/security/advisories/GHSA-wcqx-x7x9-c8rm)** — out-of-bounds read in the libiec61850 IEC 61850-9-2 Sampled Values subscriber, via a missing APDU-length check in `parseSVPayload()`. Unauthenticated and network-adjacent; crashes the SV receiver. Credited as **reporter**. Published 13 August 2026, CWE-125, CVSS 3.1 base 4.3. Fixed in v1.6.2 with the one-line length guard proposed in the report.

![Red Hat](https://img.shields.io/badge/Red%20Hat-Dec%202023-EE0000?style=flat-square&logo=redhat&logoColor=white)
![Adobe](https://img.shields.io/badge/Adobe%20PSIRT-Mar%202016-FF0000?style=flat-square&logo=adobe&logoColor=white)
![BlackBerry](https://img.shields.io/badge/BlackBerry%20SIRT-Dec%202014-000000?style=flat-square&logo=blackberry&logoColor=white)
![Sony](https://img.shields.io/badge/Sony-Nov%202014-000000?style=flat-square&logo=sony&logoColor=white)
![Microweber](https://img.shields.io/badge/Microweber-Aug%202014-4F46E5?style=flat-square)
![Nokia](https://img.shields.io/badge/Nokia-Aug%202014-124191?style=flat-square&logo=nokia&logoColor=white)
![Siteground](https://img.shields.io/badge/Siteground-Aug%202014-FF7300?style=flat-square)

LDAP server flaw research (Red Hat) and web-application vulnerability disclosures across major brands.

---

## 🌐 Roles & Affiliations

  | Role | Org | Period |
  |---|---|---|
  | Head of Threat Research | **StraightArc Technologies** | 2026 to present |
  | Information Security Specialist | **StraightArc Technologies** | 2020 to present |
  | Head of Threat Research | **SecSphere SOC** | 2020 to present |
  | Board Member | **SkyVirt** | 2017 to present |
  | Senior Subject Matter Expert | **TCS iON** | 2022 to present |
  | Board of Studies | **Ramachandra College of Engineering** | 2023 to present |
  | CHFI Item Writer | **EC-Council** | 2016 to present |
  | Director | **ARNE Solutions** | 2016 to present |
  | Technical Committee | **Digital 4n6 Journal** | 2016 to 2018 |
  | Team Member | **National Cyber Defence Research Centre** | 2016 to 2018 |

---

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mayuragnihotri-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayuragnihotri/)
[![Twitter](https://img.shields.io/badge/X-@I__AM__Mayur0021-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/I_AM_Mayur0021)
[![Website](https://img.shields.io/badge/StraightArc-straightarc.com-4dd0e1?style=for-the-badge)](https://straightarc.com)

📍 Udaipur, India · ⏱ GMT+05:30

---

<div align="center">

*Vendor-neutral standards work. Decision-rights for AI agents, reversibility as the architectural floor, manifest-declared action class as the standards-side answer.*

</div>
