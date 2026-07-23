# Columbia Bank (columbia-banking)

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
