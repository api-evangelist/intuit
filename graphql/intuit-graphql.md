# Intuit GraphQL Schema

## Description

Intuit does not offer a native public GraphQL API. Its developer platform exposes REST APIs for QuickBooks Online (Accounting, Payments, Payroll/Time, Projects, Custom Fields, Sales Tax), QuickBooks Desktop (qbXML), and related services. This GraphQL schema is a conceptual representation derived from the QuickBooks Online Accounting REST API entity model, useful for tooling, federation, schema stitching, or documentation purposes.

## Endpoint

No public GraphQL endpoint is available. Intuit's APIs are accessed via REST at:

- Base URL: `https://quickbooks.api.intuit.com/v3/company/{realmId}/`
- Sandbox URL: `https://sandbox-quickbooks.api.intuit.com/v3/company/{realmId}/`

## Documentation

- Developer Portal: https://developer.intuit.com/app/developer/homepage
- QuickBooks Online Accounting API Reference: https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account
- Getting Started: https://developer.intuit.com/app/developer/qbo/docs/get-started
- Authentication (OAuth 2.0): https://developer.intuit.com/app/developer/qbo/docs/develop/authentication-and-authorization/oauth-2.0

## Note

This schema is conceptual. It maps the QuickBooks Online REST API entity types — including financial transactions, list objects, and report types — into GraphQL SDL for use in API tooling, mock servers, and documentation generation. All types correspond to documented QBO REST entities.

Source: QuickBooks Online REST API entity model
Schema type: Conceptual / Derived
