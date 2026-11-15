<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# Awesome Protocol and cryptographic verification

Symbolic and computational protocol-verification tools, secrecy/authentication queries and attack traces. This is not a general network-security checklist.

**Status:** starter collection, 2026-11-15. Curator: unassigned. These are independently written short annotations of external resources; no benchmark, integration, solver invocation or checker execution has been performed for this starter.

## Learn and get started

- [Tamarin project](https://tamarin-prover.com/) — Multiset-rewriting protocol analysis and security lemmas.
- [Tamarin source](https://github.com/tamarin-prover/tamarin-prover) — Inspect documented analysis engine behavior and releases.
- [ProVerif project](https://bblanche.gitlabpages.inria.fr/proverif/) — Applied-pi and protocol security analysis; check supported models and abstractions.

## References and implementations

- [EasyCrypt](https://www.easycrypt.info/) — Machine-checked cryptographic proofs and game-based reasoning.
- [EasyCrypt source](https://github.com/EasyCrypt/easycrypt) — Proof developments, tactics and release history.
- [CryptoVerif](https://crypto-verif.inria.fr/) — Computational cryptographic protocol proofs and tool documentation.

## Benchmark, examples and community paths

- [Tamarin case studies](https://github.com/tamarin-prover/tamarin-prover) — Start with maintained examples and record the exact adversary model.

## First exercise — not executed here

Compare the secrecy claim and adversary assumptions of a small protocol in one maintained example, then alter a message dependency and inspect any attack trace.

## Evidence and interoperability

A successful symbolic secrecy query depends on the chosen attacker model, equational theory and assumptions; it is not a blanket guarantee for a deployed protocol or implementation.

Capture provenance (source commit, tool and checker versions, flags, inputs, assumptions, certificate formats, output status, elapsed time, licence) before using an entry in a research/assurance claim.

## Upstream survey, curation and contribution

A preliminary survey on 2026-11-15 compared broader resources such as [awesome-formal-verification](https://github.com/hohieuai/awesome-formal-verification), [formal-verification-resources](https://github.com/astrio-labs/formal-verification-resources), plus canonical projects above. This is not an exhaustive survey and no external descriptions were imported. The focused value here is evidence-aware navigation and links from the [ECHIDNA coverage ledger](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/CATALOGUE.adoc). Inclusion is not an endorsement, and upstream materials retain their respective licences.

Contribute fixes and additional learning material through an [issue](https://github.com/stuff-of-awe/awesome-protocol-verification/issues) or [PR](https://github.com/stuff-of-awe/awesome-protocol-verification/pulls); see [maintenance policy](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/MAINTENANCE.adoc). Original annotations are CC-BY-SA-4.0. Collectors and maintainers are invited; quarterly review is a goal, not evidence of actual review.
