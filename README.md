# TaxJar

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

> **Acquired or rebranded.** This company was acquired, merged or renamed. Its API, if it still exists, is offered under another name. This profile is kept as a historical record and is not maintained or rated.

TaxJar is a sales tax automation platform, now a Stripe company, providing APIs for real-time sales tax calculations, rooftop-level rate lookups, transaction recording, and automated filing across US states and international jurisdictions. The platform supports e-commerce businesses of all sizes with sub-20ms response times, 99.999% historical uptime, and AI-powered product tax classification. TaxJar handles nexus tracking, exemption certificate management, and AutoFile returns so merchants can stay compliant without manual effort. Official client libraries are available for Ruby, Python, PHP, Node.js, C#/.NET, Java, and Go.

**Areas:** Sales Tax · Tax Compliance · E-Commerce · Tax Calculation · Tax Automation · Stripe · Fintech · Tax

## TaxJar on APIs.io (historical record)

Everything profiled for TaxJar is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/taxjar/](https://apis.io/providers/taxjar/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [TaxJar Categories API](https://apis.io/apis/taxjar/taxjar-categories-api/) — Product tax categories
- [TaxJar Customers API](https://apis.io/apis/taxjar/taxjar-customers-api/) — Customer exemption management
- [TaxJar Nexus API](https://apis.io/apis/taxjar/taxjar-nexus-api/) — Nexus region tracking
- [TaxJar Rates API](https://apis.io/apis/taxjar/taxjar-rates-api/) — Sales tax rate lookups
- [TaxJar Summary Rates API](https://apis.io/apis/taxjar/taxjar-summary-rates-api/) — Summarized sales tax rates by region
- [TaxJar Taxes API](https://apis.io/apis/taxjar/taxjar-taxes-api/) — Sales tax calculation
- [TaxJar Transactions - Orders API](https://apis.io/apis/taxjar/taxjar-transactions-orders-api/) — Order transaction management
- [TaxJar Transactions - Refunds API](https://apis.io/apis/taxjar/taxjar-transactions-refunds-api/) — Refund transaction management
- [TaxJar Validations API](https://apis.io/apis/taxjar/taxjar-validations-api/) — Address and VAT validation

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Taxjar Agentic Access](https://apis.io/agentic-access/taxjar/taxjar-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [TaxJar Order Transaction](https://apis.io/schemas/taxjar/taxjar-order/)
- [TaxJar Tax Calculation Response](https://apis.io/schemas/taxjar/taxjar-tax-calculation/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Taxjar Context](https://apis.io/jsonld/taxjar/taxjar-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Taxjar Vocabulary](https://apis.io/vocabularies/taxjar/taxjar-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Calculate Tax Request](https://apis.io/examples/taxjar/calculate-tax-request/)
- [Calculate Tax Response](https://apis.io/examples/taxjar/calculate-tax-response/)
- [Create Order Request](https://apis.io/examples/taxjar/create-order-request/)

#### Collections (18)

Postman and Open Collection request collections.

- [TaxJar Sales Tax Categories API](https://apis.io/collections/taxjar/open-taxjar-categories-api/)
- [TaxJar Sales Tax Categories Customers API](https://apis.io/collections/taxjar/open-taxjar-customers-api/)
- [TaxJar Sales Tax Categories Nexus API](https://apis.io/collections/taxjar/open-taxjar-nexus-api/)
- [TaxJar Sales Tax Categories Rates API](https://apis.io/collections/taxjar/open-taxjar-rates-api/)
- [TaxJar Sales Tax Categories Summary Rates API](https://apis.io/collections/taxjar/open-taxjar-summary-rates-api/)
- [TaxJar Sales Tax Categories Taxes API](https://apis.io/collections/taxjar/open-taxjar-taxes-api/)
- [TaxJar Sales Tax Categories Transactions - Orders API](https://apis.io/collections/taxjar/open-taxjar-transactions-orders-api/)
- [TaxJar Sales Tax Categories Transactions - Refunds API](https://apis.io/collections/taxjar/open-taxjar-transactions-refunds-api/)
- [TaxJar Sales Tax Categories Validations API](https://apis.io/collections/taxjar/open-taxjar-validations-api/)
- [TaxJar Sales Tax Categories API](https://apis.io/collections/taxjar/postman-taxjar-categories-api/)
- [TaxJar Sales Tax Categories Customers API](https://apis.io/collections/taxjar/postman-taxjar-customers-api/)
- [TaxJar Sales Tax Categories Nexus API](https://apis.io/collections/taxjar/postman-taxjar-nexus-api/)
- [TaxJar Sales Tax Categories Rates API](https://apis.io/collections/taxjar/postman-taxjar-rates-api/)
- [TaxJar Sales Tax Categories Summary Rates API](https://apis.io/collections/taxjar/postman-taxjar-summary-rates-api/)
- [TaxJar Sales Tax Categories Taxes API](https://apis.io/collections/taxjar/postman-taxjar-taxes-api/)
- [TaxJar Sales Tax Categories Transactions - Orders API](https://apis.io/collections/taxjar/postman-taxjar-transactions-orders-api/)
- [TaxJar Sales Tax Categories Transactions - Refunds API](https://apis.io/collections/taxjar/postman-taxjar-transactions-refunds-api/)
- [TaxJar Sales Tax Categories Validations API](https://apis.io/collections/taxjar/postman-taxjar-validations-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [TaxJar — jsonschema rules](https://apis.io/rules/taxjar/taxjar-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Taxjar Authentication](https://apis.io/security/taxjar/taxjar-authentication/)
- [Taxjar Domain Security](https://apis.io/security/taxjar/taxjar-domain-security/)
- [Taxjar Trust Center](https://apis.io/security/taxjar/taxjar-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Taxjar Plans Pricing](https://apis.io/plans/taxjar/taxjar-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Taxjar Rate Limits](https://apis.io/rate-limits/taxjar/taxjar-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Taxjar Finops](https://apis.io/finops/taxjar/taxjar-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.taxjar.com)
- [Documentation](https://developers.taxjar.com/)
- [API reference](https://developers.taxjar.com/api/reference/)
- [Pricing](https://www.taxjar.com/pricing/)
- [Support](https://support.taxjar.com/category/233-taxjar-api)
- [Blog](https://developers.taxjar.com/blog/)
- [GitHub](https://github.com/taxjar)
- [Status](https://status.taxjar.com)

## API Evangelist rating

**Not rated** — this company is recorded as acquired or rebranded, so no score is published. If it is in fact operating, say so on this repository and it will be re-profiled.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for TaxJar: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/taxjar/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
