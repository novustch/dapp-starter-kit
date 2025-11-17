# Turbo DApp Starter Kit

Turbo DApp Starter Kit is a professionally curated full‑stack template for building decentralized applications. It combines modern frontend tooling with opinionated Web3 integrations and a contract development workflow to help teams bootstrap production‑grade DApps quickly.

## Key Features

- **Frontend:** Next.js 15 (App Router, Server Components), Tailwind CSS v4, and `shadcn/ui` for accessible UI primitives.
- **Wallet & Clients:** RainbowKit for wallet UX, Wagmi hooks for common wallet interactions, and Viem as a TypeScript‑first Ethereum client.
- **Contracts & Deployment:** Hardhat for development and testing, Solidity contracts, and Ignition to manage opinionated deployments.

## Tech Stack

- **Frontend:** `Next.js`, `Tailwind CSS`, `shadcn/ui`
- **Wallet Integration:** `RainbowKit`, `Wagmi`
- **Blockchain:** `Hardhat`, `Solidity`, `Viem`
- **Deployment:** `Ignition` (Hardhat), with optional Docker support for environment parity

## Getting Started

Prerequisites:

- Node.js (v18+ recommended)
- `pnpm` (this repository uses a pnpm workspace)

Quick start (Windows PowerShell):

```powershell
pnpm install
cd apps/web
pnpm dev
```

To run the smart contract tests and scripts:

```powershell
cd packages/contracts
pnpm install
pnpm test
```

For detailed development workflows, deployment guides, and configuration options, refer to the documentation in the `apps/web` and `packages/contracts` directories.

## Contributing

Contributions are welcome. Please open an issue to discuss significant changes or improvements before submitting a pull request. Follow the repository coding conventions and include tests for new functionality where applicable.

## License

This project is provided under the terms of the [MIT License](./LICENSE) unless otherwise specified. If no `LICENSE` file is present, please contact the maintainers for licensing details.

---

If you would like, I can also:

- Add a short developer quickstart with environment variables
- Add CI and code quality badges
- Expand sections for deployment and testing with exact commands

Tell me what you'd like next.
