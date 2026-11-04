# Security

This organisation **backports** published security fixes from Monero into Zephyr releases. It is not
the place to report new vulnerabilities in Zephyr: report those to the ZephyrProtocol team, who own
the code and the protocol. We do not develop fixes of our own.

If you find a problem **in a backport itself** (a cherry-pick that misbehaves, breaks compatibility
with upstream, or does not match its advisory), open an issue on the fork or mail
**zephyr-backports@lateo.dev**. That address only receives; the reply comes from the maintainer's own
address (`loki-notfound@proton.me`), signed with the maintainer key. For encrypted mail use the
maintainer key (`keys/loki-notfound.asc` in the home repo, fingerprint there), not the release key,
which is sign-only. Every backport has an advisory in `SECURITY-BACKPORTS.md` with origin, impact,
compatibility statement and test evidence.
