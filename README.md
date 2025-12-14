# InfoSec Navigator
**A lightweight Information Security Program Operating System**

## What This Is

**InfoSec Navigator** is a **single-file, browser-based application** designed to help security teams **understand, operate, and mature an information security program** — regardless of where they are today.

It works equally well for:
- Teams just getting started
- Teams rebuilding or maturing an existing program
- Teams with many tools but unclear value
- Teams that need to show progress, not just activity

Instead of focusing on alerts, tickets, or compliance checklists, InfoSec Navigator focuses on:

> **Security capabilities, how tools support them, and how maturity improves over time.**

---

## Who This Is For

- Security teams at **any maturity level**
- Individual contributors, team leads, managers, and CISOs
- Organizations with:
  - Partial or inconsistent ServiceNow access
  - Too many tools and not enough clarity
  - A need to prioritize, justify, and explain security work
- Teams that want a **program view**, not just operational noise

This tool is intentionally **role-agnostic**:
- Analysts can see how their work contributes to the program
- Engineers can see where tooling falls short
- Leaders can see progress and gaps
- Everyone shares the same mental model

---

## What Problem It Solves

Many security teams struggle with:
- Not knowing what to work on next
- Owning tools without understanding their effectiveness
- Measuring progress beyond “tickets closed”
- Explaining security posture to leadership in plain language
- Growing maturity without unnecessary complexity

InfoSec Navigator helps teams move from:

**Reactive execution → Intentional program growth**

---

## Core Concepts

### 1. Capabilities Define the Program

Security is modeled as **capabilities** (Detection, Incident Response, Governance, Cloud, OT, AI, etc.), not vendors or products.

Each capability includes:
- Current maturity (0–5)
- Target maturity
- Owner
- Supporting tasks and projects

This creates a shared understanding of what security actually consists of.

---

### 2. Tools Enable Capabilities

Tools are not “mature” or “immature” on their own.

Each **Tool × Capability** pairing is tracked independently:
- Current maturity (0–5)
- Target maturity
- Assessment notes
- Evidence and uplift plans

This allows teams to honestly answer:
- “We own this tool — but are we using this part of it well?”
- “Where should effort go before buying something new?”

---

### 3. Maturity Is Measured, Not Assumed

Maturity reflects **real usage and behavior**, not license ownership.

It is informed by:
- Tool capability usage
- Supporting processes
- Completed work (tasks and projects)

The heatmap shows **actual maturity**, not theoretical coverage.

---

### 4. Work Is Tied to Outcomes

All work is explicitly connected:
- Tasks → Projects
- Projects → Capabilities
- Capabilities → Domains
- Domains → Program Overview

This ensures effort contributes to **measurable security improvement**, not busy work.

---

## Key Features

### Program Overview (Operating Cockpit)
- Domain-level progress
- Capability maturity vs targets
- Tool coverage and usage
- “Now Mode” — what to focus on next
- Weekly operational summary (copy/paste ready)

### Guided Plan
- Opinionated Foundation → Core → Optimize guidance
- Useful for new teams **and** for resetting direction
- Can be ignored or adapted for mature environments

### Capability Explorer
- Drill into individual capabilities
- View maturity, gaps, tools, tasks, and projects
- Edit assessments and track improvement over time

### Tools & Platforms
- Inventory tools
- Map capabilities per tool
- Track maturity per capability
- Add uplift plans, notes, and evidence

### Tool Capability Heatmap
- Capabilities × Tools matrix
- Color-coded maturity (0–5)
- Clickable cells for drill-down and action
- Highlights gaps, overlaps, and under-used tools

### Projects & Roadmap
- Group work into meaningful initiatives
- Track progress, blockers, and maturity impact
- Keep day-to-day work aligned with program goals

### Import / Export
- Export full program state as JSON
- Import or merge state
- Enables sharing and handoffs without shared infrastructure

---

## What This Is *Not*

- ❌ A SIEM, SOAR, or SOC dashboard  
- ❌ A ticketing system replacement  
- ❌ A compliance-only GRC platform  
- ❌ A vendor product  

InfoSec Navigator is a **program-level visibility and planning layer** that complements existing tools.

---

## How It Works

- Single HTML file
- Runs entirely in the browser
- Uses `localStorage` for persistence
- No backend
- No build step
- No dependencies

Open the file → start using it.

---

## How to Use It

1. Open the HTML file in a modern browser
2. Define or adjust your security capabilities
3. Add your tools and map capabilities
4. Score maturity honestly
5. Use the Guided Plan or your own roadmap to generate work
6. Track progress through Projects and the Roadmap
7. Review the Program Overview regularly

---

## Design Philosophy

- Useful at **any maturity level**
- Honest assessment over checkbox compliance
- Capabilities before tools
- Outcomes before activity
- Lightweight, adaptable, and transparent

---

## License / Usage

This project is provided as-is for internal use, experimentation, and adaptation.  
Modify it freely to fit your organization and security model.
