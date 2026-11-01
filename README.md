# Understudy Labs

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

Understudy Labs (YC S26) is an LLM gateway and model-optimization platform that helps teams move repeated production LLM workloads onto open-weight models they own. The Understudy gateway is a drop-in replacement for the Anthropic and OpenAI API endpoints that captures request/response traces by project and workload, routes measured slices of traffic to managed open models, and falls back safely. A REST control plane manages keys, projects, workloads, routing, captures, evaluation cohorts, and reporting, while the MIT-licensed understudy-agent-tools repo ships a CLI, a coding-agent skill library, a local MCP server, and Understudy Desktop with a documented loopback OpenAPI 3.1 contract.

**Areas:** Artificial Intelligence · LLM Gateway · Machine Learning · Open Source · Model Routing · Evaluation · Fine-Tuning · AI Infrastructure · Developer Tools

## Understudy Labs on APIs.io

Everything profiled for Understudy Labs is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/understudy-labs/](https://apis.io/providers/understudy-labs/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Understudy Gateway API](https://apis.io/apis/understudy-labs/understudy-gateway-api/) — Anthropic- and OpenAI-compatible LLM proxy at api.understudylabs.com. POST /v1/messages (Anthropic Messages), POST /v1/chat/completions (OpenAI Chat…
- [Understudy Control Plane API](https://apis.io/apis/understudy-labs/understudy-control-plane-api/) — REST surface behind the dashboard and CLI, served from the gateway host under /admin/v1 and /customer/v1, org-scoped and authenticated with sk_* bearer…
- [Understudy Labs Capabilities API](https://apis.io/apis/understudy-labs/understudy-labs-capabilities-api/) — The Capabilities API from Understudy Labs — 1 operation(s) for capabilities.
- [Understudy Labs Conversations API](https://apis.io/apis/understudy-labs/understudy-labs-conversations-api/) — The Conversations API from Understudy Labs — 1 operation(s) for conversations.
- [Understudy Labs Downloads API](https://apis.io/apis/understudy-labs/understudy-labs-downloads-api/) — The Downloads API from Understudy Labs — 3 operation(s) for downloads.
- [Understudy Labs Feedback API](https://apis.io/apis/understudy-labs/understudy-labs-feedback-api/) — The Feedback API from Understudy Labs — 1 operation(s) for feedback.
- [Understudy Labs Metrics API](https://apis.io/apis/understudy-labs/understudy-labs-metrics-api/) — The Metrics API from Understudy Labs — 1 operation(s) for metrics.
- [Understudy Labs Models API](https://apis.io/apis/understudy-labs/understudy-labs-models-api/) — The Models API from Understudy Labs — 2 operation(s) for models.
- [Understudy Labs Residency API](https://apis.io/apis/understudy-labs/understudy-labs-residency-api/) — The Residency API from Understudy Labs — 6 operation(s) for residency.
- [Understudy Labs Runs API](https://apis.io/apis/understudy-labs/understudy-labs-runs-api/) — The Runs API from Understudy Labs — 2 operation(s) for runs.
- [Understudy Labs Status API](https://apis.io/apis/understudy-labs/understudy-labs-status-api/) — The Status API from Understudy Labs — 1 operation(s) for status.
- [Understudy Labs Supervision API](https://apis.io/apis/understudy-labs/understudy-labs-supervision-api/) — The Supervision API from Understudy Labs — 1 operation(s) for supervision.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (1)

Multi-step workflows that chain operations into a business task.

- [Download, warm, and chat with a local model on Understudy Desktop](https://apis.io/arazzos/understudy-labs/understudy-labs-download-warm-and-chat/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [understudy-explore](https://apis.io/servers/understudy-labs/understudy-explore/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Understudy Labs Agentic Access](https://apis.io/agentic-access/understudy-labs/understudy-labs-agentic-access/)

#### Collections (10)

Postman and Open Collection request collections.

- [Understudy Desktop Agent Capabilities API](https://apis.io/collections/understudy-labs/open-understudy-labs-capabilities-api/)
- [Understudy Desktop Agent Capabilities Conversations API](https://apis.io/collections/understudy-labs/open-understudy-labs-conversations-api/)
- [Understudy Desktop Agent Capabilities Downloads API](https://apis.io/collections/understudy-labs/open-understudy-labs-downloads-api/)
- [Understudy Desktop Agent Capabilities Feedback API](https://apis.io/collections/understudy-labs/open-understudy-labs-feedback-api/)
- [Understudy Desktop Agent Capabilities Metrics API](https://apis.io/collections/understudy-labs/open-understudy-labs-metrics-api/)
- [Understudy Desktop Agent Capabilities Models API](https://apis.io/collections/understudy-labs/open-understudy-labs-models-api/)
- [Understudy Desktop Agent Capabilities Residency API](https://apis.io/collections/understudy-labs/open-understudy-labs-residency-api/)
- [Understudy Desktop Agent Capabilities Runs API](https://apis.io/collections/understudy-labs/open-understudy-labs-runs-api/)
- [Understudy Desktop Agent Capabilities Status API](https://apis.io/collections/understudy-labs/open-understudy-labs-status-api/)
- [Understudy Desktop Agent Capabilities Supervision API](https://apis.io/collections/understudy-labs/open-understudy-labs-supervision-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Understudy Labs Desktop Api Overlay](https://apis.io/overlays/understudy-labs/understudy-labs-desktop-api-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Understudy Labs Authentication](https://apis.io/security/understudy-labs/understudy-labs-authentication/)
- [Understudy Labs Domain Security](https://apis.io/security/understudy-labs/understudy-labs-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://understudylabs.com)
- [Documentation](https://docs.understudylabs.com)
- [Getting started](https://docs.understudylabs.com/quickstart)
- [API reference](https://docs.understudylabs.com/reference/proxy-endpoints)
- [Support](https://understudylabs.com/contact)
- [Blog](https://understudylabs.com/research)
- [Terms of service](https://understudylabs.com/terms)
- [Privacy policy](https://understudylabs.com/privacy)
- [GitHub](https://github.com/understudylabs)

## API Evangelist rating

**Kin Score 42.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 43.0 |
| Contract governance | 18.2 |
| Operational transparency | 18.4 |
| Developer ergonomics | 71.4 |
| Access clarity | 27.6 |

**Agent readiness 29.4** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/understudy-labs/](https://apis.io/providers/understudy-labs/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Understudy Labs: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/understudy-labs/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
