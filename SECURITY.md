# Sentrix Labs — Security Policy

This is the org-wide security policy for `sentrix-labs`. Individual repos may have additional repo-specific guidance in their own `SECURITY.md` (see `sentrix-labs/sentrix/SECURITY.md` and `sentrix-labs/canonical-contracts/SECURITY.md` for chain-specific and contract-specific details).

## Reporting a vulnerability

**Do not open a public GitHub issue for security issues.** Please report responsibly.

Two channels:

1. **Email:** `security@sentrixchain.com`
2. **GitHub Security Advisories:** https://github.com/sentrix-labs/sentrix/security/advisories/new (private, encrypted)

## What to include

- Description of the vulnerability
- Reproduction steps
- Impact assessment (which assets / users could be affected)
- Suggested fix or mitigation, if you have one

## Response SLA

- **Acknowledgement:** within 24 hours of receipt
- **Initial assessment:** within 72 hours
- **Patch development:** within 7 days for critical / high severity
- **Public disclosure / release:** within 14 days, coordinated with reporter

## Severity levels

| Level | Examples |
|---|---|
| **Critical** | Fund loss, consensus break, validator key compromise, signature forgery |
| **High** | DoS that halts the chain, privilege escalation, contract upgrade hijack |
| **Medium** | Crashes that don't lose funds, partial degradation, info leak |
| **Low** | Best-practice deviation, performance issue, doc inaccuracy |

## Safe harbor

Researchers acting in good faith — testing the protocol, reporting privately, not exploiting findings beyond what's needed to demonstrate the issue, not damaging user data — are protected from legal action by Sentrix Labs.

## Hall of Fame

Public credit for responsible disclosure is published in chain release notes and in the repo-specific SECURITY.md hall-of-fame sections. Coordinate timing with the security team.

## Scope

The org's main protocol code is in:

- **`sentrix-labs/sentrix`** — L1 Rust core (consensus, storage, networking, RPC, EVM integration)
- **`sentrix-labs/canonical-contracts`** — Solidity contracts (WSRX, Multicall3, SentrixSafe, TokenFactory)
- **`sentrix-labs/brand-kit`** — assets only, no security-relevant code

For non-security bugs, file a regular issue in the relevant repo.
