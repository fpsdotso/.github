# fps.so

<u>**This project is a submission to colosseum cypherpunk hackathon**</u>

> Fully onchain Real-time Multiplayer 5 vs 5 First Person Shooter Game on [Solana](https://solana.com) enabled by [Magicblock](https://magicblock.xyz)'s Ephemeral Rollup

---

## About
fps.so builds a fully on-chain, real-time 5v5 FPS on Solana — low-latency, composable, and playable in-browser. We focus on deterministic game logic, provable state, and smooth peer experiences.

[Game Website](https://fps.so) • [Pitch Video](https://example.com) • [Live demo](https://example.com) • [Discord](https://discord.gg/nFD4gBjC79)

## Key repositories
- [fpsdotso-contracts](https://github.com/fpsdotso/fpsdotso-contracts) — Programs that are deployed onto solana (includes matchmaking, map-registry and game)
- [fpsdotso-game](https://github.com/fpsdotso/fpsdotso-game) - Game Interface made with React and Rust [Raylib](https://raylib.com) WASM

## Highlights
- Fully on-chain game state and matchmaking
- Deterministic rollups for fairness and verification
- 5v5 real-time matches with ephemeral session scaling
- Browser-based client (no installs)

## Quick start — Play in 2 minutes
1. Open the demo: https://example.com
2. Connect wallet (Solana)
3. Click Play → Join/Create match

For local dev:
- Clone the repos listed above
- See each repo's README for local launch commands

## Architecture & Tech
- Blockchain: Solana
- Rollups: Magicblock Ephemeral Rollup
- Client: WebGL + wasm (TypeScript)
- Server / Orchestration: Rust / Node.js (on-chain validations)

## Contributing
We welcome contributors. Please:
1. Read CODE_OF_CONDUCT and CONTRIBUTING.md in each repo
2. Open issues for bugs or RFCs
3. Send PRs against main branch; include tests & changelog entries

## Governance & Roadmap
Planned: ranked matches, spectate mode, weapon economy. See the roadmap in the core repo.

## Contact
- Discord: https://discord.gg/nFD4gBjC79
- Twitter: [@fps_so](https://x.com/fpsdotso)
- Email: contact@yumequest.xyz