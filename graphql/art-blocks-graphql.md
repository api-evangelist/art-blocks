# Art Blocks GraphQL API

The Art Blocks Hasura GraphQL API provides structured access to on-chain and off-chain data for the Art Blocks generative art platform. It exposes projects, tokens, artists, contracts, minter configurations, auction bids, ownership/transfers, dependencies, tags, favorites, showcases, and partner data across Ethereum mainnet, Arbitrum One, and Base. All major tables include aggregate variants and support Hasura-style boolean expression filtering and order-by arguments. The API also exposes real-time subscriptions via the `subscription_root`.

Authentication is required for write operations and personalized queries (such as `favorited_by_user`). Unauthenticated read access is available for most public data. Authentication uses a JWT obtained by signing a challenge message with an Ethereum wallet address.

**Endpoint:** https://data.artblocks.io/v1/graphql

**Playground:** https://cloud.hasura.io/public/graphiql?endpoint=https://data.artblocks.io/v1/graphql

**Documentation:** https://docs.artblocks.io/developer/graphql/

**References:**
- Documentation: https://docs.artblocks.io/developer/graphql/
- GettingStarted: https://docs.artblocks.io/developer/graphql/
- Playground: https://cloud.hasura.io/public/graphiql?endpoint=https://data.artblocks.io/v1/graphql
- GitHub: https://github.com/ArtBlocks
