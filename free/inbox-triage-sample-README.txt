Inbox Triage (free sample from The Inbox Operator)
==================================================

Labels every new Gmail message as urgent, lead, billing, newsletter or other.

SET UP (about 10 minutes)
1. Import inbox-triage-sample.json in n8n (Workflows > Import from file).
2. Create 6 Gmail labels (the 5 buckets plus one named "triaged") and paste their label IDs into the Config node, including the triaged ID in LABEL_TRIAGED.
3. Connect Gmail and OpenAI credentials, test with one email to yourself, then activate.

NEEDS: n8n (Cloud trial or free self-hosted) and Gmail, an OpenAI API key (gpt-4o-mini; check OpenAI pricing).
Tested: imports into n8n 1.123.

WANT THE REST?
The Inbox Operator ($149): 7 workflows incl. reply drafts, invoice logging and a morning brief. https://payhip.com/b/syg6m
Everything: The Operator Suite, all 21 workflows ($399) https://payhip.com/b/FG4vy

Questions: gavindimartino3@gmail.com

Made with AI assistance and reviewed by a human. Results depend on your setup and use; no income, time-saving or business outcome is guaranteed. n8n, Gmail, Google Sheets, OpenAI, LinkedIn, Typeform, Tally, Jotform and Calendly are trademarks of their owners; this is independent and not affiliated with or endorsed by them.
