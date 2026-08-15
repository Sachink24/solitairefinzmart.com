# SOLITAIRE Finz Mart

> **Digital Loan Distribution & DSA Management Platform**

SOLITAIRE Finz Mart is a centralized digital platform designed to manage the complete loan-processing lifecycle for a **Direct Selling Agent (DSA)** business — from customer lead generation and lead entry to credit evaluation, legal and technical verification, sanction, disbursement, and payout.

The platform is designed to connect **Business Associates, Credit, Legal, Technical, Admin, and Management teams** through a structured workflow.

## 🌐 Live Application

**[Open SOLITAIRE Finz Mart](https://sachink24.github.io/solitairefinzmart.com/)**

---

## 🎯 Purpose

SOLITAIRE Finz Mart aims to replace fragmented spreadsheets, WhatsApp communication, manual follow-ups, and disconnected department processes with a centralized digital workflow.

### Complete Loan Journey

```text
Lead Generation
      ↓
Lead Entry
      ↓
Customer & Document Collection
      ↓
Credit Evaluation
      ↓
Legal Verification
      ↓
Technical Verification
      ↓
Sanction
      ↓
Disbursement
      ↓
Payout Calculation
      ↓
Payout Settlement
```

---

## 🚀 Core Features

### 👤 Lead Management

Centralized customer and lead management.

- New lead entry
- Customer details
- Contact information
- Loan requirement
- Product selection
- Lead source
- Lead assignment
- Lead status
- Follow-up tracking
- Lead search and filtering

### 🏦 Loan Product Management

The platform can be structured to manage multiple financial products, such as:

- Home Loan
- Loan Against Property
- Personal Loan
- Business Loan
- Mortgage Loan
- Balance Transfer
- Top-Up Loan
- Other financial products

---

## 👥 Role-Based Workflow

SOLITAIRE Finz Mart is designed around department-specific responsibilities.

### 🔑 Admin

The Admin acts as the central controller.

Admin responsibilities include:

- User management
- Team management
- Lead monitoring
- Product management
- Lender management
- Workflow control
- Department assignment
- Reports
- Document management
- Performance monitoring
- Payout management

### 🤝 Business Associate / DSA Team

The BA team handles the initial customer relationship and lead generation.

Typical workflow:

```text
Customer
   ↓
Lead Entry
   ↓
Customer Information
   ↓
Document Collection
   ↓
Lead Submission
```

### 💳 Credit Team

The Credit Team evaluates the financial profile of the customer.

Possible activities:

- Income assessment
- Banking analysis
- CIBIL/credit profile review
- FOIR assessment
- Eligibility calculation
- Loan amount assessment
- Repayment capacity
- Credit observations
- Credit recommendation

### ⚖️ Legal Team

The Legal Team manages legal and property-related verification.

Possible activities:

- Document verification
- Title verification
- Ownership verification
- Legal search
- Property document review
- Legal observations
- Legal report
- Approval / rejection / query

### 🏗️ Technical Team

The Technical Team handles property and technical evaluation.

Possible activities:

- Property inspection
- Property valuation
- Construction assessment
- Market value
- Property observations
- Technical report
- Approval / rejection / query

### 📝 Sanction

After successful processing, the case can move toward sanction.

The sanction stage may contain:

- Sanction amount
- Interest rate
- Tenure
- EMI
- Processing fee
- Conditions
- Sanction status
- Sanction letter

### 💰 Disbursement

The disbursement stage manages the final funding process.

Possible information:

- Disbursement amount
- Disbursement date
- Bank/NBFC
- Disbursement status
- Tranche information
- Final documentation
- Case closure

### 💵 Payout Management

The payout module can track DSA/BA earnings after disbursement.

Possible calculations:

```text
Disbursed Amount
        ↓
Applicable Payout %
        ↓
Gross Payout
        ↓
Adjustments / Taxes
        ↓
Net Payout
```

---

## 🏢 Lender / Bank & NBFC Management

The platform can maintain a centralized lender database containing:

- Bank
- NBFC
- Loan products
- Product eligibility
- Interest rates
- Processing fees
- Loan limits
- DSA payout structure
- Documentation requirements
- Product-specific criteria

This helps the DSA team identify suitable lending partners for customer requirements.

---

## 📊 Management Dashboard

The management dashboard can provide a centralized overview of business performance.

### Key KPIs

- Total Leads
- Active Leads
- Login Cases
- Sanctioned Cases
- Disbursed Cases
- Pending Cases
- Rejected Cases
- Total Disbursement
- Expected Payout
- Paid Payout
- Team Performance

### Example Pipeline

```text
LEADS
  ↓
LOGIN
  ↓
CREDIT
  ↓
LEGAL
  ↓
TECHNICAL
  ↓
SANCTION
  ↓
DISBURSEMENT
  ↓
PAYOUT
```

---

## 📋 Case Status Management

Each application can move through clearly defined statuses.

| Stage | Example Status |
|---|---|
| Lead | New |
| Lead | Contacted |
| Lead | Documents Pending |
| Login | Submitted |
| Credit | Under Review |
| Credit | Query |
| Credit | Approved |
| Legal | Pending |
| Legal | Clear |
| Legal | Query |
| Technical | Pending |
| Technical | Clear |
| Sanction | Sanctioned |
| Disbursement | Pending |
| Disbursement | Disbursed |
| Payout | Pending |
| Payout | Paid |
| Case | Closed |
| Case | Rejected |

---

## 📄 Document Management

A centralized document system can maintain documents associated with each customer/application.

### Customer Documents

- PAN Card
- Aadhaar
- Address Proof
- Income Proof
- Bank Statements
- ITR
- GST Documents
- Business Proof
- Property Documents
- Other Supporting Documents

### Reports & Documents

- Credit Report
- Legal Report
- Technical Report
- Sanction Letter
- Disbursement Documents
- Invoice
- Payout Statement

---

## 🔄 Department Workflow

```text
                 ┌───────────────┐
                 │ Business      │
                 │ Associate     │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │ Lead Entry    │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │ Document     │
                 │ Collection   │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │ Credit Team   │
                 └───────┬───────┘
                         │
              ┌──────────┴──────────┐
              ▼                     ▼
       ┌─────────────┐       ┌─────────────┐
       │ Legal Team  │       │ Technical   │
       │             │       │ Team        │
       └──────┬──────┘       └──────┬──────┘
              └──────────┬──────────┘
                         ▼
                  ┌─────────────┐
                  │  Sanction   │
                  └──────┬──────┘
                         │
                         ▼
                  ┌─────────────┐
                  │ Disbursement│
                  └──────┬──────┘
                         │
                         ▼
                  ┌─────────────┐
                  │   Payout    │
                  └─────────────┘
```

---

## 📈 Reporting & MIS

The platform can be extended with management reports covering:

### Lead MIS

- Lead source
- BA-wise leads
- Product-wise leads
- Lender-wise leads
- Status-wise leads

### Credit MIS

- Login cases
- Approved cases
- Rejected cases
- Pending cases
- Query cases

### Disbursement MIS

- Daily disbursement
- Monthly disbursement
- Lender-wise disbursement
- Product-wise disbursement
- BA-wise production

### Payout MIS

- Expected payout
- Received payout
- Pending payout
- BA-wise payout
- Lender-wise payout

---

## 🔐 Security & Access Control

For production deployment, the platform should implement:

- Role-based access control
- Secure authentication
- Department-level permissions
- Protected customer information
- Database security policies
- Audit logs
- Secure file storage
- API authentication
- Environment variables for secrets
- HTTPS

**Never expose Supabase service-role keys, database passwords, private API keys, or other sensitive credentials in frontend code or public repositories.**

---

## 🧩 Suggested System Architecture

```text
                    SOLITAIRE FINZ MART
                           │
              ┌────────────┴────────────┐
              │                         │
          Frontend                   Backend
              │                         │
       Web Application              Database
              │                         │
       ┌──────┼──────┐          ┌───────┼───────┐
       │      │      │          │       │       │
      BA   Credit  Admin      Leads   Users  Documents
       │      │      │          │       │       │
       └──────┴──────┘          └───────┴───────┘
                    │
                    ▼
              Reports / MIS
```

---

## 🛠️ Technology

The project is currently deployed through **GitHub Pages**.

### Deployment

```text
Development
     ↓
GitHub Repository
     ↓
GitHub Pages
     ↓
SOLITAIRE Finz Mart
```

The architecture can be extended with a cloud backend such as Supabase for:

- Authentication
- Database
- File storage
- Row-level security
- Real-time updates
- API services

---

## 📱 Platform Vision

SOLITAIRE Finz Mart is intended to evolve into a complete **DSA Loan Management System** covering:

**Lead → Login → Credit → Legal → Technical → Sanction → Disbursement → Payout**

The long-term objective is to create one centralized platform where every department can work on the same application while management gets complete visibility of the business pipeline.

---

## 🔮 Future Enhancements

Planned or possible enhancements include:

- 🤖 AI-based lead scoring
- 🎯 AI lender/product matching
- 📄 OCR document extraction
- 🧠 AI credit analysis
- 📊 Advanced analytics
- 📱 Mobile application
- 💬 WhatsApp integration
- 📧 Automated email notifications
- 🔔 Task and follow-up reminders
- 🏦 Bank/NBFC API integrations
- 📑 Automated PDF reports
- 💰 Automated payout calculation
- 🔐 Advanced RBAC
- 📝 Complete audit trail
- 📈 Real-time MIS dashboard
- ☁️ Cloud-based document storage

---

## 🌐 Live Demo

**SOLITAIRE Finz Mart**

https://sachink24.github.io/solitairefinzmart.com/

---

## 👨‍💻 Developer

**Sachin Kale**

GitHub:  
https://github.com/Sachink24

---

## 📄 License

This project is developed for the **SOLITAIRE Finz Mart** business ecosystem.

Copyright © 2026 **SOLITAIRE Finz Mart**. All rights reserved.

---

## ⭐ Vision

> **One Customer · One Application · One Workflow · Complete Control**

**SOLITAIRE Finz Mart** brings the complete DSA loan-processing journey into one centralized digital ecosystem.