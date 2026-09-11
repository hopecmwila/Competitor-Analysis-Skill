# Competitor Analysis Skill

A repeatable Claude skill for producing structured, evidence-based competitor analysis reports — built for PMs who need this done consistently, not reinvented every time.

## What it does

Given a product brief and a list of what your product does, this skill:

- Web-searches for existing solutions — including competitors you already know about **and** ones you don't
- Identifies each competitor's offering, strengths, and gaps/limitations
- Separates **table stakes** (what everyone offers) from **differentiators** (what sets you apart)
- Builds a **feature matrix** mapping your core features against each competitor's
- Produces a **SWOT** analysis grounded in the research, not guesswork
- Outputs everything in one consistent report format, with sources cited

## When to use it

Trigger it any time you need to:
- Kick off a new competitor analysis or competitive landscape doc
- Refresh an existing one after competitors ship new features
- Sanity-check whether a proposed feature is actually a differentiator or just table stakes
- Validate a "no direct competitors" assumption before it goes into a deck

## What you need to provide

| Input | Required? | Notes |
|---|---|---|
| Product/feature brief | Yes | What it does, who it's for, the goal |
| Full capability list | Yes | Everything your proposed solution does — the skill won't invent features |
| Known competitors | No | The skill researches beyond this list regardless |
| Research constraints | No | e.g. region, segment, enterprise vs. SMB |

If anything's missing or ambiguous, the skill will ask before it starts researching — it won't guess at your product's scope.

## How it works

1. **Scope** — confirms product, users, goals, and any known competitors
2. **Research** — searches the web for direct, indirect, and emerging competitors, capturing offering/strengths/gaps for each
3. **Table stakes** — pulls out what's common across the landscape
4. **Differentiators** — pulls out what's unique to your solution
5. **Feature matrix (SAD)** — lines up core features side by side
6. **SWOT** — synthesizes strengths, weaknesses, opportunities, and threats
7. **Report** — compiles everything into the standard output format below

## Output format

The report always follows the same structure: Proposed Solution → Existing Solutions → Table Stakes → Differentiators → Feature Matrix → SWOT → Sources. This consistency is intentional — it's what makes reports comparable across projects and reviewers.

## Ground rules

- Every competitor claim is sourced — no unverified claims presented as fact
- The skill never limits itself to competitors you already named; it always searches for more
- It won't add features to your product that you didn't provide
- No unsupported superlatives ("best-in-class," "market-leading") without a citation backing them up

## Limitations

- Research quality depends on what's publicly discoverable online — private/unlaunched competitors won't surface
- It reports what it finds; it doesn't make the strategic call on which differentiators to prioritize — that's still on you