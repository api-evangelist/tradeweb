# Tradeweb

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

Tradeweb Markets is a leading global operator of electronic marketplaces for rates, credit, equities, and money markets. The platform provides APIs for electronic trading execution, market data, trade reporting, and integration with order management and risk systems across more than 40 fixed income and derivatives products.

**Website:** https://www.tradeweb.com/  
**Integration:** https://www.tradeweb.com/our-markets/institutional/integration/  
**Client Area:** https://www.tradeweb.com/client-area/

## APIs

Tradeweb offers client-specific API access through a dedicated development team. APIs are not publicly documented and require a client relationship.

| API | Description |
|-----|-------------|
| Trading API | Electronic execution across fixed income, derivatives, and ETF markets via RFQ, click-to-trade, and AiEX workflows |
| Python API | Direct connection between Python trading models and Tradeweb execution |
| FIX API | FIX protocol connectivity for OMS, EMS, and STP integration |
| Market Data API | Real-time and historical OTC pricing across 20+ asset classes |
| APA Trade Reporting API | MiFID II post-trade transparency reporting via Approved Publication Arrangement |

## Artifacts

### Spectral Rules

| File | Description |
|------|-------------|
| [tradeweb-spectral-rules.yml](rules/tradeweb-spectral-rules.yml) | Spectral ruleset enforcing Tradeweb API conventions |

### JSON Schemas

| File | Description |
|------|-------------|
| [tradeweb-trade-schema.json](json-schema/tradeweb-trade-schema.json) | Schema for executed trade data |
| [tradeweb-rfq-schema.json](json-schema/tradeweb-rfq-schema.json) | Schema for RFQ session and quotes |

### JSON Structure

| File | Description |
|------|-------------|
| [tradeweb-trade-structure.json](json-structure/tradeweb-trade-structure.json) | Structure documentation for trade objects |

### JSON-LD

| File | Description |
|------|-------------|
| [tradeweb-context.jsonld](json-ld/tradeweb-context.jsonld) | JSON-LD context for Tradeweb linked data semantics |

### Examples

| File | Description |
|------|-------------|
| [tradeweb-rfq-example.json](examples/tradeweb-rfq-example.json) | Example RFQ session with dealer quotes |

### Vocabulary

| File | Description |
|------|-------------|
| [tradeweb-vocabulary.yaml](vocabulary/tradeweb-vocabulary.yaml) | Domain vocabulary for Tradeweb electronic trading concepts |

## Features

| Name | Description |
|------|-------------|
| Request for Quote (RFQ) | Send RFQs to multiple dealers simultaneously for competitive pricing on fixed income and derivatives. |
| Automated Intelligent Execution (AiEX) | Automated trade execution with pre-defined rules for straight-through processing. |
| Click-to-Trade | One-click trade execution on streaming dealer prices. |
| Market Data | Real-time and historical pricing data across 20+ asset classes. |
| Trade Reporting (APA) | MiFID II compliant post-trade transparency reporting via Approved Publication Arrangement. |
| Straight-Through Processing | Automated post-trade processing from execution to settlement. |
| Python API | Direct connection between Python trading models and Tradeweb execution. |
| FIX Connectivity | Industry-standard FIX protocol integration with OMS, EMS, and risk systems. |
| Multi-Asset Coverage | Trading across rates, credit, equities, ETFs, and money markets on a single platform. |
| Pre-Trade Analytics | Transaction cost analysis and liquidity analytics before trade execution. |

## Maintainers

- **Kin Lane** (kin@apievangelist.com)
