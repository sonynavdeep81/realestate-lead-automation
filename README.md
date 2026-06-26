# Real-Estate Lead Automation

Turn messy real-estate inquiry messages into clean CRM records **and** personalized draft replies — in seconds, hands-free.

**▶️ Live 2-min demo:** https://youtu.be/E-p-vaRJmRQ

## Problem → Solution → Result
- **Problem:** Agents lose leads because messy inquiry messages don't get logged or answered fast enough.
- **Solution:** Each incoming lead is read by an LLM, the key details are extracted into a clean record, logged to a CRM, and a warm, personalized reply is drafted automatically — the agent just reviews and sends.
- **Result:** Every lead captured and answer-ready in seconds. Verified across multiple messy sample leads with **zero invented fields** on sparse inputs — no fake phone numbers, budgets, or emails.

## Why it's trustworthy
- **No hallucination:** if a detail wasn't given, the field stays blank — it never invents data.
- **Your data stays yours:** everything lives in the client's own CRM and LLM account; nothing is used for training.
- **Cheap to run:** a few fractions of a cent per lead — API cost is negligible next to the value of a captured deal.

## Stack
Make (orchestration) · OpenAI `gpt-4o-mini` (extraction + reply) · Airtable (CRM).

---
*Built by Dr. Navdeep Singh. I set these up per business in a few days — see [`case-study.md`](case-study.md) or get in touch.*
