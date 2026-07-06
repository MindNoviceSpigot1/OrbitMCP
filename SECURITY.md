# Security Policy

## Our Approach

OrbitMCP is a read-focused crypto intelligence layer. It does not store private keys or seed phrases, and it does not sign or broadcast transactions on your behalf. All wallet and portfolio analysis is done using public, read-only blockchain data and third-party API providers (CoinGecko, DexScreener, Etherscan, etc.).

## Reporting a Vulnerability

If you discover a security vulnerability, please **do not open a public issue**. Instead:

1. Email the maintainers at: `security@orbitmcp.dev` *(replace with your real contact)*
2. Include a description of the vulnerability, steps to reproduce, and potential impact.
3. Allow a reasonable window for a fix before any public disclosure.

We aim to acknowledge reports within 48 hours.

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest release | ✅ |
| Older releases | ❌ |

## Best Practices for Users

- Always verify any transaction in your own wallet before signing — OrbitMCP will never ask for your private key or seed phrase.
- Only download releases from the official [Releases](../../releases) page of this repository.
- Keep your API keys (if you configure your own provider keys) out of version control.
