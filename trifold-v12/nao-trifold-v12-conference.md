# N.A.O. OS: Trifold v12 (tech conference edition)

For: Microsoft Frontier conference, Dec 9. Audience: builders, product, accessibility and decision-makers.
Print file: `nao-trifold-v12-conference.pdf` (2 pages, 11×8.5 landscape; page 1 = outside, page 2 = inside).

---

## 1. What changed from v10/v11, and why

| Your note | What I did |
|---|---|
| "Do no evil" → "Be Righteous" | Now "Be righteous. One next step at a time." on the cover. The old logo image had "Do no evil" baked into its tagline, so I used the logo mark only and set the wordmark as text. The "DO NO EVIL" poster is not used. |
| "40 to 8 hours" is figurative | Removed. Replaced with **"Less grinding. Less context-maxing. Fewer hallucinations."** |
| Remove "free / nothing sold" | Removed everywhere, including "A movement, not a product" and "Not a service. Nothing sold." |
| Doctor's AI scribe → durable memory → HIPAA-safe companion | New hero of the inside-right panel ("Where it's going"). |
| It's for a tech conference | Cover now says what it is in one line ("Durable memory for AI. Plain files you own. Any model you choose."). The architecture (library, orchestrator, red-team pass, patch rule) is back inside, because this audience wants it. The back cover now asks for pilots and testers. |

Also cut: the "Stupidly expensive… not sustainable" line about local models. The privacy question in section 3 makes that claim a liability.

---

## 2. The copy (edit here, then update `trifold.html`)

### Outside, page 1

**Left flap: SOUND FAMILIAR?**
Every office wants the story again. You tell it once. Then again. It wears you out.
When a thought won't finish, the task doesn't finish. That costs more than time. It costs self-esteem.
**How many ideas died because the focus broke?**
And AI adds to it: the grinding, the context wall, the confident wrong answer.

**Middle (back cover): TALK TO US**
Pilot it. Break it. Build with us. We're after people who will test memory that users own, and tell us where it fails.
We also host online peer sessions: people with disabilities talking about using AI as an assistive tool, and about the systems that feel hostile to us.
*What N.A.O. never does:* use your data against you · record anyone without their okay · lock your files in (they are plain files that open anywhere).
Scan to save our contact · Nathan NAO · nao.contributor@outlook.com

**Right (front cover)**
N.A.O. OS: Neuro-Assistance Operating System
**Tell your story once. Never start from zero.**
Durable memory for AI. Plain files you own. Any model you choose.
Built for neurodivergent minds, cognitive overload, and living with mental health distress.
**Be righteous. One next step at a time.**

### Inside, page 2

**Fat library. Thin client.**
One folder of plain files: Markdown notes and a JSON ledger of events, names and facts, linked. New facts are reconciled against old ones (dated, sourced, agreed) so memory doesn't distort. Originals are stored once.
Any device → The library → Any model (thinking, rented by the hour).
Any AI walks in, reads the library and is caught up. Honest limit: it still rereads. It just never starts from zero.
*What you get:* Less grinding. Less context-maxing. Fewer hallucinations.

**Project, start to finish**
1 You (fragments are fine) · 2 Orchestrator (assigns work, checks every return) · 3 Peer models (review the structure) · 4 Coding agent (bulk work in the real folder, timer and ledger) · 5 Red-team pass (de-identified copies, checked for consensus) · 6 Human gate (you review, with advisors: legal, accounting, friends).
**The Patch Rule:** First fix is a fix. Second is flagged. Third time: stop patching and write a fresh copy.

**Where it's going**
Your doctor already uses an AI scribe. But your intent, and how you express it, are limited by durable memory.
**Imagine it comes along, and is HIPAA-safe.**
Holding the details when memory slips. Privacy designed in from the start.
*Proof so far:* an AI sat in on a live Zoom presentation (early, rough, real) · a one-page printout got an employee into a hard meeting ready · members are completing forms and complaint letters.
**The Pact:** Interdependent, never dependent. Less AI. More truth.

---

## 3. Your question: can an AI company sell logic and reasoning and still protect privacy? Or is Lumo the answer?

**Short answer: yes, it can be done, and it's not either/or. Your own architecture is the answer.**

Ways a company can sell reasoning without taking your data:
1. **By contract:** zero data retention, no training on customer data, and for health data a HIPAA Business Associate Agreement (BAA). Several large providers offer these on enterprise or API tiers, including Microsoft through Azure. Verify the exact terms for the specific product.
2. **By architecture:** confidential computing (encrypted enclaves), so even the provider's staff can't read the data being processed.
3. **By de-identifying first:** strip names and identifiers before anything leaves the device. This is already step 5 of your project flow.

**Lumo (Proton's privacy-first assistant):** as I understand it, it is built around no logging and encrypted chat history, using open models, with Proton's privacy posture behind it. Its strength is trust. The trade-offs to check yourself, because these products change fast:
- The models are typically smaller than the frontier ones, so very hard reasoning may be weaker.
- I don't know whether it offers a HIPAA BAA. If it doesn't, it can still be useful for personal use but isn't a compliance answer for a clinic.

**What I'd do:** route by sensitivity.
- **Most sensitive** (identity, medical detail): stays in your local library, or goes only to a private or BAA-covered endpoint, with Lumo-style tools as one option for personal use.
- **Heavy reasoning:** goes to a frontier model on **de-identified** copies.
- **The library never leaves your device.** That's your strongest line: "memory you own, thinking you rent, and you choose how much to share."

At a Microsoft event that framing works in your favor. You aren't attacking anyone's platform. You're saying the user decides which model sees what, and any compliant model can plug in.

---

## 4. Wording to be careful with

- **"HIPAA-safe."** HIPAA compliance belongs to the whole deployment (the provider, the contract, how it's configured), not to a single product. The flyer says "Imagine it comes along, and is HIPAA-safe," which is a vision and reads fine. Don't say "HIPAA-compliant" until a clinic or compliance advisor has signed off.
- **"Record anyone without their okay."** This is my wording for the "never does" box. Make sure it matches your real policy.
- **Proof items.** The Zoom, printout and forms/letters examples are your claims. Be ready to say who, when and what happened if someone asks at the table.
- **No Microsoft logos or implied endorsement.** The flyer is vendor-neutral and names no AI products.

---

## 5. Before you print

1. **Test both QR codes on a phone from a printed page.** I reused the codes from your v10 file. The "story in full" code that was on the old cover is gone; tell me its URL if you want it back.
2. **Email mismatch:** the flyer and `contact.vcf` use `nao.contributor@outlook.com`; the repo README says `nao.contributor@gmail.com`. Pick one.
3. **Print one copy first** to check color and trim. Dec 9 is close, so allow time for a reprint.
4. **Bring a half-sheet too.** Many people at conferences won't take a trifold. The front cover plus the "Talk to us" panel makes a good one.
5. **One clear ask.** The back says "Pilot it. Break it. Build with us." If you have a specific ask (a demo slot, a partner, a tester), put it there.
