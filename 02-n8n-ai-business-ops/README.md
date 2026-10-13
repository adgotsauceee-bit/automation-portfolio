# n8n AI Agents & Business-Ops Automation

**Client:** HH Brands

Twelve n8n workflows connecting Claude and GPT-4o with QuickBooks, Square, Shopify, Slack, Gmail, Google Workspace, MongoDB, Retell AI, SendFox and GoHighLevel. Four run live in production.

| Metric | Result |
|---|---|
| Workflows built | 12 |
| Live in production | 4 |
| Production failure rate | 0% |
| Average run time | 1.59 s |

**Stack:** Claude · GPT-4o vision · QuickBooks API · Square · Shopify · Slack · Gmail · Google Workspace · MongoDB · Retell AI · SendFox · HMAC-verified webhooks

## 1. AI bookkeeping in Slack — receipts to QuickBooks in one photo
- **Challenge:** Two companies' receipts, P&L questions and tax estimates meant constant manual QuickBooks work.
- **Solution:** Slack router, GPT-4o receipt reader with undo, on-demand finance menu and a weekly P&L digest.
- **Outcome:** Bookkeeping and reporting live in the chat tool the team already uses.

## 2. Voice-AI follow-through — every callback surfaced by 8 AM
- **Challenge:** An AI phone agent took calls, but callback requests were buried in transcripts.
- **Solution:** Daily tracker pulls every call, Claude classifies intent, callbacks land on a shared sheet.
- **Outcome:** Live daily with 100% successful runs.

## 3. Automated content engine — SEO blogs, twice a day
- **Challenge:** The Shopify store needed consistent SEO content without a writer.
- **Solution:** MongoDB topic queue → Claude drafting → Drive archive → Shopify publishing with duplicate protection.
- **Outcome:** Publishing on schedule in production with no failed runs.

## 4. AI purchasing assistant — a data-driven buy list every Monday
- **Challenge:** Reordering from Square inventory was guesswork, causing stock-outs and overstock.
- **Solution:** Weekly Square data pipeline, Claude reorder analysis by email, and an APPROVE-by-reply loop.
- **Outcome:** Reorder decisions backed by sales velocity, with a full audit trail.

## Workflow files
Sanitized workflow exports (credentials and client data removed) will be added to [`workflows/`](workflows/).
