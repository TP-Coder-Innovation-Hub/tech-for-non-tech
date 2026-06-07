# AGENTS.md

## Context

This repository contains educational content for a **non-technical audience**: business people, managers, founders, MBA students, and anyone who makes or influences technology decisions without writing code themselves. These readers are smart, experienced professionals who simply have not had exposure to how software and technology systems work under the hood.

The content must be publication-quality, plain-language, and immediately useful.

## Audience Levels

Three tiers appear throughout the content as badges:

- **`[Entry]`** — First exposure to tech concepts. Needs analogies, context, and "why this matters" framing. No assumed knowledge.
- **`[Mid]`** — Works with tech teams regularly. Needs frameworks for communication, prioritization, and collaboration.
- **`[Senior]`** — Leads tech-informed business decisions. Needs strategic perspective: ROI, risk, vendor evaluation, build-vs-buy.

Most content applies to all three levels. Some sections are marked for specific levels.

## How to Help

When writing, editing, or extending content in this repository:

- **Use analogies** to explain technical concepts. Restaurant, construction, and finance analogies work well for this audience.
- **Avoid jargon.** If a technical term is necessary (e.g., "API," "database," "server"), define it in plain language on first use.
- **Explain "why," not "how."** Business readers need to understand why something matters for their decisions, not how it works under the hood.
- **Connect everything to business outcomes.** Cost, revenue, risk, speed, customer experience.
- **Use tables, diagrams, and structured formats.** Scannable content is more useful than long paragraphs.
- **Mermaid diagrams** should be simplified and non-technical. Use sequence diagrams and flowcharts. Avoid complex architecture diagrams.
- **Be conversational but professional.** This audience is senior and experienced. Respectful tone throughout.
- **Use real-world examples** to ground abstract concepts.

## How NOT to Help

- **Never use code examples.** No Python, no JavaScript, no SQL. No code blocks of any kind.
- **Never assume technical knowledge.** Do not say "obviously" or "as you know." If a reader needs to know something, explain it.
- **Never condescend.** These readers are accomplished professionals in their own domains. They are here to learn, not to be talked down to.
- **Never use acronyms without expansion.** First use always spells out the full term: "Multi-Factor Authentication (MFA)."
- **Never recommend specific vendors as endorsements.** Mentioning tools by name for context is fine (e.g., "tools like Tableau or Power BI"). Endorsing one over another is not.
- **Never use emojis.** This is professional educational content.

## Key Concepts Covered

1. **Why technology literacy matters** — every business decision has a tech component
2. **How software gets built** — roles, lifecycle, and why projects are late
3. **How the internet works** — clients, servers, APIs, cloud in plain language
4. **Data** — storage, analytics, dashboards, privacy regulations
5. **Cybersecurity** — threats, prevention, and business impact of breaches
6. **AI** — what it can and cannot do, how to evaluate vendor claims
7. **Technology decisions** — build vs. buy, vendor evaluation, ROI, trade-offs

## Content Guidelines

- **Plain language** throughout. Target a reading level accessible to any college-educated professional.
- **Business-first framing.** Every technical concept should answer: "Why does this matter for my business?"
- **Analogies over explanations.** Prefer "an API is like a waiter at a restaurant" over "an API is a programmatic interface for inter-software communication."
- **No code.** This is non-negotiable. If a concept requires code to explain, reframe it.
- **Focus on decision-making.** The goal is not to make readers technical. It is to help them make better decisions.
- **Sources and claims.** When citing statistics (breach costs, market data), note the source. Keep numbers current.
- **Structure for scanning.** Use headers, tables, bullet points, and short paragraphs. Busy professionals scan before they read.

## Repository Structure

```
/
  README.md    — The main educational content (this is the course)
  AGENTS.md    — This file. Context for AI agents and contributors.
```

When adding new content:

- All educational material goes in README.md or dedicated section files.
- Maintain the `[Entry]` / `[Mid]` / `[Senior]` badge system.
- Keep the tone consistent: conversational, accessible, respectful.
- Test every paragraph: "Would my manager (who is not technical) understand this?" If not, rewrite.
