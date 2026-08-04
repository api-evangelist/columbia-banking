# Columbia Bank (columbia-banking)

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

Columbia Bank is an Oregon state-chartered commercial bank and the principal banking subsidiary of Columbia Banking System, Inc. (NASDAQ: COLB), a West Coast regional bank holding company headquartered in Tacoma, Washington with more than $50 billion in assets. The bank adopted the legal name "Columbia Bank" effective July 1, 2025, having operated as Umpqua Bank after the 2023 merger of Columbia Banking System and Umpqua Holdings Corporation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/columbia-banking/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/columbia-banking/refs/heads/main/apis.yml)

## Open-Finance & API Posture

Columbia is one of the relatively few US regional banks to run a first-party developer surface. **Columbia API Banking** is a commercial and treasury-management integration product that exposes banking data and operations for direct integration with financial software and ERP systems. Documented capabilities include book transfers, ACH file imports, positive pay, stop-payment and NSF management, new account requests, lockbox management, transaction and statement retrieval, check images, and real-time account balances, with responses available in JSON and XML. A production-ready SDK and the gated Columbia API Portal provide reference documentation and an event log for debugging.

This is a commercial/ERP-oriented surface rather than a self-serve public developer portal — there is no publicly resolving `developer.columbiabank.com`, and the API reference lives behind the Columbia API Portal. No public OpenAPI/Swagger specification was found to harvest. Consumer-permissioned data access is delivered through the **Plaid** aggregator rather than a first-party consumer API. No documented **FDX** participation or published **CFPB Section 1033** data-access posture was found at bootstrap time.

## Tags

- Financial Services
- Banking
- United States
- Regional Bank
- Commercial Banking
- Treasury Management
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Columbia API Banking

First-party commercial and treasury-management API product providing programmatic access to banking data and operations for integration with financial software and ERP platforms.

- **Human URL:** [https://www.columbiabank.com/commercial/api-banking/](https://www.columbiabank.com/commercial/api-banking/)

#### Tags

- Commercial Banking
- Treasury Management
- Payments
- ACH

#### Properties

- [Documentation](https://www.columbiabank.com/commercial/api-banking/)
- [Documentation — Developer Tools](https://www.columbiabank.com/commercial/api-banking/developer-tools/)

## Common Properties

- [Website](https://www.columbiabank.com/)
- [Documentation](https://www.columbiabank.com/commercial/api-banking/)
- [Blog](https://www.columbiabank.com/blog/)
- [Support](https://www.columbiabank.com/help-center/)
- [LinkedIn](https://www.linkedin.com/company/umpqua-bank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
