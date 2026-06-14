# SAP Concur GraphQL Schema

## Overview

This is a conceptual GraphQL schema for the SAP Concur platform, the leading provider of integrated travel, expense, and invoice management solutions. The schema unifies SAP Concur's multiple REST APIs — Expense, Travel, Invoice, Request, Cards, Budget, and more — into a single, coherent GraphQL surface.

SAP Concur's REST API reference: https://developer.concur.com/api-reference/
GitHub: https://github.com/SAP-docs/preview.developer.concur.com

---

## Schema Source

**Source**: Conceptual — derived from SAP Concur's public REST API documentation and data models across the following API products:

- Concur Expense API (v3.0 / v4.0)
- Concur Travel API (v3.0)
- Concur Invoice API (v3.0)
- Concur Request API (v4.0)
- Concur User Provisioning API (v4.0)
- Concur Receipt API (v3.0)
- Concur Budget API (v4.0)
- Concur Cards API (v4.0)
- Concur Cash Advance API (v4.1)
- Concur Purchase Order / Purchase Request API (v3.0 / v4.0)
- Concur Vendor API (v3.0)
- Concur Exchange Rate API (v4.0)
- Concur Financial Integration API (v4.0)
- Concur Identity API (v4.0)
- Concur Event Subscription Service (v4.0)
- Concur List / List Item API (v4.0)
- Concur Locations API (v3.0)
- Concur Travel Profile API (v2.0)
- Concur Travel Allowance API (v4.0)
- Concur Spend Documents API (v4.0)
- Concur Image API (v1.0)
- Concur Travel Receipts API (v1.0)

---

## Type Summary (70 named types)

### Expense

| Type | Description |
|------|-------------|
| `ExpenseReport` | Top-level expense report submitted by an employee |
| `ReportDetail` | Detailed view of a report including audit trail |
| `ReportEntry` | A single expense line item within a report |
| `ExpenseType` | Categorized expense type (Airfare, Hotel, Meals, etc.) |
| `ExpenseCategory` | Grouping of expense types |
| `ExpenseAllocation` | Distribution of an expense across cost centers or projects |
| `CostCenter` | Organizational cost center for financial allocation |
| `BusinessPurpose` | Business justification for an expense |
| `Itemization` | Itemized sub-line (e.g., hotel folio breakdown) |

### Attendees

| Type | Description |
|------|-------------|
| `Attendee` | A person attending a business meal or event |
| `AttendeeDetail` | Additional detail for a specific attendee instance |
| `AttendeeType` | Configured attendee type (Client, Employee, Guest) |

### Financial / Amounts

| Type | Description |
|------|-------------|
| `ExpenseAmount` | A monetary value with currency |
| `Currency` | Currency definition with code, name, and symbol |
| `TaxRate` | A tax rate applicable to expenses or invoices |
| `ExchangeRate` | Exchange rate between two currencies |
| `TaxConfiguration` | Tax configuration for a country or region |

### Receipts

| Type | Description |
|------|-------------|
| `Receipt` | A receipt attached to an expense entry |
| `ReceiptImage` | Image representation of a receipt |
| `EReceipt` | Electronic receipt from a travel or commerce partner |
| `ReceiptProvider` | An e-receipt provider partner |

### Travel

| Type | Description |
|------|-------------|
| `TripBooking` | A complete travel itinerary |
| `TravelReservation` | A single reservation within a trip |
| `HotelReservation` | A hotel stay booking |
| `Flight` | A complete flight booking with segments |
| `FlightSegment` | A single flight leg |
| `CarRental` | A car rental reservation |
| `RailBooking` | A train/rail booking |
| `DiningBooking` | A restaurant reservation |
| `GroundTransportation` | Ground transportation booking |
| `TravelAllowance` | Travel allowance itinerary for per-diem calculations |
| `TravelAllowanceDay` | Per-diem allowance for a single day |
| `TravelAllowanceAdjustment` | An adjustment to a daily travel allowance |

### Vendors

| Type | Description |
|------|-------------|
| `Vendor` | A vendor or supplier |
| `VendorDetail` | Detailed vendor contact and tax information |
| `VendorBankingInfo` | Vendor banking/payment details |
| `VendorLocation` | A specific vendor location |

### Policy & Approval

| Type | Description |
|------|-------------|
| `Policy` | An expense or travel policy |
| `PolicyRule` | A single rule within a policy |
| `Approval` | Approval state and metadata |
| `ApprovalStatus` | Status detail for an approval step |
| `Approver` | An individual approver |
| `RoleAssignment` | A role assigned to a user |
| `WorkflowStep` | A step in an approval workflow |

### Payment

| Type | Description |
|------|-------------|
| `PaymentMethod` | A payment method (card, bank account) |
| `CreditCard` | A credit card |
| `PurchaseCard` | A corporate purchase card (P-Card) |
| `BankAccount` | A bank account for reimbursement |

### Travel Requests

| Type | Description |
|------|-------------|
| `TravelRequest` | A pre-trip travel request requiring approval |
| `PreTripApproval` | Approval record for a travel request |
| `RequestEntry` | An entry within a travel request |
| `RequestAllocation` | Cost allocation within a travel request |
| `RequestApproval` | Approval details for a travel request |

### Cash Advance

| Type | Description |
|------|-------------|
| `CashAdvance` | A cash advance issued to an employee |
| `CashAdvanceRequest` | A request to create a cash advance |

### Reimbursement

| Type | Description |
|------|-------------|
| `Reimbursement` | A reimbursement payment to an employee |
| `ReimbursementBatch` | A batch of reimbursements processed together |

### Invoice

| Type | Description |
|------|-------------|
| `Invoice` | An accounts payable invoice |
| `InvoiceRequest` | A request to create or pay an invoice |
| `InvoiceLine` | A line item on an invoice |
| `Payment` | A payment made against an invoice |
| `DirectPayment` | A direct payment outside of invoice workflow |
| `PurchaseOrder` | A purchase order linked to invoices |
| `PurchaseOrderLine` | A line item on a purchase order |

### Authentication / Integration

| Type | Description |
|------|-------------|
| `APIKey` | An API key for programmatic access |
| `OAuthToken` | An OAuth 2.0 access token |
| `Webhook` | A webhook subscription for event notifications |

### Common / Shared

| Type | Description |
|------|-------------|
| `Location` | A geographic location (city, airport, etc.) |
| `Address` | A postal address |
| `User` | A Concur system user |
| `Comment` | A comment on a document or workflow step |
| `AuditEntry` | An audit trail entry |
| `ConcurList` | A configurable list resource |
| `ListItem` | An item within a configurable list |
| `Budget` | Budget header for a fiscal period |
| `FiscalYear` | A fiscal year definition |
| `FiscalPeriod` | A fiscal period within a fiscal year |
| `BudgetTrackingField` | A tracking field for a budget |

---

## Authentication

SAP Concur uses OAuth 2.0 for all API authentication. The `oauthToken` query returns an access token using the client credentials or authorization code grant flow.

Reference: https://developer.concur.com/api-reference/authentication/getting-started.html

**Scopes used across the Concur API surface:**

- `expense.report.read` / `expense.report.write`
- `expense.report.workflowstatus.write`
- `travel.itinerary.read`
- `invoice.read` / `invoice.write`
- `travelrequest.write`
- `cashadvance.read` / `cashadvance.write`
- `user.read` / `user.write`
- `budget.read` / `budget.write`
- `receipts.read` / `receipts.write`
- `webhook.write`

---

## Key Design Decisions

1. **Unified type graph**: Multiple Concur REST endpoints that return overlapping data are merged into single types (e.g., `ExpenseReport` covers both v3 and v4 report fields).

2. **ExpenseAmount scalar wrapper**: All monetary values are expressed as `ExpenseAmount { value, currency }` to enforce currency-awareness throughout the schema.

3. **Polymorphic TravelReservation**: Rather than separate query fields per segment type, `TravelReservation` includes optional fields for each segment type (`flight`, `hotel`, `carRental`, etc.) matched via `type: TravelSegmentType`.

4. **Approval workflow as first-class type**: `WorkflowStep` and `Approval` are standalone types that can be referenced from expense reports, travel requests, and invoices alike.

5. **Event-driven integration via Webhook type**: The `Webhook` type mirrors Concur's Event Subscription Service for publish/subscribe patterns.

---

## Example Queries

### Fetch an Expense Report with Entries

```graphql
query GetExpenseReport($id: ID!) {
  expenseReport(id: $id) {
    id
    name
    status
    totalAmount {
      value
      currency {
        code
        symbol
      }
    }
    owner {
      firstName
      lastName
      email
    }
    entries {
      id
      expenseType {
        name
        code
      }
      transactionDate
      transactionAmount {
        value
        currency { code }
      }
      vendor {
        vendorId
        addressLine1
        city
        country
      }
      receipt {
        id
        isVerified
        receiptImage {
          url
          contentType
        }
      }
      attendees {
        firstName
        lastName
        company
        isEmployee
      }
    }
    workflow {
      stepName
      status
      approver {
        user {
          firstName
          lastName
        }
      }
      completedDate
    }
  }
}
```

### Submit a Travel Request

```graphql
mutation CreateAndSubmitRequest {
  createTravelRequest(input: {
    name: "Q3 Sales Conference - Chicago"
    purpose: "Attend annual sales conference and meet key accounts"
    startDate: "2026-09-15"
    endDate: "2026-09-18"
    destination: "Chicago, IL"
  }) {
    id
    requestId
    status
    totalEstimatedAmount {
      value
      currency { code }
    }
  }
}
```

### Upload Bulk Exchange Rates

```graphql
mutation UploadRates {
  bulkCreateExchangeRates(input: [
    { fromCurrency: USD, toCurrency: EUR, rate: 0.9215, effectiveDate: "2026-06-14" }
    { fromCurrency: USD, toCurrency: GBP, rate: 0.7890, effectiveDate: "2026-06-14" }
    { fromCurrency: USD, toCurrency: JPY, rate: 157.42, effectiveDate: "2026-06-14" }
  ]) {
    fromCurrency { code }
    toCurrency { code }
    rate
    effectiveDate
  }
}
```

### Register a Webhook

```graphql
mutation RegisterWebhook {
  createWebhook(input: {
    topic: "expense"
    eventType: EXPENSE_REPORT_SUBMITTED
    webhookUrl: "https://my-app.example.com/hooks/concur"
  }) {
    id
    eventType
    webhookUrl
    isActive
    createdDate
  }
}
```

---

## Related Resources

- Developer Portal: https://developer.concur.com/
- API Reference: https://developer.concur.com/api-reference/
- Authentication Guide: https://developer.concur.com/api-reference/authentication/getting-started.html
- SAP Business Accelerator Hub: https://api.sap.com/products/SAPConcur/apis/REST
- GitHub (SAP Concur docs): https://github.com/SAP-docs/preview.developer.concur.com
- Status Page: https://open.concur.com/
- Release Notes: https://developer.concur.com/tools-support/release-notes/
