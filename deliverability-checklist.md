# Cold Email Deliverability Checklist

Before you send a single email, run through this list.

## Domain Setup

- [ ] **Dedicated sending domain** — don't send cold email from your main domain
- [ ] **SPF record** — `v=spf1 include:_spf.google.com ~all` (for Google Workspace)
- [ ] **DKIM signing** — enabled in your email provider
- [ ] **DMARC policy** — `v=DMARC1; p=none; rua=mailto:dmarc@yourdomain.com`
- [ ] **Domain age 2+ weeks** — brand new domains get flagged

## Warmup

- [ ] **Gradual ramp** — start with 10-20/day, increase 10% daily
- [ ] **Mix of senders** — multiple email accounts, staggered
- [ ] **Real replies needed** — have colleagues or warmup services reply
- [ ] **2-4 week warmup** — before full volume

## Content

- [ ] **No spam trigger words** — "free", "guaranteed", "act now"
- [ ] **Minimal links** — 0-1 links per email (more = spam score up)
- [ ] **No attachments** — ever, unless requested
- [ ] **Plain text or minimal HTML** — heavy formatting = promotional
- [ ] **Personalized openers** — generic templates get flagged

## Sending Patterns

- [ ] **40-50/day per account max** — stay under provider limits
- [ ] **Business hours only** — 8am-6pm recipient timezone
- [ ] **Randomized timing** — not exactly on the hour
- [ ] **Unsubscribe option** — link in signature (required by law in many places)

## Monitoring

- [ ] **Bounce rate <2%** — verify emails before sending
- [ ] **Spam complaint rate <0.1%** — stop campaign if higher
- [ ] **Check blacklists weekly** — mxtoolbox.com/blacklists

## Suplex Handles

Suplex automates most of this:
- Email verification before send (reduces bounces)
- Staggered sending across accounts
- 40-50/day limit per account enforced
- Dedicated sending infrastructure option via Smartlead integration

The hard part is content quality — that's where AI personalization (researching each lead's USP before writing) makes the difference.

→ [trysuplex.com](https://trysuplex.com)
