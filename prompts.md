# Prompt Library

Replace bracketed fields before use. Ask the AI to state assumptions and missing information rather than invent facts.

## SEO & Content Optimization

### SEO-01 — Search Intent & Keyword Mapping

**Use when:** search intent & keyword mapping.

**Prompt**

> Act as an SEO strategist. Business: [BUSINESS]. Website/page: [URL OR TOPIC]. Target audience: [AUDIENCE]. Target market: [COUNTRY/REGION]. Primary goal: [GOAL]. Review this keyword list: [KEYWORDS]. Group keywords by search intent (informational, commercial, transactional, navigational), recommend one primary keyword and 3–6 secondary terms per page, identify likely cannibalization, and suggest a page type. Do not invent search-volume or difficulty data; mark missing metrics as “needs tool validation.” Return a table with rationale and next action.

### SEO-02 — SEO Brief Builder

**Use when:** seo brief builder.

**Prompt**

> Create an SEO content brief for [TOPIC] targeting [AUDIENCE] in [MARKET]. Primary keyword: [PRIMARY KEYWORD]. Secondary terms: [TERMS]. Search intent: [INTENT]. Include proposed title tag, H1, URL slug, meta description, outline with H2/H3s, questions to answer, internal-link opportunities, evidence/expert input needed, CTA, and quality checks. Avoid keyword stuffing and unsupported claims. Flag assumptions.

### SEO-03 — On-Page SEO Audit

**Use when:** on-page seo audit.

**Prompt**

> Act as a technical/on-page SEO reviewer. Analyze the page details I provide: URL [URL], title [TITLE], meta description [META], H1/H2 structure [HEADINGS], copy [COPY], image alt text [ALT TEXT], internal links [LINKS], and target keyword [KEYWORD]. Identify issues by impact (high/medium/low), explain why each matters, and recommend specific fixes. Do not claim you crawled the live site unless browsing data is provided. Separate observed facts from hypotheses.

### SEO-04 — Title Tag & Meta Description Variants

**Use when:** title tag & meta description variants.

**Prompt**

> For this page [PAGE DETAILS] and target query [KEYWORD], write 8 distinct title tags and 5 meta descriptions for [AUDIENCE/MARKET]. Keep them accurate, natural, differentiated, and aligned with search intent. Do not promise rankings or include facts not supplied. Label each option by angle and recommend one with a short rationale.

### SEO-05 — Content Refresh Plan

**Use when:** content refresh plan.

**Prompt**

> Review this existing content [PASTE CONTENT] for target audience [AUDIENCE], target query [KEYWORD], and business goal [GOAL]. Identify outdated, thin, repetitive, unclear, or unsupported sections. Propose a prioritized refresh plan, additions/removals, internal links to consider, examples/evidence to source, and a revised outline. Preserve useful original insights and do not fabricate statistics or citations.

### SEO-06 — Internal Linking Suggestions

**Use when:** internal linking suggestions.

**Prompt**

> Given these page summaries and URLs [PASTE URL + SUMMARY LIST], suggest relevant internal links for the page [TARGET PAGE]. For each suggestion, provide source page, destination page, natural anchor text, contextual placement, and rationale. Only use URLs supplied. Avoid repetitive exact-match anchors and links that do not genuinely help readers.

### SEO-07 — Local SEO Page Draft

**Use when:** local seo page draft.

**Prompt**

> Draft a useful local landing page for [SERVICE] in [LOCATION] for [BUSINESS]. Audience: [AUDIENCE]. Differentiators: [VERIFIED DIFFERENTIATORS]. Include a clear H1, service details, process, FAQs based on supplied customer questions, trust signals, and CTA. Do not create fake addresses, testimonials, awards, service areas, or local claims. Avoid near-duplicate city-page wording.

### SEO-08 — SEO Reporting Summary

**Use when:** seo reporting summary.

**Prompt**

> Turn the following SEO data into a concise stakeholder report: [PASTE DATA]. Reporting period: [PERIOD]. Goals: [GOALS]. Summarize changes in clicks, impressions, CTR, rankings, conversions, and landing-page performance where data exists. Distinguish correlation from causation, call out data limitations, identify 3 insights and 5 prioritized actions. Never invent missing metrics.

## AEO & GEO (Answer / Generative Search)

### AEO-01 — Answer-First Content Rewrite

**Use when:** answer-first content rewrite.

**Prompt**

> Rewrite this content for people seeking a direct answer: [CONTENT]. Question/topic: [QUESTION]. Audience: [AUDIENCE]. Start with a concise, self-contained answer, then explain context, steps, exceptions, and useful details. Use clear headings and plain language. Preserve factual meaning; flag claims requiring verification. Do not claim this guarantees inclusion in AI answers.

### AEO-02 — FAQ Development from Real Questions

**Use when:** faq development from real questions.

**Prompt**

> Using these customer questions, support tickets, or interview notes [PASTE INPUT], create a prioritized FAQ for [PRODUCT/SERVICE]. Write each question in natural language and answer accurately using only supplied facts. Mark unanswered questions as “business input required.” Avoid repetitive questions and sales-heavy answers.

### AEO-03 — Structured Data Readiness Checklist

**Use when:** structured data readiness checklist.

**Prompt**

> For this page type [PAGE TYPE] and content [PAGE DETAILS], create a structured-data readiness checklist. Recommend only schema types that accurately fit the visible page and current search-engine guidance. List required source facts, validation steps, and risks. Do not invent properties or claim that schema guarantees rich results. Note that implementation should be checked against official documentation.

### GEO-01 — AI Search Visibility Content Audit

**Use when:** ai search visibility content audit.

**Prompt**

> Evaluate the content below for clarity, factual support, entity clarity, answer usefulness, source quality, and distinctiveness: [CONTENT]. Topic: [TOPIC]. Audience: [AUDIENCE]. Score each dimension from 1–5 with evidence from the supplied text, then recommend prioritized improvements. Do not claim to measure actual AI-platform visibility without platform-specific evidence.

### GEO-02 — Evidence-Rich Expert Content Outline

**Use when:** evidence-rich expert content outline.

**Prompt**

> Create an outline for an original, useful article on [TOPIC] for [AUDIENCE]. Include the main question, concise answer, supporting subtopics, first-hand expertise or data we should add, authoritative sources to research, limitations, and practical examples. Separate known facts from claims that require research. Do not fabricate citations, quotations, or statistics.

### GEO-03 — Brand Entity Consistency Review

**Use when:** brand entity consistency review.

**Prompt**

> Review these official brand descriptions and profiles [PASTE TEXT/URLS] for consistent naming, product/service definitions, audience, location, and positioning. Create a discrepancy table and recommend canonical wording. Do not infer facts not present. Prioritize official sources and mark outdated or unverified entries.

## Social Media Content

### SOC-01 — Monthly Content Calendar

**Use when:** monthly content calendar.

**Prompt**

> Build a [NUMBER]-week social media calendar for [BRAND] in [INDUSTRY]. Audience: [AUDIENCE]. Platforms: [PLATFORMS]. Goal: [GOALS]. Posting capacity: [CAPACITY]. Create a table with date/week, platform, content pillar, format, hook, key message, CTA, asset needed, and KPI. Balance educational, proof, community, product, and conversion content. Flag dates that need confirmation.

### SOC-02 — Platform-Specific Repurposing

**Use when:** platform-specific repurposing.

**Prompt**

> Repurpose this source content [PASTE CONTENT] for LinkedIn, Facebook, Instagram, and TikTok. For each platform, adapt the hook, length, tone, format, CTA, and visual suggestion rather than copying the same caption. Keep all claims consistent with the source and identify where a platform's current specifications should be checked.

### SOC-03 — Short-Form Video Script

**Use when:** short-form video script.

**Prompt**

> Write a [DURATION]-second video script about [TOPIC] for [BRAND] targeting [AUDIENCE]. Goal: [GOAL]. Structure: opening hook, problem/context, 2–3 useful points, proof or demonstration, CTA. Include voiceover, on-screen text, shot suggestions, and caption. Avoid exaggerated claims and make the first 3 seconds specific.

### SOC-04 — Social Caption Variations

**Use when:** social caption variations.

**Prompt**

> Write 10 caption options for [PRODUCT/SERVICE/CAMPAIGN] aimed at [AUDIENCE]. Platform: [PLATFORM]. Brand voice: [VOICE]. Goal and CTA: [GOAL/CTA]. Include educational, story-led, benefit-led, question-led, and direct-response angles. Use only verified product facts; label any assumptions. Avoid engagement bait.

### SOC-05 — Comment & Community Response Bank

**Use when:** comment & community response bank.

**Prompt**

> Create response templates for these common comments or questions [PASTE EXAMPLES] for [BRAND]. Voice: [VOICE]. Include helpful, neutral replies, complaint escalation, pricing inquiry, misinformation correction, and cases requiring a human response. Do not disclose private customer data, argue, or promise resolutions that are not authorized.

### SOC-06 — Creative Brief for a Static Post

**Use when:** creative brief for a static post.

**Prompt**

> Create a design brief for a static social post about [TOPIC/OFFER]. Platform and dimensions: [PLATFORM/SIZE—VERIFY CURRENT SPECS]. Audience: [AUDIENCE]. Goal: [GOAL]. Include headline, supporting copy, visual concept, hierarchy, brand elements, CTA, accessibility/contrast notes, and what must not be included. Keep the main message readable on mobile.

### SOC-07 — Social Performance Analysis

**Use when:** social performance analysis.

**Prompt**

> Analyze this post-level performance export [PASTE DATA]. Include platform, date range, reach, impressions, engagement, clicks, spend, and conversions where available. Identify top and weak performers relative to the stated goal. Calculate rates only where denominators are supplied, state formulas, account for paid vs organic differences, and recommend controlled tests.

### SOC-08 — Campaign Hashtag & Topic Set

**Use when:** campaign hashtag & topic set.

**Prompt**

> For [CAMPAIGN/TOPIC], audience [AUDIENCE], and platform [PLATFORM], suggest relevant topic phrases and a small set of hashtags if appropriate. Explain the role of each. Do not claim hashtags are trending without current evidence. Prioritize relevance and audience language over generic high-volume tags.

## Branding & Messaging

### BRAND-01 — Brand Positioning Statement

**Use when:** brand positioning statement.

**Prompt**

> Develop a positioning statement for [BRAND] using: product/service [OFFER], target customer [CUSTOMER], customer problem [PROBLEM], differentiators [DIFFERENTIATORS], alternatives [ALTERNATIVES], and proof [PROOF]. Provide one recommended statement and 2 alternatives. Flag any differentiator that lacks evidence.

### BRAND-02 — Brand Voice Guide

**Use when:** brand voice guide.

**Prompt**

> Create a practical brand voice guide for [BRAND]. Audience: [AUDIENCE]. Desired traits: [TRAITS]. Avoid: [TRAITS TO AVOID]. Include 4 voice principles, do/don't examples, vocabulary choices, sample headline, social caption, email paragraph, and customer-support reply. Make the voice distinct but usable by multiple writers.

### BRAND-03 — Value Proposition & Message Pillars

**Use when:** value proposition & message pillars.

**Prompt**

> Build a messaging framework for [PRODUCT/SERVICE] for [AUDIENCE]. Customer pain points: [PAINS]. Features: [FEATURES]. Verified outcomes/proof: [PROOF]. Create a value proposition, 3–5 message pillars, supporting proof points, objections answered, and CTA options. Separate features, benefits, and proven results.

### BRAND-04 — Competitor Positioning Matrix

**Use when:** competitor positioning matrix.

**Prompt**

> Using only these competitor notes [PASTE SOURCED NOTES], compare [BRAND] with [COMPETITORS]. Build a matrix of audience, offer, positioning, proof, content themes, and apparent gaps. Cite the supplied source or note for each factual entry. Mark unknowns rather than guessing and recommend ethical differentiation opportunities.

### BRAND-05 — Campaign Naming & Tagline Ideas

**Use when:** campaign naming & tagline ideas.

**Prompt**

> Generate 20 campaign names and 10 taglines for [CAMPAIGN/BRAND]. Audience: [AUDIENCE]. Objective: [OBJECTIVE]. Desired tone: [TONE]. Required words: [WORDS]; avoid: [WORDS]. Explain the strongest 5 concepts. Treat all names as preliminary: trademark, domain, and cultural checks are required before use.

### BRAND-06 — B2B Product Messaging for ERP/Software

**Use when:** b2b product messaging for erp/software.

**Prompt**

> Create B2B messaging for [SOFTWARE/ERP PRODUCT] aimed at [INDUSTRY/BUYER ROLE]. Buyer challenges: [CHALLENGES]. Verified modules/capabilities: [CAPABILITIES]. Evidence: [CASE STUDIES/PROOF]. Produce an elevator pitch, 3 role-specific value messages, objection responses, and a demo CTA. Do not promise integrations, savings, or features unless verified.

## B2B Lead Generation & Sales Enablement

### B2B-01 — Ideal Customer Profile

**Use when:** ideal customer profile.

**Prompt**

> Develop an ideal customer profile for [PRODUCT/SERVICE] in [MARKET]. Current best customers or hypotheses: [INPUT]. Include firmographics, industry, size, geography, buying triggers, pain points, decision roles, disqualifiers, and qualification questions. Distinguish evidence from assumptions and recommend how to validate the profile.

### B2B-02 — Lead Magnet Concept

**Use when:** lead magnet concept.

**Prompt**

> Suggest 10 useful lead magnets for [AUDIENCE] in [INDUSTRY] related to [OFFER]. For each, include audience pain, title, format, value delivered, production effort, funnel stage, and follow-up CTA. Avoid thin or misleading gated content; choose concepts the team can genuinely deliver.

### B2B-03 — Cold Outreach Email Sequence

**Use when:** cold outreach email sequence.

**Prompt**

> Write a 3-email B2B outreach sequence for [PROSPECT TYPE] about [OFFER]. Personalization facts available: [FACTS]. Sender role: [ROLE]. Desired next step: [CTA]. Keep messages concise, relevant, truthful, and easy to decline. Do not invent familiarity or research. Include subject lines and spacing suggestions; remind me to follow applicable email and privacy laws.

### B2B-04 — LinkedIn Prospecting Message

**Use when:** linkedin prospecting message.

**Prompt**

> Write 3 concise LinkedIn connection or follow-up messages for [BUYER ROLE] in [INDUSTRY]. Value offered: [VALUE]. Verified personalization: [FACT]. Goal: [GOAL]. Use a professional, non-pushy tone. Do not pretend we met, imply an endorsement, or use personal data unrelated to business relevance.

### B2B-05 — Discovery Call Question Bank

**Use when:** discovery call question bank.

**Prompt**

> Create a discovery-call guide for [PRODUCT/SERVICE] sold to [INDUSTRY]. Buyer roles: [ROLES]. Include opening, current-process questions, pain and impact, stakeholders, timeline, budget process, requirements, risks, and agreed next steps. Use open questions and avoid leading the prospect toward an unsupported conclusion.

### B2B-06 — Lead Qualification Scorecard

**Use when:** lead qualification scorecard.

**Prompt**

> Design a simple lead qualification scorecard for [OFFER]. Define criteria, scoring anchors, weights totaling 100%, disqualifiers, and handoff rules. Criteria may include fit, need, urgency, authority, and engagement. Clearly label proposed weights as a starting hypothesis to validate against actual conversion data.

### B2B-07 — Demo Follow-Up Email

**Use when:** demo follow-up email.

**Prompt**

> Draft a follow-up email after a product demo for [PROSPECT/COMPANY]. Demo topics: [TOPICS]. Prospect priorities: [PRIORITIES]. Agreed actions and owners: [ACTIONS]. Timeline: [TIMELINE]. Summarize accurately, answer only confirmed questions, list attachments if provided, and propose a clear next step.

### B2B-08 — Objection Handling Playbook

**Use when:** objection handling playbook.

**Prompt**

> Create an ethical objection-handling guide for [PRODUCT/SERVICE]. Common objections: [OBJECTIONS]. Verified evidence and limits: [PROOF/LIMITS]. For each objection, provide an empathetic acknowledgment, diagnostic question, factual response, proof to offer, and appropriate next step. Never recommend pressure tactics or unsupported guarantees.

## Campaign Strategy & Measurement

### CAMP-01 — Campaign Strategy One-Pager

**Use when:** campaign strategy one-pager.

**Prompt**

> Create a campaign strategy for [OFFER] targeting [AUDIENCE] in [MARKET]. Business objective: [OBJECTIVE]. Budget: [BUDGET]. Timeline: [DATES]. Channels: [CHANNELS]. Include audience insight, single-minded message, offer, funnel stages, assets, roles, risks, KPI definitions, and decision gates. Mark assumptions and missing inputs.

### CAMP-02 — Marketing Funnel Plan

**Use when:** marketing funnel plan.

**Prompt**

> Map a funnel for [PRODUCT/SERVICE] from awareness to conversion and retention. Audience: [AUDIENCE]. Sales cycle: [CYCLE]. Channels available: [CHANNELS]. For each stage, specify customer question, content/offer, channel, CTA, event to track, KPI, and handoff. Ensure metrics align with the business objective.

### CAMP-03 — Budget Allocation Scenarios

**Use when:** budget allocation scenarios.

**Prompt**

> Given budget [BUDGET], channels [CHANNELS], historical results [DATA], and goal [GOAL], propose conservative, balanced, and experimental allocation scenarios. Show assumptions, expected trade-offs, and what data is missing. Do not forecast precise outcomes without defensible benchmarks. Include a reallocation rule based on observed performance.

### CAMP-04 — A/B Test Plan

**Use when:** a/b test plan.

**Prompt**

> Design an A/B test for [ASSET/ELEMENT] to improve [PRIMARY METRIC]. Audience and traffic: [DATA]. Current baseline: [BASELINE]. Define hypothesis, single variable, control, variant, primary/guardrail metrics, sample-size considerations, duration, stopping rule, and interpretation. Do not declare a winner from inadequate data or change multiple variables at once.

### CAMP-05 — Campaign KPI Dashboard Specification

**Use when:** campaign kpi dashboard specification.

**Prompt**

> Specify a dashboard for [CAMPAIGN/OBJECTIVE]. Data sources: [SOURCES]. Include KPI, definition, formula, breakdown, reporting cadence, owner, and action threshold. Separate leading indicators from business outcomes. Identify data-quality checks and avoid vanity metrics unless they serve a defined purpose.

### CAMP-06 — Post-Campaign Review

**Use when:** post-campaign review.

**Prompt**

> Analyze this campaign brief and results [PASTE BRIEF + RESULTS]. Objectives: [OBJECTIVES]. Summarize outcome vs target, channel contribution where measurable, what worked, what underperformed, likely explanations, limitations, and 5 prioritized next actions. Distinguish observed facts from hypotheses and recommend what to test next.

### CAMP-07 — Integrated Campaign Asset Checklist

**Use when:** integrated campaign asset checklist.

**Prompt**

> For campaign [CAMPAIGN], objective [OBJECTIVE], audience [AUDIENCE], and channels [CHANNELS], build a launch checklist covering landing page, tracking, creative, copy, approvals, CRM, sales enablement, accessibility, QA, schedule, and contingency. Assign an owner role and due date placeholder to each task.

### CAMP-08 — Executive Campaign Summary

**Use when:** executive campaign summary.

**Prompt**

> Convert this campaign data [PASTE DATA] into a one-page executive summary. Lead with the business result, compare performance with targets, explain the most important drivers, disclose limitations, and list decisions required. Use concise language and only supplied metrics; put detailed channel metrics in a compact table.

