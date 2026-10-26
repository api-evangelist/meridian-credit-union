# Meridian Credit Union (meridian-credit-union)

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

Meridian Credit Union is Ontario's largest credit union and one of the largest in Canada — a member-owned financial cooperative headquartered in St. Catharines and Toronto, serving more than 365,000 members with roughly CAD $31 billion in assets under management, over 2,200 employees, and more than 75 years of history. Formed in 2005 through the merger of Niagara Credit Union and HEPCOE Credit Union, it offers personal, business, and wealth banking, owns Meridian OneCap Credit Corp. (commercial equipment leasing), and previously operated the digital bank motusbank (wound down in 2023).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/meridian-credit-union/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/meridian-credit-union/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Canada
- Credit Union
- Cooperative
- Ontario
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## Open Finance & API Posture

Meridian is a provincially regulated Ontario credit union (overseen by the Financial Services Regulatory Authority of Ontario / FSRA), a cooperative rather than a Schedule I or Schedule II bank. It publishes **no first-party public developer portal, developer API, or downloadable OpenAPI/Swagger specification**. A `developer.meridiancu.ca` host does not resolve, and no API product documentation is exposed on the public website.

Consumer-permissioned account-data access is **aggregator-mediated**, which is the honest and common reality for a Canadian credit union today:

- **Plaid** maintains a Meridian institution connector for consumer-permissioned data linking.
- The **Central 1 / Flinks Outbound** seam provides API-based data sharing across member credit unions in the Canadian market (screen-scraping being phased toward API access).

Canada's federal **Consumer-Driven Banking (open banking)** framework was legislated in 2024 (Budget 2024 + Fall Economic Statement 2024, with the Financial Consumer Agency of Canada / FCAC as overseer) but is **not yet operational**. There is therefore no live mandated open-banking API; Meridian's participation in open finance remains voluntary and aggregator-based.

## APIs

None. Meridian exposes no documented first-party public API. See the posture note above for the aggregator-mediated data-access reality.

## Common Properties

- [Website](https://www.meridiancu.ca/)
- [LinkedIn](https://www.linkedin.com/company/meridian-credit-union)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
