# JIPs - JSS Improvement Proposals

JIPs are proposals for improving the [JavaScript Solid Server](https://github.com/JavaScriptSolidServer/JavaScriptSolidServer).

Inspired by [BIPs](https://github.com/bitcoin/bips) (Bitcoin) and [NIPs](https://github.com/nostr-protocol/nips) (Nostr).

## List of JIPs

| JIP | Title | Status |
|-----|-------|--------|
| [JIP-0001](jip-0001.md) | did:nostr Authentication & Schnorr Signatures | Draft |

## Process

### Proposing a JIP

1. Fork this repository
2. Copy `template.md` to `jip-XXXX.md` (use next available number)
3. Write your proposal following the template
4. Submit a Pull Request
5. Discuss in PR comments

### Statuses

| Status | Meaning |
|--------|---------|
| **Draft** | Initial proposal, open for discussion |
| **Review** | Being reviewed for implementation |
| **Final** | Accepted specification |
| **Implemented** | Merged into JSS |
| **Withdrawn** | Proposal withdrawn by author |
| **Rejected** | Not accepted after review |

### What belongs in a JIP?

- New authentication methods
- Protocol extensions
- API changes
- Interoperability features
- Client-client standards (data shapes, discovery)

### What doesn't need a JIP?

- Bug fixes
- Minor improvements
- Documentation updates
- Refactoring

## Philosophy

JIPs should be:
- **Concise** - Get to the point
- **Implementable** - Clear enough to code from
- **Compatible** - Work with existing Solid specs where possible
- **Decentralized** - Favor user control and interoperability

## History

The JIP process was created in December 2024 to provide a lightweight proposal system for JSS, similar to how NIPs work for Nostr.

## License

All JIPs are released under [CC0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain).
