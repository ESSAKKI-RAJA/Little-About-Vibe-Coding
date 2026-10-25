**\# ChatGPT Project: Product Building & Business Strategy**

Paste the block below into the project's **\*\*"Instructions"\*\*** field (Custom Instructions for that project, not global settings). Then follow the **\*\*Sources\*\*** and **\*\*Anti-Hallucination Protocol\*\*** sections to load its knowledge base correctly.

\---

**\## 1. PROJECT INSTRUCTIONS (paste this verbatim)**

\`\`\`

ROLE

You are my dedicated product-building and business-strategy partner for a portfolio of active platforms: AEGON (enterprise asset intelligence), THREATWEAVE (B2B supply chain cyber risk intelligence), PAWPHILE (AI-powered preventive health app for dogs), STOCKSEE, and MEETCHI. I operate with architectural authority — I make the calls, you execute analysis and generate output. Do not ask me foundational/onboarding questions I've already answered in the project files; read them first.

OPERATING RULES

1\. GROUND EVERYTHING IN SOURCES

&nbsp; - Before answering any question about my products, market, competitors, or prior decisions, check the attached project files first.

&nbsp; - If the answer isn't in the files and isn't something you can verify, say "I don't have this in the project files" or "I'm not certain — here's my best reasoning, flag it as unverified" instead of inventing specifics.

&nbsp; - Never invent: market size numbers, competitor features, pricing data, regulatory claims, user statistics, or technical specs. If you don't have a hard source, label the number as an estimate and say so explicitly.

2\. NO SILENT ASSUMPTIONS

&nbsp; - If a request is ambiguous, state the assumption you're making in one line and proceed — don't stall with clarifying questions unless the ambiguity would send the whole answer in the wrong direction.

&nbsp; - Flag when you're reasoning from a general pattern vs. a fact about my specific product.

3\. CITE YOUR BASIS

&nbsp; - When you use web search, separate "verified from source" vs "my inference" vs "industry-general pattern" in the answer.

&nbsp; - When you reference something from an earlier chat in this project, say "per \[file/thread name\]" so I can check it.

4\. PUSH BACK

&nbsp; - Do not default to agreement. If a plan has a weak assumption, a sizing problem, a sequencing risk, or a wedge that's too broad, say so plainly before offering alternatives.

&nbsp; - Give trade-offs, not just one recommended path, on any decision with real cost (pricing, tech stack, GTM, hiring).

5\. OUTPUT DISCIPLINE

&nbsp; - Default to structured output: numbered steps, tables, or decision frameworks over long prose.

&nbsp; - For blueprints/specs: always separate "what we know," "what we're assuming," and "what we still need to validate."

&nbsp; - Keep strategic frameworks reusable — name them, so I can reference "the wedge framework" or "the moat checklist" in later chats.

6\. MEMORY DISCIPLINE

&nbsp; - Treat this project's file list as the single source of truth for my products. If I upload a new version of a doc, treat it as superseding the old one and say so.

&nbsp; - Don't blend facts from different products unless I explicitly ask for cross-portfolio synthesis.

\`\`\`

\---

**\## 2. SOURCES — what to upload to Project Files**

ChatGPT project files are retrieved (not always fully read into context), so the fewer, denser, and better-labeled they are, the less hallucination risk. Structure:

| File | Contents | Why it matters |

|---|---|---|

| \`00_portfolio_overview.md\` | One page per product: what it does, ICP, current stage, tech stack, differentiator | Gives the model a always-true anchor doc it can check every answer against |

| \`01_\[product\]\_prd.md\` (one per active product) | Problem statement, target user, core workflows, current feature set | Prevents scope drift when brainstorming new features |

| \`02_\[product\]\_market_research.md\` | Named competitors, actual pricing/feature data you've verified, TAM/SAM sources with links | If this is empty, the model WILL hallucinate market numbers — keep it populated or explicitly mark "unverified" |

| \`03_\[product\]\_decisions_log.md\` | Dated log: "Decided X because Y, rejected Z because W" | Stops the model from re-litigating settled decisions or contradicting past reasoning |

| \`04_frameworks.md\` | Your existing 80-principle product strategy framework, wedge/PMF/GTM models you already use | Makes the model apply _\*your\*_ mental models instead of generic ones |

| \`05_glossary.md\` | Your own shorthand/acronyms (ICP definitions per product, internal stage names) | Prevents misinterpretation of terse instructions |

**\*\*Upload hygiene:\*\***

\- Keep each file under ~2–3k words; split large docs by product rather than one giant file.

\- Put a one-line **\*\*last-updated date\*\*** at the top of every file — tell the model in-chat to prefer the most recently dated file when documents conflict.

\- Re-upload (replace, don't duplicate) when a doc materially changes — duplicate stale versions are the single biggest cause of contradictory answers.

\- Don't dump raw meeting transcripts — summarize decisions out of them first; raw transcripts dilute retrieval quality.

\---

**\## 3. ANTI-HALLUCINATION PROTOCOL (how to actually use it day to day)**

1\. **\*\*Ask "sourced or reasoned?" explicitly\*\*** when a number or claim matters — e.g., "Is that TAM figure from a file or your estimate?" Train yourself to ask this every time a stat shows up.

2\. **\*\*Use web search for anything time-sensitive\*\*** (competitor pricing, funding news, regulation) — don't let the model answer from memory for anything that changes month to month.

3\. **\*\*Version-control your decisions log\*\*** — every time you make a real call (pricing model, wedge, stack choice), add one line to \`03_\[product\]\_decisions_log.md\` in the same session. This is your strongest lever against contradiction across sessions.

4\. **\*\*Start ambiguous sessions with a one-line context reset\*\***: "We're on AEGON, current stage = backend complete, frontend build in progress" — even with good files, an explicit anchor cuts drift.

5\. **\*\*Audit monthly\*\***: skim the decisions log and portfolio overview for anything the model said that never actually got logged — fold it in or discard it.

\---

**\## 4. TOP 20 PRODUCT BUILDING STRATEGIES**

1\. **\*\*Narrow the wedge before you widen it\*\*** — win one specific use case for one specific user before expanding scope.

2\. **\*\*Design for a named ICP, not "everyone in the industry"\*\*** — specificity in targeting drives specificity in features.

3\. **\*\*Validate the problem before the solution\*\*** — confirm people already pay (money, time, workaround effort) to solve this pain.

4\. **\*\*Build the smallest thing that tests the riskiest assumption first\*\***, not the smallest thing that's easiest to build.

5\. **\*\*Talk to users before and after every major feature decision\*\*** — qualitative signal catches what usage metrics miss early.

6\. **\*\*Instrument from day one\*\*** — you can't find PMF signal in a product with no usage data.

7\. **\*\*Define your moat early, even if it's not built yet\*\*** — data network effects, switching costs, workflow lock-in, proprietary integrations. Know which one you're playing for.

8\. **\*\*Price on value delivered, not on cost-plus\*\*** — especially in B2B, anchor pricing to the cost of the problem you solve.

9\. **\*\*Sequence GTM before scaling infra\*\*** — don't over-engineer for a scale you haven't earned distribution for yet.

10\. **\*\*Pick one acquisition channel and prove it before diversifying\*\*** — spreading GTM thin early kills signal clarity.

11\. **\*\*Treat your first 10–20 customers as co-designers\*\***, not just revenue — their edge cases define your roadmap.

12\. **\*\*Kill features that don't move the core metric\*\*** — feature bloat is the default failure mode of founder-led product building.

13\. **\*\*Separate "must-have for launch" from "nice-to-have for retention"\*\*** — most teams build v1 with v3 scope.

14\. **\*\*Build your differentiation into the architecture, not just the UI\*\*** — a copyable UI advantage isn't a moat.

15\. **\*\*Design onboarding as a product feature, not an afterthought\*\*** — time-to-first-value is often the single best predictor of retention.

16\. **\*\*Set a PMF bar in advance\*\*** (retention curve shape, NPS threshold, organic referral rate) so you know when to shift from build-mode to scale-mode.

17\. **\*\*Run pricing experiments early, not after "the product is done"\*\*** — pricing is product, and late pricing changes are painful.

18\. **\*\*Build a repeatable decision log\*\*** — write down why, not just what, so strategy doesn't silently drift across a multi-product portfolio.

19\. **\*\*Treat competitors' roadmap gaps as your research, not your fear\*\*** — analyze what they're structurally unable to build (business model, architecture, or positioning constraints).

20\. **\*\*Revisit the wedge quarterly\*\*** — the market you validated for at MVP is rarely the market you should be optimizing for a year in; treat wedge-fit as a living hypothesis, not a one-time decision.

\---

_\*Tip: keep this file itself as \`06_project_operating_manual.md\` in the project's Sources — that way the instructions and the source list stay versioned together.\*_