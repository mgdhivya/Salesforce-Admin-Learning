# 📄 Day 6 — Salesforce Admin Learning
## Topic: Page Layout

---

## 📌 What is a Page Layout?

> Controls which **fields, buttons, sections and related lists** appear on a Record Page and how they are arranged.

- Created by **Admin**
- Assigned to Users through **Profiles**
- Different users can see **different page layouts**
- One Object can have **multiple page layouts**

---

## 🎛️ What Admin can Control

- Which **Fields, Buttons, Sections, Related Lists** appear on the page
- Which fields are **Required** (must fill) and **Read Only** (only view)
- **Order** of fields on the page

---

## 💡 Real Time Example — IT Company

| Field | Employee Sees | HR Sees |
|---|---|---|
| Name | ✅ | ✅ |
| ID | ✅ | ✅ |
| Department | ✅ | ✅ |
| Joining Date | ✅ | ✅ |
| Salary | ❌ Hidden | ✅ |
| Appraisal | ❌ Hidden | ✅ |

---

## 🔗 Simple Assignment Rule

```
Page Layout → assigned to → Profile → assigned to → User
```

---

## 📋 Types of Page Layout

### 1. Standard Page Layout
- Created by **Salesforce**
- Already available when you create an object
- Admin can **Edit** but **cannot Delete**
- Examples: `Account Layout`, `Contact Layout`, `Opportunity Layout`

### 2. Custom Page Layout
- Created by **Admin**
- Based on company needs
- Admin can **Create, Edit and Delete**
- Examples: `HR Layout`, `Employee Layout`, `Manager Layout`

---

## 🛠️ How to Create a Page Layout

```
Step 1: Go to Setup → Click Object Manager
Step 2: Type Account in search box
Step 3: Account page opens
Step 4: Click Page Layouts → Click New button
Step 5: Choose Existing Page Layout + Give New Name
Step 6: Page Layout Editor opens
        → Drag and Drop fields, buttons, sections
Step 7: Click Save ✅
```

---

## 👁️ How to Assign Page Layout to a Profile

```
Step 1: Go to Setup → Click Object Manager
Step 2: Type Account in search box
Step 3: Account page opens
Step 4: Click Page Layouts → Click Page Layout Assignment
Step 5: Click Edit Assignment
        → Choose Profile → Choose Page Layout
Step 6: Click Save ✅
```

---

## 👤 Profile Quick Reference

| Profile Name | Who Uses It |
|---|---|
| System Administrator | Admin / HR |
| Standard User | Normal Employee |
| Read Only | People who can only VIEW data |
| Solution Manager | Manager |
| Chatter User | Basic users |

---

## 🔒 Required and Read Only Fields

**Location:**
```
Page Layout Editor
→ Double Click any field
→ Popup opens
→ Required and Read Only checkboxes appear!
```

| Setting | Meaning |
|---|---|
| ✅ Required | User MUST fill this field before saving |
| ✅ Read Only | User can only VIEW, cannot edit |

---

## 📎 Related Lists

### What is it?
> Shows **connected records** from other objects at the **bottom** of a record page.
> Saves time — no need to go to object tabs separately!

### Real Time Example:
```
Open HDFC Bank India (Account Record)
→ Scroll to bottom
→ You can see:
   ✅ Contacts  → Ravi, Priya
   ✅ Opportunities → Loan Deal $50,000
   ✅ Cases → Ticket #001
```

### Admin Controls:
- Which related lists **appear**
- Which are **hidden**
- **Order** of related lists
- **Columns** inside each list

### How to Set it:
```
Step 1: Go to Setup → Click Object Manager
Step 2: Type Account → Click Page Layouts
Step 3: Page Layout Editor opens
Step 4: Click "Related Lists" tab in top palette
Step 5: Drag and Drop related lists
Step 6: Click Save ✅
```

### How to Verify:
```
→ Open any Account record
→ Click Related tab
→ You can see all related lists ✅
```

---

## 🔍 Mini Page Layout

### What is it?
> Controls fields shown in a **small popup** that appears when you **hover** over a blue colour text (blue link) — without opening the full record!

### What is Blue Colour Text?
> When **one record is connected to another record** — it shows as **blue colour text (blue link)**

```
Example — Loan Deal (Opportunity Record):
Account Name : HDFC Bank India  ← 🔵 Blue Link
Owner        : DHIVYA MG        ← 🔵 Blue Link
```

### What is Hover?
> Moving your mouse OVER a blue link **without clicking** it → wait 1-2 seconds → small popup appears!

### Why it is Needed?
> To see **quick information** without opening the full record — saves time!

### Real Time Example:
```
Open Opportunity Record (Loan Deal)
→ You see HDFC Bank India in blue colour
→ Hover your mouse over it without clicking
→ Small popup appears instantly showing
  quick information about HDFC Bank India ✅
```

### How to Set it:
```
Step 1: Go to Setup → Click Object Manager
Step 2: Type Account → Click Page Layouts
Step 3: Open Account Layout
        → Page Layout Editor opens
Step 4: Look at TOP RIGHT corner
        → Click "Mini Page Layout" link
Step 5: New window opens
        → Drag fields you want in popup
Step 6: Click Save ✅
```

### How to Verify:
```
→ Open any Opportunity Record
→ Hover over Account Name blue link
→ Popup shows the new fields you added ✅
→ You can see only controlled fields
  created by Admin ✅
```

---

## 📊 Full Summary

| Topic | One Line |
|---|---|
| Page Layout | Controls what appears on a record page |
| Created by | Admin |
| Assigned through | Profile |
| Standard Layout | Created by Salesforce — can edit, not delete |
| Custom Layout | Created by Admin — can create, edit, delete |
| Required Field | Must fill before saving |
| Read Only Field | Can view but not edit |
| Related Lists | Connected records at bottom of page — saves time |
| Mini Page Layout | Fields in hover popup over a blue link |

---

## 🔗 Difference: Full Page Layout vs Mini Page Layout

| | Full Page Layout | Mini Page Layout |
|---|---|---|
| Opens when | You CLICK a record | You HOVER over blue link |
| Size | Full big page | Small popup box |
| Shows | Everything | Quick info only |
| Purpose | View and edit everything | Quick view without opening |

---

## 💻 Dev Org Practical — What I did today

- ✅ Created a new Custom Page Layout for Account object
- ✅ Assigned Page Layout to different Profiles
- ✅ Set Required and Read Only fields in Page Layout Editor
- ✅ Added and removed Related Lists from Page Layout
- ✅ Edited Mini Page Layout — added Phone, Industry fields to hover popup
- ✅ Verified all changes live in Dev Org

---
