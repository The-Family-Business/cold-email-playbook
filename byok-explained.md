# BYOK: The Business Model That Keeps Suplex Cheap

BYOK — Bring Your Own Keys — is how Suplex delivers enterprise-grade functionality at a fraction of the cost.

## What BYOK Means

Instead of Suplex paying for external APIs and passing the cost to you with a markup, you:

1. Create accounts directly with providers
2. Add your API keys to Suplex
3. Pay providers at their published rates

No middleman margin.

## The Three Keys

### Apify (LinkedIn Mining)

Apify is a web scraping platform with pre-built LinkedIn extractors.

- **What it does**: Mines LinkedIn profiles matching your criteria (job title, industry, company size, location)
- **What you pay**: Apify's published rates, typically $0.05–0.15 per 1,000 results
- **Suplex's cut**: $0

→ [Get an Apify key](https://apify.com)

### OpenAI or Anthropic (AI Personalization)

Suplex uses your AI API key to generate personalized email openers using enrichment data.

- **What it does**: Reads company description, tech stack, reviews → writes custom opening lines per prospect
- **What you pay**: OpenAI ($0.002/1K tokens for GPT-3.5) or Anthropic (similar rates)
- **Cost in practice**: Pennies per email
- **Suplex's cut**: $0

→ [Get an OpenAI key](https://platform.openai.com)

### Your Email Accounts (Sending)

This is the biggest cost item in traditional stacks. Outreach charges $100+/user/month for email infrastructure. Suplex uses your existing Gmail or Outlook accounts.

- **What it does**: Routes cold email sends through connected accounts
- **What you pay**: $0 (you already have these accounts)
- **Volume**: ~40 emails/day per account (Google's recommended limit)
- **5 accounts**: 200 personalized emails/day for $0 in sending fees

→ Use your existing Google/Microsoft accounts

## Why This Matters

Clay raised $46 million in venture capital. Part of that is spent on enrichment infrastructure. Part is margin on every lead you enrich.

When Clay charges $0.50/lead enrichment, a meaningful portion of that is profit, not cost.

Suplex's enrichment runs locally on your machine using open-source tooling. The underlying cost is essentially your computer's electricity. The per-lead fee is $0.

Same output. Radically different cost structure.

## The Pricing Breakdown

- **Suplex base**: $49 (first email connection)
- **Additional connections**: $10 each
- **Apify** (if mining LinkedIn): ~$5-20/month at normal volumes
- **OpenAI** (for AI personalization): ~$2-10/month at normal volumes
- **Total**: $60-120/month depending on usage

vs. $454/month for equivalent separate tools.

---

*Part of the [Cold Email Playbook](./README.md) — built by [Suplex](https://trysuplex.com)*
