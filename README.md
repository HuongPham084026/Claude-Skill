# Claude Skill — Affiliate AI Skill Library

A 50-skill Claude Agent Skills library for building and scaling an affiliate-marketing business with AI — from niche research to offer design, content production, distribution, and analytics.

Adapted and repackaged from the open-source [Affitor/affiliate-skills](https://github.com/Affitor/affiliate-skills) collection (MIT License) into standalone [Claude Skill](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview) format — each skill is a self-contained folder with a `SKILL.md` file (YAML frontmatter + workflow instructions) that Claude can upload and auto-invoke.

## How to use

1. Zip an individual skill folder (the folder itself must be the zip root, containing `SKILL.md`).
2. In Claude, go to **Customize → Skills → "+" → "+ Create skill" → "Upload a skill"** and select the zip.
3. Repeat for whichever skills you need — you don't have to install all 50 at once. Start with `skill-finder` (S8) to get guided recommendations for the rest based on your goal.

## Skill Index (50 skills across 8 stages)

### S1 · Research & Discovery

| Skill | What it does |
|---|---|
| [`affiliate-program-search`](./affiliate-program-search) | Search and evaluate affiliate programs by niche, commission structure, and cookie duration, then score each candidate across earning potential, content potential, market demand, competition, and trust. |
| [`commission-calculator`](./commission-calculator) | Project realistic monthly and year-one affiliate earnings from traffic estimates, platform-specific conversion benchmarks, and a program's commission structure. |
| [`competitor-spy`](./competitor-spy) | Analyze competitor affiliate sites, YouTube channels, and social profiles to reverse-engineer which programs they promote, what content drives their traffic, and which content gaps you can exploit. |
| [`content-angle-ranker`](./content-angle-ranker) | Generate 8-12 concrete content angle candidates and score them on platform fit, competition level, predicted engagement, and creator fit to pick the strongest one data-first instead of by gut feeling. |
| [`monopoly-niche-finder`](./monopoly-niche-finder) | Find intersection niches where the user can become the dominant authority by combining two unrelated domains of expertise, applying the "competition is for losers" principle to escape saturated markets. |
| [`niche-opportunity-finder`](./niche-opportunity-finder) | Analyze search demand, competition, and affiliate program availability to find untapped, high-opportunity affiliate niches with a data-backed scoring model. |
| [`purple-cow-audit`](./purple-cow-audit) | Score a product's remarkability 1-10 across seven weighted dimensions before deciding whether to promote it, using Seth Godin's "Purple Cow" test — would you recommend this to a friend without earning a commission. |
| [`traffic-analyzer`](./traffic-analyzer) | Evaluate website traffic health, engagement metrics, and traffic-source mix for one or more domains, producing a 0-100 score and verdict for affiliate promotion, competitor analysis, or advertiser evaluation. |
| [`trending-content-scout`](./trending-content-scout) | Analyze top-performing content across YouTube, TikTok, X, and Reddit for a niche to surface winning formats, hooks, durations, and creators before writing anything new. |

### S2 · Content Creation

| Skill | What it does |
|---|---|
| [`content-pillar-atomizer`](./content-pillar-atomizer) | Turn one long-form piece (blog post, article, or review) into 15-30 platform-native micro-content pieces for Twitter/X, LinkedIn, Reddit, TikTok, and email — re-contextualized for each platform's culture, not just reformatted. |
| [`infographic-generator`](./infographic-generator) | Generate a complete branded infographic specification — layout, copy, data, and color scheme — from any content, stat, or comparison, ready to render as HTML/CSS or in a design tool. |
| [`reddit-post-writer`](./reddit-post-writer) | Write Reddit posts and comments that recommend an affiliate product the way a real Redditor would — leading with genuine value and only mentioning the product after trust is established — so they earn upvotes instead of getting flagged as spam or banned. |
| [`tiktok-script-writer`](./tiktok-script-writer) | Write structured 30-60 second video scripts for TikTok, Instagram Reels, and YouTube Shorts that hook viewers in the first 3 seconds, demo the product naturally, and drive affiliate/product link clicks. |
| [`twitter-thread-writer`](./twitter-thread-writer) | Write research-backed X/Twitter threads that hook readers on tweet 1, deliver real value across the body, and drive clicks to a product or affiliate link without feeling like an ad. |
| [`viral-post-writer`](./viral-post-writer) | Write high-converting, platform-native social media posts (LinkedIn, X, Reddit, Facebook) that promote an affiliate product through story or opinion rather than a direct pitch. |

### S3 · Blog & SEO

| Skill | What it does |
|---|---|
| [`content-decay-detector`](./content-decay-detector) | Audit existing blog content for ranking drops, outdated information, and competitor freshness gaps, then produce a prioritized refresh queue. Use for monthly content maintenance, when traffic is declining on specific pages, or when the user asks which articles need updating — refreshing decaying content is typically the highest-ROI SEO activity available. |
| [`content-moat-calculator`](./content-moat-calculator) | Estimate how many pages of content are needed to build topical authority in a niche, by benchmarking against top-ranking competitors, and deliver a go/no-go feasibility verdict before months of writing effort are committed. |
| [`how-to-tutorial-writer`](./how-to-tutorial-writer) | Write step-by-step how-to tutorial blog posts that solve a real reader problem and naturally recommend an affiliate product as the tool for the job, using a "problem to solution to tool" structure. |
| [`keyword-cluster-architect`](./keyword-cluster-architect) | Map 50-200+ keywords into topical clusters by search intent, then build a hub-and-spoke content roadmap for SEO topical authority. |
| [`listicle-generator`](./listicle-generator) | Write "Top N Best [Category]" roundup articles for affiliate marketing, with SEO-optimized structure, mini-reviews per product (features, pricing, pros/cons), comparison tables, and CTAs. |

### S4 · Offer & Landing Pages

| Skill | What it does |
|---|---|
| [`bonus-stack-builder`](./bonus-stack-builder) | Designs an exclusive stack of bonuses that make one specific affiliate link the obvious choice, since the underlying product is identical no matter whose link a buyer uses. |
| [`guarantee-generator`](./guarantee-generator) | Crafts a personal risk-reversal guarantee that sits on top of an affiliate product's own refund policy, addressing "what if it doesn't work for me" objections that stop buyers from clicking. |
| [`landing-page-creator`](./landing-page-creator) | Builds a single self-contained HTML landing page (no build step, no dependencies) that promotes one affiliate product, either as a solo product spotlight or a multi-product comparison/"vs" page. |
| [`product-showcase-page`](./product-showcase-page) | Builds a long-form, deep-dive single-product showcase page (self-contained HTML) with feature breakdowns, use-case walkthroughs, pricing comparisons, testimonials, and an FAQ accordion, aimed at warm traffic that needs more convincing than a short landing page provides. |
| [`squeeze-page-builder`](./squeeze-page-builder) | Builds a single self-contained HTML email-capture (squeeze) page that trades a free lead magnet for the visitor's email, then redirects to an affiliate offer on submission. |
| [`value-ladder-architect`](./value-ladder-architect) | Maps the full free-to-premium customer ascension journey for an affiliate promotion — free content, a low-cost tripwire, the core affiliate product, and an upsell — specifying which page or email builds each rung and how visitors move between them. |
| [`webinar-registration-page`](./webinar-registration-page) | Builds a self-contained HTML webinar or live-event registration page with a live JavaScript countdown timer, speaker bio, agenda, and an email-capture form, designed to feed a "free training" funnel that promotes an affiliate product during the event itself. |

### S5 · Distribution & Deployment

| Skill | What it does |
|---|---|
| [`bio-link-deployer`](./bio-link-deployer) | Generate a self-contained, single-file "link in bio" hub page (Linktree-style) that aggregates affiliate links, blog posts, landing pages, and social profiles into one mobile-first HTML page with theme options. |
| [`email-drip-sequence`](./email-drip-sequence) | Write a 5-7 email drip sequence that nurtures a subscriber list from cold to buyer for a specific affiliate product, following a value-first Welcome-Value-Soft Sell-Hard Sell-Objection-Follow Up arc. |
| [`github-pages-deployer`](./github-pages-deployer) | Generate a complete, ready-to-deploy GitHub Pages setup (repo structure, CI/CD workflow, custom domain/SSL config) for a landing page, bio-link hub, or blog. |
| [`social-media-scheduler`](./social-media-scheduler) | Generate a 30-day social media content calendar for affiliate promotion across platforms like LinkedIn, X, Facebook, and Reddit, mixing educational, engagement, and promotional posts on an 80/20 value-to-pitch ratio with an escalating weekly promotional arc. |

### S6 · Analytics & Optimization

| Skill | What it does |
|---|---|
| [`ab-test-generator`](./ab-test-generator) | Generate A/B test variants for affiliate content — headlines, CTAs, landing page sections, email subject lines, and social hooks — each paired with a copywriting-grounded hypothesis and a test plan (sample size, duration, winner criteria). |
| [`conversion-tracker`](./conversion-tracker) | Design a UTM tagging scheme and lightweight tracking setup so every piece of content and traffic source can be measured for clicks and conversions, then read the resulting data to identify what's actually working. |
| [`internal-linking-optimizer`](./internal-linking-optimizer) | Audit a site's internal link architecture using hub-and-spoke SEO methodology — finds orphan pages, weak hub-to-spoke connections, and missing contextual links, then outputs specific linking instructions (source, target, anchor text, placement, priority). |
| [`performance-report`](./performance-report) | Turn raw affiliate program data (clicks, conversions, revenue) into a weekly/monthly performance report with KPI calculations (EPC, conversion rate, ROAS), a Star/Cash Cow/Question Mark/Dog ranking of programs, trend analysis, and prioritized recommendations. |
| [`seo-audit`](./seo-audit) | Audit an affiliate blog post or landing page across on-page SEO dimensions — structure, keyword usage, meta tags, E-E-A-T signals, affiliate-link compliance (rel=nofollow sponsored, FTC disclosure), and internal linking — producing a 0-100 scorecard and a prioritized fix-it checklist. |

### S7 · Automation & Scale

| Skill | What it does |
|---|---|
| [`content-repurposer`](./content-repurposer) | Turn one piece of affiliate content (blog post, landing page, video script, social post) into multiple platform-native formats — tweet threads, LinkedIn posts, TikTok scripts, newsletters, Reddit posts, emails, Pinterest pins — each respecting that platform's length limits, tone, and disclosure rules. |
| [`email-automation-builder`](./email-automation-builder) | Design multi-sequence email automations with branching if/then logic (opened, clicked, purchased, inactive) instead of a flat drip — covering welcome flows, nurture flows, win-back flows, and cart-abandonment flows, with platform-specific setup steps. |
| [`multi-program-manager`](./multi-program-manager) | Manage and compare multiple affiliate programs as an investment portfolio — computing EPC and revenue share per program, flagging concentration risk, and producing double-down/maintain/optimize/phase-out recommendations plus a weekly time-allocation plan. |
| [`paid-ad-copy-writer`](./paid-ad-copy-writer) | Generate compliant, platform-formatted paid ad copy (Facebook, Google Search/Display, TikTok, Pinterest) for affiliate offers — 3-5 variants per platform testing different angles (pain point, benefit, social proof, curiosity, urgency), routed through a bridge landing page since most ad platforms ban direct affiliate links. |
| [`proprietary-data-generator`](./proprietary-data-generator) | Design and automate the collection of original surveys, benchmark studies, or aggregated datasets that don't exist yet in a niche, so the resulting content becomes a moat competitors can't copy. |

### S8 · Meta

| Skill | What it does |
|---|---|
| [`category-designer`](./category-designer) | Help an affiliate escape a crowded, price-competitive niche by designing a new "category" — a fresh buying frame with its own name, point of view, and evaluation criteria — instead of competing head-on inside an existing one. |
| [`compliance-checker`](./compliance-checker) | Audit affiliate/marketing content (blog posts, social posts, video scripts, landing pages, emails) for FTC-style disclosure compliance, checking placement, clarity, and platform-specific requirements before publishing. Use before publishing any affiliate content, or when the user asks if their content is compliant. |
| [`self-improver`](./self-improver) | Run a structured retrospective on affiliate campaign results — diagnose why content, offers, or funnels underperformed using offer-market fit, traffic-content match, and funnel-leak analysis — then produce a prioritized, measurable improvement plan. |
| [`skill-finder`](./skill-finder) | Help the user pick the right skill(s) from this 50-skill affiliate-marketing library — across S1 Research, S2 Content, S3 Blog/SEO, S4 Offer/Landing, S5 Distribution, S6 Analytics, S7 Automation, and S8 Meta — based on a plain-language goal. |

## Attribution & License

Original skill concepts and workflows adapted from [Affitor/affiliate-skills](https://github.com/Affitor/affiliate-skills) (MIT License, © Affitor). Each `SKILL.md` in this repository has been independently rewritten/condensed to fit the Claude Skill format while preserving the source's process and intent; each file carries its own `source` frontmatter field and an `## Attribution` section.

This repository is shared for personal/portfolio use. If you reuse or redistribute it, please keep the attribution above per the MIT License terms of the original collection.

