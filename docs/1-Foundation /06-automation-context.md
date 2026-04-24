# English Business Practice — Kosbah's Full Work Context

> This file is for an LLM to use as a reference when running English speaking practice with Kosbah.
> All information is real. All scenarios are based on his actual business. Practice should use this data,
> not generic examples. Ask Kosbah to explain, describe, pitch, handle objections, and tell stories —
> all using HIS real work, HIS real clients, and HIS real process.

---

## Who Kosbah Is

Kosbah is a freelance AI automation specialist. He builds automation systems for small and medium businesses (1–20 people) that are losing time, revenue, or leads because their processes are still manual.

He works on Upwork. He has 7 years of backend development experience. He is now focused entirely on automation freelancing using n8n, AI (OpenAI), and connecting business tools like Gmail, HubSpot, Slack, Calendly, and social media platforms.

His goal is to reach $1,000–$3,000 per month within 90 days.

He is Egyptian, and Arabic is his first language. English is what he uses in his work.

---

## What He Sells — Three Productized Services

### Service 1: "Every Lead Followed Up Automatically" (UC1 — Lead Response)

**Price:** $400–$600 fixed. Delivered in 7 days.

**The pain this solves:**
A business gets leads from a contact form. Nobody follows up fast enough. The competitor calls first. The lead goes cold. Deals are lost not because the product is bad — but because the response was slow. Sometimes the lead form submission just sits there and nobody sees it for hours. The follow-up email that goes out is generic and manual. There's no record in the CRM. The sales team finds out about new leads by accident.

**What the system does:**
1. A lead fills out a web form (Typeform, Tally, Gravity Forms, or any form with a webhook).
2. The moment they click Submit, n8n receives the data instantly — no delay.
3. AI (OpenAI) reads the lead's message and classifies them: **Hot**, **Warm**, or **Cold**.
4. A personalized follow-up email is sent from the client's Gmail address — automatically — within 60 seconds of the form submission.
5. The lead's contact details are logged to the CRM (HubSpot, Salesforce, GoHighLevel, or Google Sheets).
6. The sales team gets a Slack notification: lead name, contact info, priority level, and confirmation that the email was already sent.

**Additional parts of the system:**
- **Calendly Booking Sync:** When a lead books a meeting through Calendly, their data automatically syncs to the CRM, Google Sheets, and Notion. No manual data entry.
- **Meeting Outcome Tracking (Fathom):** If the client records sales calls using Fathom, the system receives the recording webhook, AI classifies the meeting outcome as Won / Lost / Follow-up / No Show, and updates the CRM deal stage automatically.
- **Daily Health Check:** Every morning at 8 AM, the system runs a test to verify all credentials are working. If something is broken (OAuth token expired, API key invalid), the client gets a Slack alert before the day starts — not after a lead is lost.

**Measurable result:** Lead response time drops from hours (or days) to under 60 seconds. Zero manual steps. Zero missed leads.

---

### Service 2: "Never Miss an Important Email Again" (UC2 — Email Triage)

**Price:** $300–$500 fixed. Delivered in 4 days.

**The pain this solves:**
A business owner or operations manager receives 80–120 emails per day. Half of them are newsletters and noise. But buried inside are time-sensitive messages: a client asking about a candidate, a contractor accepting an offer, a supplier confirming a delivery. These important emails get buried. The person misses them. They apologize to clients. They lose deals. They spend 2 hours a day reading emails that don't matter, and still miss the ones that do.

**What the system does:**
1. Gmail is monitored continuously for new incoming emails.
2. AI reads each email and classifies it by priority: **High**, **Normal**, or **Low**.
3. Every morning at 9 AM, the client receives a daily digest in Slack — only the High priority emails, summarized in plain language, with a reply draft already written and ready to send.
4. The client reviews the digest, sends the reply with one click. They never open their inbox unless they choose to.

**What makes this different from simple email filters:**
- AI understands context, not just keywords. It classifies based on what the email actually means.
- Reply drafts are pre-written — the client doesn't start from a blank page.
- The system handles Gmail API failures gracefully — if something breaks, the client gets a Slack alert instead of silent failure.

**Measurable result:** Client goes from checking their inbox 30+ times a day to 3 times. No important email missed. Reply drafts ready to send every morning.

---

### Service 3: "Content Published Without You Touching It" (UC3 — Content Pipeline)

**Price:** $300–$400 fixed. Delivered in 5 days.

**The pain this solves:**
A business needs to post on social media every day — Facebook, Instagram, LinkedIn. Content gets written (or planned) but never actually goes out consistently. Someone has to log into each platform, copy the caption, adjust it per platform, find the image, post it. It takes 20–30 minutes per post, per platform. It gets skipped. The brand goes quiet. Opportunities are missed. For MENA-market businesses, there's an added challenge: they need content in Arabic and English, which doubles the manual work.

**What the system does:**
1. The client writes content ideas in a Google Sheets spreadsheet — one row per post, with the caption, image URL, target platforms, and language flag.
2. On a scheduled trigger, the system reads new rows from the sheet.
3. AI rewrites and localizes the content — English version, Arabic version, or both.
4. The system publishes the content automatically to Facebook, Instagram, and LinkedIn.
5. A log entry is created in Notion confirming what was published, when, and where.
6. The client gets a Slack notification for each published post.

**Specific capability:** Arabic language support is built in. Kosbah's system handles Arabic content natively — this is a differentiator, especially for clients in the MENA market.

**Measurable result:** 100% of planned content gets published automatically. Zero manual posting. Consistent brand presence across all platforms.

---

## How the Whole Business Process Works — Step by Step

### Step 1: Finding the Client (Upwork Search)

Kosbah searches Upwork daily for job posts that match one of his three services. He filters for:
- Category: AI & Machine Learning / Automation
- Budget: $200+ fixed or $25+/hr
- Posted in the last 24–72 hours
- Client with at least 1 completed job and verified payment

Key pain words he looks for in job posts: manual, slow, missing, follow-up, inconsistent, buried, overwhelmed.

He applies to one strong match instead of ten weak ones.

---

### Step 2: The Proposal

The proposal is 100–150 words. Structure:
1. **Line 1 — Hook:** Name the client's exact pain in their words. Example: "Your leads are coming in and nobody's following up — I can fix that in 7 days."
2. **Line 2 — Loom Link:** Drop the 2-minute video right away, before anything else.
3. **Lines 3–4 — What I'd Build:** Describe the system specifically for their tools (their CRM, their form, their Slack channel).
4. **Line 5 — CTA:** One clear next step. "Watch the video and let me know if this is what you're looking for."

No generic pitches. No "I am an expert in..." openers. Pain first, solution second.

---

### Step 3: The Loom Demo (2-minute video)

Before sending any proposal, Kosbah records a 2-minute Loom video showing the actual system running — real data flowing through a real n8n workflow.

The video structure:
- **0–15 sec:** Name the pain. "Right now, when a lead fills your form, what happens? They submit. Then they wait. Five minutes pass. They go to a competitor."
- **0:15–1:30:** Live workflow walkthrough in n8n. Show every node firing: webhook receives data → AI classifies → email sends → CRM logs → Slack notifies. The speed IS the demo — don't pause.
- **1:30–1:50:** Outcome. "Every lead gets a response within 60 seconds. Your CRM stays current. Your team sees it in Slack."
- **1:50–2:00:** CTA. "If you want to see this mapped to your exact tools, let's do a 30-minute audit call."

This Loom is the main reason clients reply. They see it working before they hire.

---

### Step 4: The Audit Call (30 minutes)

This is a diagnosis call, not a sales call.

**Opening:** "Before I show you anything, I want to make sure I fully understand what you're dealing with. Can you walk me through what's happening right now?"

**Diagnosis questions Kosbah asks:**
- "How are you handling this today — what does the manual process look like?"
- "Where does it break down most?"
- "What does it cost you when this doesn't work — leads missed, time lost, revenue?"
- "Have you tried to fix this before? What happened?"
- "What does success look like for you 30 days from now?"

**System walkthrough:** After listening, Kosbah shares his Miro board — a visual map of exactly what he'd build. He customizes it live: updates the client's CRM name, their form tool, their Slack channel. The client sees their own problem drawn out with the solution overlaid.

**Close:** "Does this solve the problem you described?" — If yes, confirm deliverables, timeline, and budget. No pushing, no discounting.

---

### Step 5: Onboarding (Credentials & Setup)

After the client says yes:
1. Upwork contract sent, first milestone funded.
2. During a screen-share, Kosbah opens a secure Tally.so form and collects credentials while the client reads them out — API keys, OAuth tokens, CRM access.
3. **Credentials are NEVER sent via chat or email.** Only via HTTPS form on a screen-share.
4. All credentials are entered into n8n's Credential Manager immediately during the call.
5. Notion confirms receipt. Then the Notion page is deleted — credentials stored only in n8n.

---

### Step 6: Build (Days 2–6)

- Built in Kosbah's dev n8n.cloud instance first, then imported to the client's instance.
- Every workflow starts with a **Config node** — all client-specific values live here (Slack channel name, email template, CRM field names, AI prompt). Zero hardcoded values anywhere else.
- Every critical node (AI call, Gmail API, HubSpot write) has an **error branch**: if it fails, the client gets a Slack alert immediately — not a silent failure.
- All testing uses dummy data — no real client data touches the system until after delivery.

---

### Step 7: Delivery (Day 7)

Before sending anything to the client, Kosbah runs a full end-to-end test:
- Inject dummy lead → verify all nodes fire → check Slack notification format → check CRM entry → test error branches by intentionally breaking a credential.

Delivery message: "Milestone [X] is ready. Here's a quick walkthrough so you can see exactly how it works: [Loom link]. Everything has been tested end to end."

After client approves:
1. Full admin access transferred to client — they own the n8n instance, all credentials, all API keys.
2. Kosbah's own access removed from every connected account within 24 hours.
3. Handoff document delivered — lists every connected account, how to test the system, how to fix common issues, re-authentication instructions per tool, and ongoing costs.

---

### Step 8: Testimonial

Immediately after the final milestone is approved, Kosbah sends:
> "Really glad we got this across the finish line — the system is live and running exactly as we planned. If you're happy with how everything turned out, I'd really appreciate a review on Upwork."

One follow-up after 48 hours if no reply. Then move on.

---

## The Key Differentiators (What Makes This Different from Other Freelancers)

1. **Demo before hire.** The client sees a 2-minute Loom of the real system running before they pay anything. They know exactly what they're buying.

2. **Miro system map on the audit call.** The client approves the blueprint before a single workflow is built. No surprises. No scope creep.

3. **Fixed scope, fixed price, fixed timeline.** Not hourly. Not open-ended. "7 days. $500. Done." The client knows exactly what they're getting and when.

4. **Health check included in every delivery.** A monitoring workflow runs every morning. If something breaks, the client knows before a lead is lost or a post is missed. This is standard in enterprise software but rare in SMB freelancing.

5. **Zero-dependency handoff.** After delivery, the client owns everything — their n8n instance, all API keys, all credentials. Kosbah removes his own access within 24 hours. No lock-in. No ongoing dependency.

---

## Client Personas (Real Examples Used in the Business)

### Marcus — Solar Panel Company Owner
- 38 years old. Runs a 6-person solar installation company.
- Gets 15–20 leads a month from a contact form.
- Between job sites and client calls, he responds the next morning — sometimes two days later.
- Lost a $4,000 job to a competitor who called first.
- Found Kosbah on Upwork at 11pm after that loss.
- Bought UC1. Result: leads get a response in 38 seconds. His sales rep now dials within the hour instead of waiting for Marcus to forward leads manually.

### Diana — Operations Manager at a Recruitment Agency
- 44 years old. Manages Gmail inbox with 80–120 emails per day.
- Missed two time-sensitive client replies this quarter and had to apologize.
- Was burned by automation before — a Zapier setup a freelancer built broke for three weeks and nobody fixed it.
- Her first question on the audit call: "What happens when it breaks?"
- Kosbah walked her through the error handling on the Miro board. She relaxed.
- Bought UC2. Result: checks her inbox 3 times a day instead of 30. Reply drafts ready every morning.

### Sofia — Sales Rep (Not the Buyer — the End User)
- 27 years old. Works at Marcus's solar company.
- Doesn't know what n8n is and doesn't need to.
- Starting last Tuesday, a Slack message shows up every time a new lead comes in — name, contact, what they want, and confirmation the follow-up email already went out.
- She used to wait for Marcus to forward leads manually. That took hours.
- Now she dials within the hour. Her close rate went from 1 in 4 to 2 in 4.

---

## Tools and Vocabulary Kosbah Uses Every Day

**n8n** — The automation platform. It's like Zapier or Make, but more powerful and used for complex workflows. Kosbah uses n8n.cloud (the hosted version). Each client gets their own n8n.cloud instance.

**Webhook** — A trigger. When a lead fills a form, the form sends a signal (a webhook) to n8n instantly. No polling, no delay — it fires the moment something happens.

**Config node** — The first step in every workflow Kosbah builds. All the client-specific settings live here: Slack channel name, email template, CRM field names. This means zero hardcoded values anywhere else in the workflow.

**OAuth token** — The key that connects n8n to Gmail, HubSpot, social media accounts, etc. These expire over time (Gmail OAuth, for example, can expire). When they expire, workflows break. That's why the health check workflow exists — it tests the token every morning.

**HubSpot** — A CRM (Customer Relationship Management) system. Kosbah's default for UC1. Stores leads, contacts, deal stages.

**Fathom** — A call recording tool. Automatically records and transcribes sales calls. Sends a webhook to n8n after each recording. Kosbah's system uses this to classify meeting outcomes.

**Loom** — A screen recording tool. Kosbah uses it to send video messages: pre-sale demos, delivery walkthroughs, client updates.

**Miro** — An online whiteboard. Kosbah uses it to draw system maps. He shows the Miro board on the audit call so the client can see the full flow before anything is built.

**Slack** — The notification hub for every workflow. All system alerts, lead notifications, daily digests, and error warnings go to Slack.

**Tally.so** — The secure form used to collect client credentials during onboarding. Never email, never chat.

**Hot / Warm / Cold** — How leads are classified by AI. Hot = needs attention today. Warm = follow-up sequence. Cold = low priority.

**High / Normal / Low** — How emails are classified by AI in UC2.

**Won / Lost / Follow-up / No Show** — Meeting outcome classifications in UC1's Fathom integration.

**End-to-end test** — Before every delivery, Kosbah runs the full system with dummy data: injects a fake lead, traces every node, checks the Slack notification format, checks the CRM entry. Nothing goes to a client without passing this test.

**Error branch** — A parallel path in the workflow. Every critical node has one. If the Gmail API call fails, instead of the workflow crashing silently, it routes to the error branch, which sends a Slack alert with the exact error message.

**Handoff document** — A client-facing guide delivered at the end of every project. Covers: what was built, where to find it, how to test it, what to do if something breaks, re-auth instructions for each connected tool, and ongoing monthly costs.

**DIY Maintenance Pack ($79)** — An optional upsell. A video library teaching the client how to re-authenticate tools, reconnect tokens, and fix common issues without calling Kosbah.

**Done-For-You Fix ($129/session)** — Another upsell. Kosbah diagnoses the issue via Loom, fixes it in the client's n8n instance, and sends a confirmation video — all within 24 hours.

---

## Pricing

| Service | Max Price | First-Client Floor | Delivery |
|---|---|---|---|
| UC1 — Lead Response | $600 | $400 | 7 days |
| UC2 — Email Triage | $500 | $300 | 4 days |
| UC3 — Content Publishing | $400 | $300 | 5 days |
| DIY Maintenance Pack | $79 | — | Video library |
| Done-For-You Fix | $129/session | — | 24h async |

**Minimum for any engagement: $200.**

**Strategy:** List all services at maximum price. Use the floor price only to land a first-time client (to get the review). All repeat clients pay the full maximum rate from the second engagement onward.

---

## The Full Project Lifecycle (One Complete Cycle)

```
Find Client on Upwork
  → Write Proposal (pain-first, 100-150 words, Loom link)
  → Record and Send 2-min Loom Demo
  → Client Replies → Book Audit Call
  → Audit Call: Diagnose → Show Miro → Close
  → Send Upwork Contract → Client Funds Milestone
  → Onboarding: Collect Credentials via Tally (screen-share)
  → Build in Dev Instance (days 2-5)
  → End-to-End Test with Dummy Data (day 6)
  → Deliver (Loom walkthrough + Upwork message) (day 7)
  → Client Approves → Transfer Admin Access
  → Remove Kosbah's Access Within 24 Hours
  → Send Handoff Document
  → Ask for Testimonial → Get 5-Star Review
  → Start Again
```

---

## Practice Scenarios for the LLM to Use

These are real situations Kosbah will face. Use them for role-play and speaking practice.

**Discovery / Intake:**
- "Tell me about your freelance work."
- "What do you actually build?"
- "What problem do you solve?"
- "Who are your clients?"
- "Why would a client choose you over someone cheaper?"

**On a Client Call (Audit Call):**
- Client: "I have 20 leads a month and I respond manually. It works fine."
- Client: "What happens when it breaks? The last freelancer's automation broke and nobody fixed it for weeks."
- Client: "I don't use HubSpot. I use a spreadsheet."
- Client: "Can you do this for $200?"
- Client: "How long will this actually take?"

**Explaining the System:**
- "Walk me through what happens after a lead fills my form."
- "What is a webhook and why does it matter?"
- "Why does the follow-up email go out in 60 seconds and not instantly?"
- "What does the health check workflow do exactly?"
- "What happens if Gmail breaks at 2am and I miss a lead?"

**Handling Objections:**
- "I already use Zapier, why do I need n8n?"
- "This feels expensive for something I could build myself."
- "What if I don't use Slack?"
- "What happens after you leave — am I stuck with a system I don't understand?"

**Pitching on Upwork:**
- Describe your service in 3 sentences to a prospect who doesn't know you.
- Explain the difference between your three services.
- Explain why you do a Loom demo before the client hires you.
- Explain what makes your delivery process trustworthy.

**Post-Delivery:**
- "The system worked for a week and now Slack stopped notifying me."
- "I need to add my colleague to the Slack notifications."
- "The CRM isn't updating anymore."
- "I want to add Instagram to the content pipeline."

---

## Common Phrases Kosbah Should Practice Saying Naturally

- "The moment a lead fills your form, the system fires automatically — no manual step."
- "I classify every lead as Hot, Warm, or Cold — so your team knows who to call first."
- "The follow-up email goes out within 60 seconds. The competitor hasn't even seen the lead yet."
- "Everything is configured in one place — the Config node. If you want to change the email template or the Slack channel, you change it there and it updates everywhere."
- "I remove my own access within 24 hours of delivery. You own everything."
- "Before I send anything, I run a full end-to-end test with dummy data. Nothing goes to you without passing that test."
- "This isn't a template you rent. This is a custom system built for your tools and your workflow."
- "Fixed price, fixed timeline, no surprises. $500. 7 days. Done."
- "The health check runs every morning at 8 AM. If something breaks overnight, you know before the day starts."
- "The Miro board shows you exactly what gets built before I build anything. You approve it first."
