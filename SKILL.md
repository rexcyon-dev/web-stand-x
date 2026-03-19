---
name: defi-campaign-article
description: >
  Use this skill to write professional DeFi project research articles and X (Twitter) thread campaigns
  optimized for community missions, airdrop competitions, and content campaigns.
  Trigger whenever the user mentions writing about a crypto/DeFi project, creating content for a
  mission or campaign, submitting articles to earn points/rewards, or wants to write a thread about
  a blockchain protocol, DEX, token, or Web3 platform.
  Also trigger for: "write an article about [project]", "create a thread for [protocol]",
  "help me win this mission", "make content for [crypto project]", "write a DeFi review",
  or any request involving crypto content creation for rewards or community engagement.
---

# DeFi Campaign Article & X Thread Skill

A skill for creating professional-grade DeFi research articles and X threads that win community
content campaigns, earn mission rewards, and drive airdrop point accumulation.

## Overview

This skill produces two deliverables:
1. A **publication-quality HTML article** — deployable as a live website (GitHub Pages, Netlify, etc.)
2. A **ready-to-post X thread** — embedded inside the article with one-click copy buttons per tweet

## Workflow

### Step 1 — Research the Project

Before writing anything, research the project thoroughly:

```
1. Search: "[project name] DeFi protocol 2025 2026"
2. Search: "[project name] tokenomics airdrop points campaign"
3. Search: "[project name] team founder TVL stats"
4. Fetch the official website / docs if available
```

Key facts to gather:
- **TVL** (Total Value Locked)
- **Daily trading volume**
- **APY / yield rates**
- **Token/airdrop details and points system**
- **Team credentials** (always a high-trust signal)
- **Unique mechanism** (what makes this project different)
- **Funding status** (VC-backed vs self-funded)
- **Chain(s)** supported

### Step 2 — Identify the Winning Angle

Every great campaign article needs ONE clear hook. Choose the strongest:

| Angle | Best for |
|-------|----------|
| "Nobody else does this" | Unique technical mechanism |
| "The team no one talks about" | Strong institutional backgrounds |
| "The numbers don't lie" | Impressive TVL/volume/APY stats |
| "Early = most points" | Active airdrop/points campaign |
| "I tried it, here's what happened" | Personal experience / UX |

### Step 3 — Build the HTML Article

Use this structure (all sections in English unless user requests otherwise):

```
1. HERO — Bold headline, italic accent phrase, meta info
2. STATS BAR — 4 key metrics with accent colors
3. THE PROBLEM — What pain point does this project solve?
4. THE INNOVATION — Core mechanism explained clearly
5. FEATURE GRID — 4 cards: key features with icons
6. THE TEAM — Credentials and trust signals
7. HOW TO START — Numbered step-by-step guide
8. POINTS/AIRDROP — Points breakdown table
9. PERSONAL EXPERIENCE — First-person authenticity section
10. X THREAD — 8 tweets embedded with Copy buttons
11. FINAL VERDICT — Strong closing + CTA button
12. HASHTAGS — 10-12 relevant tags
```

#### Design Standards

- **Theme:** Dark (background `#050508`) with accent colors
- **Fonts:** DM Serif Display (headings) + DM Sans (body) + JetBrains Mono (code/stats)
- **Accent color:** Purple `#6c56f0` primary, Teal `#00d4b4` secondary
- **Atmosphere:** Glow orbs, subtle noise texture, animated elements
- **Navigation:** Fixed top bar with project logo + CTA button
- **Stats:** Monospace font, accent color per metric
- **Cards:** Dark surface `#0c0c14`, subtle borders, hover effects
- **Responsive:** Mobile-friendly grid breakpoints at 700px

#### Must-Have Interactive Elements

- ✅ Fixed nav bar with "Try [Project]" CTA
- ✅ Animated pulsing dot in hero eyebrow badge
- ✅ Hover effects on all cards and feature grids
- ✅ One-click Copy button per tweet (turns green with "✓ Copied")
- ✅ Points table with hover row highlights
- ✅ Final CTA with glow shadow effect

### Step 4 — Write the X Thread (8 Tweets)

Structure that consistently performs well:

```
Tweet 1 — HOOK: Discovery framing ("I just found...")
Tweet 2 — PROBLEM: Pain point all traders/users face
Tweet 3 — SOLUTION: Core mechanism with bullet checkmarks
Tweet 4 — MECHANISM: How the yield/innovation actually works
Tweet 5 — TEAM: Credentials and trust signals
Tweet 6 — STATS: Numbers-only tweet (most shareable)
Tweet 7 — POINTS/AIRDROP: How to earn, urgency framing
Tweet 8 — CTA: Article link + closing line + hashtags
```

#### Tweet Writing Rules

- Max 280 characters per tweet
- Use ✅ for features, 📊 for stats, 🚨 for urgency
- End hook tweet with "🧵👇" 
- Use line breaks for scanability
- Mention `@OfficialHandle` in Tweet 1
- Close Tweet 8 with 3-5 hashtags maximum
- Always include `$TICKER` in Tweet 8

### Step 5 — Package for Deployment

After creating the HTML file:
1. Name it `index.html` for GitHub Pages compatibility
2. Create `README.md` with project stats table, usage instructions, and links
3. Present both files for download

## GitHub Pages Deployment Guide

Include this in your response after delivering files:

```
1. github.com → New repository → name: [project-slug] → Public
2. Upload index.html → commit
3. Settings → Pages → Branch: main → Save
4. Live in ~60 seconds at: https://username.github.io/[project-slug]
5. Paste URL in Tweet 8 → post thread → submit to mission
```

## Quality Checklist

Before delivering, verify:

- [ ] All content is in the correct language (English unless specified)
- [ ] No placeholder text left (e.g., "[PROJECT NAME]")
- [ ] Stats are accurate and sourced from research
- [ ] Tweet 8 has `[PASTE ARTICLE LINK HERE]` placeholder clearly marked
- [ ] Copy buttons work (JavaScript `navigator.clipboard.writeText`)
- [ ] Article loads without external dependencies that might fail
- [ ] Mobile responsive (test at 375px mental model)
- [ ] README.md has accurate stats table and clear mission instructions

## Tone & Voice Guide

| Section | Tone |
|---------|------|
| Hero/Hook | Bold, confident, slightly provocative |
| Problem | Empathetic, analytical |
| Solution | Clear, technical-but-accessible |
| Team | Authoritative, factual |
| Personal Experience | Genuine, first-person, specific details |
| Tweets | Punchy, urgent, social-native |
| Conclusion | Inspiring, forward-looking |

## Hashtag Strategy

Always include:
- `#[ProjectName]` — primary tag
- `#[TokenTicker]` — token tag  
- `#DeFi` — broad category
- `#[Chain]` — e.g., `#BNBChain`, `#Solana`, `#Ethereum`
- `#Airdrop` or `#Crypto` — discovery tags
- 1-2 niche tags relevant to the mechanism

## Example Projects This Skill Has Covered

- **StandX** — Perp DEX with yield-bearing margin via $DUSD
  - Hook: "Your margin earns yield while you trade"
  - Key stat: $200M+ TVL, 3-13% APY, 100x leverage
  - Team: ex-Binance Futures + Goldman Sachs

Use past projects as reference for quality bar and structure.

## File Output

Always output:
1. `/mnt/user-data/outputs/index.html` — Full article (production-ready)
2. `/mnt/user-data/outputs/README.md` — GitHub repo README

Present both files using `present_files` tool.
