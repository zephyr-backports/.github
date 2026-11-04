# zephyr-backports

Security backports for [Zephyr Protocol](https://github.com/ZephyrProtocol), Debian-security style:
the upstream release **plus** security fixes cherry-picked from Monero (the project Zephyr is
derived from), tagged `vX.Y.Z-sec.N`, fully compatible with upstream, GPG-signed.

**Not affiliated with ZephyrProtocol.** An independent, community effort. We do not write fixes of
our own; we only backport fixes that Monero has published. Report Zephyr security issues to the
ZephyrProtocol team.

- Policy, inventories, advisories and tooling: [`zephyr-backports`](https://github.com/zephyr-backports/zephyr-backports)
- Forks: `zephyr` (branch `security/v2.3.0`), `zephyr-cpp`, `zephyr-javascript` as needed
- Contact: zephyr-backports@lateo.dev (GPG via WKD); not for reporting Zephyr vulnerabilities, see SECURITY.md
- Every commit above an upstream tag is a `git cherry-pick -x` from `monero/release-v0.18`, checked by CI
