<div align="center" markdown="1">

# PSVL — Proprietary Source-Visible License

[![Version](https://img.shields.io/badge/version-1.0-blue)](CHANGELOG.md)
[![Clauses](https://img.shields.io/badge/clauses-460+-blueviolet)](PSVL.txt)
[![Type](https://img.shields.io/badge/type-source--visible-orange)](#-what-is-psvl)
[![Status](https://img.shields.io/badge/status-stable-brightgreen)](CHANGELOG.md)

**A comprehensive source-visible license template for solo developers
and indie teams who want to show their code without giving it away.**

460+ active sub-clauses. 31 defined terms. 9 sections.

📄 [**Read the Full License Text — PSVL.txt**](PSVL.txt)

</div>

## 🧭 Table of Contents

- 📖 &nbsp;[**What is PSVL?**](#-what-is-psvl)
- 👥 &nbsp;[**Who is PSVL For?**](#-who-is-psvl-for)
- 🚫 &nbsp;[**Who is PSVL NOT For?**](#-who-is-psvl-not-for)
- 📋 &nbsp;[**What Does PSVL Cover?**](#-what-does-psvl-cover)
- ⚖️ &nbsp;[**Quick Comparison**](#%EF%B8%8F-quick-comparison)
- 🚀 &nbsp;[**How to Use**](#-how-to-use)
- ❓ &nbsp;[**FAQ**](#-faq)
- 🌍 &nbsp;[**Origin Story**](#-origin-story)
- ⚠️ &nbsp;[**Important Disclaimer**](#%EF%B8%8F-important-disclaimer)
- 🤝 &nbsp;[**Contributing**](#-contributing)
- 🔒 &nbsp;[**Security**](#-security)
- 📄 &nbsp;[**License for This Repository**](#-license-for-this-repository)

---

## 📖 What is PSVL?

PSVL is a **proprietary source-visible license** designed for developers who want to:

- Make their source code **publicly visible** for transparency,
  security auditing, and community contributions
- **Retain full ownership** and control over their intellectual property
- **Prevent cloning, unauthorized commercial use, and AI training**
- Allow contributions only via Pull Requests that transfer IP to the author

> **PSVL is NOT an open-source license.** It is the opposite — maximum
> legal protection with maximum code visibility.

---

## 👥 Who is PSVL For?

| Audience | Why PSVL |
|---|---|
| **Solo developers** | Protect your work from unauthorized cloning |
| **Indie hackers** | Show your code without losing control |
| **Startups (pre-funding)** | Let investors review code under legal protection |
| **Security-conscious projects** | Enable auditing without giving away IP |
| **Social / messaging apps** | Privacy, message-content, and anti-exploitation clauses |
| **Fintech / payment apps** | Financial data, fraud, and anti-money-laundering protections |
| **Marketplace / e-commerce** | Payment-fraud, purchase-interception, and data-resale protections |
| **Games / interactive apps** | Anti-clone and competing-product protections |
| **Any app with sensitive user data** | Comprehensive privacy and data-protection clauses |

---

## 🚫 Who is PSVL NOT For?

| Audience | Reason |
|---|---|
| **Open-source community projects** | PSVL prohibits redistribution and forking-for-deployment |
| **Public libraries / SDKs / frameworks** | PSVL prohibits use as a dependency in third-party projects |
| **Projects that must be OSI-approved** | PSVL is not OSI-approved and never will be |
| **High-risk / life-critical software** | PSVL explicitly disclaims fitness for such use |

---

## 📋 What Does PSVL Cover?

### ✅ Permitted Uses (Section 3)
- Personal non-commercial evaluation
- Educational and academic research
- Security vulnerability research (in local Sandbox environments)
- Performance benchmarking and optimization
- Localization and accessibility testing
- Community contributions via Pull Requests
- UI/UX improvement proposals
- Integration and compatibility testing
- Portfolio display of your own contributions (resumes, CVs, LinkedIn)
- Non-profit and humanitarian evaluation

### ❌ Prohibited Uses (Section 4)
- Commercial use, resale, hosting, or monetization
- Redistribution or sublicensing
- AI / ML training on the code or user data
- Reverse engineering or decompilation (with EU mandatory-law carve-out)
- Operational government, military, or intelligence use
- Data scraping, harvesting, or resale
- Building competing products
- Side-channel, hardware, network, and supply-chain attacks
- Deepfake, bot, and fraud operations
- [**See Section 4 of PSVL.txt for the full list of prohibitions**](PSVL.txt)

### 🏛️ Legal Framework (Sections 5–9)
- Contributor IP assignment with 18+ age requirement and moral-rights fallback
- Governing law and jurisdiction
- Binding arbitration with class-action waiver (EU/UK consumer carve-outs)
- Severability — one invalid clause cannot void the rest
- Indemnification proportional to fault
- Confidentiality with 5-year survival
- Data-breach notification within 48 hours
- Statute of limitations: 5 years
- Enterprise cyber-liability insurance requirement (tiered)
- Force majeure protection
- Disclaimer of warranties including high-risk-use disclaimer
- Limitation of liability with carve-outs for fraud, gross negligence, etc.

---

## ⚖️ Quick Comparison

This table summarizes the differences between PSVL and several common
licenses. Counts are approximate and exact terms differ; consult each
license's full text for authoritative details.

| | MIT | Apache 2.0 | GPL v3 | BUSL 1.1 | Elastic 2.0 | PSVL 1.0 |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| **Type** | **Permissive** | **Permissive** | **Copyleft** | **Source-available** | **Source-available** | ***Source-visible*** |
| **Commercial use** | ✅ | ✅ | ✅ | ⏳ **Time-delayed** | ❌ | ❌ |
| **Modification** | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ ***PR only*** |
| **Redistribution** | ✅ | ✅ | ✅ | ✅ | ⚠️ **Limited** | ❌ |
| **Explicit AI-training stance** | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| **Contributor IP transfer** | ❌ | ⚠️ **CLA-based** | ❌ | ❌ | ❌ | ✅ |
| **Arbitration clause** | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| **Governing-law clause** | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| **Severability** | ❌ | ⚠️ **Implied** | ✅ | ❌ | ❌ | ✅ |
| **Indemnification of Author** | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| **Confidentiality** | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| **Data-breach notification** | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ ***48-hour*** |
| **Side-channel attack bans** | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| **Approx. length** | **~165 words** | **~9 sections** | **~17 sections** | **~5 sections** | **~7 sections** | ***9 sections, 460+ clauses*** |

---

## 🚀 How to Use

### 1. Copy the Template

Download [**PSVL.txt**](PSVL.txt) from this repository. This is the full
license text with placeholders ready to fill in.

### 2. Replace Placeholders

| Placeholder | Replace With |
|---|---|
| `[AUTHOR_LEGAL_NAME]` | Your full legal name |
| `[AUTHOR_LEGAL_NAME_TRANSLITERATED]` | A plain A–Z spelling of your name with accents removed (e.g. `Elxan Huseynov`). If your name has no special characters, simply use the same value as `[AUTHOR_LEGAL_NAME]`. |
| `[YEAR]` | Current year (e.g. `2026`) |
| `[MONTH_YYYY]` | Publication month and year (e.g. `May 2026`) |
| `[MONTH_DD_YYYY]` | Specific effective date (e.g. `May 14, 2026`) |
| `[GOVERNING_COUNTRY]` | Country whose law governs the license |
| `[GOVERNING_CITY]` | City where arbitration takes place |

### 3. Adapt to Your App (Optional)

PSVL is intentionally broad. Clauses that reference features your app
does not provide (such as biometrics, in-app purchases, or push
notifications) are simply inoperative — you do not need to remove them.

You may also:

- Add industry-specific clauses for your domain
- Adjust the enterprise insurance minimum
- Tweak the governing law, dispute resolution, or age requirements

### 4. Save as `LICENSE`

Save the completed file as `LICENSE` (no extension) in the root of your
project repository. This is the standard location that GitHub, GitLab,
and most tooling recognize automatically.

### 5. Reference in Your `README.md`

Add the following to your project's `README.md`:

```text
Licensed under the Proprietary Source-Visible License 1.0 (PSVL 1.0),
based on the PSVL template by Elxan Hüseynov.
See LICENSE for full terms.
```

### 6. Credit the Original Author

Add the following footer at the bottom of your project's `LICENSE` file:

```text
================================================================================
Based on PSVL by Elxan Hüseynov — https://github.com/BMBOMICH/psvl
================================================================================
```

### 7. Have a Lawyer Review

**Before deploying PSVL on a real product**, consult a qualified attorney
in your jurisdiction. PSVL is a strong template, but it is not legal
advice. See [**DISCLAIMER.md**](DISCLAIMER.md).

---

## ❓ FAQ

**Q: Is PSVL open source?**
No. PSVL is explicitly *not* an open-source license. It is the opposite
end of the spectrum: maximum visibility, maximum protection.

**Q: Why not just use MIT or Apache 2.0?**
MIT and Apache 2.0 allow anyone to copy your code, sell it, host it, or
build competing products with no obligation back to you. PSVL is designed
for developers who do not want that.

**Q: Can someone fork my PSVL-licensed repository?**
Only to submit improvements back via Pull Request. Forks may not be
used commercially, redistributed, or published.

**Q: What happens to contributions?**
Contributor IP is assigned to the project Author when a Pull Request is
submitted (see [**Section 5 of PSVL.txt**](PSVL.txt)). In jurisdictions
where full assignment is not possible (such as the EU), the Author
receives an exclusive license instead.

**Q: Does PSVL allow AI training on my code?**
No. PSVL explicitly states that the Author does not consent to AI training
on the code, and reserves all rights against such use.

**Q: Can government agencies use software licensed with PSVL?**
Not for operational use without a separate agreement. PSVL includes
carve-outs for academic research by public universities, evaluation by
public libraries, lawful proceedings, and humanitarian use.

**Q: What if a clause is invalid in my country?**
The severability clause ([**Section 6.2**](PSVL.txt)) keeps the rest of
the license in force. The license also includes specific carve-outs for
EU, UK, and several other jurisdictions to maximize global enforceability.

**Q: Can I use PSVL for a commercial product?**
Yes — PSVL is designed for proprietary commercial software. The license
itself blocks others from using your software commercially without your
agreement.

**Q: Where do I report a problem with PSVL?**
[**Open a GitHub Issue**](https://github.com/BMBOMICH/psvl/issues/new/choose)
for legal gaps, clause conflicts, or clause proposals. For security or
loophole issues, use [**Report a vulnerability**](https://github.com/BMBOMICH/psvl/security/advisories/new).
See [**SECURITY.md**](SECURITY.md).

---

## 🌍 Origin Story

PSVL was created on **May 14, 2026** by **Elxan Hüseynov** in **Baku,
Azerbaijan**.

The motivation was simple: existing licenses did not cover the specific
combination of needs — letting people see and audit the source code,
accept community contributions, and block clones, AI training, and
exploitation, while keeping full ownership of the work.

Nothing quite like that existed, so the template was built and then
released publicly so other developers facing the same need do not have
to start from scratch.

PSVL was drafted with the assistance of **Claude by Anthropic**, an
AI writing assistant, combining knowledge of existing source-available
licenses (BUSL, SSPL, Elastic 2.0), cybersecurity threat modeling, and
international legal best practices.

---

## ⚠️ Important Disclaimer

> **This is NOT legal advice.** The author is not a lawyer. This license
> has not been reviewed by legal counsel. Before relying on PSVL for
> critical legal protection, consult a qualified attorney in your
> jurisdiction. See [**DISCLAIMER.md**](DISCLAIMER.md) for full details.

---

## 🤝 Contributing

Found a legal gap? Have a clause idea? Spotted a typo?

Contributions are welcome:

- [**Open an Issue**](https://github.com/BMBOMICH/psvl/issues/new/choose)
  for legal gaps, clause conflicts, or proposals
- [**Open a Pull Request**](https://github.com/BMBOMICH/psvl/pulls)
  for direct text changes
- [**Start a Discussion**](https://github.com/BMBOMICH/psvl/discussions)
  for open-ended ideas

For more, see:

- [**CONTRIBUTING.md**](CONTRIBUTING.md) — full contribution guidelines
- [**CODE_OF_CONDUCT.md**](CODE_OF_CONDUCT.md) — community standards
- [**SUPPORT.md**](SUPPORT.md) — where to go for help
- [**GOVERNANCE.md**](GOVERNANCE.md) — how the project is run
- [**AUTHORS.md**](AUTHORS.md) — author, contributors, and inspirations
- [**CITATION.cff**](CITATION.cff) — how to cite PSVL in academic work

---

## 🔒 Security

To report a security or legal-loophole concern privately, see [**SECURITY.md**](SECURITY.md).
Do **not** open a public issue for security concerns.

---

## 📄 License for This Repository

The PSVL **template itself** is governed by the [**PSVL Template License**](LICENSE).

In short:

- ✅ You may copy, use, and adapt the template for your own projects
- ✅ You may fork or mirror this repository
- ✅ You may quote or excerpt the template for review, teaching, or commentary
- ⚠️ You must credit the original author when adopting the template
- ❌ You may not republish the template under your own name without credit
- ❌ You may not use the template text to train AI models

See [**LICENSE**](LICENSE) for the full text.

---

<div align="center" markdown="1">

**Built with ❤️ in Baku, Azerbaijan — Drafted with Claude by Anthropic**

If PSVL was useful for your project, a ⭐ would help other indie developers find it.

</div>
