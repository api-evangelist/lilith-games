# Lilith Games

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
