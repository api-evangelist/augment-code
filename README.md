# Augment Code

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

Augment Code is a context-aware AI platform for software engineering teams. The flagship is Cosmos, a "unified agents platform" for agentic software development at organizational scale, packaged as a set of specialized agents — Work Dispatcher (triages tickets), PR Author (drives tasks from first commit through merge), Pair Review and Deep Code Review (inline review feedback), and Tester (verification of changes end-to-end). The product also ships the Auggie CLI for local use and IDE plugins for Visual Studio Code and JetBrains. Augment is built around a proprietary Context Engine for codebase understanding and a unified agents runtime with scheduling, sandboxed execution, and human-in-the-loop escalation. Deployment options span local, managed cloud, customer cloud (AWS, GCP), and on-premises. As of this writing Augment does not advertise a public REST API — it is a product-led, partner-driven surface — so this profile documents the product surfaces and developer resources rather than endpoint shapes.

**Areas:** AI Coding Agents · Context Engine · IDE Plugin · Cosmos · Auggie CLI · Software Engineering

## Augment Code on APIs.io

Everything profiled for Augment Code is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/augment-code/](https://apis.io/providers/augment-code/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Augment Cosmos](https://apis.io/apis/augment-code/cosmos/) — Cosmos is Augment's unified agents platform for agentic software development at organizational scale. It bundles specialized agents — Work Dispatcher…
- [Auggie CLI](https://apis.io/apis/augment-code/auggie-cli/) — Auggie is Augment's command-line interface that brings the Augment agent, Context Engine, and tool integrations to the terminal for local development.
- [Augment for Visual Studio Code](https://apis.io/apis/augment-code/vscode-plugin/) — IDE plugin that surfaces Augment's Context Engine and agent capabilities inside Visual Studio Code for completion, chat, and inline edits.
- [Augment for JetBrains](https://apis.io/apis/augment-code/jetbrains-plugin/) — IDE plugin for IntelliJ IDEA, PyCharm, GoLand, and other JetBrains IDEs.
- [Augment Context Engine](https://apis.io/apis/augment-code/context-engine/) — Proprietary indexing and retrieval engine that gives Augment's agents codebase-aware context — intelligent file selection, organization knowledge, and…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Moved to /providers/augment-code/](https://apis.io/servers/augment-code/augment-code/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Augment Code Domain Security](https://apis.io/security/augment-code/augment-code-domain-security/)
- [Augment Code Trust Center](https://apis.io/security/augment-code/augment-code-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Augment Code Plans Pricing](https://apis.io/plans/augment-code/augment-code-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Augment Code Rate Limits](https://apis.io/rate-limits/augment-code/augment-code-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Augment Code Finops](https://apis.io/finops/augment-code/augment-code-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.augmentcode.com/)
- [Documentation](https://docs.augmentcode.com)
- [Pricing](https://www.augmentcode.com/pricing)
- [Support](https://docs.augmentcode.com)
- [Blog](https://www.augmentcode.com/blog)

## API Evangelist rating

**Kin Score 19.8** — emerging · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 5.3 |
| Developer ergonomics | 26.2 |
| Access clarity | 36.8 |

**Agent readiness 9.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/augment-code/](https://apis.io/providers/augment-code/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Augment Code: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/augment-code/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
