# bOpen.io

**Open protocol developers and consultants. Be open. Be the source.**

Welcome to the team. This README contains internal resources and private repository links.

---

## Quick Links

| Resource | Link |
|----------|------|
| Main Site | [bopen.io](https://bopen.io) |
| 1Sat Ordinals | [1satordinals.com](https://1satordinals.com) |
| Sigma Identity | [sigmaidentity.com](https://sigmaidentity.com) |
| Gorilla Pool | [gorillapool.com](https://gorillapool.com) |
| TokenPass | [tokenpass.app](https://tokenpass.app) |

---

## Private Repositories

### Infrastructure and Services

| Repository | Description |
|------------|-------------|
| [bopen.io](https://github.com/b-open-io/bopen.io) | Main bOpen website |
| [gorillapool.com](https://github.com/b-open-io/gorillapool.com) | Gorilla Pool website |
| [gorillanode](https://github.com/b-open-io/gorillanode) | Node infrastructure |
| [sigma-auth](https://github.com/b-open-io/sigma-auth) | OAuth server with bitcoin-auth |
| [sigma-auth-web](https://github.com/b-open-io/sigma-auth-web) | Web components for Sigma Auth |
| [better-auth-plugin](https://github.com/b-open-io/better-auth-plugin) | Better Auth plugin |
| [tokenpass-server](https://github.com/b-open-io/tokenpass-server) | Personal identity server |
| [tokenpass.app](https://github.com/b-open-io/tokenpass.app) | TokenPass web app |
| [go-faucet-api](https://github.com/b-open-io/go-faucet-api) | Testnet faucet |

### Products and Applications

| Repository | Description |
|------------|-------------|
| [jamify](https://github.com/b-open-io/jamify) | Music platform |
| [jamify-hls](https://github.com/b-open-io/jamify-hls) | HLS streaming server |
| [scribe-desktop](https://github.com/b-open-io/scribe-desktop) | Work evidence desktop app |
| [HyperSwag](https://github.com/b-open-io/HyperSwag) | Collectibles platform |
| [mintflow](https://github.com/b-open-io/mintflow) | Minting workflows |
| [droplit](https://github.com/b-open-io/droplit) | Drop management |
| [bopen-ai](https://github.com/b-open-io/bopen-ai) | AI tools |

### SDKs and Libraries

| Repository | Description |
|------------|-------------|
| [1sat-sdk](https://github.com/b-open-io/1sat-sdk) | 1Sat Ordinals SDK |
| [bigblocks](https://github.com/b-open-io/bigblocks) | React component library |
| [bigblocks.dev](https://github.com/b-open-io/bigblocks.dev) | BigBlocks documentation site |
| [sigmaidentity](https://github.com/b-open-io/sigmaidentity) | Identity components |

### Overlay Services

| Repository | Description |
|------------|-------------|
| [bsv21-overlay-1sat-sync](https://github.com/b-open-io/bsv21-overlay-1sat-sync) | BSV-21 to 1Sat sync |
| [a2b-overlay](https://github.com/b-open-io/a2b-overlay) | A2B protocol overlay |
| [a2b](https://github.com/b-open-io/a2b) | A2B protocol |
| [gib-overlay](https://github.com/b-open-io/gib-overlay) | GIB protocol overlay |
| [gib](https://github.com/b-open-io/gib) | GIB protocol |

### Websites

| Repository | Description |
|------------|-------------|
| [openprotocollabs.com](https://github.com/b-open-io/openprotocollabs.com) | Open Protocol Labs site |
| [nodeless-website](https://github.com/b-open-io/nodeless-website) | Nodeless site |
| [sigmaidentity.com](https://github.com/b-open-io/sigmaidentity.com) | Sigma Identity site |
| [metalens.app](https://github.com/b-open-io/metalens.app) | MetaLens app |

### Projects

| Repository | Description |
|------------|-------------|
| [alchema-genesis](https://github.com/b-open-io/alchema-genesis) | Alchema genesis collection |
| [alchema-story](https://github.com/b-open-io/alchema-story) | Alchema narrative |
| [minerva](https://github.com/b-open-io/minerva) | Minerva project |
| [1sat-name](https://github.com/b-open-io/1sat-name) | Hackathon naming project |
| [agent-master](https://github.com/b-open-io/agent-master) | Agent orchestration |
| [agent-master-cli](https://github.com/b-open-io/agent-master-cli) | Agent CLI |

### Internal Tools

| Repository | Description |
|------------|-------------|
| [opl-admin](https://github.com/b-open-io/opl-admin) | Admin dashboard |
| [mnee-dashboard](https://github.com/b-open-io/mnee-dashboard) | MNEE dashboard |
| [mnee-cosigner](https://github.com/b-open-io/mnee-cosigner) | MNEE cosigner service |
| [bsocial-cli](https://github.com/b-open-io/bsocial-cli) | BSocial CLI tools |
| [demo-repository](https://github.com/b-open-io/demo-repository) | Demo and examples |
| [design-productive](https://github.com/b-open-io/design-productive) | Design assets |

---

## Public Repositories

See the [public organization profile](https://github.com/b-open-io) for the full list of open source projects.

Key public repos:

- [bitcoin-auth](https://github.com/b-open-io/bitcoin-auth) - Bitcoin message signing/verification
- [bsv-mcp](https://github.com/b-open-io/bsv-mcp) - MCP server for AI tools
- [bsv-skills](https://github.com/b-open-io/bsv-skills) - Claude Code plugin
- [ordfs-server](https://github.com/b-open-io/ordfs-server) - ORDFS file server
- [go-overlay-services](https://github.com/b-open-io/go-overlay-services) - Overlay engine
- [prompts](https://github.com/b-open-io/prompts) - AI prompts for Bitcoin development

---

## Development

### Claude Code Plugins

Install our Claude Code plugins for enhanced Bitcoin development:

```bash
# BSV blockchain operations
claude plugins add b-open-io/bsv-skills

# 1Sat Ordinals NFT operations
claude plugins add b-open-io/1sat-skills

# Project color awareness
claude plugins add b-open-io/claude-peacock
```

### Common Commands

```bash
# Run local build before pushing
bun run build

# Type check
bun run typecheck

# Lint
bun run lint
```

---

*Building the future of Bitcoin, one satoshi at a time.*
