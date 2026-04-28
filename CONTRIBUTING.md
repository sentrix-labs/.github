# Sentrix Labs — Contributing

This is the org-wide contributing guide. Individual repos may add specifics in their own `CONTRIBUTING.md`.

Currently active repos:

- **`sentrix-labs/sentrix`** — L1 chain (Rust). PRs: tests + clippy clean + docs updates required for behavior changes.
- **`sentrix-labs/canonical-contracts`** — Solidity contracts. PRs: forge tests + slither clean + clear deploy + verification path.
- **`sentrix-labs/brand-kit`** — design assets. PRs: respect license + match brand guide.

## How to contribute

1. **Find an issue or open a discussion first** — for non-trivial changes, propose your approach in a GitHub issue or Discussion before opening a PR. This avoids wasted work if direction differs.
2. **Fork + branch** — typical GitHub flow. Branch naming: `feat/short-desc`, `fix/short-desc`, `docs/short-desc`.
3. **Run the local test gate** before opening PR:
   - `sentrix`: `cargo test --workspace --release && cargo clippy --workspace --tests --release -- -D warnings`
   - `canonical-contracts`: `forge test && slither contracts/`
4. **Open the PR** — include a clear description, link to relevant issue / Discussion, and tick the PR template checkboxes.
5. **Address review feedback** — repos enforce review-before-merge.

## What we look for

- **Tests:** new code should have tests. Bug fixes should include a regression test.
- **Docs:** behavior changes update the relevant docs in the same PR (or follow-up PR linked from same Discussion).
- **Style:** match the surrounding code; don't reformat unrelated lines.
- **Atomic commits:** one logical change per PR. Big multi-concern PRs are hard to review.

## Code of conduct

Be respectful. Disagreements are fine; ad hominem is not. We follow the spirit of the [Contributor Covenant](https://www.contributor-covenant.org/) for behavior expectations even where it's not formally adopted.

## Reporting bugs

- For **security issues**, follow [`SECURITY.md`](SECURITY.md) — do not open public issues for vulnerabilities.
- For **non-security bugs**, open an issue in the relevant repo with reproduction steps + expected vs. actual behavior.

## Communication channels

- **GitHub Discussions** (per-repo) — design conversations, feature proposals, Q&A
- **Telegram:** see org profile README for current invite link
- **Email:** for private / sensitive matters, see contact addresses in [`profile/README.md`](profile/README.md)

## License

Each repo's contributions are governed by that repo's `LICENSE` file. Most code is BUSL-1.1 (with conversion to Apache/MIT after a change date); contracts are MIT; brand assets are proprietary. By submitting a PR you agree your contribution is licensed under the receiving repo's license.
