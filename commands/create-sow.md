---
name: create-sow
description: Generate a Scope of Work document for a freelance project
argument-hint: "[project name and client]"
allowed-tools:
  - Read
  - Write
  - Edit
  - Bash
---

# /freelancer:create-sow

Generate a professional Scope of Work document.

## Instructions

1. Ask the user for the project name, client name, and a brief description of the work.
2. Ask about deliverables, timeline, pricing, and revision rounds.
3. Ask what is explicitly **out of scope** — this prevents the majority of freelancer-client disputes. Also ask about communication preferences (channels, response times, meeting cadence) and who approves deliverables on the client side.
4. Follow the **scope-of-work** skill's 9-section document structure to generate the complete SOW.
5. Offer to draft the email to send the SOW to the client. If the user wants a Word or PDF export, generate one using available tools — or save as a `.txt` file as a fallback.
