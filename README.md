# AI Automation Build Log

Public build log for my AI automation journey — no-code/low-code automation with n8n, AI APIs, and real business workflows. Updated as each project ships.

**Stack:** n8n · OpenAI/Claude APIs · Slack/Gmail · Google Sheets/Notion

---

## Progress

### Phase 0 — Foundations
- [x] **Project 1: Hello Automation** — RSS feed → formatted message → email/Slack delivery
  - Trigger → transform (Edit Fields) → deliver (SMTP/Slack)
  - Notable: worked through Gmail OAuth vs SMTP app-password tradeoffs to get delivery working
  - 
  - <a href="./workflows/Hello%20Automation.json">  <img width="1366" height="768" alt="Hello Automation Workflow" src="https://github.com/user-attachments/assets/e1735a13-ecf3-463e-b5c7-47018391d0dd" /> </a>
 · [Workflow export](./workflows/Hello%20Automation.json)
- [ ] **Project 2: Form-to-Sheet Pipeline** — form submission → Google Sheets row → confirmation email

### Phase 1 — Adding AI
- [ ] **Project 3: AI Email Triage** — incoming emails classified by LLM, routed by category
- [ ] **Project 4: Content Summarizer Bot** — URL/PDF in → AI summary → saved to Notion/Sheets
- [ ] **Project 5: AI Social Content Pipeline** — blog post → AI-generated social captions → review sheet

### Phase 2 — Agents & Business Logic
- [ ] **Project 6: AI Customer Support Agent** — RAG chatbot over a knowledge base, escalates to human when unsure
- [ ] **Project 7: Document Processing Bot** — invoice/receipt → AI extraction → validation → CRM/sheet
- [ ] **Project 8: Lead Qualification Funnel** — new lead → AI scoring → CRM record → sales notification

### Phase 3 — Portfolio-Grade Systems
- [ ] **Project 9: End-to-End Ops Automation** — full business process automation (recruiting / e-commerce / real estate)
- [ ] **Project 10: Multi-Tool Orchestration** — 4+ tools tied into one cohesive automation

---

## Repo structure
```
/project-01-hello-automation
  README.md          -- what it does, tools used, what I learned
  workflow.json       -- exported n8n workflow
  screenshot.png       -- canvas + result proof
/project-02-form-to-sheet
  ...
```

Each project folder gets its own short README: **problem → workflow → outcome**. That's the format recruiters and clients actually scan for.

## About
Following a self-directed, project-based curriculum toward becoming job-ready in AI automation. Open to freelance/junior automation roles.

**Connect:** [LinkedIn](#) · [Portfolio](#)
