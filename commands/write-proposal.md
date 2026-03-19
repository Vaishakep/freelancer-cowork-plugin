---
name: write-proposal
description: Generate a freelance proposal from a job posting or client brief
argument-hint: "[paste job posting or brief]"
allowed-tools:
  - Read
  - Write
  - Edit
  - Bash
---

# /freelancer:write-proposal

Write a client-winning freelance proposal.

## Instructions

1. Ask the user to paste the job posting, client brief, or intake call notes.
2. Ask what their relevant experience is for this specific project.
3. Ask for their preferred pricing (fixed, hourly, or range) and desired tone (formal, conversational, technical).
4. Follow the **proposal-writer** skill's 8-part structure to generate the proposal.
5. Deliver the proposal as clean, copy-paste-ready text.
6. Offer to adjust tone, pricing, or scope. If the user wants a Word document, generate one using available tools — or save as a `.txt` file as a fallback.
