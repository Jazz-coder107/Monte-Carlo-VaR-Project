# What Real Projects Pay: AI-Deliverable Services for a Solo Operator (2026)

Research date: 2026-08-11. Researcher: pricing/GTM research agent.

## CRITICAL METHOD NOTE — evidence provenance

**The research environment's egress proxy blocked ALL WebFetch requests** (every domain tested — upwork.com, fiverr.com, zapier.com, reddit.com, wikipedia.org, jina.ai reader — returned EGRESS_BLOCKED; curl through the proxy got 403 on CONNECT for every host). **No source below was opened directly.** All evidence comes from WebSearch result snippets and search-engine summaries of the named pages, triangulated across multiple independent queries. Per the evidence contract this caps origin quality: origin for every finding is "WebSearch snippet of the cited URL (page not opened)". Confidence is capped at **probable** even where figures corroborate across 3+ independent sources; treat exact numbers as directionally reliable, not verified. URLs are provided so the figures can be re-verified from an unrestricted network.

Tier definitions used:
- **T1** — platform primary data (Upwork/Fiverr official rate & cost pages, Upwork investor press releases)
- **T2** — named practitioner/vendor pricing you could buy at (consultant pricing pages, reseller platform pricing)
- **T3** — SEO content-marketing cost guides by agencies/tool vendors (directionally useful, incentive to inflate agency prices)
- **T4** — guru/course-seller claims and aggregated Reddit summaries (flagged for bias)

---

## 1. Workflow automation (n8n / Make / Zapier)

**F1.1 — Upwork hourly band for n8n experts: ~$40–$100/hr.**
- Evidence: "The cost of hiring a freelance n8n expert generally ranges from $40 to $100 per hour."
- Source: https://www.upwork.com/hire/n8n-experts/ (Aug 2026 page)
- Tier: T1 | Origin: WebSearch snippet (page not opened) | Confidence: probable

**F1.2 — Zapier/Make consultant rates: beginners $20–40/hr, intermediate $40–80, experts $80–200+, senior independents up to $300/hr; advisory floor ~$150/hr for established consultants.**
- Evidence: "beginner Zapier developers charge $20-$40/hour, intermediate $40-$80/hour, and experts $80-$200+/hour"; "Established consultants often set a floor around $150/hour for advisory work."
- Sources: https://golmtech.solutions/blog/how-much-does-a-zapier-consultant-cost/ ; https://www.hireoverseas.com/blogs/hire-a-zapier-expert (2026)
- Tier: T3 | Origin: WebSearch snippets | Confidence: probable (corroborated by F1.4)

**F1.3 — Typical project fees: simple automations $300–$1,000; custom API integrations $1,000–$3,000; multi-workflow builds from ~$5,000.**
- Evidence: "Simple automations run $300-$1,000, custom API integrations $1,000-$3,000, and enterprise-scale, multi-workflow projects start around $5,000."
- Source: https://golmtech.solutions/blog/how-much-does-a-zapier-consultant-cost/ (2026)
- Tier: T3 | Origin: WebSearch snippet | Confidence: probable

**F1.4 — Real named consultant pricing page (Chris Wray, certified Pipedrive/Google Cloud partner): $150 one-hour discovery session; typical 6-week automation programme $2,500–$3,500; tiered offers $3,800 (Systems Diagnostic) / $7,500 (Operations Blueprint) / $15,000 (Full Business OS). No ad-hoc hourly work.**
- Evidence: "Zapier consulting starts at $150 for an hour"; "on average clients invest between $2500 and $3500 for a 6 week programme"; tiers "$3,800 / $7,500 / $15,000".
- Source: https://cjwray.com/zapier-consultant-prices/ and https://cjwray.com/business-automation-consultant-services/ (live pricing pages, 2026)
- Tier: T2 (best-quality pricing evidence found — an actual practitioner rate card) | Origin: WebSearch snippet | Confidence: probable

**F1.5 — Marketplace floor is much lower: Freelancer.com n8n project postings at $30–$250, €250–€750, and $10–20/hr; Fiverr n8n gigs exist at low three figures.**
- Evidence: "Workflow consulting and automation projects range from $30-250 USD... €250-750 EUR... $10-20 USD/hour."
- Source: https://www.freelancer.com/projects/n8n/workflow-automation-specialist and sibling listings (Aug 2026)
- Tier: T1 (real postings) | Origin: WebSearch snippet | Confidence: probable
- Implication: open-marketplace bidding is a race to the bottom; the $1.5k–$5k band comes from direct/positioned sales, not job-board bids.

**F1.6 — Guided pricing for new n8n freelancers: charge ~$500–$3,000 per project; ~$1,500 as anchor; realistic month-2 target $1,500–$3,000 from 2–3 projects.**
- Source: https://learnforge.dev/blog/n8n-freelance-automation/ (2026)
- Tier: T4 (content site adjacent to selling training — course-seller bias flagged) | Origin: WebSearch snippet | Confidence: thin as a market fact, probable as common practitioner guidance

## 2. Chatbots / RAG knowledge-base builds

**F2.1 — Fiverr platform cost-guide averages (closest thing to real transaction data found): AI chatbot development ≈ $216–$520 avg fixed price; AI agents ≈ $295; custom GPT apps ≈ $341; AI integrations ≈ $298; hourly $47–$270 for chatbot specialists; AI agents specialists $15–$175/hr.**
- Evidence: "AI chatbot development projects typically command fixed prices around $216... AI agents development services average approximately $295... Custom GPT applications... approximately $341... AI integrations cost around $298 on average." (One Fiverr guide states chatbot average $520.)
- Sources: https://www.fiverr.com/resources/guides/costs/chatbot-developer ; https://www.fiverr.com/resources/guides/costs/ai-automation-experts ; https://www.fiverr.com/resources/costs/ai-development (2026)
- Tier: T1 | Origin: WebSearch snippets | Confidence: probable
- Implication: commodity marketplace price for "a chatbot" is a few hundred dollars. Differentiation/integration is what moves it to four figures.

**F2.2 — Freelance-scale RAG builds: basic RAG on a small doc set $4,000–$10,000; intermediate pipeline $8,000–$18,000; enterprise $15,000–$40,000+. Freelance chatbot dev rates $40–$200/hr.**
- Evidence: "a basic RAG setup that connects to a small set of documents... costs $4,000 to $10,000; an intermediate RAG pipeline... $8,000 to $18,000."
- Sources: https://denser.ai/blog/how-much-chatbot-cost/ ; https://www.biztoolkit.co/post/freelance-chatbot-developer-rates-in-2026-ai-pricing ; https://www.metageeks.tech/insights/chatbot-developer-cost (2026)
- Tier: T3 | Origin: WebSearch snippets | Confidence: probable (three independent guides converge)

**F2.3 — Agency-scale RAG is an order of magnitude higher: internal knowledge assistants $30k–$80k; complex RAG+CRM builds $30k–$45k (8–12 wks); "median mid-complexity" $75k–$120k; permissioned enterprise RAG $80k–$180k. US agency blended rates $150–$350/hr; Eastern Europe $80–$150/hr. Ongoing API/hosting $300–$2,000/mo.**
- Sources: https://www.kellton.com/kellton-tech-blog/custom-ai-chatbot-development-llm-rag ; https://sfailabs.com/guides/rag-development-costs-breakdown ; https://www.raftlabs.com/blog/chatbot-development-cost (2026)
- Tier: T3 (agencies quoting their own market — inflation incentive) | Origin: WebSearch snippets | Confidence: probable for direction, contested on absolute levels
- Implication: enormous spread between Fiverr ($300) and agency ($80k) for nominally the same artifact — pricing is positioning-dominated.

**F2.4 — Fiverr RAG-specific gigs: $300 basic to $1,200+ custom.**
- Source: https://denser.ai/blog/how-much-chatbot-cost/ (citing Fiverr listings, 2026)
- Tier: T3 relaying T1 | Origin: WebSearch snippet | Confidence: probable

## 3. AI integration work (Claude/GPT APIs into existing tools)

**F3.1 — Upwork published rates, AI engineers: typical $35–$60/hr, median $50/hr; full observed spread $25–$100+/hr; entry $30–50, intermediate $50–75, expert $75–100+.**
- Evidence: "Hourly rates for Artificial Intelligence Engineers on Upwork typically range between $35 and $60, with the median... at $50."
- Source: https://www.upwork.com/hire/artificial-intelligence-engineers/cost/ (2026)
- Tier: T1 | Origin: WebSearch snippet (upwork.com egress-blocked; could not open) | Confidence: probable

**F3.2 — Upwork ML engineers median higher: ~$100/hr ($50–$200). AI developer pages: $30–$150/hr; AI automation specialists listed $35–$150/hr.**
- Sources: https://www.upwork.com/hire/machine-learning-experts/cost/ ; https://www.upwork.com/hire/ai-developers/ ; https://www.upwatcher.io/guides/upwork-ai-jobs-2026/ (2026)
- Tier: T1/T3 mix | Origin: WebSearch snippets | Confidence: probable

**F3.3 — Upwork platform data (investor PR, Feb 2026 + Future Workforce Index Jul 2026): AI integration skill demand +178% YoY; AI chatbot development +71%; AI-related work >$300M annualized GSV in Q4 2025, +50% YoY; freelancers doing AI work earn 34% more per hour; BUT gen-AI per-contract earnings declined 13% as contract volume grew 90%.**
- Evidence: "AI integration (+178%)... AI chatbot development (+71%)"; "AI-related work alone surpassed $300 million on an annualized basis in Q4 2025"; "freelancers performing AI-related work on Upwork earn 34% more per hour"; "generative AI and creative production contracts grew 90% year-over-year as per-contract earnings declined 13%."
- Sources: https://investors.upwork.com/news-releases/news-release-details/upworks-demand-skills-2026-demand-top-ai-skills-more-doubles-ai (2026-02-04) ; https://www.globenewswire.com/news-release/2026/07/14/3326964/0/en/Upwork-s-Future-Workforce-Index-2026-How-AI-is-Redefining-the-Value-of-Work-as-Skilled-Freelancing-Accelerates.html (2026-07-14)
- Tier: T1 | Origin: WebSearch snippets of press releases | Confidence: probable (specific figures consistent across multiple syndications)
- Implication: demand is real and paying a premium, but average ticket size in commodity gen-AI work is FALLING — volume up, price per contract down.

**F3.4 — AI consultant rates (multiple 2026 guides converge): independent freelancers $75–$150/hr with 1–3 yrs experience; experienced solo consultants $93–$160/hr market average; solo experts $80–$200; boutique $150–$300; Big-4 $300–$600. Rates up 10–15%/yr since 2024.**
- Sources: https://golance.com/hiring/best-freelance-ai-consultants-hourly-rate ; https://nicolalazzari.ai/guides/ai-consultant-pricing-us ; https://rockstardeveloperuniversity.com/ai-consultant-hourly-rate/ ; https://aidolsgroup.com/en/blog/category/research-report/ai-consulting-cost-guide/ (2026)
- Tier: T3 | Origin: WebSearch snippets | Confidence: probable

## 4. Document / data extraction pipelines

**F4.1 — Custom IDP build costs: simple cloud-service pattern projects from ~$7,500; single-format invoice extractor $10k–$25k; custom pipelines integrated into internal systems $25k–$120k; contract intelligence $50k–$200k. Overall $5k–$125k+ at ~$50/hr average AI dev rates.**
- Evidence: "A single-format invoice extractor ships for ten to twenty-five thousand"; "Custom-built IDP pipelines... usually $25,000 to $120,000."
- Sources: https://www.businesswaretech.com/blog/how-much-does-ai-document-processing-system-development-cost ; https://imagetotable.ai/blog/build-vs-buy-document-extraction (2026)
- Tier: T3 | Origin: WebSearch snippets | Confidence: probable

**F4.2 — The solo-operator opening is integration + exception handling, not extraction: SaaS extraction is nearly free ($19–$59/mo tools; Parsio from $41/mo; Azure Read API $1.50/1,000 pages) — the paid work is wiring output into CRM/accounting and building human-in-the-loop exception flows.**
- Evidence: "The extraction itself is often the easy part. Getting extracted data to land correctly in your accounting system, ATS, or CRM... is usually where budget and timeline actually go."
- Sources: https://imagetotable.ai/blog/document-extraction-pricing-small-teams-2026 ; https://zerentry.com/blog/invoice-ocr-freelancers-small-business (2026)
- Tier: T3 | Origin: WebSearch snippets | Confidence: probable
- ROI anchor for sales: manual invoice processing costs $12.42–$40/invoice vs ~$2.65 automated (Brex figure) — https://www.brex.com/spend-trends/cash-flow-management/ocr-invoice-processing

## 5. Voice AI agents (Vapi / Retell reseller economics)

**F5.1 — Platform COGS: Vapi $0.05/min hosting + pass-through provider costs, realistically $0.10–$0.33/min all-in; Retell base $0.055–$0.07/min, $0.07–$0.31 all-in depending on voice/model.**
- Sources: https://www.cekura.ai/blogs/vapi-ai-pricing ; https://www.cekura.ai/blogs/retell-ai-pricing-per-minute ; https://www.cloudtalk.io/blog/vapi-ai-pricing/ (2026)
- Tier: T3 (testing-tool vendor summarizing platform pricing) | Origin: WebSearch snippets | Confidence: probable

**F5.2 — What agencies charge clients: resold per-minute rates $0.50–$2.00/min (vs. $0.07–$0.33 cost); typical deal structure = one-time setup/build fee $500–$3,000 (simple) up to $2,000–$25,000 (complex), plus monthly retainer $300–$1,500 (small) or $800–$3,500 (voice-specific agency work); bundled plans include 500–2,000 minutes with $0.05–$0.15/min overage.**
- Evidence: "clients often pay $0.50-$2.00/min when resold by agencies"; "monthly retainer of $800–$3,500/month... one-time setup/build fee of $2,000–$25,000+"; "typically charge a flat monthly retainer that includes... 500 to 2,000 minutes."
- Sources: https://medium.com/convocore/how-to-price-ai-voice-agent-services-real-agency-models-a233aa1a849d ; https://www.cekura.ai/blogs/how-to-price-ai-voice-agents ; https://rajsuyash.com/blog/ai-voice-agent-pricing-cost-2026.html (2026)
- Tier: T3 | Origin: WebSearch snippets | Confidence: probable (multiple independent sources; wide ranges reflect real variance)

**F5.3 — Vertical reseller math (dental): practices pay $250–$1,200/mo for AI receptionists; reseller platform example (Trillet agency plan) $299/mo flat for unlimited sub-accounts → 10 clients × $397/mo = $3,970 MRR against $299 platform cost + usage; claimed agency margins 50–70%. Named reseller packages: $399/mo CORE, $699/mo PRO (Jirexus). White-label wrappers from $29/mo (VoiceAIWrapper, over Vapi/Retell/ElevenLabs, billed via own Stripe).**
- Sources: https://trillet.ai/blogs/voice-agent-for-dental-practices-reseller ; https://www.dentivoice.ai/blogs/finance/ai-dental-receptionist-cost-2026-pricing-guide ; https://voiceaiwrapper.com/ (2026)
- Tier: T2/T3 (vendor pricing, but vendors selling the reseller dream — bias flagged) | Origin: WebSearch snippets | Confidence: probable on prices, thin on achievable client counts

**F5.4 — Freelance-marketplace floor: Fiverr voice-agent builds (Vapi/Retell/Synthflow) start ~$400.**
- Source: Fiverr gig listings via https://ciela.ai/blogs/is-starting-an-ai-automation-agency-worth-it-reddit and block.fiverr.com gig indexes (2026)
- Tier: T1 (listings) relayed | Origin: WebSearch snippet | Confidence: probable

## 6. Productized services & retainers

**F6.1 — Standard AI-automation agency deal shape: setup/build fee $2,500–$15,000 + monthly retainer $1,500–$5,000; maintenance-only retainers $500–$3,000/mo; tiered packaging = quick-win build $500–$1,500 one-time → department automation $1,500–$5,000/mo → full ops stack $5,000–$20,000/mo.**
- Evidence: "Agencies charge a setup fee (roughly $2,500 to $15,000 per build) plus a monthly retainer ($1,500 to $5,000)"; documented case: "$14,000 project fee with a $900 monthly retainer."
- Sources: https://arsum.com/blog/posts/ai-automation-agency-pricing/ ; https://taskip.net/ai-automation-agency-pricing/ ; https://buldrr.com/n8n-automation-agency-pricing/ (2026)
- Tier: T3 | Origin: WebSearch snippets | Confidence: probable

**F6.2 — Productized flat-fee models cluster at $99–$500/mo for simple automation subscriptions, with $497/mo a common anchor; small-business AI retainers start ~$500/mo; claimed 30–40% margin improvement from productizing vs. custom work.**
- Sources: https://flexxable.com/how-to-charge-clients-for-ai-services-pricing-models-for-ai-automation-agencies/ ; https://hummingagent.ai/blog/ai-automation-cost-pricing-guide-2026 ; https://taskip.net/productized-services-how-to/ (2026)
- Tier: T3/T4 (Flexxable sells agency training) | Origin: WebSearch snippets | Confidence: probable on price points, thin on margin claim

**F6.3 — Support-triage vertical example: build $3,000–$8,000 + $1,000–$2,000/mo retainer.**
- Source: https://learnforge.dev/blog/n8n-automation-agency/ (2026)
- Tier: T4 (training-adjacent) | Origin: WebSearch snippet | Confidence: thin

## 7. Proven entry paths & practitioner evidence

**F7.1 — Time-to-first-revenue by channel (converging guidance): warm/network outreach closes in days; Upwork with a complete profile → first response within ~1 week, first hire in 2–3 weeks; cold outreach 4–6 weeks (longer sales cycle). Upwork invites convert 5–10× better than cold bids; recommended cadence 3–5 quality proposals/week.**
- Sources: https://learnforge.dev/blog/n8n-freelance-automation/ ; https://learnforge.dev/blog/sell-n8n-automation-upwork/ (2026)
- Tier: T4 (training-adjacent content; no independent verification found) | Origin: WebSearch snippets | Confidence: thin-to-probable (consistent with general freelancing evidence, but single publisher)

**F7.2 — Consensus first-client playbook (multiple independent sources): pick ONE automation offer, build a demo on the prospect's own business, start with warm network / local businesses for a testimonial-priced first build, then convert the case study into outreach ammunition. "The goal of client number one is not to make money — it's to build a real case study."**
- Sources: https://futureworknavigator.com/how-to-get-your-first-ai-automation-client/ ; https://ciela.ai/blogs/is-starting-an-ai-automation-agency-worth-it-reddit (2026)
- Tier: T3/T4 | Origin: WebSearch snippets | Confidence: probable (consistent across sources with different incentives)

**F7.3 — Reddit reality check (aggregated): most who start an "AI automation agency" never reach meaningful revenue; failures blamed on chasing many automations instead of mastering one, buying guru courses expecting sales to follow, and underestimating prospect skepticism. The barrier named is differentiation + provable results, not saturation per se. Margins for those who succeed: 70–90%.**
- Source: https://ciela.ai/blogs/is-starting-an-ai-automation-agency-worth-it-reddit (2026; secondhand aggregation — reddit.com itself unfetchable)
- Tier: T4 | Origin: WebSearch snippet | Confidence: probable as a sentiment reading, thin as statistics

**F7.4 — Practitioner revenue claims (COURSE-SELLER BIAS FLAGGED): Nick Saraev claims LeftClick (solo automation agency, Make/n8n) reached $72k/mo, later $100k+/mo teaching; won Skool Games at $290k MRR — the large figures are from selling training, not client services. Doby Lanete claims $12k first month after repositioning to a clear AI-automation offer with "Dream 100" outreach (via Client Ascension, itself a coaching program).**
- Sources: https://www.scamrisk.com/maker-school-review-is-nick-saraev-legit/ ; https://nicksaraevskool.com/ ; https://www.clientascension.io/case-studies (2026)
- Tier: T4 | Origin: WebSearch snippets | Confidence: contested — unaudited self-reports with direct financial incentive; the agency-revenue-to-course-revenue pipeline is itself evidence that teaching pays better than doing

**F7.5 — Vertical specialization vs. generalist: widely repeated claims of a 30–50% price premium for specialists, retention 78% vs 54%, project profitability 43% vs 28% — but no primary study was locatable; every figure traces to agency-marketing content citing "Agency Management Institute and independent surveys" without linkable data. Upwork's own data (+34% premium for AI-skilled work, NLP specialists $350–$700/hr vs $150–$250 generalist per one guide) supports skill-premium directionally.**
- Sources: https://agencyacquisitions.io/insights/why-niche-agencies-outperform-generalists/ ; https://lightningpathpartners.com/agency-blog/niche-vs-generalist-agency-valuation ; https://www.hausadvisors.com/blog/vertical-vs-horizontal-positioning (2026)
- Tier: T3/T4 | Origin: WebSearch snippets | Confidence: contested — direction (specialists charge more) is probable; the specific percentages are thin/unverifiable

**F7.6 — Marketplace structure data point: AI jobs under $500 are <6% of Upwork's AI gross services volume — i.e., the dollars are overwhelmingly in mid/large engagements even on a marketplace famous for cheap gigs.**
- Source: https://gigradar.io/blog/upwork-market-report-2026 (2026, third-party Upwork data analysis)
- Tier: T3 | Origin: WebSearch snippet | Confidence: probable

---

## Synthesis for a solo operator

1. **Two markets exist under one name.** Marketplace-commodity pricing (Fiverr chatbot ≈ $216–$520, n8n gig $30–$250, voice agent $400) and positioned-consultant pricing ($2.5k–$15k builds + $1k–$5k/mo retainers) differ by 10–30× for similar artifacts. The variable is sales channel and framing, not tech.
2. **The realistic solo band:** $500–$3k first projects → $2.5k–$8k standard builds + $500–$2k/mo retainers within a few months of proof. Hourly equivalents $50–$150.
3. **Retainers are the business model;** one-off builds are the customer-acquisition mechanism. Every credible pricing structure found converges on setup-fee + monthly-retainer.
4. **Voice AI has the cleanest unit-economics story** (cost $0.10–$0.30/min, resale $0.50–$2.00/min or $300–$1,200/mo per local-business client) but also the heaviest guru-marketing contamination — discount claimed client counts.
5. **Fastest verified-ish path to revenue:** warm network first build (days), Upwork with strong profile (2–3 weeks), cold niche outreach (4–6 weeks). Content/LinkedIn is a compounding channel, not a first-revenue channel.

## Gaps

- **No primary source could be opened** (egress-blocked environment) — every figure needs re-verification; Upwork/Fiverr official cost pages are the top re-check priorities.
- No audited or survey-based data on solo-operator income distribution in this niche; only self-reports with course-seller incentive.
- No linkable primary study behind the specialist-vs-generalist percentages despite wide repetition.
- Reddit threads (r/n8n, r/automation) were unreachable both directly and via search — firsthand "my first client" accounts are secondhand only.
- Make.com/Zapier certified-partner directory rate data not obtained.
- Churn/retention data for automation retainers: nothing found — the durability of the $1.5k–$5k/mo retainer model is asserted, never evidenced.

## Surprises

1. **Per-contract gen-AI earnings on Upwork FELL 13% YoY while contract volume grew 90%** (Upwork's own Future Workforce Index) — commoditization is measurable and fast at the low end, even as the AI-skill hourly premium (+34%) holds. Pricing power is migrating from "can use AI" to "can integrate AI into a specific business system."
2. **AI jobs under $500 are <6% of Upwork's AI GSV** — the cheap-gig image of marketplaces is wrong at the dollar-weighted level.
3. **The most credible pricing evidence found was a lone consultant's public rate card** (cjwray.com: $2.5k–$3.5k programmes, $3.8k/$7.5k/$15k tiers) — almost no practitioners publish prices, which itself signals that opacity is part of the pricing power.
4. **The teaching layer visibly out-earns the doing layer** (Saraev: $72k/mo claimed agency vs $290k+ MRR teaching), which quantifies the course-seller bias that contaminates most "what I charge" content in this space.
