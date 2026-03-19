---
name: invoice-followup
description: Handle overdue invoice follow-ups and payment chasing for freelancers. Trigger with "they haven't paid", "overdue invoice", "chase payment", "late payment", "payment reminder", "how do I ask for payment", "my client is ghosting me on payment", or any payment-related client issue.
---

# Invoice Follow-Up System

Generate escalating payment reminders that maintain client relationships while protecting the freelancer's income.

## Escalation Ladder

### Level 1: Friendly Nudge (1-3 days overdue)
**Tone**: Casual, assumes an oversight
**Approach**:
- Keep it to 3-4 sentences maximum
- Reference the invoice number and amount
- Assume positive intent: "Just floating this to the top of your inbox"
- Include payment link or instructions
- No pressure, no formality

**Template direction**:
Quick note — Invoice #[X] for $[amount] was due on [date]. Totally understand if it slipped through. [Payment link/instructions]. Let me know if you need anything resent.

### Level 2: Professional Reminder (7-10 days overdue)
**Tone**: Warm but direct
**Approach**:
- Reference the project by name, reminding them of the value delivered
- State the amount and original due date clearly
- Ask if there's an issue with the invoice or payment process
- Offer to hop on a quick call if something's wrong
- Mention your payment terms if you have them

### Level 3: Firm Follow-Up (14-21 days overdue)
**Tone**: Professional, direct, boundary-setting
**Approach**:
- Lead with the facts: invoice number, amount, days overdue
- State that payment is now X days past the agreed terms
- Reference any late payment terms from your SOW/contract
- Ask for a specific payment date commitment
- Mention that you'll need to pause any ongoing/future work until resolved
- Still professional — never hostile

### Level 4: Final Notice (30+ days overdue)
**Tone**: Formal, serious
**Approach**:
- This is a formal payment demand, not a friendly email
- State all outstanding amounts with invoice numbers
- Reference contract terms and late fees if applicable
- Give a specific deadline (7-10 days)
- State next steps if payment isn't received (collections, small claims, etc.)
- Offer one last opportunity to discuss a payment plan
- Send from a professional email, not Slack/chat

## Context Questions

Ask the user:
1. How overdue is the invoice? (determines escalation level)
2. What's the relationship like with this client? (adjusts tone)
3. Do they have a contract/SOW with payment terms?
4. Is there ongoing work with this client? (leverage point)
5. Have they sent any previous reminders?
6. Is the client responsive on other topics but avoiding payment?

## Important Rules

- Never be aggressive, threatening, or passive-aggressive
- Always include the specific invoice number and amount
- Always make it easy to pay — include the payment link/method every time
- If the user is emotional, help them be professional — draft what THEY should send, not what they feel like sending
- Mention that pausing work is a business decision, not a punishment
- For amounts over $5,000 overdue 30+ days, suggest consulting a lawyer
- For international clients, mention that payment terms may vary by jurisdiction

## After the Draft

Offer:
- "Want me to set a reminder for a follow-up if they don't respond by [date]?"
- "Should I draft the next escalation level in case you need it?"
- "Want me to draft an email pausing current work until payment is resolved?"
