---
name: project-retro
description: Run a retrospective on a completed freelance project to extract lessons and create a case study
argument-hint: "[project name]"
allowed-tools:
  - Read
  - Write
  - Edit
  - Bash
---

# /freelancer:project-retro

Run a full retrospective on a completed project.

## Instructions

1. Ask the user about the project: client, deliverables, timeline, what they charged, hours spent.
2. Ask what went well and what was challenging. Also ask whether the deliverables grew beyond the original scope (not just hours — did they deliver more assets or features than planned?).
3. Follow the **project-retro** skill to generate all three outputs:
   - Lessons document (with scope creep %, estimation accuracy, effective hourly rate)
   - Case study draft (result-focused headline, quantified outcomes)
   - Pricing intelligence note (verdict: profitable / break-even / underpriced)
4. Offer to format the case study for LinkedIn or their portfolio site. If the user wants a file export, generate one using available tools — or save as a `.txt` file as a fallback.
5. Offer to draft a testimonial request email to the client while the project is fresh.
