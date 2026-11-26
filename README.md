# Mywalleteosz

**Smart-contract, backend, and security-focused developer.**

I build code-verified projects across Web3, backend engineering, and
application security. My public work includes Solidity and TON contract
tooling, generated blockchain clients, and TypeScript code for
security-sensitive flows. I am interested in AI systems, cybersecurity,
infrastructure, and developer tooling.

## About Me

- **Focus:** smart contracts, generated blockchain clients, TypeScript
  application code, and secure session handling.
- **Working style:** source-first — technologies and features are listed
  only when the repository code supports them.
- **Current interests:** Artificial Intelligence, Cybersecurity, Web3,
  Blockchain, Backend Engineering, DevOps / Infrastructure.
- **Profile:** [github.com/Mywalleteosz][profile]

## Technology Stack

Only technologies visible in the linked repositories are listed.

- **Languages:** Solidity, Tolk, TypeScript, JavaScript
- **Web3:** Hardhat, `viem`, Acton, TON, TonConnect, GitMyABI
- **Frontend:** React, Vite, Astro, CSS
- **Backend & tooling:** Node.js, npm, `node:test`, Hardhat Ignition,
  GitHub Actions
- **Security-related work:** SHA-256 digest storage, replay protection,
  session revocation, access-version invalidation

## Selected Projects

Repository visibility is stated explicitly. Private repositories are real
repositories, but their links are visible only to accounts with access.

### [gitmyabi-lab][gitmyabi-lab] — Public

Hardhat 3 laboratory for Solidity contracts and generated `viem` clients.

- **Stack:** Solidity, TypeScript, Hardhat 3, `viem`, `node:test`,
  GitMyABI, Hardhat Ignition
- **What the code does:** includes `Counter` (`inc`, `incBy`) plus
  `SimpleStorage` and `OwnerVault` contracts; configures ABI-to-`viem`
  client generation through `gma.config.json`; tests a generated client
  by deploying and calling it on a simulated network; provides Ignition
  modules and a Sepolia network configuration.
- **Repository:** [Mywalleteosz/gitmyabi-lab][gitmyabi-lab]

### [first_counter][first_counter] — Private

TON counter dApp derived from the Acton counter template.

- **Stack:** Tolk, Acton, TypeScript, React, Vite, TonConnect,
  GitHub Actions
- **What the code does:** implements an owner-controlled counter with
  increase, decrease, reset, and underflow checks; includes generated
  Tolk and TypeScript wrappers, integration tests for deployment and
  state changes, a React/Vite frontend wired for TON transactions, and
  CI workflows for contract and dApp checks.
- **Repository:** [Mywalleteosz/first_counter][first_counter] *(private)*

### [neon-relics-arena][neon-relics-arena] — Private

Security-focused Telegram session store. The repository README describes
a game; the current source confirms the session layer rather than gameplay.

- **Stack:** TypeScript, Node.js, `node:test`
- **What the code does:** creates Telegram sessions with a 12-hour TTL,
  stores only SHA-256 digests of session and CSRF tokens, rejects
  replayed `initData` digests with receipts, supports per-session
  revocation and access-version invalidation, and fails closed when
  storage is unavailable. A Node test suite covers these paths.
- **Repository:** [Mywalleteosz/neon-relics-arena][neon-relics-arena]
  *(private)*

### [astro-web3-dashboard][astro-web3-dashboard] — Private

Astro-based Web3 dashboard UI prototype.

- **Stack:** Astro, TypeScript, CSS
- **What the code does:** provides a static dashboard shell with
  navigation, a "Connect Wallet" button, and panels for wallet status,
  planned network integrations, and system status. The configured dev
  server runs on port 4321. No on-chain connection is implemented in the
  current source.
- **Repository:** [Mywalleteosz/astro-web3-dashboard][astro-web3-dashboard]
  *(private)*

## Areas of Interest

- **Artificial Intelligence:** AI agents and developer automation.
- **Cybersecurity:** secure session handling, replay resistance, and
  defensive application design.
- **Web3 / Blockchain:** Solidity and TON contracts, ABI-generated
  clients, wallet integrations.
- **Backend Engineering:** TypeScript services and contract-facing
  application logic.
- **DevOps / Infrastructure:** CI workflows, reproducible builds, and
  developer tooling.

## GitHub Statistics

Live statistics rendered by `github-readme-stats`.

![Stats](https://github-readme-stats.vercel.app/api?username=Mywalleteosz&show_icons=true&theme=default)

![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Mywalleteosz&layout=compact&theme=default)

## GitHub Activity

Snapshot of public events checked on 2026-11-26. For current activity, see
the [GitHub activity page][activity].

- 2026-11-08 — opened and closed issues in
  [OOOSEC-U2DPN][OOOSEC-U2DPN].
- 2026-11-02 — pushes to [gitmyabi-lab][gitmyabi-lab].
- 2026-10-27 — repository creation and pushes involving
  [Omine][Omine] and [gitmyabi-lab][gitmyabi-lab].

## Contact

- GitHub: [@Mywalleteosz][profile]
- Profile repository: [Mywalleteosz/Mywalleteosz][profile-repo]
- Public activity: [github.com/Mywalleteosz?tab=activity][activity]

[profile]: https://github.com/Mywalleteosz
[profile-repo]: https://github.com/Mywalleteosz/Mywalleteosz
[activity]: https://github.com/Mywalleteosz?tab=activity
[gitmyabi-lab]: https://github.com/Mywalleteosz/gitmyabi-lab
[first_counter]: https://github.com/Mywalleteosz/first_counter
[neon-relics-arena]: https://github.com/Mywalleteosz/neon-relics-arena
[astro-web3-dashboard]: https://github.com/Mywalleteosz/astro-web3-dashboard
[OOOSEC-U2DPN]: https://github.com/Mywalleteosz/OOOSEC-U2DPN
[Omine]: https://github.com/Mywalleteosz/Omine
