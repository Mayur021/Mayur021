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
| **OWASP AISVS** | ![Contributor](https://img.shields.io/badge/-Contributor-10b981?style=flat-square) | C9.2.6 (manifest-declared action class) + C9.2.7 (worst-case chain rule) merged into C09 research chapter, proposed for v1.01 |
| **OWASP SPVS** | ![Active](https://img.shields.io/badge/-Active%20Work-f59e0b?style=flat-square) | V5.6.5 IR decision-rights ([PR #14](https://github.com/OWASP/www-project-spvs/pull/14)), V1.3.7 NHI runtime decision-rights ([PR #15](https://github.com/OWASP/www-project-spvs/pull/15)), supply-chain ([Issue #13](https://github.com/OWASP/www-project-spvs/issues/13)) |
| **OWASP Cornucopia (Agentic AI)** | ![Active](https://img.shields.io/badge/-Active%20Work-f59e0b?style=flat-square) | Action-authority taxonomy ([Issue #3018](https://github.com/OWASP/www-project-cornucopia/issues/3018)) |
| **OWASP GenAI Security Project** | ![Active](https://img.shields.io/badge/-Active%20Work-f59e0b?style=flat-square) | Reversibility-graded authority into Agentic AI Threats & Mitigations v1.1 ([Issue #13](https://github.com/GenAI-Security-Project/GenAI-Agent-Security-Initiative/issues/13)) |
| **CSA NHI v1.0** | ![Reviewer](https://img.shields.io/badge/-Reviewer-4dd0e1?style=flat-square) | Peer review June 2026 |

**Prior OWASP leadership**: AppSec India Co-Leader (2016–2020) · OWASP Indore Chapter Leader (2017–2018)

---

## ⚙️ Reference Implementations

<table>
<tr>
<td width="50%" valign="top">

### 🔒 [aisvs-action-class-reference](https://github.com/Mayur021/aisvs-action-class-reference)

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JSON Schema](https://img.shields.io/badge/-JSON%20Schema-grey?style=flat-square)
![CC BY 4.0](https://img.shields.io/badge/-CC%20BY%204.0-green?style=flat-square)

Reference implementation of **OWASP AISVS C9.2.6 + C9.2.7**: manifest-declared action class, deterministic gate, worst-case chain rule. JSON schema + Python.

</td>
<td width="50%" valign="top">

### 🆔 [nhi-runtime-decision-rights](https://github.com/Mayur021/nhi-runtime-decision-rights)

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SPIFFE](https://img.shields.io/badge/-SPIFFE-grey?style=flat-square)
![CC BY 4.0](https://img.shields.io/badge/-CC%20BY%204.0-green?style=flat-square)

NHI runtime decision-rights companion to **OWASP SPVS V1.3.7**. Identity provenance verification, token freshness, action-class authorization.

</td>
</tr>
</table>

---

## 📜 Writings

[![Writings](https://img.shields.io/badge/Repository-Mayur021%2Fwritings-1d4ed8?style=flat-square&logo=github&logoColor=white)](https://github.com/Mayur021/writings)

Long-form essays on AI agent security, decision-rights, reversibility-graded authority, and contribution methodology. Three essays published June 2026 (~9,900 words + 7 figures):

- **[The Decision-Rights Plane: An Architectural Gap in AI Security](https://github.com/Mayur021/writings/tree/main/2026-06-02-decision-rights-plane)** — the missing primitive at layers 4 and 5
- **[Investigation Is Reversible. Actuation Is Not.](https://github.com/Mayur021/writings/tree/main/2026-06-02-investigation-vs-actuation)** — the read/write architectural fold as design primitive
- **[What I Learned Contributing Across Five Standards Surfaces](https://github.com/Mayur021/writings/tree/main/2026-06-02-contributing-across-standards-surfaces)** — the cross-surface contributor method

### Magazine Publications

- *Interview with Mayur Agnihotri* — Science Of Cyber Security (Oct 2017)
- *Conviction Of Digital Crime* — National Cyber Defence eMagazine (Aug 2016)
- *PenTest: Penetration Testing in Linux* — PenTest Magazine (Mar 2016)
- *PowerShell For Penetration Testing* — PenTest Magazine (Jan 2016)
- *Predictions For Cyber Security in 2016* — eForensics and Hakin9 (Dec 2015)

---

## 🏆 Responsible Disclosure Recognition

![Red Hat](https://img.shields.io/badge/Red%20Hat-Dec%202023-EE0000?style=flat-square&logo=redhat&logoColor=white)
![Adobe](https://img.shields.io/badge/Adobe%20PSIRT-Mar%202016-FF0000?style=flat-square&logo=adobe&logoColor=white)
![BlackBerry](https://img.shields.io/badge/BlackBerry%20SIRT-Dec%202014-000000?style=flat-square&logo=blackberry&logoColor=white)
![Sony](https://img.shields.io/badge/Sony-Nov%202014-000000?style=flat-square&logo=sony&logoColor=white)
![Microweber](https://img.shields.io/badge/Microweber-Aug%202014-4F46E5?style=flat-square)
![Nokia](https://img.shields.io/badge/Nokia-Aug%202014-124191?style=flat-square&logo=nokia&logoColor=white)
![Siteground](https://img.shields.io/badge/Siteground-Aug%202014-FF7300?style=flat-square)

LDAP server flaw research (Red Hat) and web-application vulnerability disclosures across major brands.

---

## 🌐 Current Roles

| Role | Org | Since |
|---|---|---|
| Information Security Specialist | **StraightArc Technologies** | 2020 |
| Board Member | **SkyVirt** | 2017 |
| Senior Subject Matter Expert | **TCS iON** | 2022 |
| Board of Studies | **Ramachandra College of Engineering** | 2023 |
| CHFI Item Writer | **EC-Council** | 2016 |
| Technical Committee | **Digital 4n6 Journal** | 2016 |
| Team Member | **National Cyber Defence Research Centre** | 2016 |
| Director | **ARNE Solutions** | 2016 |

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
