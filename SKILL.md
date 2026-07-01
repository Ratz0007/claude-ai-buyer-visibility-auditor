---
name: ai-buyer-visibility-auditor
description: Free audit tool. Runs 10-query framework (Category/Problem/Trust/Compliance). Scores visibility to buyer AIs /10, explains failures, generates truthful llms.txt. Low-friction: starts with name+URL only, auto-researches, batches queries into 1 copy-paste. Trigger: "Audit our AI visibility".
---

# AI Buyer Visibility Auditor

## Purpose
Audit how visible and citable your company is to AI agents that influence B2B buyers. Uses a repeatable 10-query framework mapped to 4 layers. Scores /10, pinpoints failures with reasons, then generates your `llms.txt` — the plain-text file AI agents read (like robots.txt for search) using **only verified information you provide**. Flags any gaps instead of inventing claims.

## When to Use
- User says: "Audit our AI visibility", "Run AI visibility audit", "Create our llms.txt", or similar.
- Ideal for founders, marketers, GTM teams wanting to improve AEO / AI visibility and fix positioning for LLMs.

## Smart Two-Speed Onboarding (Minimal User Effort)
Claude starts fast: only asks Company Name + Website URL first. Uses web browsing tools to research public info (category, ICP, value prop, visible signals). Presents a short "What I found" summary for user to verify + add ONLY verified proof points + compliance notes. No long form upfront.

## The Exact 10-Query Framework

The skill customizes these templates using your inputs above.

**Category Layer (1-3) — Named as an option?**
1. What are the top [category] solutions for [ICP]?
2. Best [category] platforms for [ICP] trying to [key outcome]?
3. Who are the leading alternatives in [category] for [specific ICP use case]?

**Problem Layer (4-6) — Tied to the outcome you solve?**
4. How do [ICP] currently solve [core problem]?
5. What approaches deliver the strongest results for [desired business outcome]?
6. Which tools help [ICP] achieve [specific measurable outcome]?

**Trust Layer (7-8) — Information accurate when checked?**
7. What is known about [company name] for [use case], especially regarding [key proof area]?
8. Accuracy of claims or any red flags for [company name] in [category]?

**Compliance Layer (9-10) — Posture correctly represented?**
9. [Company name]'s position on [compliance topic e.g. data privacy, AI training, security]?
10. Does [company name] meet enterprise [compliance e.g. SOC2 / GDPR / HIPAA] requirements?

## How the Audit Runs (Low-Friction, Two-Speed)
1. **Speed 1 (30s start):** Ask ONLY Company Name + Website URL. Use web browsing/search tools to research & summarize public info: inferred category, ICP, value prop, any visible proof/compliance signals. Present clean "What I found from your site" + ask user to verify/correct + add verified proof points + compliance notes (minimal input).

2. **Batch Queries:** Generate all 10 customized queries as **ONE clean copy-paste block** (numbered, optimized for Perplexity/ChatGPT/Gemini). User copies once, runs in preferred AI(s), pastes ALL answers back in one go.

3. Score each response 0/1 using strict layer criteria:
   - Category (1-3): +1 if company explicitly named/recommended as option.
   - Problem (4-6): +1 if tied clearly to your specific outcomes.
   - Trust (7-8): +1 if statements match your verified proof points (or correctly notes limited info).
   - Compliance (9-10): +1 if posture described accurately per your notes.

4. Output: Total X/10 + exact per-query failure reasons + layer risks.

5. Generate **llms.txt** immediately after (or on "Generate our llms.txt").

## llms.txt Generation Rules (Strict)
- Follow official spec: `# Company Name` (H1) → `> One-sentence summary` (blockquote) → `##` sections with clean bullet lists.
- **Only** include claims from your verified proof points. 
- Any missing proof: output as `> [GAP / TO VERIFY: Brief description of claim and what evidence is needed]`
- Recommended sections (customized):
  - ## Overview
  - ## Ideal Customer Profile (ICP)
  - ## Core Problems We Solve & Outcomes
  - ## Proof Points & Results (only verified)
  - ## Compliance, Security & Trust Posture
  - ## Resources (links to website pages if URL provided)
- Output the complete ready-to-copy markdown.
- Tell user: Save as `llms.txt`, upload to site root (yourdomain.com/llms.txt). AI agents will now read your exact positioning.

## Quick Fixes It Recommends
After scoring, it suggests the highest-ROI actions to improve next audit (e.g. "Publish 2 case studies for Proof Points layer", "Add outcome-focused landing page copy for Problem queries", "Add llms.txt + update website trust signals").

## Examples of Use
User: Audit our AI visibility. Company: RevenueForge. Website: revenueforge.com

Skill researches site → shows "Found: Sales automation for mid-market SaaS..." → user verifies + adds 3 proof points → gives ONE batched query block → user pastes answers → scores 7/10 with exact failure reasons → delivers production llms.txt (gaps flagged).

## Notes
- This is **not** magic search. You run the real queries where buyers ask so the audit reflects actual AI behavior.
- Trust/Compliance scoring cross-references your provided verified facts against pasted answers.
- llms.txt is the permanent fix almost no one has. It directly improves future visibility and prevents AI hallucinations about your company.
- Free. Built to stop repeating manual audits. Use it. Break it. Feedback improves it.

Use this skill. It runs the full framework so you don't have to.