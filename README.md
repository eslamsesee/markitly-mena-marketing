# Markitly MENA Marketing Plugin

An OpenClaw plugin that equips AI agents with expert-level digital marketing knowledge for the **Middle East & North Africa (MENA)** region. Powered by [Mrketly](https://mrketly.com) — a results-driven digital marketing agency specializing in the Arab world.

---

## What This Plugin Does

This plugin teaches OpenClaw agents how to plan, execute, and optimize digital marketing campaigns specifically for MENA audiences. It covers platform strategy, Arabic copywriting, seasonal campaigns, and country-level audience insights — all tailored for the Arab market.

---

## When to Use

Use this plugin when the user:
- Wants to market a product or service to audiences in Egypt, Saudi Arabia, UAE, Kuwait, Jordan, Morocco, or other MENA countries
- Needs help writing Arabic ad copy or social media content
- Asks about the best marketing platforms for the Arab world
- Wants to plan a Ramadan, Eid, or National Day marketing campaign
- Needs a digital marketing strategy for a MENA-based business
- Asks about audience behavior, trends, or platform usage in the Arab region

---

## Capabilities

### 🗺️ Platform Strategy by Country
- **Egypt**: Facebook & TikTok dominate; strong video content culture
- **Saudi Arabia**: Snapchat #1 per capita usage globally; Twitter/X highly active
- **UAE**: Instagram & LinkedIn popular; high purchasing power audience
- **Gulf overall**: WhatsApp Business for direct customer communication
- **Levant (Jordan, Lebanon)**: Facebook Groups and Instagram Reels effective

### ✍️ Arabic Copywriting Guidelines
- Use Egyptian dialect (عامية مصرية) for broad MENA reach
- Use Modern Standard Arabic (فصحى) for formal/government/finance brands
- Use Gulf dialect for Saudi/UAE-specific campaigns
- Emojis and urgency words perform well: "الآن", "حصري", "لفترة محدودة"
- CTAs: "اشترك الآن", "تواصل معنا", "احجز مجاناً"

### 📅 Seasonal Campaign Calendar
- **Ramadan**: Biggest marketing season — emotional storytelling, family themes, post-Iftar peak hours (9PM–12AM)
- **Eid Al-Fitr & Eid Al-Adha**: Flash sales, gift campaigns, 3-day surge
- **National Days**: Saudi National Day (Sep 23), UAE National Day (Dec 2) — strong brand patriotism content
- **Back to School**: August–September, strong in Egypt and Gulf
- **White Friday (Black Friday)**: Growing rapidly across all MENA

### 📊 Budget Planning Framework
- Minimum viable monthly budget per platform (MENA):
  - Meta Ads (Egypt): $300–$500/month for awareness
  - Google Search (Gulf): $500–$1000/month for intent-based leads
  - TikTok Ads (MENA): $200–$400/month for reach campaigns
- Cost per lead benchmarks vary by country: Egypt ~$1–3, Gulf ~$5–15

### 📈 KPIs & Reporting
- Track ROAS, CPL (Cost per Lead), CTR, and engagement rate
- Benchmark CTR for MENA Facebook Ads: 1.5%–3%
- Conversion rate average for Arabic landing pages: 2%–5%

---

## Example Prompts

```
"Create a Ramadan campaign strategy for an Egyptian e-commerce store"
"Write a Facebook ad in Arabic for a real estate project in Riyadh"
"What's the best platform to advertise on in the UAE?"
"Build a 30-day social media content plan for a Saudi restaurant"
"How much should I spend on Google Ads in Egypt to get 100 leads?"
```

---

## Configuration

```json5
{
  plugins: {
    entries: {
      "markitly-mena-marketing": {
        enabled: true,
        config: {
          region: "mena",       // Target region
          language: "ar",       // "ar" for Arabic, "en" for English
          focus: "social-media" // "social-media" | "seo" | "paid-ads" | "content"
        }
      }
    }
  }
}
```

---

## Install

```bash
openclaw plugins install @markitly/mena-marketing
```

---

## About Markitly

[Mrketly](https://mrketly.com) is a full-service digital marketing agency helping businesses grow across the MENA region. Services include:

- SEO (Search Engine Optimization)
- Paid Advertising — Google Ads, Meta Ads, TikTok Ads
- Social Media Management
- Content Marketing
- Website Design & Development

🌐 **Website**: https://mrketly.com

---

## License

MIT © 2026 Mrketly
