# Contributing

Forks in this organisation accept exactly one kind of change: a `git cherry-pick -x` of a commit
from `monero-project/monero` (`release-v0.18`) that fixes a clear security issue, with a
context-only conflict resolution if needed, plus an advisory entry in `SECURITY-BACKPORTS.md`.
See the policy in the home repo (`docs/POLICY.md`): what counts as a security issue, the
compatibility rules, and the workflow.

Not accepted: features, refactors, correctness-only fixes, dependency bumps without a current
CVE, own fixes, anything that changes consensus, relay, p2p, RPC or file formats.

To propose a backport: open an issue naming the Monero commit, the class of issue and why it
applies to Zephyr; a PR with the cherry-pick and a filled-in advisory is welcome. CI checks
provenance; the maintainer verifies compatibility (wallet cross-open, full-chain scan) before
a signed tag.
