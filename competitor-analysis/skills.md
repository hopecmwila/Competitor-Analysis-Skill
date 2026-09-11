---
name: competitor-analysis
description: Generates a structured, evidence-based competitor analysis report — SWOT, proposed solution, existing solutions (known plus web-researched), table stakes, differentiators, and a feature matrix. Searches the web to surface competitors not already known to the user. Use whenever a competitor analysis, competitive landscape, or market research report is requested.
---

# Competitor Analysis Skill

## Purpose
Produce a rigorous, repeatable competitor analysis: map the proposed solution against the real competitive landscape, combining provided context with fresh web research, so no relevant competitor or gap is missed.

## Required Inputs
1. Product/feature brief — what it does, target users, goals
2. Full proposed solution capability list
3. Known competitors, if any
4. Research constraints (market, region, segment), if any

If any input is missing or ambiguous, ask clarifying questions before researching.

## Rules
- Never limit research to competitors the user names — always web-search for additional, emerging, and indirect competitors.
- Every competitor claim must trace to a source (URL); mark unverifiable claims as unverified.
- Do not invent proposed-solution features — use only what's provided.
- Table Stakes = capabilities most/all competitors share. Differentiators = what the proposed solution has beyond table stakes.
- No unsupported superlatives ("best," "leading") without a citation.

## Workflow
1. **Scope** — confirm product, users, goals, and known competitors.
2. **Research** — web-search for existing solutions (direct, indirect, emerging). For each, capture offering, strengths, weaknesses, and gaps.
3. **Table Stakes** — list capabilities common across competitors.
4. **Differentiators** — list what sets the proposed solution apart.
5. **Feature Matrix (SAD)** — table mapping core features across the proposed solution and each competitor, to pinpoint the main features that matter.
6. **SWOT** — Strengths/Weaknesses/Opportunities/Threats for the proposed solution given the landscape.
7. **Compile** into the Output Format below, with a full source list.

## Output Format
```
# Competitor Analysis: [Product]

## Proposed Solution
[Full capability list]

## Existing Solutions
### [Competitor] — [source]
- Offering:
- Strengths:
- Limitations/Gaps:
(repeat per competitor, known + researched)

## Table Stakes
- [feature]

## Differentiators
- [feature]: why it matters

## Feature Matrix (SAD)
| Feature | Our Product | Competitor A | Competitor B |

## SWOT
- Strengths:
- Weaknesses:
- Opportunities:
- Threats:

## Sources
[All URLs used]
```

## What to avoid
- Skipping web research and relying only on user-named competitors.
- Presenting unverified claims as fact.
- Missing sources for competitor data.
- Mixing table stakes into differentiators.
- Listing proposed-solution features not actually provided by the user.

## Example Trigger
User: [uploads product brief + known competitors] → Run competitor analysis.

You: [Full report in the format above, with sources cited and unverified items flagged.]
