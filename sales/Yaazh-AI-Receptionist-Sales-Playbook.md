# Yaazh AI Receptionist — Sales Playbook

**The complete field kit for selling the AI WhatsApp Receptionist to clinics, dental practices, diagnostic centres & hospitals in India.**

Pair this document with the interactive demo (`Yaazh-AI-Receptionist-Demo.html`). The demo is what you *show*; this playbook is what you *say, send, and set up*.

> **Note on data:** All numbers, doctors, patients, and the demo clinic ("Sri Ramachandra Multi-Speciality Clinic, Chennai") are illustrative examples for demonstration. Pricing figures are Yaazh's recommended go-to-market pricing — verified against WhatsApp/Meta message costs but adjustable per deal.

---

## Contents

1. [Product overview & positioning](#1-product-overview--positioning)
2. [The ROI story (with the maths)](#2-the-roi-story-with-the-maths)
3. [Before vs After](#3-before-vs-after)
4. [The 5-minute pitch](#4-the-5-minute-pitch)
5. [The 10-minute pitch](#5-the-10-minute-pitch)
6. [Live demo script (you act as the AI)](#6-live-demo-script-you-act-as-the-ai)
7. [All 13 conversation flows (full transcripts)](#7-all-13-conversation-flows-full-transcripts)
8. [Objection handling](#8-objection-handling)
9. [Pricing & packaging](#9-pricing--packaging)
10. [Knowledge Base template](#10-knowledge-base-template)
11. [AI functions specification](#11-ai-functions-specification)
12. [Integrations](#12-integrations)
13. [Technical architecture & API flow](#13-technical-architecture--api-flow)
14. [Database schema (SQL)](#14-database-schema-sql)
15. [Sample data](#15-sample-data)
16. [Implementation & timeline](#16-implementation--timeline)
17. [The close & follow-up](#17-the-close--follow-up)

---

## 1. Product overview & positioning

**One-liner:** *Yaazh is an AI receptionist that lives on your clinic's WhatsApp number — answering every patient in seconds, booking appointments 24×7, and handing off to your staff only when it matters.*

**The problem it solves:** Clinics lose patients not because of bad care, but because of a busy front desk. Calls go unanswered during rush hours and after closing. WhatsApp messages sit unread. Staff burn hours repeating fees, timings, and directions. And patients — who now expect instant replies — simply message the next clinic.

**Who it's for:**

| Segment | Primary hook |
|---|---|
| Dental clinics | Booking + recall + review generation |
| Multi-speciality clinics | Doctor availability, fees, department routing |
| Diagnostic centres / labs | Test prices, prep instructions, report delivery |
| Hospitals & chains | Multi-branch, EMR/HMS integration, voice add-on |
| Solo practitioners | Never miss a patient while you're with one |

**Why it wins (positioning against alternatives):**

- **vs a human receptionist:** never sleeps, never on lunch, handles 50 chats at once, costs a fraction, never quits.
- **vs a generic chatbot:** Yaazh *does things* — checks the live calendar, books the slot, sends the report link, takes the payment. It's an agent, not an FAQ page.
- **vs "we'll just reply faster":** you can't reply at 11pm, and speed-to-reply is the single biggest driver of who gets the patient.

---

## 2. The ROI story (with the maths)

Lead with money. This is the slide that closes clinics.

**Illustrative mid-size clinic:** ~25 patients/day, ₹500 average consultation, open 6 days/week.

**Where the money leaks today:**

- Missed calls during rush/lunch/after-hours: conservatively **10–15 calls/day** go unanswered.
- Of those, ~40% would have booked → **~5 lost appointments/day**.
- 5 × ₹500 × 26 days = **₹65,000/month in lost consults alone** — before lab tests, packages, and repeat visits.

**What Yaazh recovers:**

| Lever | Monthly impact (illustrative) |
|---|---|
| Recovered missed & after-hours enquiries (~120/mo) | **+₹60,000** consult revenue |
| No-show reduction (~38% via reminders) | **+₹25,000** reclaimed slots |
| Lab & package upsell surfaced in chat | **+₹40,000–₹1,00,000** |
| Staff time saved (3–4 hrs/day) | Redeployed to in-clinic patient care |
| **Total upside** | **₹1.2L–₹1.8L/month typical** |

**Cost:** ₹9,999/month (Professional). **Payback: under 2 weeks.** ROI: **6–12×.**

**The one-sentence version to say out loud:**
> *"If Yaazh recovers just **one** missed appointment a day, it has already paid for itself — everything after that is profit."*

---

## 3. Before vs After

| | **Front desk today** | **Front desk with Yaazh** |
|---|---|---|
| Missed calls | 30–40% during rush & after hours | 0 — every patient answered in seconds |
| Response time | Minutes to hours (or never) | < 5 seconds, 24×7 |
| Booking | Manual, phone-tag, errors | Auto-booked into the live calendar |
| Repetitive queries | Staff repeat fees/timings all day | Deflected instantly by AI |
| No-shows | High — reminders rarely sent | −38% with auto reminders & confirms |
| After-hours enquiries | Lost | Captured & booked |
| Reviews | Rarely asked | Auto-requested from happy patients |
| Staff focus | Phone + walk-ins simultaneously | In-clinic patients get full attention |

---

## 4. The 5-minute pitch

Use when you have a distracted clinic owner between patients.

> **[0:00 — Hook]**
> "Doctor, quick question — how many WhatsApp messages and calls does your front desk miss on a busy day? … Most clinics we talk to miss 10 to 15. Each of those is a patient who books with someone else."
>
> **[0:45 — Problem]**
> "Your team is brilliant with patients *in* the clinic. But they can't answer the phone, message on WhatsApp, and check someone in — all at once. So enquiries slip. Especially after 8pm and on Sundays, when patients are actually free to message."
>
> **[1:30 — Solution]**
> "Yaazh is an AI receptionist that lives on your existing WhatsApp number. A patient messages 'do you do root canal, and what's the cost?' — Yaazh answers instantly, shares the fee, checks Dr. Meera's live calendar, and books the appointment. All by itself. 24 hours a day."
>
> **[2:30 — Show, don't tell]**
> "Let me show you — this is a real conversation." *(Open the demo, play 'Book an appointment'.)* "Notice it didn't just chat — it booked the slot and sent a confirmation."
>
> **[3:30 — ROI]**
> "If this recovers just one missed appointment a day, that's ₹15,000 a month back in your pocket. Yaazh costs ₹9,999. It pays for itself in under two weeks."
>
> **[4:15 — Close]**
> "I can set this up on your number in a week, and the first two weeks are a free pilot. If it doesn't book appointments, you don't pay. Shall we start the pilot?"

---

## 5. The 10-minute pitch

Use in a sit-down meeting. Structure: **Problem → Solution → Demo → Benefits → ROI → Pricing → Implementation → Close.**

**[Problem — 2 min]**
Open with their reality. "Walk me through a busy Monday morning at your front desk." Let them describe the chaos. Then reflect it back: missed calls, WhatsApp piling up, no-shows, staff stretched. Quantify: "So realistically, 10–15 enquiries slip through on a busy day?" Get the nod. That nod is the sale.

**[Solution — 1.5 min]**
"Yaazh is an AI receptionist on your WhatsApp number. Three things make it different from a chatbot: **one**, it takes actions — it books, reschedules, sends reports, takes payments. **Two**, it knows *your* clinic — your doctors, fees, timings, packages. **Three**, it knows when to step back and call a human."

**[Demo — 3 min]**
This is the heart. Open the interactive demo:
1. Play **"New patient enquiry"** — show instant, natural, accurate replies.
2. Play **"Book an appointment"** — show it *booking* and confirming.
3. Play **"Emergency case"** — show the safety guardrail + human escalation. (This builds trust that it won't do anything reckless.)
4. Click to the **Dashboard** — "and you see everything: today's appointments, live chats, revenue influenced, satisfaction."

**[Benefits — 1 min]**
"So what changes for you: zero missed enquiries, appointments booked while you sleep, staff freed to care for patients in the chair, fewer no-shows, and more Google reviews from happy patients."

**[ROI — 1.5 min]**
Walk the maths from Section 2. Land the line: *"one recovered appointment a day pays for the whole thing."*

**[Pricing — 0.5 min]**
"Professional is ₹9,999 a month plus a one-time ₹30,000 setup. That covers booking, lab, reports, payments, analytics — everything you just saw."

**[Implementation & Close — 0.5 min]**
"Setup takes about a week. First two weeks are a free pilot on your real number — if it doesn't book appointments, you don't pay the subscription. Can I get your WhatsApp number and doctor list to start the pilot this week?"

---

## 6. Live demo script (you act as the AI)

If you don't have a screen — or want a dramatic moment — role-play the AI live. Ask the clinic owner to be the patient and message a WhatsApp number (or just speak it aloud).

**You:** "Message me anything a patient would ask. Go ahead — try to stump it."

**Owner:** "What are your timings?"
**You (as Yaazh):** "We're open Mon–Fri 9am to 9pm, Saturday till 6pm, and Sundays for emergencies. Would you like to book an appointment?"

**Owner:** "Do you do teeth cleaning and how much?"
**You (as Yaazh):** "Yes — dental scaling and polishing is ₹999, with Dr. Kavya Reddy. She's in today until 6pm. I have slots at 2:00, 3:30 and 5:00. Which suits you?"

**Owner:** "3:30"
**You (as Yaazh):** "Booked ✅ Dr. Kavya Reddy, today 3:30pm, token #P-072. I've sent a confirmation and I'll remind you an hour before. See you soon!"

**Then break character:** "Notice three things — it knew your fee, it checked a real calendar, and it *booked* — no staff touched it. Now imagine that happening 40 times a day, including at midnight."

**Pro tips for the live demo:**
- Always run **one emergency/handoff example** — it proves the AI is safe and knows its limits. Owners worry most about this.
- If they ask something niche ("do you accept Star Health?"), answer confidently from the KB — it shows the AI is grounded in *their* data, not making things up.
- End on a booking every time. The "booked ✅" moment is the dopamine hit that sells.

---

## 7. All 13 conversation flows (full transcripts)

These mirror the interactive demo. Use them to build WhatsApp templates and to train/tune the assistant. **🧑 = patient, 🤖 = Yaazh AI, ⚙️ = system event.**

### 7.1 New patient enquiry
- 🧑 Hi, is this Sri Ramachandra clinic? Do you do root canal?
- 🤖 Hello! 👋 Yes — you've reached Sri Ramachandra Multi-Speciality Clinic. We do root canals with Dr. Meera Krishnan (Endodontist). Consultation is ₹600, root canal from ₹3,500 depending on the tooth. Would you like to book a visit? 🦷
- 🧑 What are your timings?
- 🤖 Mon–Fri 9am–9pm, Sat 9am–6pm, Sun emergencies only. Dr. Meera is in Mon–Sat. Shall I check her next free slot?
- 🧑 Yes please
- 🤖 Next available with Dr. Meera: *Today 6:30pm · Tomorrow 11am · Tomorrow 4pm.* Which works?

### 7.2 Booking an appointment
- 🧑 I want to book an appointment for braces
- 🤖 Perfect — that's Orthodontics with Dr. Arjun Nair, consult ₹500. May I have your name and age to create the booking?
- 🧑 Ramesh Kumar, 24
- 🤖 Thanks Ramesh! Dr. Arjun is in Mon, Wed & Fri. Nearest slots: *Wed 10:00am · Wed 5:30pm · Fri 11:00am.*
- 🧑 Wed 10am
- 🤖 Booked ✅ **Dr. Arjun Nair · Orthodontics · Wed 21 Aug · 10:00 AM · Token #A-118.** Added to your calendar; I'll remind you the day before. See you Wednesday! 🙌

### 7.3 Rescheduling
- 🧑 I need to move my appointment tomorrow to next week
- 🤖 No problem! I found it: Dr. Arjun Nair, tomorrow 10:00 AM. When next week works?
- 🧑 Monday evening if possible
- 🤖 Monday evening options: *5:30pm · 6:15pm · 7:00pm.*
- 🧑 6:15 works
- 🤖 Done ✅ Moved to **Mon 26 Aug · 6:15 PM.** Old slot released, reminders updated. Anything else? 😊

### 7.4 Cancelling
- 🧑 Please cancel my appointment for tomorrow
- 🤖 Sure — confirm you want to cancel with Dr. Meera Krishnan, tomorrow 4:00 PM?
- 🧑 Yes
- 🤖 Cancelled ✅ It's more than 4 hours away, so no cancellation fee. Want me to help you rebook another day?
- 🧑 I'll rebook later, thanks
- 🤖 Absolutely 🙏 Message anytime and I'll find you a slot. Take care!

### 7.5 Doctor availability
- 🧑 Is the gum doctor available today?
- 🤖 That's Dr. Kavya Reddy (Periodontist) — yes, in today until 6pm. Slots: *2:00pm · 3:30pm · 5:00pm.*
- 🧑 Does she treat bleeding gums?
- 🤖 Yes, that's exactly her specialty — usually a cleaning and gum assessment, consult ₹500. Shall I book one of those slots?
- 🧑 3:30 today
- 🤖 Booked ✅ **Dr. Kavya Reddy · today 3:30 PM · Token #P-072.** See you soon!

### 7.6 Lab test enquiry
- 🧑 How much is a lipid profile test and do I need to fast?
- 🤖 Lipid Profile is ₹650. ⚠️ **Prep: 12 hours fasting** (water is fine), best between 7–11am. Report same day by evening.
- 🧑 Can someone collect from home?
- 🤖 Yes! Home collection +₹150. Which area, and what date/time?
- 🧑 Anna Nagar, tomorrow 8am
- 🤖 Done ✅ Home collection **tomorrow 7:30–8:30 AM, Anna Nagar.** Please fast from 8pm tonight. Report link here by evening. 🏠

### 7.7 Diagnostic package enquiry
- 🧑 Do you have any full body checkup offers?
- 🤖 Two popular ones: **Comprehensive ₹4,999** (75+ params, ECG + doctor review) and **Basic ₹1,999** (40 essentials + consult). Both include a free doctor consult. Book one?
- 🧑 What's included in the comprehensive one?
- 🤖 CBC, lipid, liver & kidney function, thyroid, sugar & HbA1c, vitamin D & B12, urine routine, ECG, and a physician consultation. Fasting 10–12 hrs. Shall I schedule it?
- 🧑 Yes, this Saturday
- 🤖 Booked ✅ **Comprehensive · Sat 24 Aug · 8:00 AM** (come fasting) · ₹4,999. Prep instructions sent. 🙌

### 7.8 Health check-up package (guided)
- 🧑 My father is 58 and diabetic, which checkup is best?
- 🤖 For a 58-year-old with diabetes I'd suggest **Diabetic Care (₹2,499)** — HbA1c, fasting/PP glucose, kidney, lipid + diet counselling. Add heart screening with **Cardiac Screen (₹3,499)** if you'd like. Which one?
- 🧑 Diabetic care is fine
- 🤖 Great choice 👍 His name and a preferred day? A fasting morning sample works best.
- 🧑 Sanjay, Sunday morning
- 🤖 Booked ✅ **Diabetic Care for Sanjay · Sun 25 Aug · 8:30 AM** (fasting). Diet counselling right after results. Take care of him 🙏

### 7.9 Report collection
- 🧑 Is my blood test report ready?
- 🤖 Let me check for you… 🔎
- 🤖 Yes Priya, it's ready ✅ **CBC + Lipid Profile · collected 19 Aug · verified.** 📄 Secure download link (valid 30 days, password = your DOB).
- 🤖 Would you like a doctor to walk you through the results? (Teleconsult ₹250)
- 🧑 No it's fine, thank you
- 🤖 You're welcome, Priya! Stay healthy 💚

### 7.10 Emergency case
- 🧑 My tooth is bleeding badly after an accident and pain is severe
- 🤖 I'm really sorry 🙏 This needs urgent attention. Right now: apply gentle pressure with clean gauze, use a cold compress on the cheek, avoid forceful rinsing. I'm alerting our team immediately.
- ⚙️ *Emergency detected — reception notified*
- 🤖 Our on-call dentist Dr. Rahul Menon can see you right away. Can you come to the clinic now? If it's a severe medical emergency, please call 108.
- 🧑 Coming now
- 🤖 👩‍⚕️ Priya from reception will call you within a minute to guide you. Head over — we're ready. 🚑

### 7.11 Human escalation
- 🧑 I was charged twice for my last visit, this is frustrating
- 🤖 I'm sorry about that — a double charge is something we'll fix. This needs our accounts team, so I'm connecting you to a human now. 🙏
- ⚙️ *Conversation handed to Reception · context shared*
- 🤖 👩‍💼 Hi, this is Anitha from the front desk. I can see your 18 Aug visit. I'll check the gateway and confirm the refund within 24 hours. What amount was debited twice?
- 🧑 ₹500 twice
- 🤖 Got it — ₹500 duplicate. Refund request raised; you'll get a confirmation SMS. So sorry for the trouble! 💚

### 7.12 Follow-up reminder (proactive)
- ⚙️ *Automated reminder · 1 day before*
- 🤖 Hi Ramesh! ⏰ Reminder for tomorrow: **Dr. Arjun Nair · Orthodontics · Wed 21 Aug · 10:00 AM · Anna Nagar.** Confirm you're coming? *[✅ Confirm] [🔁 Reschedule] [❌ Cancel]*
- 🧑 ✅ Confirm
- 🤖 Perfect, confirmed! 🙌 Please arrive 10 min early with any previous X-rays. See you tomorrow!
- ⚙️ *Status → Confirmed · no-show risk cleared*

### 7.13 Feedback & review
- ⚙️ *Automated · 2 hours after visit*
- 🤖 Hi Lakshmi! Thanks for visiting today 💚 How was your experience with Dr. Meera? *[⭐⭐⭐⭐⭐] [⭐⭐⭐⭐] [⭐⭐⭐ or less]*
- 🧑 ⭐⭐⭐⭐⭐
- 🤖 That means a lot! 🙏 Would you share a quick Google review? Takes 20 seconds ⭐ → *[review link]*
- 🧑 Sure, done!
- 🤖 Thank you Lakshmi! 💚 Wishing you a speedy recovery. We're always here on WhatsApp.

> **Routing logic for feedback:** 4–5★ → route to public Google review. 3★ or less → route privately to clinic manager for service recovery (protects the clinic's rating).

---

## 8. Objection handling

Answer the emotion first, then the logic. Keep it short and confident.

**"We already have a receptionist."**
> "Perfect — Yaazh isn't here to replace her, it's here to give her superpowers. It handles the repetitive stuff — timings, fees, bookings, the 11pm messages — so she can focus on patients standing in front of her. She becomes your VIP handler, not your switchboard. And unlike a person, Yaazh handles 50 chats at once and never takes a day off."

**"It's too expensive."**
> "I understand — but let's look at what it *makes*, not just what it costs. If you miss even one appointment a day, that's ₹15,000 a month gone. Yaazh is ₹9,999 and recovers many more than one. It's not a cost, it's a revenue line. And the first two weeks are free — you only pay once you've seen it book real patients."

**"Our staff already handles WhatsApp."**
> "They do — during working hours, when they're free, which on a busy day is almost never. Yaazh replies in 5 seconds, every time, including nights and Sundays when your staff are home but patients are messaging. Your staff still jump in whenever they want — Yaazh just makes sure nobody waits and nobody is missed."

**"We don't need AI."**
> "Totally fair — and honestly, your patients won't know or care that it's AI. They just know they got an instant, helpful reply and their appointment was booked. Think of it less as 'AI' and more as a front desk that's open 24×7 and never drops a message. The technology is invisible; the extra appointments are not."

**"What about patient privacy?"**
> "It's a serious concern and we treat it that way. Conversations stay on WhatsApp's encrypted channel, patient data is encrypted and stored in *your own* secure database — you own it, not us. We're aligned with India's DPDP Act, we never share data, and the AI is explicitly barred from giving any medical diagnosis. Everything sensitive routes to a human."

**"Can patients still talk to a human?"**
> "Always — that's built in. The moment a patient asks for a person, or the topic is sensitive — a complaint, a payment issue, an emergency — Yaazh hands off instantly to your reception with the full chat history, so nobody has to repeat themselves. It's AI-first, human-always-available."

---

## 9. Pricing & packaging

| | **Starter** | **Professional** ⭐ | **Enterprise** |
|---|---|---|---|
| Monthly | **₹4,999** | **₹9,999** | **₹24,999+** |
| One-time setup | ₹15,000 | ₹30,000 | ₹75,000+ |
| Best for | Solo / single-doctor | Multi-doctor clinics & labs | Hospitals & chains |
| WhatsApp AI 24×7 | ✅ | ✅ | ✅ |
| Book / reschedule / cancel | ✅ | ✅ | ✅ |
| FAQs, fees, timings, location | ✅ | ✅ | ✅ |
| Lab tests, reports, packages | — | ✅ | ✅ |
| Razorpay payments + CRM | — | ✅ | ✅ |
| Analytics + review funnel | — | ✅ | ✅ |
| Conversations / month | 1,000 | 5,000 | Unlimited |
| Calendars | 1 | 5 | Unlimited |
| EMR / HMS integration | — | Add-on | ✅ Deep |
| AI voice agent | — | — | ✅ Add-on |
| Support | Email | Priority | Dedicated manager + SLA |

**Pass-through:** WhatsApp/Meta conversation charges (~₹0.11 utility / ₹0.86 marketing per template) billed transparently at cost + 18% GST.

**Deal sweeteners in your back pocket:**
- **Free 2-week pilot** on their real number — "no bookings, no charge."
- **Annual prepay** → 2 months free.
- **Multi-branch** → volume discount on setup.
- **Founding-clinic discount** → ₹7,999 locked for 12 months for your first 5 clients (gets you case studies fast).

---

## 10. Knowledge Base template

This is what you fill in per clinic — the AI's single source of truth. Collect this in the onboarding call.

**Clinic profile:** name · WhatsApp number · reception handoff number · address · Google Maps link · landmark · languages.

**Doctors**

| Doctor | Department | Specialisation | Consult fee | Days available |
|---|---|---|---|---|
| Dr. Meera Krishnan | Endodontics | Root canal, retreatment | ₹600 | Mon–Sat |
| Dr. Arjun Nair | Orthodontics | Braces, clear aligners | ₹500 | Mon, Wed, Fri |
| Dr. Kavya Reddy | Periodontics | Gum disease, cleaning | ₹500 | Tue–Sat |
| Dr. Rahul Menon | Oral Surgery | Implants, extractions | ₹800 | Mon, Thu, Sat |
| Dr. Sneha Iyer | Pediatric Dentistry | Kids' dental care | ₹500 | Tue, Thu, Sat |

**Departments & fees:** General ₹300 · Specialist ₹500–800 · Second opinion ₹400 · Follow-up (≤15 days) free · Teleconsult ₹250.

**Working hours:** Mon–Fri 9am–9pm · Sat 9am–6pm · Sun emergencies only · Lab collection 7–11am.

**Lab tests**

| Test | Price | Fasting | Report |
|---|---|---|---|
| CBC | ₹350 | No | Same day |
| Lipid Profile | ₹650 | 12 hrs | Same day |
| HbA1c | ₹450 | No | Same day |
| Thyroid (T3 T4 TSH) | ₹550 | No | Next day |
| Vitamin D | ₹1,200 | No | 2 days |
| Full Body Checkup | ₹2,999 | 10–12 hrs | Next day |

**Health packages:** Comprehensive ₹4,999 · Basic ₹1,999 · Diabetic Care ₹2,499 · Cardiac Screen ₹3,499 · Dental Hygiene ₹999.

**Policies:** Cancellation free ≥4 hrs before, else ₹100 · Reschedule free anytime · Refunds in 5–7 working days · Reports valid 30 days · DPDP-compliant data handling.

**Insurance:** Cashless with Star Health, HDFC Ergo, ICICI Lombard, New India Assurance, CGHS · policy card + photo ID · TPA desk handles pre-auth.

**FAQs:** walk-ins accepted (appointments prioritised) · free basement parking · EMI on treatments > ₹15,000 · teleconsults available · pediatric care available.

---

## 11. AI functions specification

The AI's "tools" — each is a function the model calls to take a real action. Function-calling is what separates Yaazh from a chatbot.

| Function | Params | Returns | Side effects |
|---|---|---|---|
| `bookAppointment` | `patient, doctorId, slot, reason` | `bookingId, token, confirmation` | Calendar event + EMR record + confirmation msg |
| `rescheduleAppointment` | `bookingId, newSlot` | `updated booking` | Moves event, notifies patient & doctor |
| `cancelAppointment` | `bookingId, reason` | `status, feeApplied` | Frees slot, applies cancellation policy |
| `checkDoctorAvailability` | `doctorId, date` | `[open slots]` | Reads live calendar (read-only) |
| `searchLabTest` | `query` | `{price, fasting, reportTime}` | KB lookup |
| `searchHealthPackage` | `query` | `{name, inclusions, price}` | KB lookup |
| `sendReportStatus` | `patientId` | `{ready, secureLink}` | Checks LIS/EMR, issues signed URL |
| `sendLocation` | `—` | `{mapsUrl, landmark, parking}` | Sends Maps pin |
| `collectPatientDetails` | `fields[]` | `patientId` | Validates & upserts patient record |
| `handoffToReception` | `context` | `ticketId` | Pushes chat + context to staff console |
| `notifyReceptionist` | `alert, priority` | `ack` | Real-time alert (emergency/VIP/complaint) |
| `requestPayment` | `amount, purpose` | `paymentLink` | Generates Razorpay link |

**Guardrails:** the model is instructed to (a) never diagnose or prescribe, (b) hand off on low confidence or sensitive intent, (c) confirm before any write action (book/cancel/pay), (d) never invent facts outside the KB.

---

## 12. Integrations

| System | What it does | How |
|---|---|---|
| **WhatsApp Cloud API** | The patient channel | Official Meta API, webhooks in/out |
| **Google Calendar** | Live slot booking | OAuth, two-way sync |
| **Outlook Calendar** | Live slot booking | Microsoft Graph, two-way sync |
| **CRM** | Lead & contact capture | API / webhook push |
| **EMR / HMS** | Patient records, reports | REST/HL7 connector (Enterprise) |
| **Google Maps** | Location & directions | Static/dynamic Maps link |
| **Razorpay** | Advances, deposits, packages | Payment links + webhook confirm |
| **SMS gateway** | Fallback reminders | Provider API (e.g., MSG91) |
| **Email** | Reports & invoices | SMTP / transactional (e.g., Resend) |

Positioning line: *"Yaazh plugs into what you already run — nothing to rip out."*

---

## 13. Technical architecture & API flow

**Stack:** WhatsApp Cloud API · n8n (orchestration) · OpenAI GPT-4o (reasoning + tool-calling) · Supabase (Postgres data, auth, storage) · Next.js (staff dashboard).

**Message flow:**

```
Patient (WhatsApp)
   │  1. sends message
   ▼
WhatsApp Cloud API  ──2. webhook──▶  n8n orchestration
                                        │  3. load clinic context + history
                                        ▼
                                   OpenAI GPT-4o
                                        │  4. decides: reply OR call a tool
                        ┌───────────────┼────────────────┐
                        ▼               ▼                ▼
                 checkAvailability  bookAppointment   sendReportStatus …
                        │               │                │
                   Supabase / Calendar / EMR / Razorpay / Maps
                        └───────────────┼────────────────┘
                                        │  5. tool result → model → final reply
                                        ▼
                        n8n ──6. send──▶ WhatsApp Cloud API ──▶ Patient
                                        │
                                        └──7. log to Supabase ──▶ Next.js dashboard (staff)
```

**Why this stack for clinics:** self-hostable in India for data residency; Supabase means the clinic *owns* its patient data; n8n makes new integrations fast; GPT-4o tool-calling is what makes the agent reliable at *doing* things, not just chatting.

---

## 14. Database schema (SQL)

Core tables (Supabase / Postgres). Simplified for clarity; add RLS policies per clinic tenant.

```sql
-- Tenancy
create table clinics (
  id uuid primary key default gen_random_uuid(),
  name text not null,
  whatsapp_number text unique not null,
  address text, maps_url text, landmark text,
  languages text[] default '{English}',
  created_at timestamptz default now()
);

-- Staff / doctors
create table doctors (
  id uuid primary key default gen_random_uuid(),
  clinic_id uuid references clinics(id) on delete cascade,
  name text not null,
  department text,
  specialisation text,
  consult_fee integer,
  available_days text[]      -- e.g. {Mon,Wed,Fri}
);

-- Patients
create table patients (
  id uuid primary key default gen_random_uuid(),
  clinic_id uuid references clinics(id) on delete cascade,
  name text, phone text not null,
  age integer, dob date,
  created_at timestamptz default now(),
  unique (clinic_id, phone)
);

-- Appointments
create table appointments (
  id uuid primary key default gen_random_uuid(),
  clinic_id uuid references clinics(id) on delete cascade,
  patient_id uuid references patients(id),
  doctor_id uuid references doctors(id),
  slot_start timestamptz not null,
  type text,                 -- consult / procedure / lab / package
  status text default 'confirmed',   -- confirmed|pending|cancelled|completed|no_show
  source text default 'whatsapp',
  token text,
  created_at timestamptz default now()
);

-- Conversations & messages (for dashboard + analytics)
create table conversations (
  id uuid primary key default gen_random_uuid(),
  clinic_id uuid references clinics(id) on delete cascade,
  patient_phone text not null,
  status text default 'ai',  -- ai|handoff|resolved
  intent text,
  handled_by text default 'yaazh_ai',
  started_at timestamptz default now(),
  resolved_at timestamptz
);

create table messages (
  id uuid primary key default gen_random_uuid(),
  conversation_id uuid references conversations(id) on delete cascade,
  direction text,            -- in|out
  sender text,               -- patient|ai|staff
  body text,
  tool_called text,          -- e.g. bookAppointment
  created_at timestamptz default now()
);

-- Knowledge base (per clinic)
create table kb_items (
  id uuid primary key default gen_random_uuid(),
  clinic_id uuid references clinics(id) on delete cascade,
  category text,             -- doctor|dept|lab|package|faq|policy|insurance|hours
  key text, value jsonb
);

-- Lab reports
create table reports (
  id uuid primary key default gen_random_uuid(),
  clinic_id uuid references clinics(id),
  patient_id uuid references patients(id),
  test_name text, status text default 'processing',  -- processing|ready
  secure_url text, verified_by text,
  created_at timestamptz default now()
);

-- Payments
create table payments (
  id uuid primary key default gen_random_uuid(),
  clinic_id uuid references clinics(id),
  patient_id uuid references patients(id),
  amount integer, purpose text,
  razorpay_link text, status text default 'created',  -- created|paid|failed
  created_at timestamptz default now()
);
```

---

## 15. Sample data

Load these to make demos and pilots feel real.

**Sample doctors** — the five in the KB table above.

**Sample patients**

| Name | Age | Phone | Notes |
|---|---|---|---|
| Ramesh Kumar | 24 | +91 90000 10001 | Ortho — braces |
| Lakshmi Sundaram | 41 | +91 90000 10002 | Endo — root canal |
| Priya Nair | 33 | +91 90000 10003 | Lab — CBC + lipid |
| John Mathew | 52 | +91 90000 10004 | Oral surgery — implant |
| Sanjay Bhaskar | 58 | +91 90000 10005 | Diabetic care package |
| Divya Anand | 29 | +91 90000 10006 | Perio — gum treatment |
| Reena Iyer | 8 | +91 90000 10007 | Pedo — child check-up |

**Sample appointments (today)**

| Time | Patient | Doctor · Dept | Type | Status |
|---|---|---|---|---|
| 09:00 | Ramesh Kumar | Dr. Arjun Nair · Ortho | Braces review | Confirmed |
| 09:30 | Lakshmi S. | Dr. Meera Krishnan · Endo | Root canal | Confirmed |
| 10:00 | Priya Nair | Diagnostics · Lab | CBC + Lipid | Checked-in |
| 10:30 | John Mathew | Dr. Rahul Menon · Oral Surg | Implant consult | Pending |
| 11:15 | Divya A. | Dr. Kavya Reddy · Perio | Gum treatment | Confirmed |
| 12:00 | Sanjay B. | Health Package | Comprehensive | Confirmed |
| 15:00 | Reena I. | Dr. Sneha Iyer · Pedo | Child check-up | Reminder sent |
| 17:30 | Nithya K. | Dr. Arjun Nair · Ortho | Aligner scan | Confirmed |

---

## 16. Implementation & timeline

Sell the ease. "You'll be live in a week, with almost nothing to do on your side."

| Day | Milestone |
|---|---|
| **Day 1–2** | Onboarding call → collect KB (doctors, fees, timings, tests, packages, policies). Connect WhatsApp Business number. |
| **Day 3–4** | Configure AI persona, load KB into Supabase, connect calendar + Razorpay, set handoff rules. |
| **Day 5** | Internal testing against the 13 flows; tune replies to clinic's tone. |
| **Day 6–7** | Go live on real number → **2-week free pilot begins.** |
| **Week 3** | Review pilot metrics (bookings, recovered enquiries, CSAT) → convert to paid. |

**Clinic effort required:** one 45-min onboarding call + WhatsApp number access. That's it.

---

## 17. The close & follow-up

**The assumptive close (best default):**
> "Let's get your number set up this week so the pilot can start Monday. If I could get your doctor list and WhatsApp number, I'll handle the rest — you'll just watch appointments start coming in."

**The risk-reversal close (for the hesitant):**
> "Here's my offer: two weeks, free, on your real number. If Yaazh doesn't book real appointments, you owe nothing and we walk away. All the risk is on me. Fair?"

**The scarcity close (for your first clients):**
> "I'm onboarding only five founding clinics at the ₹7,999 locked rate in exchange for a testimonial. After that it's ₹9,999. I'd love yours to be one of them."

**If they say "let me think about it":**
> "Of course. While you think — can we at least start the free pilot? It costs you nothing and gives you real data to think *with*, instead of guessing. Worst case, you've lost nothing; best case, it's already booking patients by the time we next talk."

**Follow-up cadence after the meeting:**
- **Same day:** thank-you WhatsApp + the demo link + one-line ROI recap.
- **Day 2:** send a 60-sec screen recording of the demo booking an appointment.
- **Day 4:** a short case-study/number ("clinics like yours recover ₹1L+/month").
- **Day 7:** "closing the loop — shall we start the pilot this week or should I check back next month?"

---

*Yaazh — automation with harmony. Built for Indian clinics.*
