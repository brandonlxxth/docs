# Reference placeholders (—) to document

The following table rows use **—** as the description. Document each in the corresponding MDX file so users know what the field or column does.

---

## enterprise/pages/user-profile.mdx

| Location | Field / Column | Table | Action |
|----------|----------------|-------|--------|
| Required permissions | **User Profile** | Permissions table (User Role Permission column) | Replace "—" with the actual permission name if any, or "N/A" and note "Available to all authenticated users". |

---

## enterprise/pages/management/product-prices.mdx

| Location | Field / Column | Table | Action |
|----------|----------------|-------|--------|
| Field reference | **Cost** | Grid | Describe what the Cost column shows and how it's used (e.g. cost price per product/outlet for margin or reporting). |

---

## enterprise/pages/management/sessions.mdx

| Location | Field / Column | Table | Action |
|----------|----------------|-------|--------|
| Session fields reference | **External reference** | Details | Describe purpose (e.g. integration ID, external system reference). |
| Session fields reference | **Availability** | Self Checkout Availability | Describe what this controls (e.g. whether session is available for self-checkout/ordering). |
| Session fields reference | **First order time**, **Last order time** | Self Checkout Availability | Describe time window for first/last order in ordering. |
| Session fields reference | **Slot interval**, **Delay minutes**, **Timeslot maximum order count** | Self Checkout Availability | Describe how timeslots and limits work for ordering. |

---

## enterprise/pages/management/tenders.mdx

| Location | Field / Column | Table | Action |
|----------|----------------|-------|--------|
| Tender fields reference | **Reference** | Details | Describe (e.g. internal code, SKU, or reference for reporting). |
| Tender fields reference | **Name (alt)** | Details | Describe (e.g. alternate name for receipts or display). |
| Tender fields reference | **External reference** | Details | Describe (e.g. integration or external system reference). |
| Tender fields reference | **Minimum value**, **Maximum value** | Details | Describe min/max payment or transaction limits. |
| Tender fields reference | **Cash drawer** | Options | Describe when the cash drawer opens for this tender. |
| Tender fields reference | **Session close declare** | Options | Describe whether this tender is included in session close declaration. |
| Tender fields reference | **Session close include variance** | Options | Describe whether variance is included in session close. |
| Tender fields reference | **Exclude from tender total** | Options | Describe effect on tender totals (e.g. not included in report totals). |
| Tender fields reference | **Override print** | Options | Describe receipt/print override behaviour. |
| Tender fields reference | **Email receipt** | Options | Describe when/how email receipt is sent (note: not shown for Portugal). |
| Tender fields reference | **Report taxable** | Options | Describe whether this tender is included in taxable reporting. |
| Tender fields reference | **Cost centre** | Options | Describe link to cost centre (e.g. for allocation or reporting). |

---

## enterprise/pages/management/products.mdx

### Details tab

| Field | Action |
|-------|--------|
| **Reporting Name** | Describe use in reports (e.g. alternate name for reports). |
| **Long Name** | Describe (e.g. full product name for display or receipts). |
| **Description** | Describe (e.g. internal or customer-facing description). |
| **Adjustment %** | Describe (e.g. price or quantity adjustment percentage). |
| **Report Quantity Multiplier** | Describe how quantity is multiplied for reporting. |
| **Cook time minutes** | Describe (e.g. default cook time for kitchen display). |
| **External Reference 1**, **External Reference 2** | Describe (e.g. integration IDs, external system codes). |
| **Popup List Group** (Kiosk Menu Group) | Describe (e.g. which kiosk menu group is used for popup list). |

### Options tab

| Field | Action |
|-------|--------|
| **Weighed** | Describe (e.g. product is sold by weight). |
| **Tare Weight** | Describe (e.g. container weight deducted when weighing). |
| **Kitchen Print** | Describe (e.g. whether order line prints to kitchen). |
| **Open Price** | Describe (e.g. operator can enter custom price). |
| **Open Price Percentage** | Describe (e.g. percentage used when price is open). |
| **Kiosk Meal Deal** | Describe (e.g. product is part of a meal deal on kiosk). |
| **Use as Cover** (Cover Indicator) | Describe (e.g. used as cover charge). |
| **Preparator** | Describe (e.g. prep station or preparator assignment). |
| **Ordering Hide Price** | Describe (e.g. hide price in ordering/self-service). |
| **Send to Order Screen** | Describe (e.g. send to order display or KDS). |
| **Top Up** (Account Top Up) | Describe (e.g. used for account/member top-up). |
| **Deposit Return Scheme** (Use as Deposit) | Describe (e.g. product is used as deposit in return scheme). |
| **Credit** | Describe (not shown for Portugal). |
| **Allow Negative Order** | Describe (not shown for Portugal). |
| **Kitchen Screen** (External Kitchen Screen) | Describe (e.g. which kitchen screen receives this product). |
| **Kitchen Department** | Describe (e.g. department for kitchen routing or display). |

---

## enterprise/pages/admin/users.mdx

| Location | Field / Column | Table | Action |
|----------|----------------|-------|--------|
| User fields reference | **Phone number** | User | Describe (e.g. user's phone number for contact or 2FA). |

---

## Summary count

- **user-profile.mdx**: 1 placeholder
- **product-prices.mdx**: 1 placeholder
- **sessions.mdx**: 4 placeholders (5 field names)
- **tenders.mdx**: 12 placeholders
- **products.mdx**: 24 placeholders
- **admin/users.mdx**: 1 placeholder

**Total: 43 placeholders** across 6 files.

Update each "—" in the MDX files with the correct description, then you can remove or archive this list.
