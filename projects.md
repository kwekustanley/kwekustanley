# GitHub Projects Roadmap
**Goal:** Build real, public projects that brand Stanley Yeboah as a Fullstack Developer · AI Systems · Automations

---

## Project 1 — `paystack-nextjs-starter`
**Status:** Not started

**What it is:**
A production-ready Next.js boilerplate with Paystack fully integrated. Fills a genuine gap — most Paystack documentation is poor and there's no clean open-source starter for African developers.

**Features to build:**
- One-time payments (checkout flow)
- Subscription/recurring billing
- Webhook handling + signature verification
- Payment verification endpoint
- Paystack popup and redirect modes
- TypeScript throughout
- Environment variable setup guide

**Stack:** Next.js 14 · TypeScript · Tailwind CSS · Paystack API · Prisma · PostgreSQL

**Why it matters:** Every Ghanaian/African developer building a product needs this. Gets organic GitHub stars and shows real fullstack + payments depth.

**Live demo target:** Vercel

---

## Project 2 — `whatsapp-ai-agent`
**Status:** Not started (concept already being built for mbvogue — generalize it)

**What it is:**
An open-source WhatsApp Business API + AI template. Businesses connect it to their product catalog and it answers questions, handles FAQs, and escalates to a human agent.

**Features to build:**
- WhatsApp Business Cloud API integration
- AI response engine (Claude API)
- Product catalog Q&A (RAG — retrieval from a JSON/DB catalog)
- Human handoff trigger (keyword or confidence threshold)
- Webhook setup + verification
- Admin dashboard to configure responses and view conversations
- Docker setup for easy self-hosting

**Stack:** Next.js · Node.js · TypeScript · Claude API · WhatsApp Business API · Prisma · PostgreSQL

**Why it matters:** Directly tied to real client work. Shows AI integration + automation + fullstack in one project. Very searchable — tons of devs look for this.

**Live demo target:** Railway + Vercel

---

## Project 3 — `ai-document-processor`
**Status:** Not started

**What it is:**
Upload any PDF or image → AI extracts structured data → download as JSON or CSV. Works for invoices, contracts, grant applications, receipts.

**Features to build:**
- File upload UI (PDF, image)
- AI extraction with configurable schema (what fields to pull)
- Preview extracted data before download
- Export as JSON or CSV
- History of processed documents (per session or with auth)

**Stack:** Next.js · TypeScript · Tailwind CSS · Claude API (claude-sonnet-4-6) · pdf-parse · Vercel

**Why it matters:** Short to build, clean demo, clearly showcases AI integration. Useful to any business owner — broad appeal.

**Live demo target:** Vercel

---

## Project 4 — `workflow-automator`
**Status:** Not started

**What it is:**
A lightweight automation tool. Connect triggers (Paystack webhook, form submission, schedule) to actions (send WhatsApp message, email, Slack notification). Think mini-n8n.

**Features to build:**
- Trigger types: Paystack webhook, HTTP webhook, cron schedule, form submit
- Action types: WhatsApp message, email (Resend), Slack webhook, HTTP request
- Visual workflow builder (drag or form-based)
- Execution logs
- Retry on failure

**Stack:** Next.js · Node.js · TypeScript · Prisma · PostgreSQL · Resend (email) · WhatsApp API · BullMQ (job queue)

**Why it matters:** Shows deep systems thinking — queuing, reliability, multi-service integration. Strong signal for senior-level positioning.

**Live demo target:** Railway + Vercel

---

## Build Order
1. `paystack-nextjs-starter` — fastest win, tied to real work, fills a real gap
2. `whatsapp-ai-agent` — reuses mbvogue chatbot work, high impact
3. `ai-document-processor` — standalone AI project, quick to complete
4. `workflow-automator` — most complex, build last

## Profile Pinned Repos (target state)
1. `paystack-nextjs-starter`
2. `whatsapp-ai-agent`
3. `ai-document-processor`
4. `workflow-automator`
5. `hackathon` (already public, has live demo)
6. `mbvogue-storefront` (when ready to make public)
