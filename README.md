# Meridian Credit Union (meridian-credit-union)

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
