# Intuit (intuit)

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

Collection of APIs offered by Intuit for financial and business management services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/intuit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/intuit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Accounting
- Custom Fields
- Financial
- Financial Services
- Invoicing
- Payments
- Payroll
- Project Management
- Sales Tax
- Small Business
- Tax
- Tax Preparation
- Taxes
- Time Tracking

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Intuit APIs

Intuit APIs provide developers with access to a wide range of services and functionalities to help them build innovative solutions for financial management, accounting, and tax-related needs. These APIs allow developers to integrate with popular Intuit products such as QuickBooks, TurboTax, and Mint, giving users the ability to securely access and manage their financial data across multiple platforms.

- **Human URL:** [https://developer.intuit.com/app/developer/homepage](https://developer.intuit.com/app/developer/homepage)

#### Tags

- Accounting
- Financial
- Tax Preparation
- Taxes

#### Properties

- [Documentation](https://developer.intuit.com/app/developer/homepage)
- [Postman Collection](collections/quickbooks-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quickbooks-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickBooks Online Accounting API

The QuickBooks Online Accounting API is a RESTful API that provides programmatic access to QuickBooks Online company data, including customers, invoices, payments, bills, vendors, accounts, and reports. It enables developers to build integrations that automate accounting workflows, synchronize financial data, and extend QuickBooks Online functionality for small and mid-sized businesses.

- **Human URL:** [https://developer.intuit.com/app/developer/qbo/docs/develop](https://developer.intuit.com/app/developer/qbo/docs/develop)

#### Tags

- Accounting
- Bookkeeping
- Financial
- Invoicing
- Small Business

#### Properties

- [Documentation](https://developer.intuit.com/app/developer/qbo/docs/develop)
- [API Reference](https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account)
- [Getting Started](https://developer.intuit.com/app/developer/qbo/docs/get-started)
- [Console](https://developer.intuit.com/app/developer/qbo/docs/get-started/get-started-with-the-api-explorer)
- [Authentication](https://developer.intuit.com/app/developer/qbo/docs/develop/authentication-and-authorization/oauth-2.0)
- [Documentation](https://developer.intuit.com/app/developer/qbo/docs/learn/explore-the-quickbooks-online-api)
- [Versioning](https://developer.intuit.com/app/developer/qbo/docs/learn/explore-the-quickbooks-online-api/minor-versions)
- [SDK](https://developer.intuit.com/app/developer/qbo/docs/develop/sdks-and-samples)
- [Release Notes](https://developer.intuit.com/app/developer/qbo/docs/release-notes/platform-release-notes)
- [OpenAPI](openapi/quickbooks-accounting.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/quickbooks-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quickbooks-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/quickbooks-webhooks.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/intuit-invoice-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/intuit-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/intuit-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### QuickBooks Payments API

The QuickBooks Payments API enables developers to process credit card charges, bank account debits (ACH), and manage payment methods within the QuickBooks ecosystem. It supports tokenized card storage, refunds, and the ability to link payments directly to QuickBooks Online invoices for seamless reconciliation.

- **Human URL:** [https://developer.intuit.com/app/developer/qbpayments/docs/learn/explore-the-quickbooks-payments-api](https://developer.intuit.com/app/developer/qbpayments/docs/learn/explore-the-quickbooks-payments-api)

#### Tags

- Credit Cards
- eCommerce
- Financial
- Payments

#### Properties

- [Documentation](https://developer.intuit.com/app/developer/qbpayments/docs/learn/explore-the-quickbooks-payments-api)
- [Getting Started](https://developer.intuit.com/app/developer/qbpayments/docs/get-started)
- [API Reference](https://developer.intuit.com/app/developer/qbpayments/docs/develop)
- [Postman Collection](collections/quickbooks-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quickbooks-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickBooks Payroll and Time API

The QuickBooks Payroll and Time API provides programmatic access to payroll and time-tracking data within QuickBooks Online. It supports use cases including time entry management, payroll compensation, and deductions, enabling developers to build integrations that streamline workforce and payroll operations for small businesses.

- **Human URL:** [https://developer.intuit.com/app/developer/payroll-time/docs/get-started](https://developer.intuit.com/app/developer/payroll-time/docs/get-started)

#### Tags

- HR
- Payroll
- Small Business
- Time Tracking

#### Properties

- [Getting Started](https://developer.intuit.com/app/developer/payroll-time/docs/get-started)
- [Documentation](https://developer.intuit.com/app/developer/payroll-time/docs/develop/develop-payroll)
- [Postman Collection](collections/quickbooks-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quickbooks-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickBooks Desktop API

The QuickBooks Desktop API allows developers to integrate with QuickBooks Desktop applications using qbXML messages. It provides capabilities for adding, querying, modifying, and deleting data across list objects, transaction objects, query objects, and report objects, enabling third-party applications to interact with on-premise QuickBooks installations.

- **Human URL:** [https://developer.intuit.com/app/developer/qbdesktop/docs/api-reference/qbdesktop](https://developer.intuit.com/app/developer/qbdesktop/docs/api-reference/qbdesktop)

#### Tags

- Accounting
- Desktop
- Financial
- Small Business

#### Properties

- [API Reference](https://developer.intuit.com/app/developer/qbdesktop/docs/api-reference/qbdesktop)
- [Documentation](https://developer.intuit.com/app/developer/qbdesktop/docs/api-reference)
- [Postman Collection](collections/quickbooks-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quickbooks-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickBooks Projects API

The QuickBooks Projects API is a premium API that provides programmatic access to project data within QuickBooks Online Plus, Advanced, Accountant, and Intuit Enterprise Suite. It enables developers to create projects, track profitability, and manage project-level financial data, allowing integrations that enhance project-based accounting and reporting workflows.

- **Human URL:** [https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account](https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account)

#### Tags

- Accounting
- Financial
- Project Management
- Projects
- Small Business

#### Properties

- [API Reference](https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account)
- [Documentation](https://developer.intuit.com/app/developer/qbo/docs/develop)
- [Postman Collection](collections/quickbooks-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quickbooks-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickBooks Custom Fields API

The QuickBooks Custom Fields API is a premium API that provides programmatic access to custom field definitions and values in QuickBooks Online and Intuit Enterprise Suite. It allows developers to create and manage up to 12 custom fields that can be used across different transaction types, enabling flexible metadata extensions for invoices, estimates, sales receipts, and other entities.

- **Human URL:** [https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account](https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account)

#### Tags

- Accounting
- Custom Fields
- Financial
- Metadata
- Small Business

#### Properties

- [API Reference](https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account)
- [Documentation](https://developer.intuit.com/app/developer/qbo/docs/develop)
- [Postman Collection](collections/quickbooks-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quickbooks-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickBooks Sales Tax API

The QuickBooks Sales Tax API is a premium API that provides programmatic access to the automated sales tax calculation capabilities within QuickBooks Online. It enables developers to leverage QuickBooks automated sales tax engine to calculate the correct sales tax for invoices and other transactions, supporting tax compliance across different jurisdictions.

- **Human URL:** [https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/taxrate](https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/taxrate)

#### Tags

- Accounting
- Financial
- Sales Tax
- Small Business
- Tax

#### Properties

- [API Reference](https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/taxrate)
- [Documentation](https://developer.intuit.com/app/developer/qbo/docs/develop)
- [Postman Collection](collections/quickbooks-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quickbooks-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Developer Portal](https://developer.intuit.com)
- [Sign Up](https://developer.intuit.com/app/developer/appcard/overview)
- [Blog](https://developer.intuit.com/app/developer/blog)
- [Support](https://help.developer.intuit.com)
- [Status Page](https://status.developer.intuit.com)
- [Terms of Service](https://developer.intuit.com/app/developer/qbo/docs/learn/terms-of-service)
- [Privacy Policy](https://www.intuit.com/privacy/)
- [Authentication](https://developer.intuit.com/app/developer/qbo/docs/develop/authentication-and-authorization/oauth-2.0)
- [Sandbox](https://developer.intuit.com/app/developer/qbo/docs/develop/sandboxes/postman)
- [Console](https://developer.intuit.com/app/developer/qbo/docs/get-started/get-started-with-the-api-explorer)
- [F A Q](https://developer.intuit.com/app/developer/qbo/docs/get-started/partner-faq)
- [GitHub Organization](https://github.com/intuit)
- [GitHub Organization](https://github.com/intuitdeveloper)
- [SDK](https://github.com/intuit/QuickBooks-V3-PHP-SDK)
- [SDK](https://github.com/intuit/QuickBooks-V3-DotNET-SDK)
- [SDK](https://github.com/intuit/QuickBooks-V3-Java-SDK)
- [SDK](https://github.com/intuit/oauth-rubyclient)
- [SDK](https://developer.intuit.com/app/developer/qbo/docs/develop/sdks-and-samples-collections/nodejs)
- [SDK](https://developer.intuit.com/app/developer/qbo/docs/develop/sdks-and-samples-collections/python)
- [Changelog](https://blogs.intuit.com/)
- [Release Notes](https://developer.intuit.com/app/developer/qbo/docs/release-notes/platform-release-notes)
- [Release Notes](https://developer.intuit.com/app/developer/qbo/docs/release-notes/general-release-notes)
- [Versioning](https://developer.intuit.com/app/developer/qbo/docs/learn/explore-the-quickbooks-online-api/minor-versions)
- [Rate Limits](https://help.developer.intuit.com/s/article/API-call-limits-and-throttling)
- [Security](https://developer.intuit.com/app/developer/qbo/docs/go-live/publish-app/security-requirements)
- [Marketplace](https://quickbooks.intuit.com/app/apps/home/en-global/)
- [X (Twitter)](https://x.com/IntuitDev)
- [LinkedIn](https://www.linkedin.com/company/intuit-developer)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [M C P Server](https://github.com/intuit/quickbooks-online-mcp-server)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**Email:** developer-support@intuit.com
**URL:** https://help.developer.intuit.com
