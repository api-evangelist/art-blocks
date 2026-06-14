# Art Blocks

Art Blocks is the leading on-chain generative art platform where artists deploy deterministic algorithms to Ethereum, Arbitrum One, and Base. Each token is minted by invoking the on-chain script with a unique hash, producing a provably unique artwork stored permanently on the blockchain.

## APIs

| API | Base URL | Auth |
|-----|----------|------|
| Token API | `https://token.artblocks.io/{chainID}/{contractAddress}/{tokenID}` | None |
| Generator API | `https://generator.artblocks.io/{chainID}/{contractAddress}/{tokenID}` | None |
| Media Proxy API | `https://media-proxy.artblocks.io/{chainID}/{contractAddress}/{tokenID}.png` | None |
| Hasura GraphQL API | `https://data.artblocks.io/v1/graphql` | JWT |
| Subgraph (Ethereum) | The Graph Network | API Key |
| Subgraph (Arbitrum) | The Graph Network | API Key |
| Subgraph (Base) | The Graph Network | API Key |
| MCP Server | `https://mcp.artblocks.io/mcp` | OAuth 2.1 |

## Supported Networks

- Ethereum (chain ID 1)
- Arbitrum One (chain ID 42161)
- Base (chain ID 8453)
- Sepolia testnet (staging)

## Resources

- Website: https://www.artblocks.io
- Documentation: https://docs.artblocks.io
- GitHub: https://github.com/ArtBlocks
- Twitter: https://x.com/artblocks_io
- Discord: https://discord.gg/artblocks
- GraphQL Playground: https://cloud.hasura.io/public/graphiql?endpoint=https://data.artblocks.io/v1/graphql
