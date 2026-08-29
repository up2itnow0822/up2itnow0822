# Building the AI Agent Economy

[![Discord](https://img.shields.io/discord/1475549260140253194?label=Community&logo=discord&color=5865F2)](https://discord.gg/958AACqf7Y)

**Open-source policy and proof for agents that spend money.**

## The payment trial

Basic payment execution is becoming commodity infrastructure. We're testing a
narrower claim: teams won't let buyer agents spend at scale without budgets,
approval rules, idempotency, receipts, and an audit trail.

Three repositories make up that trial:

| Repository | Role | Current gate |
| --- | --- | --- |
| [agent-wallet-sdk](https://github.com/up2itnow0822/agent-wallet-sdk) | Non-custodial spending policy and signed receipts | One observed external policy-governed transaction |
| [agentpay-mcp](https://github.com/up2itnow0822/agentpay-mcp) | Policy-aware x402 payment tools for MCP clients | One credible buyer-agent pilot commitment |
| [agentpay-wallet-starter](https://github.com/up2itnow0822/agentpay-wallet-starter) | Controlled end-to-end proof path | Green CI and one independent completion under 15 minutes |

These are trial gates, not claims of product-market fit. Stars, downloads, and
our own demos don't count as independent use.

## Try the current packages

```bash
npm install agentwallet-sdk
npx -y agentpay-mcp
```

For the combined path, start with the
[wallet starter](https://github.com/up2itnow0822/agentpay-wallet-starter).

## How we build

- Agents keep control of their keys.
- Spending decisions produce portable evidence.
- Claims stay bounded by tests, external use, and paid outcomes.
- Recursive self-improvement work must clear reproducible benchmark gates.

## Links

- [AI Agent Economy](https://ai-agent-economy.com/#products)
- [Discord community](https://discord.gg/958AACqf7Y)
- [GitHub repositories](https://github.com/up2itnow0822?tab=repositories)

Read the code before you trust the pitch. Issues and pull requests are welcome.
