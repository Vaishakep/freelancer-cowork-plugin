---
name: chase-payment
description: Draft an overdue invoice follow-up email at the right escalation level
argument-hint: "[days overdue, invoice # and amount]"
allowed-tools:
  - Read
  - Write
  - Edit
---

# /freelancer:chase-payment

Draft a payment follow-up email calibrated to how overdue the invoice is.

## Instructions

1. Ask: How many days overdue is the invoice?
2. Ask: What's the invoice number and amount?
3. Ask: What's the relationship like with this client? (new, established, difficult). Also ask whether they have a contract/SOW with payment terms, whether there's ongoing work with this client, and if they've sent any previous reminders.
4. Follow the **invoice-followup** skill's escalation ladder to select the appropriate level and generate the email.
5. Generate the email ready to send.
6. Offer to draft the next escalation level as a backup, and offer to draft an email pausing current work until payment is resolved (if applicable).
