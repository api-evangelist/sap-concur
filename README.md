# SAP Concur (sap-concur)
SAP Concur is a leading provider of integrated travel, expense, and invoice management solutions. Their APIs enable developers to integrate Concur functionality into their applications, automate business processes, and access travel and expense data.

**URL:** [Visit APIs.json URL](https://www.concur.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Business Travel, Expense Management, Financial Services, Invoice Management, Travel Management

## Timestamps

- **Created:** 2024 
- **Modified:** 2026-04-18 

## APIs

### Concur Expense API
Enables integration with Concur Expense for creating, retrieving, and managing expense reports, entries, and related data.

**Human URL:** [https://developer.concur.com/api-reference/expense/](https://developer.concur.com/api-reference/expense/)

#### Tags:

 - Expenses, Receipts, Reports

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/)
- [OpenAPI](openapi/sap-concur-expense-openapi.yml)
- [JSONSchema](json-schema/sap-concur-expense-report-schema.json)
- [JSONLD](json-ld/sap-concur-context.jsonld)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)

### Concur Travel API
Provides access to travel booking data, profiles, and itinerary information within Concur Travel.

**Human URL:** [https://developer.concur.com/api-reference/travel/](https://developer.concur.com/api-reference/travel/)

#### Tags:

 - Bookings, Itineraries, Travel

#### Properties

- [Documentation](https://developer.concur.com/api-reference/travel/)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)

### Concur Invoice API
Allows integration with Concur Invoice for managing purchase requests, invoices, and payment requests.

**Human URL:** [https://developer.concur.com/api-reference/invoice/](https://developer.concur.com/api-reference/invoice/)

#### Tags:

 - Invoices, Payments, Purchase Requests

#### Properties

- [Documentation](https://developer.concur.com/api-reference/invoice/)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)

### Concur Request API
Enables management of travel requests and approvals within the Concur system.

**Human URL:** [https://developer.concur.com/api-reference/request/](https://developer.concur.com/api-reference/request/)

#### Tags:

 - Approvals, Travel Requests, Workflows

#### Properties

- [Documentation](https://developer.concur.com/api-reference/request/)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)

## Common Properties

- [DeveloperPortal](https://developer.concur.com/)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)
- [Support](https://developer.concur.com/support/)
- [TermsOfService](https://www.concur.com/terms-of-use)
- [PrivacyPolicy](https://www.concur.com/privacy-policy)
- [StatusPage](https://open.concur.com/)
- [Blog](https://www.concur.com/newsroom)
- [SignUp](https://developer.concur.com/register)
- [GitHubRepository](https://github.com/SAP-docs/preview.developer.concur.com)
- [ReleaseNotes](https://developer.concur.com/tools-support/release-notes/)
- [Tutorials](https://developers.sap.com/tutorials/data-to-value-conn-concur-part01..html)

## Features

| Name | Description |
|------|-------------|
| OAuth 2.0 Authentication | Secure token-based authentication supporting both company-level and user-level access tokens with automatic refresh. |
| Multi-Datacenter Support | Separate API endpoints for US, US2, EMEA, and China datacenters ensuring data residency compliance. |
| Event Subscription Service | Publish/Subscribe event-driven architecture for real-time notifications on business events like report submissions. |
| SCIM 2.0 User Provisioning | Standards-based user identity management following SCIM protocol for automated user lifecycle operations. |
| Direct Connect Framework | Integration framework allowing travel suppliers to provide inventory directly to the Concur booking tool. |
| Multi-Currency Exchange Rates | Custom exchange rate management supporting bulk uploads for currency conversion across global operations. |

## Use Cases

| Name | Description |
|------|-------------|
| Expense Report Automation | Automate expense report creation, submission, and approval workflows by integrating with ERP and financial systems. |
| Travel Booking Integration | Connect travel management companies and suppliers to provide booking, itinerary, and receipt data within Concur Travel. |
| Invoice Processing | Streamline accounts payable by automating invoice creation, purchase order matching, and vendor management. |
| Financial Posting | Extract approved expense reports and invoices for automated posting into ERP systems like SAP, Oracle, and NetSuite. |
| Receipt Digitization | Submit and manage digital receipts from e-receipt partners and mobile capture for paperless expense management. |

## Integrations

| Name | Description |
|------|-------------|
| SAP ERP | Native integration with SAP S/4HANA and SAP ERP for financial posting, cost center sync, and master data management. |
| Microsoft Teams | Approve expense reports and travel requests directly from Microsoft Teams notifications. |
| Uber for Business | Automatic e-receipt submission for Uber business rides directly into Concur Expense. |
| Salesforce | Sync customer and opportunity data to pre-populate expense reports and travel requests. |
| Oracle NetSuite | Automated financial posting of approved expense reports and invoices into Oracle NetSuite. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [SAP Concur Expense Report API](openapi/sap-concur-expense-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Concur Expense API](capabilities/shared/concur-expense.yaml) -- 14 operations for expense report lifecycle and approval workflows

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Expense Management](capabilities/expense-management.yaml) | Concur Expense | 14 | Finance Team / Approver |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
