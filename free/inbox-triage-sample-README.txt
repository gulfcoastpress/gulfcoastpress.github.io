Gmail Inbox Triage (free starter workflow)
===========================================

WHAT IT DOES
Every 5 minutes, new unread mail is labelled urgent, lead, billing, newsletter or other by gpt-4o-mini, then marked triaged so it is never sorted twice. Failed AI replies are left unlabelled and retried.

NEEDS
Gmail · OpenAI. n8n Cloud or self-hosted, n8n 1.x (import-tested on 1.123.91).

SET UP (about 10 min)
1. In n8n: Workflows > Import from file > pick inbox-triage-sample.json.
2. Read the yellow note on the canvas, then fill the Config node if there is one.
3. Open each node with a red warning and pick your own credential. Nothing is hard-coded.
4. Test with your own email or a test form post first. Then activate.

COST
Uses gpt-4o-mini. At OpenAI's published $0.15 per 1M input and $0.60 per 1M output tokens, a typical run costs well under a cent. See the FAQ for per-1,000 estimates.

WHAT THE PAID PACK ADDS (The Inbox Operator, $149)
- Reply drafts in your voice for anything you tag needs-reply
- Receipts and invoices pulled into a Sheet
- Leads turned into Sheet rows plus an acknowledgement draft
- Follow-up nudges for quiet leads
- A 7 AM inbox brief and a nightly promo sweep
- 10-page setup guide
https://payhip.com/b/syg6m

Everything: The Operator Suite, all 21 workflows, $399: https://payhip.com/b/FG4vy

Questions: gavindimartino3@gmail.com

Made with an AI assistant; each file passes our QA checklist and an n8n import test before release. Not tested against your accounts: test before you activate. No income, time-saving or business outcome is guaranteed. n8n, Gmail, Google Sheets, OpenAI, LinkedIn, X, Typeform, Tally and Jotform are trademarks of their owners. Not affiliated or endorsed.
