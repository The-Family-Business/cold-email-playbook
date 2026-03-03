# Cold Email Playbook 2026

The complete guide to B2B cold email outreach — tools, tactics, and systems that actually work.

> **Maintained by [Suplex](https://trysuplex.com)** — the desktop app that replaces your entire outreach stack for $97/month.

---

## Table of Contents

- [The Cold Email Stack Problem](#the-stack-problem)
- [Tools Comparison](#tools-comparison)
- [Lead Generation Guide](#lead-generation)
- [Email Deliverability](#deliverability)
- [Writing Cold Emails](#writing)
- [Scaling Your Outreach](#scaling)
- [Resources](#resources)

---

## The Stack Problem

A typical B2B outreach stack in 2026 costs **$454/month**:

| Tool Category | Common Tools | Monthly Cost |
|--------------|-------------|-------------|
| Lead Database | Apollo, ZoomInfo, Lusha | $99-199 |
| Email Verification | NeverBounce, ZeroBounce | $0.003-0.01/email |
| Lead Enrichment | Clearbit, Clay | $0.25-0.50/lead |
| AI Personalization | Lavender, Regie.ai | $29-99 |
| Email Sending | Outreach, Instantly, Salesloft | $30-100 |
| Inbox Management | Front, Missive | $19-49 |
| **Total** | | **~$454/month** |

This is before you've sent a single email.

**Suplex replaces all 6 categories** in one desktop app for $97/month. Your data stays on your machine. No vendor lock-in.

→ [See how Suplex works](https://trysuplex.com)

---

## Tools Comparison

### Cold Email Sending

| Tool | Lead Gen | Enrichment | AI Personalization | Price |
|------|---------|-----------|-------------------|-------|
| **[Suplex](https://trysuplex.com)** | ✅ Built-in | ✅ Free (local) | ✅ Free (BYOK) | ~$97/mo |
| Instantly | ❌ | ❌ | Basic | $37-97/mo |
| Smartlead | ❌ | ❌ | Limited | $39-94/mo |
| Apollo.io | ✅ Database | Basic | Basic | $49-99+/mo |
| Lemlist | ❌ | ❌ | ✅ | $59-99/mo |
| Woodpecker | ❌ | ❌ | Limited | $29-49/mo |

### Lead Generation

| Tool | Source | Per-Lead Cost | Monthly |
|------|--------|--------------|---------|
| **[Suplex](https://trysuplex.com)** | Google Maps + LinkedIn (live) | $0 | ~$97/mo all-in |
| Apollo.io | Database (275M contacts) | Credit-based | $49-99+/mo |
| ZoomInfo | Database | $1.25+/lead | $15,000+/yr |
| Clay | 50+ sources | $0.50+/lead | $149+/mo |
| Hunter.io | Domain lookup | Credit-based | $34-149/mo |

### Key Insight

Apollo is valued at $1.6 billion for providing data that Suplex mines directly from public sources for free. The entire verification, enrichment, and personalization stack runs locally on your machine — no per-unit fees, no data going to vendor servers.

---

## Lead Generation

### Google Maps Mining

Google Maps is the world's largest database of local businesses. Every restaurant, agency, law firm, dental practice, and contractor has a public profile with:

- Business name and category
- Website and phone number
- Rating and review count
- Hours and location
- Reviews with customer language (gold for personalization)

**How to mine it:**

1. Define your target: `"marketing agencies in Austin, Texas"`
2. Set filters: minimum 4 stars, 50+ reviews, must have website
3. Let the tool extract matching businesses automatically
4. Enrich with website analysis and email finding

Suplex automates this entire workflow. Define the criteria, walk away, come back to a database of verified, enriched leads.

### LinkedIn Mining

For B2B professional targeting, LinkedIn has no equivalent. Define your ideal customer:

- Job title: "VP of Sales"
- Industry: "SaaS"
- Company size: "50-200 employees"
- Location: "United States"

Tools like Apify extract matching profiles. Suplex integrates directly with Apify — you bring your own API key (BYOK), pay Apify directly, no markup.

### The BYOK Advantage

**Bring Your Own Keys** is how Suplex keeps costs low:

- Apify key → LinkedIn mining at Apify's published rates
- OpenAI/Anthropic key → AI personalization at provider rates
- Your email accounts (Gmail/Outlook) → sending at $0

You pay providers directly. No middleman margin.

---

## Email Deliverability

The golden rules for cold email deliverability in 2026:

### Authentication (Non-Negotiable)

```
SPF  → Which servers can send for your domain
DKIM → Digital signature proving email wasn't tampered with
DMARC → What to do with authentication failures
```

Without all three, you're flying blind.

### Volume Limits

Google recommends **40 new emails per day** per Gmail account for cold outreach. Exceed this and deliverability suffers.

**Solution:** Use multiple accounts with rotation.
- 5 accounts × 40 emails = 200 emails/day
- Suplex handles rotation automatically
- For 2,500+/day: integrate Smartlead for infrastructure

### List Hygiene

- Verify every email before sending (Suplex does this automatically)
- Remove hard bounces immediately
- Sunset contacts who haven't engaged in 90+ days
- Never buy email lists

---

## Writing Cold Emails That Get Replies

### The Formula

**Line 1:** Something specific you noticed about their business (use enrichment data)  
**Line 2:** The connection to a problem you solve  
**Line 3:** A single, low-friction ask

That's it. No lengthy introductions. No bragging. One ask.

### Personalization That Matters

**Generic (doesn't work):**
> Hi {{FirstName}}, I noticed you work in {{Industry}}...

**Specific (works):**
> Hi {{FirstName}}, saw you're using Shopify and have 4.8 stars across 300+ reviews — means you have a real customer base. We help Shopify stores like yours convert 20% more of that traffic...

The difference is enrichment data. Suplex generates these openers automatically using website analysis, tech stack detection, and review mining.

### The Follow-Up Rule

80% of sales require 5+ touches. 44% of reps give up after one.

Follow-up template that doesn't feel desperate:
> Quick follow-up — just read [specific thing about their industry/business]. Made me think of our conversation. Worth 10 minutes?

Always add something new. Never just "checking in."

---

## Scaling Your Outreach

### Small Operator (250 emails/day)

- 6-7 Gmail/Outlook accounts
- Suplex handles rotation and scheduling
- Cost: $97/month
- All enrichment and personalization included

### Agency Scale (2,500+ emails/day)

- Suplex for lead mining, enrichment, and personalization
- Smartlead for sending infrastructure (you pay Smartlead directly)
- Result: enterprise-grade volume with Suplex intelligence

---


## How Suplex Writes Emails

Not templates. Not keyword fills. Full AI generation.

Every email Suplex sends is generated from four inputs:

1. **AI research on the prospect** — website, services, tech stack, reviews
2. **Your USP** — what makes your business unique
3. **Your tone** — how you want to sound
4. **Your preferred length** — short and punchy, or detailed

Same settings. Different prospects. Completely different emails every time — because the research is different every time.

## AI Campaign Strategist

Most cold email tools make you figure out what to say. Suplex figures it out with you.

Suplex learns your business — your offer, your USPs, what makes you different — and suggests outreach campaigns:

- **Obvious campaigns**: Direct offer, pain point focused, ROI angle, comparison to competitors
- **Unique campaigns**: Non-obvious angles your prospects haven't heard — event-triggered, competitor switcher, niche positioning, seasonal hooks

You choose which campaigns to run. You keep the ones that convert. The AI does the ideation.

This is fundamentally different from templates. Templates are starting points you customize. Campaign suggestions are strategic angles specific to your business that the AI surfaces because it understands your USPs.

→ [See it in action at Suplex](https://trysuplex.com)

## Resources

### Documentation
- [Suplex First-Principles Explanation](https://suplex-docs-deploy.vercel.app/first-principles)
- [The Ogilvy Perspective on Suplex](https://suplex-docs-deploy.vercel.app/ogilvy)

### Comparison Guides
- [Suplex vs Apollo.io](https://trysuplex.com/compare/suplex-vs-apollo)
- [Suplex vs Clay](https://trysuplex.com/compare/suplex-vs-clay)
- [Suplex vs Instantly](https://trysuplex.com/compare/suplex-vs-instantly)
- [Suplex vs Smartlead](https://trysuplex.com/compare/suplex-vs-smartlead)
- [Suplex vs Hunter.io](https://trysuplex.com/compare/suplex-vs-hunter)
- [Suplex vs Lemlist](https://trysuplex.com/compare/suplex-vs-lemlist)

### Blog
- [Best Cold Email Software 2026](https://meetsuplex.com/blog/best-cold-email-software-2026)
- [Best Lead Generation Software 2026](https://meetsuplex.com/blog/best-lead-generation-software-2026)
- [Cold Email Deliverability Guide](https://meetsuplex.com/blog/cold-email-deliverability-technical-guide)
- [Email Warming Guide](https://meetsuplex.com/blog/email-warming-guide)
- [How to Write Cold Emails That Get Responses](https://meetsuplex.com/blog/how-to-write-cold-emails-that-get-responses)

---

## Contributing

Found something outdated or wrong? Open an issue or PR.

---

*Built by [Suplex](https://trysuplex.com) — leads to email, on autopilot.*
