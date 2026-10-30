# ID.me

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

ID.me is a digital identity network that provides NIST 800-63-3 IAL2/AAL2 identity verification, single sign-on, and group affiliation (community) verification for government agencies, healthcare, and commercial partners. For developers, ID.me exposes an OpenID Connect and OAuth 2.0 identity provider (authorization code flow with PKCE, plus SAML 2.0 federation), a REST Services API for telecom and document verification, an Applications API, a Document Passback API, and a Shared Signals Framework (SSF) event stream for fraud and verification signals. Native iOS and Android SDKs, a button widget, conversion tracking, and multi-language sample code round out the developer surface, letting relying parties add strong identity proofing and attribute exchange to any application or IAM platform (Okta, Keycloak, Entra, PingOne, AWS Cognito).

**Areas:** Company · Identity · Identity Verification · Authentication · OpenID Connect · SAML · SSO · Digital Identity · KYC · Fraud Prevention · Government · Identity Federation

## ID.me on APIs.io

Everything profiled for ID.me is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/idme/](https://apis.io/providers/idme/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [ID.me OpenID Connect & OAuth 2.0 API](https://apis.io/apis/idme/id-me-openid-connect-oauth-2-0-api/) — ID.me's OpenID Connect and OAuth 2.0 identity provider. Supports the authorization code flow (with PKCE), refresh tokens, encrypted ID tokens and userinfo,…
- [ID.me Services API](https://apis.io/apis/idme/id-me-services-api/) — ID.me's REST Services API for orchestrating identity verification: create and manage verifications, verify phone possession and identity via telecom…
- [ID.me applications API](https://apis.io/apis/idme/applications-api/) — ID.me applications API as documented publicly: 10 operations. Contract generated from the documentation by API Evangelist (2026-10-20); not the provider's…
- [ID.me core API](https://apis.io/apis/idme/core-api/) — ID.me core API as documented publicly: 1 operations. Contract generated from the documentation by API Evangelist (2026-10-20); not the provider's own document.
- [ID.me document passback API](https://apis.io/apis/idme/document-passback-api/) — ID.me document passback API as documented publicly: 3 operations. Contract generated from the documentation by API Evangelist (2026-10-20); not the…
- [ID.me services API](https://apis.io/apis/idme/services-api/) — ID.me services API as documented publicly: 14 operations. Contract generated from the documentation by API Evangelist (2026-10-20); not the provider's own…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Idme Services Webhooks](https://apis.io/asyncapis/idme/idme-services-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [ID.me Developer Docs](https://apis.io/servers/idme/id-me-developer-docs/)

#### JSON Schema (16)

The data models the API reads and writes.

- [GetApiPublicV3AttributesJsonResponse](https://apis.io/schemas/idme/idme-get-api-public-v3-attributes-json-response/)
- [GetApiV2DocumentPasscardVerifyResponse](https://apis.io/schemas/idme/idme-get-api-v2-document-passcard-verify-response/)
- [GetApiV2DocumentPassportVerifyResponse](https://apis.io/schemas/idme/idme-get-api-v2-document-passport-verify-response/)
- [GetApiV2ProductTransactionidResponse](https://apis.io/schemas/idme/idme-get-api-v2-product-transactionid-response/)
- [GetV1DomainsDomainResponse](https://apis.io/schemas/idme/idme-get-v1-domains-domain-response/)
- [GetV1SectorsIdStructuresResponse](https://apis.io/schemas/idme/idme-get-v1-sectors-id-structures-response/)
- [PatchV1OrganizationsUuidRequest](https://apis.io/schemas/idme/idme-patch-v1-organizations-uuid-request/)
- [PatchV1OrganizationsUuidResponse](https://apis.io/schemas/idme/idme-patch-v1-organizations-uuid-response/)
- [PostApiAuthV1CredentialsUuidCheckResponse](https://apis.io/schemas/idme/idme-post-api-auth-v1-credentials-uuid-check-response/)
- [PostApiPublicV3DocumentsDocumenttokenResponse](https://apis.io/schemas/idme/idme-post-api-public-v3-documents-documenttoken-response/)
- [PostApiPublicV3DocumentsRefreshDocumenttokenResponse](https://apis.io/schemas/idme/idme-post-api-public-v3-documents-refresh-documenttoken-response/)
- [PostApiV2TelecomIdentityRequest](https://apis.io/schemas/idme/idme-post-api-v2-telecom-identity-request/)
- [PostApiV2TelecomPossessionSmsConfirmRequest](https://apis.io/schemas/idme/idme-post-api-v2-telecom-possession-sms-confirm-request/)
- [PostApiV2TelecomPossessionSmsSendRequest](https://apis.io/schemas/idme/idme-post-api-v2-telecom-possession-sms-send-request/)
- [PostV1DomainsResponse](https://apis.io/schemas/idme/idme-post-v1-domains-response/)
- [PostV1OrganizationsOrganizationuuidApplicationsRequest](https://apis.io/schemas/idme/idme-post-v1-organizations-organizationuuid-applications-request/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Idme Context](https://apis.io/jsonld/idme/idme-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [ID.me API Rules](https://apis.io/rules/idme/idme-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Idme Authentication](https://apis.io/security/idme/idme-authentication/)
- [Idme Domain Security](https://apis.io/security/idme/idme-domain-security/)
- [Idme Trust Center](https://apis.io/security/idme/idme-trust-center/)
- [Idme Vulnerability Disclosure](https://apis.io/security/idme/idme-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Idme Scopes](https://apis.io/scopes/idme/idme-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.id.me)
- [Documentation](https://docs.id.me)
- [Getting started](https://docs.id.me/home)
- [API reference](https://docs.id.me/services-api-overview)
- [Sign up](https://developers.id.me)
- [Support](https://docs.id.me/integrations/deploy-and-monitor/help)
- [Blog](https://network.id.me/insights-home/)
- [Compliance](https://docs.id.me/guides/learn-more/digital-wallet/nist-ial-2)
- [GitHub](https://github.com/IDme)
- [Status](https://status.id.me)

## API Evangelist rating

**Kin Score 49.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 33.5 |
| Contract governance | 35.6 |
| Operational transparency | 36.8 |
| Developer ergonomics | 73.2 |
| Access clarity | 28.9 |

**Agent readiness 36.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly |

**Regulatory alignment 37.3** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/idme/](https://apis.io/providers/idme/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for ID.me: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/idme/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
