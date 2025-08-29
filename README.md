# Mutual of Omaha Dashboard Demo 📅🎬🚀
> *For the consideration of Mutual of Omaha by [Elijah Offutt](https://elijahoffutt.com)*
---
**Ever feel like managing insurance is as much fun as untangling holiday lights? Not anymore.** This dashboard brings clarity, control, and maybe even a tad of joy to managing policies—because who said policy portals have to be dull?
---
## 👷 Project Overview  
- 🖼️ **Purpose**:  Build a polished, customer-facing portal inspired by Mutual of Omaha’s Customer Access feature suite — let users manage policies, billing, claims, and support all.
- 🧩 **Design Pattern**:  Left-side ranked-order navigation; right-side tabbed feature views (e.g., Policy Details, Billing, Claims, Resources).  
- ⚙️ **Tech Stack**:  
  - 👨 **Frontend**: Vue => Framework + Pinia => State + Vuetify => Visual  
  - 🧠 **Backend**: PHP 8 => Language + Laravel => Framework  
  - 🗃️ **Database**: SQLite 

---
## 📋 Feature List
### 1. Policy Overview  
**Specification**  
- Displays active policies (Life, Medicare Supplement, Long-Term Care)  
- Shows policy type, status, effective/renewal dates, plus a quick coverage summary  
- Click a policy to open a detailed view with tabs: **Overview**, **Documents**, **Coverage Details**

**Acceptance Criteria**  
-  Sidebar lists policies sorted by renewal date  
-  Each policy shows essential summary data at a glance  
-  Clicking a policy loads the correct Overview tab  
-  Documents tab delivers downloadable PDFs; Coverage Details tab shows specifics

---

### 2. Billing & Payments  
**Specification**  
- Displays unpaid or pending payments, with due dates and amounts  
- Includes one-click **Pay Now**, with saved or new payment methods  
- Contains a Payment History tab detailing date and amount

**Acceptance Criteria**  
-  Upcoming due payments are front and center  
-  Payment modal functions properly in test mode  
-  Payment History accurately lists past transactions

---

### 3. Claims Management  
**Specification**  
- Tabbed interface for submitting new claims, checking status, and accessing support  
- Claims List displays type, filing date, status, and reference number  
- Submit Claim form adapts fields based on claim type

**Acceptance Criteria**  
-  Claim form validates and successfully submits  
-  New claims appear instantly with a “Pending” status  
-  Claim detail view shows full information; updates are possible if permitted  
-  Support links (e.g., “File a Life Insurance claim”) are visible and functional

---

### 4. Forms & Support Resources  
**Specification**  
- **Resources** tab: quick access to forms (by category/state), FAQs, policy guides  
- Features search/filtering; items are downloadable or linked

**Acceptance Criteria**  
-  Resources list populates correctly (Forms, FAQs, Guides)  
-  Filters return relevant documents by keyword or state  
-  Downloads and links work seamlessly (new tab or file download)

---

### 5. Enrollment & Benefits Tools *(Employer-Sponsored Users Only)*  
**Specification**  
- Special tab for employer-sponsored users: **Benefits Overview**, **Provider Directory**, **Enrollment Platform**  
- Benefits Overview shows group plans (e.g., Dental, Disability, FMLA)  
- Provider Directory allows filtering by type or location  
- Enrollment Platform integrates a STEPS-style workflow

**Acceptance Criteria**  
-  Benefits table displays enrolled plans with coverage details  
-  Provider Directory filters and lists providers correctly  
-  Enrollment workflow link or embedded flow is accessible and working

---

### 6. Advocacy & Additional Services  
**Specification**  
- Includes optional services: Advocacy (nurse coordination, preauthorization), Travel Assistance, EAP, Will Preparation, Hearing Discounts  
- Service cards with description and buttons: **Learn More** or **Activate**

**Acceptance Criteria**  
-  Service cards display accurate information  
-  “Learn More” opens detailed info (page or modal)  
-  “Activate” simulates an enrollment flow

---

