# Workday Financials (workday-financials)
Workday Financials is a cloud-based financial management system that provides comprehensive solutions for accounting, procurement, expenses, and financial reporting.

**URL:** [https://www.workday.com/en-us/products/financial-management/overview.html](https://www.workday.com/en-us/products/financial-management/overview.html)

## Tags

Accounting, Cloud ERP, Financial Management, Procurement

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-03

## APIs

### Workday Financial Management API
Core API for managing financial transactions, general ledger, accounts payable, accounts receivable, and financial reporting.

**Human URL:** [https://www.workday.com/en-us/products/financial-management/overview.html](https://www.workday.com/en-us/products/financial-management/overview.html)

#### Tags

Accounts Payable, Accounts Receivable, Financial Reporting, General Ledger

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Financial_Management/v38.2/Financial_Management.json)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/authentication-and-authorization.html)
- [OpenAPI](openapi/workday-financials-financial-management-openapi.yml)

### Workday Revenue Management API
API for managing revenue recognition, contracts, billing, and revenue accounting in compliance with ASC 606 and IFRS 15.

**Human URL:** [https://www.workday.com/en-us/products/financial-management/revenue-management.html](https://www.workday.com/en-us/products/financial-management/revenue-management.html)

#### Tags

Billing, Contracts, Revenue Recognition, Subscription Management

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Revenue_Management/v38.2/Revenue_Management.json)
- [OpenAPI](openapi/workday-financials-revenue-management-openapi.yml)

### Workday Expenses API
API for expense report submission, approval workflows, receipt management, and expense policy enforcement.

**Human URL:** [https://www.workday.com/en-us/products/financial-management/expense-management.html](https://www.workday.com/en-us/products/financial-management/expense-management.html)

#### Tags

Approvals, Expense Reports, Receipt Management, Travel Expenses

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Expenses/v38.2/Expenses.json)
- [OpenAPI](openapi/workday-financials-expenses-openapi.yml)

### Workday Procurement API
API for purchase requisitions, purchase orders, supplier management, and procurement processes.

**Human URL:** [https://www.workday.com/en-us/products/financial-management/procurement.html](https://www.workday.com/en-us/products/financial-management/procurement.html)

#### Tags

Procurement, Purchase Orders, Requisitions, Suppliers

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Resource_Management/v38.2/Resource_Management.json)
- [OpenAPI](openapi/workday-financials-procurement-openapi.yml)

### Workday Cash Management API
API for managing cash positions, bank accounts, transactions, and cash forecasting.

**Human URL:** [https://www.workday.com/en-us/products/financial-management/cash-management.html](https://www.workday.com/en-us/products/financial-management/cash-management.html)

#### Tags

Bank Accounts, Cash Management, Forecasting, Treasury

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Cash_Management/v38.2/Cash_Management.json)
- [OpenAPI](openapi/workday-financials-cash-management-openapi.yml)

### Workday Financial Accounting API
API for journal entries, account reconciliation, period close activities, and audit trails.

**Human URL:** [https://www.workday.com/en-us/products/financial-management/financial-accounting.html](https://www.workday.com/en-us/products/financial-management/financial-accounting.html)

#### Tags

Account Reconciliation, Audit, Journal Entries, Period Close

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Financial_Management/v38.2/Financial_Management.json)
- [OpenAPI](openapi/workday-financials-financial-accounting-openapi.yml)

### Workday Reporting API
API for accessing financial reports, custom report execution, and analytics data extraction.

**Human URL:** [https://www.workday.com/en-us/products/financial-management/financial-reporting.html](https://www.workday.com/en-us/products/financial-management/financial-reporting.html)

#### Tags

Analytics, Custom Reports, Financial Reports, Reporting

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Report_as_a_Service/v38.2/Report_as_a_Service.json)
- [OpenAPI](openapi/workday-financials-reporting-openapi.yml)

## Common Properties

- [Developer Portal](https://community.workday.com/developer)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/authentication-and-authorization.html)
- [Rate Limits](https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/rate-limiting.html)
- [Status Page](https://status.workday.com/)
- [Support](https://www.workday.com/en-us/company/latest/support.html)
- [Terms of Service](https://www.workday.com/en-us/legal.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [Contact](https://www.workday.com/en-us/company/latest/contact-us.html)
- [JSON-LD](json-ld/workday-financials-context.jsonld)
- [JSONSchema](json-schema/workday-financials-journal-entry-schema.json)
- [JSONSchema](json-schema/workday-financials-supplier-invoice-schema.json)
- [Spectral Rules](rules/workday-financials-rules.yml)
- [Naftiko Capabilities](capabilities/financial-close.yaml)
- [Naftiko Capabilities](capabilities/procure-to-pay.yaml)
- [Vocabulary](vocabulary/workday-financials-vocabulary.yml)

## Capabilities

### Workflow Capabilities

- [Financial Close](capabilities/financial-close.yaml) — Record-to-report workflow: GL, journal entries, supplier invoices, and financial reporting (8 tools)
- [Procure To Pay](capabilities/procure-to-pay.yaml) — Supplier management, requisitions, purchase orders, and invoice processing (7 tools)

### Shared Per-API Capabilities

- [Financial Management API](capabilities/shared/financial-management.yaml)
- [Procurement API](capabilities/shared/procurement.yaml)
- [Reporting API](capabilities/shared/reporting.yaml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
