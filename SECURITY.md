# Security Policy

## Scope

In the context of PSVL, a "security issue" is a problem with the
**license text itself** that could undermine its protective purpose.
Examples include:

- An unintended legal loophole created by clause wording
- A contradiction between two clauses that could be exploited
- A clause that is void under mandatory law in a major jurisdiction
- An ambiguity that a bad actor could weaponize
- A missing protection in an area PSVL was meant to cover

PSVL is a license template, not software, so traditional vulnerability
classes (CVEs, exploits, etc.) do not apply. This policy adapts the
spirit of responsible disclosure to a legal document.

## Supported Versions

| Version | Supported |
|---|---|
| 1.0 | ✅ |

When new major versions are released, the previous major version will
continue to receive critical fixes for a reasonable period.

## How to Report

Please use GitHub's **"Report a vulnerability"** flow:

1. Go to the [**Security and quality tab**](https://github.com/BMBOMICH/psvl/security) of this repository
2. Click **"Report a vulnerability"** (or use the [**direct link**](https://github.com/BMBOMICH/psvl/security/advisories/new))
3. Describe the issue clearly, including:
   - The specific clause numbers affected
   - The exact wording at issue
   - The scenario or actor that could exploit the issue
   - Any suggested fix

This routes the report directly to the maintainer privately.

## What to Expect

- **Acknowledgment:** as soon as practicable (typically within a few
  business days; PSVL is maintained in spare time, not on a 24/7 SLA).
- **Assessment:** the maintainer will evaluate the report and respond
  with next steps.
- **Fix:** if the report is confirmed, a fix will be drafted, reviewed,
  and merged.
- **Credit:** if your report leads to a fix and you wish to be credited,
  you will be acknowledged in the [**CHANGELOG.md**](CHANGELOG.md).

## What NOT to Do

- ❌ **Do not** open a public issue for security-related concerns
- ❌ **Do not** publicly disclose the issue before it is addressed
  (or before a reasonable disclosure window has passed)
- ❌ **Do not** use a confirmed loophole against any project that has
  adopted PSVL

## Scope Limit

This policy covers the **PSVL template text itself**. If you are using
PSVL in your own project and experience a security incident, your own
completed license — not this repository — governs.

For Code-of-Conduct concerns (interpersonal conduct in this repository's
community), see [**CODE_OF_CONDUCT.md**](CODE_OF_CONDUCT.md), not this policy.
