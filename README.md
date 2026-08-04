# Glia

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Glia (formerly SaleMove) is a digital customer service and applied-AI platform built for banks,
credit unions and insurers, unifying chat, voice, video, messaging and CoBrowsing under what the
company calls ChannelLess architecture.

The developer surface is a REST API at `api.glia.com` with regional US/EU hosts, a public Visitor
JS SDK for embedding engagements in web properties, native iOS/Android/Ionic widget SDKs published
to CocoaPods and Maven Central, and Glia Functions — a workerd-based serverless JavaScript runtime
with a first-party CLI and MCP server.

**Note on the contract.** Glia publishes no public OpenAPI. Its developer reference is served from
a Fern-hosted portal that redirects to a Glia account login, and `/openapi.json` on that host
returns `401`. The artifacts in this repository are therefore assembled from what *is* public:
observed HTTP responses from `api.glia.com`, Glia's own open-source API client and CLI, the public
Visitor JS SDK reference, published package registries, and the company's security, status and
compliance pages.

- Website — https://www.glia.com
- Developer portal (login required) — https://docs.glia.com/glia-dev
- Visitor JS SDK reference — https://sdk-docs.glia.com/visitor-js-api/current/
- GitHub — https://github.com/salemove
- Status — https://status.glia.com
- Security & compliance — https://www.glia.com/security
- Bug bounty — https://www.glia.com/security-bounty
