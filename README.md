# AI Buyer Visibility Auditor

Free Claude skill. Install in 60 seconds.

Not a prompt. Not a template.  
An actual audit tool that scores whether your company is visible to AI — and writes the fix for you.

## What it does
- Runs the exact 10-query audit across 4 layers: Category, Problem, Trust, Compliance
- Scores you out of 10
- Tells you exactly which query failed and why
- Writes your real, publishable `llms.txt` file (the AI equivalent of robots.txt)
- Zero fabrication — flags gaps instead of inventing claims

## How to install

### Option 1: Claude Code (recommended, 10 seconds)
Run this in your terminal:

```bash
npx skills add Ratz0007/claude-ai-buyer-visibility-auditor
```

That's it. Restart Claude Code if it doesn't pick up automatically, then say: **"Audit our AI visibility"**

### Option 2: Claude Code (manual)
```bash
git clone https://github.com/Ratz0007/claude-ai-buyer-visibility-auditor.git
mv claude-ai-buyer-visibility-auditor ~/.claude/skills/
```
Restart Claude Code, then say: **"Audit our AI visibility"**

### Option 3: Claude.ai (web)
Skills upload in Claude.ai is currently limited. The easiest path: copy the contents of `SKILL.md` into your Project's custom instructions or paste into any chat as a system prompt.

Then trigger with: **"Audit our AI visibility"**

That's it. It runs the framework, not you.

## Files included
- `SKILL.md` — The complete skill definition (this is what Claude reads)
- `README.md` — This file

## Feedback
Use it. Break it. Tell me what's wrong with it.  
Score the audit in comments — I'll tell you which layer to fix first.

#AIAgents #ClaudeAI #B2BMarketing #GTM #AEO

Built because I was tired of writing the same audit by hand every time.