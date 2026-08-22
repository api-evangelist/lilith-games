# Lilith Games

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

Lilith Games (上海莉莉丝网络科技有限公司) is a Shanghai-headquartered video game developer and publisher founded in 2013, known for globally distributed mobile and PC titles including Rise of Kingdoms (万国觉醒), AFK Arena (剑与远征), AFK Journey (剑与远征：启程), Farlight 84 (远光84), Warpath (战火勋章) and Art of Conquest (剑与家园).

Backed by: idg-capital

## API surface

Lilith Games is a consumer game publisher, not an API platform. As of the 2026-07-19 enrichment pass it publishes **no public API, developer portal, API documentation, or partner API program**. No `developer.`, `open.`, `api.`, `status.` or `trust.` subdomain resolves, and every `/.well-known/` discovery path returns a hard 404.

Its public engineering surface is the [LilithGames GitHub organization](https://github.com/lilithgames) — open-sourced backend and build infrastructure (Go networking and reverse-proxy tooling, build caching, Perforce virtual file system work) rather than client SDKs for a Lilith API.

## Artifacts

| Artifact | Method | Notes |
|---|---|---|
| `llms/lilith-games-llms.txt` | searched | Real published `/llms.txt` (200, 4,470 bytes), saved verbatim — an SEO-oriented LLM knowledge base |
| `well-known/lilith-games-well-known.yml` | searched | `/.well-known/` probe index; all paths 404 (verified true negatives) |
| `security/lilith-games-domain-security.yml` | probed | TLS 1.3, no HSTS, no DNSSEC, no CAA, SPF present, no DMARC |

Spec-dependent artifacts (OpenAPI, overlays, MCP, skills, conventions, errors, data model, scopes, authentication, sandbox, CLI, changelog) are **not applicable** — there is no API to ground them in. No vulnerability-disclosure program or trust center was found.
