# SAP Concur (sap-concur)

SAP Concur is a leading provider of integrated travel, expense, and invoice management solutions. Their APIs enable developers to integrate Concur functionality into their applications, automate business processes, and access travel and expense data.

**APIs.json:** [https://www.concur.com](https://www.concur.com)

## Tags

- Business Travel
- Expense Management
- Financial Services
- Invoice Management
- Travel Management

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Concur Expense API

Enables integration with Concur Expense for creating, retrieving, and managing expense reports, entries, and related data.

- **Human URL:** [https://developer.concur.com/api-reference/expense/](https://developer.concur.com/api-reference/expense/)
- **Base URL:** `https://www.concursolutions.com/api/v3.0`

#### Tags

- Expenses
- Receipts
- Reports

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/)
- [OpenAPI](https://developer.concur.com/api-reference/expense/expense-report/expense-report.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-concur-expense-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-concur-expense-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sap-concur-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)
- [Documentation](https://developer.concur.com/api-reference/expense/expense-report/v4.reports.html)
- [Documentation](https://developer.concur.com/api-reference/expense/expense-report/v4.allocations.html)
- [Documentation](https://developer.concur.com/api-reference/expense/expense-report/v4.workflows.html)
- [Documentation](https://developer.concur.com/api-reference/expense/expense-report/v4.comments.html)
- [Documentation](https://developer.concur.com/api-reference/expense/expense-report/v4.expense-attendee-associations.html)
- [Resources](https://api.sap.com/package/ConcurExpense)

### Concur Travel API

Provides access to travel booking data, profiles, and itinerary information within Concur Travel.

- **Human URL:** [https://developer.concur.com/api-reference/travel/](https://developer.concur.com/api-reference/travel/)
- **Base URL:** `https://www.concursolutions.com/api/v3.0`

#### Tags

- Bookings
- Itineraries
- Travel

#### Properties

- [Documentation](https://developer.concur.com/api-reference/travel/)
- [OpenAPI](https://developer.concur.com/api-reference/travel/itinerary/itinerary.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Invoice API

Allows integration with Concur Invoice for managing purchase requests, invoices, and payment requests.

- **Human URL:** [https://developer.concur.com/api-reference/invoice/](https://developer.concur.com/api-reference/invoice/)
- **Base URL:** `https://www.concursolutions.com/api/v3.0`

#### Tags

- Invoices
- Payments
- Purchase Requests

#### Properties

- [Documentation](https://developer.concur.com/api-reference/invoice/)
- [OpenAPI](https://developer.concur.com/api-reference/invoice/v3.invoice.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)
- [Resources](https://api.sap.com/package/ConcurInvoice)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Request API

Enables management of travel requests and approvals within the Concur system.

- **Human URL:** [https://developer.concur.com/api-reference/request/](https://developer.concur.com/api-reference/request/)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Approvals
- Travel Requests
- Workflows

#### Properties

- [Documentation](https://developer.concur.com/api-reference/request/)
- [OpenAPI](https://developer.concur.com/api-reference/request/v4.request.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)
- [Documentation](https://developer.concur.com/api-reference/request/v4.get-started.html)
- [Documentation](https://developer.concur.com/api-reference/request/v4.endpoints.cashadvance-resources.html)
- [Resources](https://api.sap.com/package/ConcurRequest)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur User Provisioning API

Manages user accounts and profiles, including creating, updating, and retrieving user information. Supports provisioning across Identity, Spend, and Travel services with bulk operations for managing multiple user records.

- **Human URL:** [https://developer.concur.com/api-reference/user/](https://developer.concur.com/api-reference/user/)
- **Base URL:** `https://www.concursolutions.com/api/user/v1.0`

#### Tags

- Identity Management
- Provisioning
- Users

#### Properties

- [Documentation](https://developer.concur.com/api-reference/user/)
- [Documentation](https://developer.concur.com/api-reference/user-provisioning/v4.user-provisioning.html)
- [Documentation](https://developer.concur.com/api-reference/user-provisioning/spend/v4.spend-role-code-definition.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Receipt API

Allows for the submission and management of digital receipts within Concur Expense.

- **Human URL:** [https://developer.concur.com/api-reference/receipts/](https://developer.concur.com/api-reference/receipts/)
- **Base URL:** `https://www.concursolutions.com/api/v3.0`

#### Tags

- Documents
- Images
- Receipts

#### Properties

- [Documentation](https://developer.concur.com/api-reference/receipts/)
- [Documentation](https://developer.concur.com/api-reference/receipts/endpoints.html)
- [Documentation](https://developer.concur.com/api-reference/receipts/sample-receipts.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Budget API

Exposes budget and fiscal year data, enabling partners and clients to read and manage fiscal years, budget categories, budget items, budget tracking fields, and budget adjustments through API endpoints.

- **Human URL:** [https://developer.concur.com/api-reference/budget/getting-started.html](https://developer.concur.com/api-reference/budget/getting-started.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Budgets
- Financial Planning
- Fiscal Years

#### Properties

- [Documentation](https://developer.concur.com/api-reference/budget/getting-started.html)
- [Documentation](https://developer.concur.com/api-reference/budget/v4.fiscal-year.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Cards API

Provides an automated integration pathway for certified partner financial networks, issuing banks, and fin-tech partners to submit credit card account and transaction data to Concur Expense in near real time.

- **Human URL:** [https://developer.concur.com/api-reference/cards/v4.cards-get-started.html](https://developer.concur.com/api-reference/cards/v4.cards-get-started.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Credit Cards
- Financial Data
- Transactions

#### Properties

- [Documentation](https://developer.concur.com/api-reference/cards/v4.cards-get-started.html)
- [Documentation](https://developer.concur.com/api-reference/cards/v4.cards-endpoints.schemas.html)
- [Documentation](https://developer.concur.com/api-reference/cards/v4.cards-endpoints.account.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Quick Expense API

Enables the creation of expenses with minimal information such as date, amount, and expense type, with or without a receipt image. Supports attaching receipt files including PNG, PDF, TIFF, and JPEG formats up to 50 MB.

- **Human URL:** [https://developer.concur.com/api-reference/expense/quick-expense/v4.quick-expense.html](https://developer.concur.com/api-reference/expense/quick-expense/v4.quick-expense.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Expenses
- Quick Entry
- Receipts

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/quick-expense/v4.quick-expense.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Exchange Rate API

Allows users to create custom exchange rates for a company, supporting bulk uploads of exchange rate data for specified currency pairs and effective dates with a maximum of 100 rates per request.

- **Human URL:** [https://developer.concur.com/api-reference/expense/exchange-rate/v4.exchange-rate.html](https://developer.concur.com/api-reference/expense/exchange-rate/v4.exchange-rate.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Currency
- Exchange Rates
- Financial Data

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/exchange-rate/v4.exchange-rate.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Financial Integration API

Allows an external system to interact with financial documents generated from SAP Concur for financial posting into an ERP, providing an automated solution to request approved expense reports, cash advances, and invoices for import into client internal systems.

- **Human URL:** [https://developer.concur.com/api-reference/financial-integration/v4.financial-integration.html](https://developer.concur.com/api-reference/financial-integration/v4.financial-integration.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- ERP
- Financial Integration
- Posting

#### Properties

- [Documentation](https://developer.concur.com/api-reference/financial-integration/v4.financial-integration.html)
- [Documentation](https://developer.concur.com/api-reference/financial-integration/v4.financial-integration-use-cases-extract-information.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Identity API

Creates, updates, and reads user core identity profiles following the SCIM 2.0 standard. Enables looking up SAP Concur UUIDs for accessing other v4 APIs for individual users.

- **Human URL:** [https://developer.concur.com/api-reference/profile/v4.identity.html](https://developer.concur.com/api-reference/profile/v4.identity.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Identity
- SCIM
- User Profiles

#### Properties

- [Documentation](https://developer.concur.com/api-reference/profile/v4.identity.html)
- [Documentation](https://developer.concur.com/api-reference/profile/v1.getting-started.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Event Subscription Service API

Implements the Publish/Subscribe pattern using principles of Event Driven Architecture, notifying clients and partners when specific business events occur such as expense report status changes and travel request updates.

- **Human URL:** [https://developer.concur.com/api-reference/ess/v4.event-subscription.html](https://developer.concur.com/api-reference/ess/v4.event-subscription.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Events
- Subscriptions
- Webhooks

#### Properties

- [Documentation](https://developer.concur.com/api-reference/ess/v4.event-subscription.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Callouts API

Allows clients to add interactions with outside systems to their users SAP Concur experience through application connectors, supporting attendee data fetch, list item fetch, event notifications, and external URL launches.

- **Human URL:** [https://developer.concur.com/api-reference/callouts/callouts-application-connectors.html](https://developer.concur.com/api-reference/callouts/callouts-application-connectors.html)
- **Base URL:** `https://www.concursolutions.com/api/v1.0`

#### Tags

- Callouts
- Connectors
- Integrations

#### Properties

- [Documentation](https://developer.concur.com/api-reference/callouts/callouts-application-connectors.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Direct Connect Hotel Service API

Provides a method for custom hotel source suppliers to provide hotel inventory, rates, and booking related functionality to SAP Concur Online Booking Tool, supporting search, rate retrieval, reservation management, and cancellation handling.

- **Human URL:** [https://developer.concur.com/api-reference/direct-connects/hotel-service-4/v4.getting-started.html](https://developer.concur.com/api-reference/direct-connects/hotel-service-4/v4.getting-started.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Booking
- Direct Connect
- Hotels

#### Properties

- [Documentation](https://developer.concur.com/api-reference/direct-connects/hotel-service-4/v4.getting-started.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Direct Connect Ground Transportation API

Enables travel users to access ground transportation inventory from service providers, supporting search, reservation, cancellation, and update operations for ground transportation bookings.

- **Human URL:** [https://developer.concur.com/api-reference/direct-connects/ground-transportation.html](https://developer.concur.com/api-reference/direct-connects/ground-transportation.html)
- **Base URL:** `https://www.concursolutions.com/api/v1.0`

#### Tags

- Booking
- Direct Connect
- Ground Transportation

#### Properties

- [Documentation](https://developer.concur.com/api-reference/direct-connects/ground-transportation.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Spend Documents API

Facilitates ingestion and retrieval of receipt documents for use within Concur Expense, enabling users to create and retrieve simple receipts by uploading documents with associated metadata.

- **Human URL:** [https://developer.concur.com/api-reference/spend-documents/v4.spend-documents.html](https://developer.concur.com/api-reference/spend-documents/v4.spend-documents.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Documents
- Receipts
- Spend Management

#### Properties

- [Documentation](https://developer.concur.com/api-reference/spend-documents/v4.spend-documents.html)
- [Documentation](https://developer.concur.com/api-reference/spend-documents/get-receipt.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur List Item API

Provides an automated solution for retrieving, adding, updating, and deleting list items within SAP Concur, supporting hierarchical list structures with parent-child relationships across multiple levels.

- **Human URL:** [https://developer.concur.com/api-reference/common/list-item/v4.list-item.html](https://developer.concur.com/api-reference/common/list-item/v4.list-item.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Configuration
- List Items
- Lists

#### Properties

- [Documentation](https://developer.concur.com/api-reference/common/list-item/v4.list-item.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Lists API

Enables viewing configured lists within SAP Concur products and creating new lists, supporting shared lists across Expense, Invoice, and Request applications with managed list capabilities for partner applications.

- **Human URL:** [https://developer.concur.com/api-reference/common/lists/v4.list.html](https://developer.concur.com/api-reference/common/lists/v4.list.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Configuration
- Lists
- Shared Resources

#### Properties

- [Documentation](https://developer.concur.com/api-reference/common/lists/v4.list.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Travel Profile API

Enables retrieval of travel profile information for specified users and lists of travel profile summaries, available to developers, travel suppliers, and travel management companies.

- **Human URL:** [https://developer.concur.com/api-reference/travel-profile/v2.profile-service.html](https://developer.concur.com/api-reference/travel-profile/v2.profile-service.html)
- **Base URL:** `https://www.concursolutions.com/api/v2.0`

#### Tags

- Loyalty Programs
- Travel Profiles
- User Profiles

#### Properties

- [Documentation](https://developer.concur.com/api-reference/travel-profile/v2.profile-service.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Travel Allowance API

Allows extraction of travel allowance information from the SAP Concur platform, providing the ability to read travel allowance itinerary data, calculation results, and configuration settings.

- **Human URL:** [https://developer.concur.com/api-reference/travelallowance/v4.travelallowance-get-started.html](https://developer.concur.com/api-reference/travelallowance/v4.travelallowance-get-started.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Expenses
- Per Diem
- Travel Allowance

#### Properties

- [Documentation](https://developer.concur.com/api-reference/travelallowance/v4.travelallowance-get-started.html)
- [Documentation](https://developer.concur.com/api-reference/expense/travelallowance/v4.travel-allowance-days-endpoints.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Cash Advance API

Enables users to create, view, and issue cash advances within Concur Expense. Supports single cash advance creation, retrieval, and issuance operations for both Professional and Standard editions. Requires the Identity v4 API to obtain user IDs.

- **Human URL:** [https://developer.concur.com/api-reference/cash-advance/v4-1.cash-advance.html](https://developer.concur.com/api-reference/cash-advance/v4-1.cash-advance.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Cash Advances
- Expenses
- Reimbursements

#### Properties

- [Documentation](https://developer.concur.com/api-reference/cash-advance/v4-1.cash-advance.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Purchase Order API

Gives SAP Concur clients the ability to leverage external data to create and update approved purchase orders. Enables direct connections to manage purchase orders and resolve matching exceptions on invoices through create, update, and retrieve operations.

- **Human URL:** [https://developer.concur.com/api-reference/invoice/v3.purchase-order.html](https://developer.concur.com/api-reference/invoice/v3.purchase-order.html)
- **Base URL:** `https://www.concursolutions.com/api/v3.0`

#### Tags

- Invoices
- Procurement
- Purchase Orders

#### Properties

- [Documentation](https://developer.concur.com/api-reference/invoice/v3.purchase-order.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Purchase Request API

Enables SAP Concur clients to leverage external data to create purchase requests for pre-authorization of purchase orders. Organizations can establish direct connections to automatically generate and submit purchase requests into approval workflows, with approved requests resulting in purchase orders for vendor transmission.

- **Human URL:** [https://developer.concur.com/api-reference/invoice/v4.purchase-request-get-started.html](https://developer.concur.com/api-reference/invoice/v4.purchase-request-get-started.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Approvals
- Procurement
- Purchase Requests

#### Properties

- [Documentation](https://developer.concur.com/api-reference/invoice/v4.purchase-request-get-started.html)
- [Documentation](https://developer.concur.com/api-reference/invoice/v4.purchase-request-endpoints.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Vendor API

Provides processes for managing vendor collections used in invoicing, including adding new vendors, updating, retrieving, and deleting information for existing vendors. Supports vendor banking information, grouping, and extensive search filtering with up to 20 custom fields.

- **Human URL:** [https://developer.concur.com/api-reference/invoice/v3.vendor.html](https://developer.concur.com/api-reference/invoice/v3.vendor.html)
- **Base URL:** `https://www.concursolutions.com/api/v3.0`

#### Tags

- Invoices
- Supplier Management
- Vendors

#### Properties

- [Documentation](https://developer.concur.com/api-reference/invoice/v3.vendor.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Sales Tax Validation API

Enables retrieval and updating of invoices for tax calculation purposes, allowing external tax systems to fetch invoices requiring tax assessment and submit calculated tax amounts and rates back to Concur. Handles comprehensive invoice data including vendor information, billing and shipping addresses, and line items.

- **Human URL:** [https://developer.concur.com/api-reference/invoice/v3.sales-tax-validation.html](https://developer.concur.com/api-reference/invoice/v3.sales-tax-validation.html)
- **Base URL:** `https://www.concursolutions.com/api/v3.0`

#### Tags

- Invoices
- Tax Compliance
- Tax Validation

#### Properties

- [Documentation](https://developer.concur.com/api-reference/invoice/v3.sales-tax-validation.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Document Compliance Gateway API

Manages transmission of compliance documents between SAP Concur and validating vendors, enabling vendors to exchange compliance documents, validate them against relevant authoritative or regulatory sources, and return the validation results. Streamlines compliance document validation and tax data extraction for expense creation.

- **Human URL:** [https://developer.concur.com/api-reference/document-compliance-gateway/V4.document-compliance-gateway.html](https://developer.concur.com/api-reference/document-compliance-gateway/V4.document-compliance-gateway.html)
- **Base URL:** `https://www.concursolutions.com/api/v4.0`

#### Tags

- Compliance
- Document Validation
- Tax Documents

#### Properties

- [Documentation](https://developer.concur.com/api-reference/document-compliance-gateway/V4.document-compliance-gateway.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Image API

Enables clients to manage receipt images attached to expense reports and images associated with invoices. Users can retrieve existing images by report ID, image ID, or invoice ID, and upload new images in PDF, JPEG, JPG, and PNG formats up to 10 MB to users, expense entries, reports, or invoices.

- **Human URL:** [https://developer.concur.com/api-reference/image/v1.image.html](https://developer.concur.com/api-reference/image/v1.image.html)
- **Base URL:** `https://www.concursolutions.com/api/image/v1.0`

#### Tags

- Documents
- Images
- Receipts

#### Properties

- [Documentation](https://developer.concur.com/api-reference/image/v1.image.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Travel Receipts API

Exposes receipt requests to inform E-Receipt partners which E-Receipts to send to SAP Concur and for which user. Partners receive paginated responses and can filter results using optional timestamps, with support for separate US and EMEA datacenter endpoints.

- **Human URL:** [https://developer.concur.com/api-reference/travel-receipts/getting-started.html](https://developer.concur.com/api-reference/travel-receipts/getting-started.html)
- **Base URL:** `https://us.api.concursolutions.com/travelreceipts/v1`

#### Tags

- E-Receipts
- Travel
- Travel Receipts

#### Properties

- [Documentation](https://developer.concur.com/api-reference/travel-receipts/getting-started.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Locations API

Retrieves details about locations used by Concur that are valid at a user's company. Supports filtering by name, city, country, and other geographic parameters, and returns location data including IATA codes, geographic coordinates, airport status, and booking tool availability.

- **Human URL:** [https://developer.concur.com/api-reference/common/locations/v3.locations.html](https://developer.concur.com/api-reference/common/locations/v3.locations.html)
- **Base URL:** `https://www.concursolutions.com/api/v3.0`

#### Tags

- Common Resources
- Geography
- Locations

#### Properties

- [Documentation](https://developer.concur.com/api-reference/common/locations/v3.locations.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Concur Expense Attendee Types API

Provides access to the configured attendee types within SAP Concur, allowing retrieval and management of attendee type resources used for categorizing attendees in expense reports.

- **Human URL:** [https://developer.concur.com/api-reference/expense/attendee-types/v3.attendee-types.html](https://developer.concur.com/api-reference/expense/attendee-types/v3.attendee-types.html)
- **Base URL:** `https://www.concursolutions.com/api/v3.0`

#### Tags

- Attendees
- Configuration
- Expenses

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/attendee-types/v3.attendee-types.html)
- [Postman Collection](collections/sap-concur-expense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sapconcur)
- [Developer Portal](https://developer.concur.com/)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)
- [Authentication](https://developer.concur.com/api-reference/authentication/company-auth.html)
- [Support](https://developer.concur.com/support/)
- [Terms of Service](https://www.concur.com/terms-of-use)
- [Privacy Policy](https://www.concur.com/privacy-policy)
- [Status Page](https://open.concur.com/)
- [Blog](https://www.concur.com/newsroom)
- [Sign Up](https://developer.concur.com/register)
- [GitHub Repository](https://github.com/SAP-docs/preview.developer.concur.com)
- [Release Notes](https://developer.concur.com/tools-support/release-notes/)
- [Changelog](https://developer.concur.com/tools-support/release-notes/)
- [Resources](https://api.sap.com/products/SAPConcur/apis/REST)
- [Tutorials](https://developers.sap.com/tutorials/data-to-value-conn-concur-part01..html)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://www.concur.com/integrations)

## Maintainers

**Email:** kin@apievangelist.com
**URL:** https://developer.concur.com/
