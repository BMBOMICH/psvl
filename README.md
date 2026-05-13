# PSVL — Proprietary Source-Visible License

**The most comprehensive source-visible license ever written.**

276 clauses. 9 sections. Built for solo developers and indie teams
who want to show their code without giving it away.

---

## What is PSVL?

PSVL is a **proprietary source-visible license** designed for
developers who want to:

- Make their source code **publicly visible** for transparency,
  security auditing, and community contributions
- **Retain full ownership** and control over their intellectual
  property
- **Prevent cloning, theft, and unauthorized commercial use**
- Allow contributions only via Pull Requests that transfer IP
  to the author

It is **NOT** an open-source license. It does not grant open-source
freedoms. It is the opposite — maximum protection with maximum
visibility.

---

## Who is PSVL For?

| Audience | Why PSVL |
|---|---|
| Solo developers | Protect your life's work from clones |
| Indie hackers | Show your code without losing control |
| Startups (pre-funding) | Let investors see code under protection |
| Security-conscious projects | Enable auditing without giving away IP |
| Dating / social apps | Specific protections for user safety |
| Any app with sensitive user data | Privacy and data protection clauses |

---

## Who is PSVL NOT For?

- Open-source community projects seeking contributions at scale
- Libraries or frameworks intended for public use as dependencies
- Projects that want OSI-approved license compatibility

---

## Quick Comparison

| | MIT | Apache 2.0 | GPL v3 | BSL 1.1 | Elastic 2.0 | PSVL 1.0 |
|---|---|---|---|---|---|---|
| Type | Permissive | Permissive | Copyleft | Source-available | Source-available | Source-visible |
| Clauses | ~3 | ~9 | ~17 | ~5 | ~7 | **~276** |
| Commercial use | ✅ | ✅ | ✅ | ⏳ | ❌ (competing) | ❌ |
| Modification | ✅ | ✅ | ✅ | ✅ | ✅ | PR only |
| AI training ban | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| Contributor IP transfer | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| Arbitration clause | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| Governing law | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| Severability | ❌ | ❌ | ✅ | ❌ | ❌ | ✅ |
| Indemnification | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| Confidentiality | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| Data breach notification | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| Side-channel attack bans | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| Exotic threat prohibitions | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |

---

## How to Use

### 1. Copy the Template

Download `PSVL-1.0.txt` from this repository.

### 2. Replace Placeholders

Find and replace the following placeholders with your information:

| Placeholder | Replace With |
|---|---|
| `[AUTHOR_LEGAL_NAME]` | Your full legal name |
| `[AUTHOR_LEGAL_NAME_TRANSLITERATED]` | ASCII transliteration if needed, or same as above if not applicable |
| `[YEAR]` | Current year |
| `[MONTH]` | Publication month |
| `[GOVERNING_COUNTRY]` | Your country |
| `[GOVERNING_CITY]` | Your city for arbitration |

### 3. Customize (Optional)

- Remove app-specific clauses if not applicable to your project
- Add industry-specific clauses for your domain
- Adjust the enterprise insurance minimum if needed

### 4. Save as LICENSE

Save the completed file as `LICENSE` (no extension) in the root
of your project repository.

### 5. Reference in README

Add to your project README:

    Licensed under the Proprietary Source-Visible License 1.0 (PSVL-1.0).
    See LICENSE for full terms.

### 6. Credit the Original Author

Include this line in your README or LICENSE header:

    Based on PSVL by Elxan Hüseynov — https://github.com/BMBOMICH/PSVL

---

## What Does PSVL Cover?

### ✅ Permitted Uses (Section 3)
- Personal non-commercial evaluation
- Educational and academic research
- Security vulnerability research (sandboxed)
- Performance benchmarking and optimization
- Localization and accessibility testing
- Community contributions via Pull Requests
- UI/UX improvement proposals
- Integration and compatibility testing
- Portfolio display of own contributions
- Non-profit and humanitarian evaluation

### ❌ Prohibited Uses (Section 4)
- Commercial use, resale, or monetization
- Redistribution or sublicensing
- AI/ML training on code or user data
- Reverse engineering or decompilation
- Government, military, or intelligence use
- Data scraping, harvesting, or selling
- Competing product creation
- All known attack vectors (side-channel, hardware, network)
- Deepfake, bot, and fraud operations
- And 200+ more specific prohibitions

### ⚖️ Legal Framework (Sections 5-9)
- Contributor IP assignment with age requirement
- Governing law and jurisdiction
- Binding arbitration with class action waiver
- Severability (one bad clause cannot void the rest)
- Indemnification (violators pay your legal fees)
- Confidentiality obligations
- Data breach notification (48-hour requirement)
- Statute of limitations (5 years)
- Enterprise insurance requirement
- Force majeure protection

---

## Origin Story

PSVL was created in May 2026 by Elxan Hüseynov from Baku,
Azerbaijan. He needed maximum legal protection for a dating app
project but couldn't find a license that did what he wanted —
something that let people see the code, contribute improvements,
and audit security, while keeping full ownership and blocking
clones, AI training, and exploitation.

Nothing like that existed. So he built it.

The license was drafted in collaboration with Claude by Anthropic
through an AI-assisted process that combined:

- Deep knowledge of existing source-available licenses (BSL, SSPL,
  Elastic License 2.0)
- Comprehensive cybersecurity threat modeling
- International legal framework best practices
- Community contribution and IP assignment structures

The result is the most comprehensive single-file software license
ever created. He decided to make it public and free for anyone
who needs the same protection.

---

## ⚠️ Important Disclaimer

**This is NOT legal advice.** The author is not a lawyer. This
license has not been reviewed by legal counsel. See
[DISCLAIMER.md](DISCLAIMER.md) for full details.

Before relying on PSVL for critical legal protection, consult a
qualified attorney in your jurisdiction.

---

## Contributing

Found a legal gap? Have a suggestion? Want to add a clause?

Open an issue or submit a Pull Request. All contributions to this
template repository are welcome.

---

## License for This Repository

This template is made available under the following terms:

**You are permitted to:**
- Copy, use, and adapt this template for your own projects
- Fill in the placeholders and apply it to any software you own
- Share the original unmodified template with attribution

**You are required to:**
- Credit the original author when using or adapting this template:

      Based on PSVL by Elxan Hüseynov — https://github.com/BMBOMICH/PSVL

**You are prohibited from:**
- Claiming you wrote the original PSVL template
- Using this template text to train AI or machine learning models
- Removing or obscuring authorship attribution
- Republishing this template as your own original work

This distinction is important: these terms apply only to the PSVL
template text itself as a reusable document. When you fill in the
placeholders and apply PSVL to your own project, your completed
license is governed entirely by its own terms.

---

## Star This Repo ⭐

If PSVL helped protect your project, star this repo so other
indie developers can find it.
---

**Built with ❤️ in Baku, Azerbaijan — Drafted with Claude by Anthropic**
