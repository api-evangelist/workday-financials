# Workday Financials (workday-financials)

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

Workday Financials is a cloud-based financial management system that provides comprehensive solutions for accounting, procurement, expenses, and financial reporting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workday-financials/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workday-financials/refs/heads/main/apis.yml)

## Tags

- Accounting
- Cloud ERP
- Financial Management
- Procurement

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Workday Financial Management API

Core API for managing financial transactions, general ledger, accounts payable, accounts receivable, and financial reporting.

- **Human URL:** [https://www.workday.com/en-us/products/financial-management/overview.html](https://www.workday.com/en-us/products/financial-management/overview.html)
- **Base URL:** `https://api.workday.com/financialManagement`

#### Tags

- Accounts Payable
- Accounts Receivable
- Financial Reporting
- General Ledger

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Financial_Management/v38.2/Financial_Management.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/authentication-and-authorization.html)
- [OpenAPI](openapi/workday-financials-financial-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-financials-financial-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-financials-financial-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Revenue Management API

API for managing revenue recognition, contracts, billing, and revenue accounting in compliance with ASC 606 and IFRS 15.

- **Human URL:** [https://www.workday.com/en-us/products/financial-management/revenue-management.html](https://www.workday.com/en-us/products/financial-management/revenue-management.html)
- **Base URL:** `https://api.workday.com/revenueManagement`

#### Tags

- Billing
- Contracts
- Revenue Recognition
- Subscription Management

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Revenue_Management/v38.2/Revenue_Management.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/workday-financials-revenue-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-financials-revenue-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-financials-revenue-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Expenses API

API for expense report submission, approval workflows, receipt management, and expense policy enforcement.

- **Human URL:** [https://www.workday.com/en-us/products/financial-management/expense-management.html](https://www.workday.com/en-us/products/financial-management/expense-management.html)
- **Base URL:** `https://api.workday.com/expenses`

#### Tags

- Approvals
- Expense Reports
- Receipt Management
- Travel Expenses

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Expenses/v38.2/Expenses.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/workday-financials-expenses-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-financials-expenses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-financials-expenses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Procurement API

API for purchase requisitions, purchase orders, supplier management, and procurement processes.

- **Human URL:** [https://www.workday.com/en-us/products/financial-management/procurement.html](https://www.workday.com/en-us/products/financial-management/procurement.html)
- **Base URL:** `https://api.workday.com/procurement`

#### Tags

- Procurement
- Purchase Orders
- Requisitions
- Suppliers

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Resource_Management/v38.2/Resource_Management.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/workday-financials-procurement-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-financials-procurement.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-financials-procurement.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Cash Management API

API for managing cash positions, bank accounts, transactions, and cash forecasting.

- **Human URL:** [https://www.workday.com/en-us/products/financial-management/cash-management.html](https://www.workday.com/en-us/products/financial-management/cash-management.html)
- **Base URL:** `https://api.workday.com/cashManagement`

#### Tags

- Bank Accounts
- Cash Management
- Forecasting
- Treasury

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Cash_Management/v38.2/Cash_Management.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/workday-financials-cash-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-financials-cash-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-financials-cash-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Financial Accounting API

API for journal entries, account reconciliation, period close activities, and audit trails.

- **Human URL:** [https://www.workday.com/en-us/products/financial-management/financial-accounting.html](https://www.workday.com/en-us/products/financial-management/financial-accounting.html)
- **Base URL:** `https://api.workday.com/financialAccounting`

#### Tags

- Account Reconciliation
- Audit
- Journal Entries
- Period Close

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Financial_Management/v38.2/Financial_Management.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/workday-financials-financial-accounting-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-financials-financial-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-financials-financial-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Reporting API

API for accessing financial reports, custom report execution, and analytics data extraction.

- **Human URL:** [https://www.workday.com/en-us/products/financial-management/financial-reporting.html](https://www.workday.com/en-us/products/financial-management/financial-reporting.html)
- **Base URL:** `https://api.workday.com/reporting`

#### Tags

- Analytics
- Custom Reports
- Financial Reports
- Reporting

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Report_as_a_Service/v38.2/Report_as_a_Service.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/workday-financials-reporting-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-financials-reporting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-financials-reporting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Developer  Portal](https://community.workday.com/developer)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/authentication-and-authorization.html)
- [Rate Limits](https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/rate-limiting.html)
- [Status Page](https://status.workday.com/)
- [Support](https://www.workday.com/en-us/company/latest/support.html)
- [Terms of Service](https://www.workday.com/en-us/legal.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [Contact](https://www.workday.com/en-us/company/latest/contact-us.html)
- [JSON-LD](json-ld/workday-financials-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/workday-financials-journal-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/workday-financials-supplier-invoice-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral  Rules](rules/workday-financials-rules.yml)
- [Vocabulary](vocabulary/workday-financials-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
