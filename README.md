# GST-Hindi-2

# 🗂️ Vyapar TaxOne GST Automation Module  
### Trainer’s Handbook (Conversational Style)

**For:** Sales & Support Teams  
**Module:** GST Automation  
**Version:** Internal Use Only  

---

## 📌 Table of Contents

- [1️⃣ Welcome](#1️⃣-welcome-to-the-gst-automation-module)
- [2️⃣ Why We Built This](#2️⃣-why-we-built-this)
- [3️⃣ Dashboard & Company Overview](#3️⃣-dashboard--company-overview)
- [GST Reconciliation](#gst-reconciliation)
- [Invoice Management System (IMS)](#invoice-management-system-ims)
- [Return Filing (GSTR-1 / IFF / 3B)](#return-filing-gstr-1--iff--3b)
- [Key Advantages](#key-advantages)

---

# 1️⃣ Welcome to the GST Automation Module

Hey team! 👋  

इस session में हम explore करेंगे Vyapar TaxOne का powerful feature — **GST Automation**.

यह एक automation layer है specially CAs & Accountants के लिए, जिससे वे अपने clients का GST compliance monitor, reconcile और manage कर सकते हैं — directly Vyapar TaxOne के अंदर।

---

# 2️⃣ Why We Built This

आज हर CA multiple GSTINs handle करता है, dozens of clients manage करता है और hundreds of filings करता है।

Earlier, GST portal पर बार-बार login करना पड़ता था:

- Filing status check करने के लिए  
- Notices देखने के लिए  
- Return mismatches identify करने के लिए  

With GST Automation:

> “Entire GST visibility — filings, notices, returns और compliance health — in one place.”

---

# 3️⃣ Dashboard & Company Overview

<details>
<summary><strong>📊 3.1 Dashboard – The Compliance Control Room</strong></summary>

### What It Shows:
- GSTIN validity (Active / Cancelled / Suspended / Invalid)
- GSTR-1 & GSTR-3B filing status
- Current month filing summary
- Notices & alerts (Graphical view)

### 💬 Sales Pitch
> “Entire GST filing health visible at a glance — no portal hopping.”

### 💬 Support Checklist
1. GSTIN added?
2. GST credentials connected?
3. Sync performed?

</details>

---

<details>
<summary><strong>🧾 3.2 Company Summary – GST Storyboard</strong></summary>

### Includes:
- Return Filing Tracker
- GSTR-1 & 3B Summary
- Graphs:
  - GSTR-1 vs 3B
  - GSTR-2B vs 3B
  - Interest vs Late Fees
- Tax Ledger Summary
- One-click PDF report

</details>

---

<details>
<summary><strong>📬 3.3 Notices & Orders</strong></summary>

### Features:
- Auto-fetch from GST Portal
- General Notices (FYI)
- Additional Notices (Action Required)
- Calendar View
- Company View
- Direct Download Option

</details>

---

# 🔐 Data Sync & Portal Fetching

<details>
<summary><strong>🗂️ Option 1 — OTP Sync (Manual)</strong></summary>

- OTP via registered mobile/email
- Valid for 6 hours
- Suitable for occasional sync

</details>

<details>
<summary><strong>🖥️ Option 2 — Desktop App Sync (Automated)</strong></summary>

- Uses saved GST credentials
- Faster recurring sync
- Recommended for multi-GSTIN firms

### Pre-Requisites:
1. Credentials correct
2. Retry password if needed
3. GST portal not open in browser

### Sync Types:
- Global Sync → Full data
- Month-wise Sync → Selected month only

</details>

---

# GST Reconciliation

<details>
<summary><strong>1️⃣ Overview</strong></summary>

Line-by-line comparison between GST Portal & Tally based on:

- GSTIN
- Invoice Number
- Invoice Date
- Taxable Amount
- Tax Amount

</details>

---

<details>
<summary><strong>2️⃣ Supported Reconciliation Types</strong></summary>

- GSTR-1 vs Tally Sales Register  
- GSTR-2A / 2B / IMS vs Tally Purchase Register  

Credit/Debit Notes automatically included.

</details>

---

<details>
<summary><strong>3️⃣ Match Categories</strong></summary>

| Match Type | Meaning |
|------------|---------|
| Exact Match | 99–100% match |
| Suggested Match | Minor difference |
| Partial Match | Major mismatch |
| Not in Portal | Present in Tally only |
| Not in Books | Present in Portal only |

</details>

---

<details>
<summary><strong>4️⃣ Error Configuration</strong></summary>

Location: `More Action > Error Configuration`

Settings:
- Round-off tolerance
- Invoice number tolerance
- Date allowance
- Amount tolerance (₹200 etc.)
- Auto Forward/Backward

</details>

---

# Invoice Management System (IMS)

<details>
<summary><strong>Actions Available</strong></summary>

- ✅ Accept  
- ❌ Reject  
- ⏳ Pending  

</details>

---

<details>
<summary><strong>ITC Comparison</strong></summary>

Compare:
- As per Vyapar TaxOne
- As per GSTR-3B
- As per GSTR-2B

Suggested invoices → One-click Accept → Submit to Portal

</details>

---

# Return Filing (GSTR-1 / IFF / 3B)

<details>
<summary><strong>GSTR-1 / IFF Filing</strong></summary>

Supports:
- Government Excel formats
- Amazon / Flipkart files
- OCR (JPG/PDF)
- Any Format Upload

No reformatting required.

</details>

---

<details>
<summary><strong>Validation (Rule 59, CGST Rules 2017)</strong></summary>

- Invalid Invoice Number
- Invalid GSTIN
- POS mismatch
- Invalid Tax Rate
- Duplicate Invoice

Review & Fix Errors panel available.

</details>

---

<details>
<summary><strong>GSTR-3B Filing</strong></summary>

- Auto-fetched data
- Editable ITC & liability
- Payment of Tax
- File Return

Interface similar to GST Portal.

</details>

---

# ⭐ Key Advantages

- All file formats supported
- Integrated error detection
- Direct linkage with Reconciliation & IMS
- Complete GST automation ecosystem

---

# 🏁 Demo Closing Line

> “Vyapar TaxOne’s GST Automation isn’t just software — it’s a CA’s compliance command center.”
