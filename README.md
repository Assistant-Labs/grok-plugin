# AssistantLabs for Grok Bot and Cursor

Run the customer side of a small business from chat. Your bot reads every
WhatsApp, Instagram, Messenger and email conversation, answers what it can,
chases leads going cold, keeps the CRM and bookings straight, and brings you
anything that needs a decision. It asks you before anything reaches a customer.

## What it can do

- **Conversations:** who is waiting for a reply, search what customers asked, reply
- **Leads:** add and update leads, log what happened, find who went quiet
- **CRM:** look up, create and update contacts and companies
- **Bookings:** free slots, appointments, booking and rescheduling
- **Help desk:** view, update and resolve tickets
- **Marketing:** social posts, email campaigns and Meta ads
- **Your AI agent:** teach it new answers and approve suggested corrections

## Install

**Grok Bot:** open **Connect apps**, choose **AssistantLabs**, select **Connect**
and sign in. Then ask your bot "brief me" or "who is waiting for a reply?".

**Cursor:** open **Cursor Settings → Plugins**, search for **AssistantLabs** and
click **Install**, or run `/add-plugin assistantlabs` in chat. Then open
**Tools & MCPs**, select **Connect** next to `assistantlabs` and sign in.

No AssistantLabs account yet? Ask "set up my business" before signing in. The
`assistantlabs-start` connection needs no login: it reads your website and
drafts your agent, which waits for you when you sign up.

## Before you connect

You need an AssistantLabs account with at least one channel connected (WhatsApp,
Instagram, Messenger, email or website chat). Sign up at https://assistantlabs.io.

## How access works

- You sign in with OAuth and tick which products the connection may use. Revoke
  it any time at https://assistantlabs.io/app/account/developers.
- The bot reaches only the workspaces your account belongs to.
- Publishing a post, sending marketing email, running Instagram automations and
  spending on ads are off until you switch them on in the connection's permissions.

## Privacy and data

The plugin's files are instructions only; no code runs on your machine. Your
business data stays in AssistantLabs and reaches the bot only through the MCP
server, for the products you approve. AssistantLabs does not use data from this
connection to train AI models. Privacy policy:
https://assistantlabs.io/al-privacy-policy.html

## Contents

| | |
|---|---|
| `skills/` | 40 skills: daily brief, conversations, leads, CRM, bookings, marketing, reports, setup |
| `agents/` | 6 read-only specialists: customer health, triage, lead scout, money check, agent auditor, site reader |
| `mcp.json` | `assistantlabs` (OAuth) and `assistantlabs-start` (no login) at `mcp.assistantlabs.io` |

Support: support@assistantlabs.io · Terms: https://assistantlabs.io/al-terms-and-conditions.html ·
Privacy: https://assistantlabs.io/al-privacy-policy.html
