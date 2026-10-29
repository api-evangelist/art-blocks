# Art Blocks

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Art Blocks is the leading on-chain generative art platform where artists deploy deterministic code to Ethereum, Arbitrum One, and Base; each token is minted by invoking the script with a unique hash, producing a one-of-a-kind artwork stored permanently on-chain. The platform exposes four public API surfaces: a Token API that returns ERC-721 metadata conforming to the OpenSea standard, a Generator API that serves an iframe-able live view of each artwork, a Media Proxy API that provides static PNG renders, and a Hasura GraphQL API (data.artblocks.io) that gives structured access to on-chain and off-chain data including projects, tokens, artists, features, minting configuration, and ownership. Decentralised access is available through The Graph subgraph for on-chain-only data across all three networks. An MCP Server with 21 tools enables AI-agent integration for querying, minting, and generative script scaffolding.

**Areas:** Generative Art · NFT · On-Chain Art · Blockchain · Ethereum · Arbitrum · Base · GraphQL · Token Metadata · Web3 · Smart Contracts · The Graph

## Art Blocks on APIs.io

Everything profiled for Art Blocks is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/art-blocks/](https://apis.io/providers/art-blocks/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Art Blocks GraphQL API (Hasura)](https://apis.io/apis/art-blocks/graphql-api/) — Hasura-backed GraphQL API providing structured access to on-chain and off-chain Art Blocks data including projects, tokens, artists, contracts, minter…
- [Art Blocks Subgraph — Ethereum](https://apis.io/apis/art-blocks/subgraph-ethereum/) — Decentralised subgraph on The Graph Network providing on-chain-only data for Art Blocks tokens, projects, and ownership on Ethereum mainnet. Uses camelCase…
- [Art Blocks Subgraph — Arbitrum One](https://apis.io/apis/art-blocks/subgraph-arbitrum/) — Decentralised subgraph on The Graph Network providing on-chain-only data for Art Blocks tokens, projects, and ownership on Arbitrum One. Requires a…
- [Art Blocks Subgraph — Base](https://apis.io/apis/art-blocks/subgraph-base/) — Decentralised subgraph on The Graph Network providing on-chain-only data for Art Blocks tokens, projects, and ownership on Base. Requires a developer API…
- [Art Blocks MCP Server](https://apis.io/apis/art-blocks/mcp-server/) — Model Context Protocol server exposing 21 tools for AI agents to interact with the Art Blocks ecosystem across Ethereum, Arbitrum, and Base. Tools cover…
- [Art Blocks Generator API](https://apis.io/apis/art-blocks/art-blocks-generator-api/) — Live generative artwork view endpoints.
- [Art Blocks Media API](https://apis.io/apis/art-blocks/art-blocks-media-api/) — Static image media proxy endpoints.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Art Blocks GraphQL API](https://apis.io/graphqls/art-blocks/art-blocks-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [mcp](https://apis.io/servers/art-blocks/mcp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Art Blocks Agentic Access](https://apis.io/agentic-access/art-blocks/art-blocks-agentic-access/)

#### Collections (3)

Postman and Open Collection request collections.

- [Art Blocks Generator API](https://apis.io/collections/art-blocks/open-art-blocks-generator-api/)
- [Art Blocks Generator Media API](https://apis.io/collections/art-blocks/open-art-blocks-media-api/)
- [Art Blocks Generator Token Metadata API](https://apis.io/collections/art-blocks/open-art-blocks-token-metadata-api/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Art Blocks Domain Security](https://apis.io/security/art-blocks/art-blocks-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Art Blocks Plans](https://apis.io/plans/art-blocks/art-blocks-plans/)

#### Rate limits (1)

Published request limits.

- [Art Blocks Rate Limits](https://apis.io/rate-limits/art-blocks/art-blocks-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Art Blocks Finops](https://apis.io/finops/art-blocks/art-blocks-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.artblocks.io)
- [Documentation](https://docs.artblocks.io)
- [Blog](https://www.artblocks.io/articles)
- [GitHub](https://github.com/ArtBlocks)

## API Evangelist rating

**Kin Score 25.5** — emerging · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.3 |
| Contract quality | 50.8 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 20.2 |
| Access clarity | 7.9 |

**Agent readiness 57.8** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | na |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | flavored (partial credit) |
| Dry Run Mode | na |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/art-blocks/](https://apis.io/providers/art-blocks/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Art Blocks: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/art-blocks/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
