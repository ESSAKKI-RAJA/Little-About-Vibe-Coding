# AI Startup Builder's Field Manual

## A practical synthesis of five foundational books

**Purpose:** Turn the ideas in *The Mom Test*, *INSPIRED*, *The Lean
Startup*, *AI Engineering*, and *Traction* into one actionable operating
system for building an AI-enabled technology startup.

**Who this is for:** A founder or small founding team moving from an
early idea to a validated, useful, reliable, and commercially viable
product.

**Important note:** This is an original, practical synthesis of the
books' core concepts, not a substitute for reading them and not a
reproduction of their text. It adds implementation checklists, examples,
metrics, and decision gates to connect the ideas into one workflow.

------------------------------------------------------------------------

## Executive summary

A startup is not simply a product that gets built. It is a set of
hypotheses about a customer, a painful problem, a solution, a
distribution method, and a sustainable business model. The founder's job
is to test the riskiest hypotheses in the cheapest credible way, then
build only what the evidence supports.

Use the five books for five complementary jobs:

1.  **The Mom Test --- Rob Fitzpatrick:** Discover real customer
    problems without leading people or collecting empty compliments.
2.  **INSPIRED --- Marty Cagan:** Create products around customer value,
    usability, feasibility, and business viability.
3.  **The Lean Startup --- Eric Ries:** Reduce uncertainty through MVPs,
    experiments, validated learning, and iteration.
4.  **AI Engineering --- Chip Huyen:** Design AI applications as
    evaluated, observable, reliable systems---not merely prompts wrapped
    around a model.
5.  **Traction --- Gabriel Weinberg and Justin Mares:** Find a
    repeatable way to reach and acquire the right customers.

The central operating loop is:

**Discover → Define → Prototype → Evaluate → Build → Launch → Measure →
Learn → Repeat.**

Do not treat the steps as a rigid waterfall. New evidence can send you
back to customer discovery, product definition, technical design, or
positioning.

------------------------------------------------------------------------

# Part I --- Start with the problem, not the technology

## 1. Write down the startup hypotheses

Before coding, write one page that states what must be true for the
business to work.

### Customer hypothesis

-   Who experiences the problem?
-   Who uses the solution?
-   Who pays for it?
-   Who approves or blocks adoption?
-   In what context does the problem occur?

### Problem hypothesis

-   What job is the customer trying to get done?
-   What makes the current approach slow, expensive, risky, confusing,
    or frustrating?
-   How frequently does the problem occur?
-   What happens if the customer does nothing?
-   What workaround is already being used?

### Solution hypothesis

-   What is the smallest outcome the product can deliver?
-   Why might this approach be better than the current workaround?
-   What must be automated, and what can remain manual initially?
-   Why is AI necessary, if it is necessary at all?

### Business hypothesis

-   Who pays, how much, and from which budget?
-   What triggers a purchase?
-   How will customers discover the product?
-   What will it cost to serve each customer?
-   What could make customers stay, expand, or leave?

### Technical hypothesis

-   Can the proposed experience be built with available data and
    systems?
-   What does the model need to know?
-   What happens when the model is wrong, unavailable, slow, or
    expensive?
-   Are there privacy, security, legal, or compliance constraints?
-   What quality threshold must be met before launch?

**Rule:** Label assumptions as assumptions. Do not present a guess as a
customer fact.

## 2. Define a narrow first customer

Avoid starting with "everyone," "all businesses," or "anyone who uses
AI."

Create a specific initial customer profile:

-   **Role:** Who has the problem?
-   **Organization/context:** Where do they work or what situation are
    they in?
-   **Trigger:** What event makes the problem urgent?
-   **Current workaround:** How do they handle it today?
-   **Pain:** What does the workaround cost in time, money, quality, or
    risk?
-   **Buying authority:** Can this person pay or influence the purchase?
-   **Reachability:** Can you find ten more people like this?

A useful initial segment is narrow enough to interview, reach, and
understand. It can expand later.

## 3. Conduct customer discovery using The Mom Test

The Mom Test's core lesson is to ask about the other person's life and
past behavior rather than pitching your idea and asking whether they
like it.

### Good interview principles

-   Ask about specific events that have already happened.
-   Ask what the person did, what happened next, and what it cost.
-   Ask about existing tools, workarounds, budgets, and decision
    processes.
-   Listen more than you speak.
-   Avoid explaining the solution too early.
-   Separate facts from interpretation.
-   Ask for evidence of commitment when appropriate, such as access to a
    workflow, a follow-up meeting, a pilot, or a paid trial.

### Example questions

1.  "Tell me about the last time you had to do \[job\]."
2.  "What triggered it?"
3.  "Walk me through how you handled it."
4.  "What was the most difficult part?"
5.  "How often has this happened in the last month?"
6.  "What have you tried already?"
7.  "What did that solution cost---in money or time?"
8.  "Who else was involved in the decision?"
9.  "What happens if this is not solved?"
10. "Can you show me an example of the workflow or artifact, with
    confidential details removed?"

### Questions to avoid

-   "Would you use an app that does this?"
-   "Do you think this is a good idea?"
-   "Would you pay for this someday?"
-   "Is this feature useful?"
-   "Don't you hate how much time this takes?"

These invite politeness, speculation, or agreement rather than evidence.

### Interview note template

For each conversation, record: - Customer segment and role - Date and
context - Last concrete occurrence of the problem - Existing workflow
and tools - Frequency and severity - Time/money/risk impact - Current
workaround and dissatisfaction - Buying process and budget owner - Exact
evidence observed - Your interpretation (kept separate) - Open questions
and next action

### Evidence hierarchy

From weaker to stronger evidence: 1. Compliments and opinions 2. General
claims about future intent 3. Specific past behavior 4. Repeated, costly
problem with an existing workaround 5. Customer shares workflow/data or
introduces the decision-maker 6. Customer commits time to a pilot 7.
Customer pays or makes a credible purchasing commitment 8. Customer
repeatedly uses the product and renews/pays again

This is a practical hierarchy, not a universal law. A free pilot may be
useful evidence, but it is not proof of willingness to pay.

### Discovery decision gate

Proceed to a focused solution prototype when: - A recognisable segment
repeatedly describes the same problem. - The problem has meaningful
consequences. - Customers already spend time, money, or effort
addressing it. - You can identify a reachable initial group. - You can
explain why current alternatives are insufficient. - At least some
people are willing to take a concrete next step.

If evidence is weak, change the segment or problem before building more.

------------------------------------------------------------------------

# Part II --- Turn discovery into a product

## 4. Apply INSPIRED: product value, usability, feasibility, viability

A good product is not simply a feature list. It must solve a real
problem, be understandable and usable, be technically achievable, and
work for the business.

Evaluate product ideas across four dimensions:

### Value

-   Does the product solve a problem the target customer cares about?
-   Is the improvement meaningful compared with the current alternative?
-   Will users change their behavior to get the outcome?

### Usability

-   Can a first-time user understand what to do?
-   Is the core workflow clear?
-   Does the product communicate limitations and next steps?
-   Can users recover from mistakes?

### Feasibility

-   Can the team build and operate it with available skills, time, data,
    and budget?
-   What integrations, permissions, and infrastructure are needed?
-   Which parts are technically uncertain?

### Business viability

-   Can the product be sold and delivered sustainably?
-   Does pricing fit the customer's value and budget?
-   Are security, legal, support, and operational requirements
    manageable?
-   Does the product fit the company's strategic direction?

A product can fail if any one of these dimensions is ignored.

## 5. Define the product's first promise

Write a concise product promise:

> For **\[specific customer\]** who needs to **\[job or outcome\]**, the
> product helps them **\[measurable result\]** by **\[distinctive
> approach\]**, unlike **\[current alternative\]**.

Example (illustrative only):

> For small recruiting teams that manually review large applicant
> queues, the product helps organise and summarise applications against
> a defined rubric, while keeping human reviewers in control of final
> decisions.

This is stronger than "an AI recruitment platform," because it names a
customer, job, outcome, and operating boundary.

## 6. Map the end-to-end user journey

Map the full path, not just the main screen:

1.  **Trigger:** Why does the user arrive?
2.  **Entry:** How do they sign up or gain access?
3.  **Input:** What information or action is required?
4.  **Core value:** What useful result do they receive?
5.  **Review:** How do they judge, correct, or approve the result?
6.  **Completion:** What action finishes the job?
7.  **Return:** Why would they come back?
8.  **Recovery:** What happens if the input is invalid, the model fails,
    or the user disagrees?

Mark every step that creates friction. The first product should optimise
for delivering the core outcome, not for having many screens.

## 7. Write an MVP specification

An MVP is the smallest credible product or experiment that tests the
most important business and product assumptions. It is not necessarily a
low-quality or incomplete software application.

### MVP one-page template

-   **Target user:**
-   **Problem and evidence:**
-   **Desired outcome:**
-   **Core workflow:**
-   **Must-have capabilities:**
-   **Explicitly out of scope:**
-   **Manual steps allowed at first:**
-   **Risks to test:**
-   **Success metric:**
-   **Quality and safety thresholds:**
-   **Pilot users:**
-   **Decision date:**
-   **Decision rules:** Continue, change, or stop.

### Prioritise features by evidence

For each candidate feature, estimate: - Customer pain addressed - Number
of target users affected - Impact on the core outcome - Confidence in
the evidence - Build and maintenance cost - Risk introduced - Whether it
is necessary to test the main hypothesis

Build the smallest set of capabilities that produces a complete, useful
outcome. Avoid adding features because competitors have them or because
a model makes them easy to demo.

## 8. Prototype before committing to full implementation

Use the cheapest realistic method that can test the assumption: - Paper
sketches or clickable mockups for usability - Concierge/manual service
for workflow demand - Scripted demo for concept comprehension -
Wizard-of-Oz prototype for testing an experience before automating it -
Small technical spike for feasibility - Limited pilot for real-world
value and operational risk

Be transparent about what is automated and what is manual when customers
could reasonably rely on that distinction.

### Prototype test

Give a target user a realistic task. Observe whether they can complete
it without excessive help. Ask what they expected, where they hesitated,
what they trusted, and what they would do next. Do not rely only on "Did
you like it?"

------------------------------------------------------------------------

# Part III --- Use Lean Startup to learn quickly

## 9. Build--Measure--Learn

Every development cycle should test a stated hypothesis.

### Build

Create the smallest experiment capable of producing useful evidence. It
might be an interview, landing page, manual service, prototype, model
evaluation, or software feature.

### Measure

Collect behavior and outcomes tied to the hypothesis---not vanity
metrics alone.

### Learn

Compare the evidence with your prediction. Decide what to do next: -
**Persevere:** Evidence supports the hypothesis. - **Iterate:** The
problem is real, but the solution or workflow needs improvement. -
**Pivot:** A core assumption is not supported; change a meaningful part
of the strategy. - **Stop:** The opportunity no longer justifies the
resources.

### Experiment card

-   **Hypothesis:** We believe [customer](#customer) will \[behavior\]
    because \[reason\].
-   **Risk:** If false, \[consequence\].
-   **Experiment:** We will \[smallest credible test\].
-   **Audience/sample:** \[who and how selected\].
-   **Primary metric:** \[observable outcome\].
-   **Guardrails:** \[quality, safety, cost, or user-experience
    limits\].
-   **Expected result:** \[threshold and rationale\].
-   **Duration:** \[timebox\].
-   **Result:** \[observed evidence\].
-   **Decision:** \[persevere, iterate, pivot, stop\].
-   **Next experiment:** \[action\].

Set the threshold before running the test where practical. This reduces
the temptation to reinterpret disappointing results as success.

## 10. Avoid common Lean Startup mistakes

-   **MVP as excuse for poor quality:** Keep the scope small, but
    protect the core experience and user trust.
-   **Vanity metrics:** Sign-ups without activation or retention can be
    misleading.
-   **Premature scaling:** Do not scale acquisition before users
    reliably reach value.
-   **Feature accumulation:** More features do not prove product-market
    fit.
-   **Confirmation bias:** Seek disconfirming evidence and record failed
    experiments.
-   **False certainty from tiny samples:** Early interviews are
    directional; treat small samples as learning, not population-level
    proof.
-   **Changing too many variables at once:** Make experiments
    interpretable.
-   **Endless discovery:** Eventually test real behavior with a working
    solution and real users.

## 11. Use a staged evidence model

### Stage A --- Problem evidence

Can you show that the problem is repeated, painful, and attached to a
reachable segment?

### Stage B --- Solution evidence

Can users understand and successfully complete the core workflow?

### Stage C --- Value evidence

Does the product materially improve the outcome compared with the
existing alternative?

### Stage D --- Retention evidence

Do users return when the problem recurs, or do they keep using the
product in a meaningful workflow?

### Stage E --- Commercial evidence

Will customers pay at a price that supports delivery and growth?

### Stage F --- Repeatability evidence

Can you acquire and serve customers repeatedly without heroic founder
effort or unsustainable economics?

Do not treat these as perfectly linear gates. They are a practical
checklist for avoiding premature conclusions.

------------------------------------------------------------------------

# Part IV --- Engineer the AI product, not just the demo

## 12. First decide whether AI is the right tool

Use AI when the task benefits from language understanding, synthesis,
generation, flexible classification, retrieval over unstructured
information, or other capabilities that are difficult to specify with
conventional rules alone.

Prefer ordinary software when deterministic rules, simple database
queries, or structured workflows can solve the problem more cheaply and
reliably.

Ask: - Does AI improve the user outcome enough to justify added
variability? - Can the output be evaluated? - What is the cost of a
wrong answer? - Is a human review step needed? - Is there sufficient
data or context? - Could a simpler baseline perform well enough?

The customer buys the outcome, not the use of a particular model.

## 13. Design the AI system as a complete pipeline

A typical AI application may include:

1.  User interface and authentication
2.  Input validation and permissions
3.  Data retrieval or context construction
4.  Prompt and model orchestration
5.  Model inference
6.  Output validation and post-processing
7.  Human review or confirmation, where needed
8.  Storage, logging, and feedback
9.  Monitoring, evaluation, and incident handling

For a retrieval-augmented generation (RAG) system, add document
ingestion, parsing, chunking, indexing, retrieval, ranking, and source
attribution. RAG is not automatically necessary; use it when external or
private knowledge must ground the response.

For an agentic system, explicitly define available tools, permissions,
action limits, approval gates, timeouts, retries, and what the agent may
not do.

## 14. Create an evaluation set before optimising prompts

Do not evaluate an AI system by trying a few happy-path examples.

Build a representative test set containing: - Common, ordinary
requests - Difficult or ambiguous inputs - Missing, malformed, or
conflicting information - Rare but important cases - Adversarial or
prompt-injection attempts, where relevant - Privacy and permission edge
cases - Cases where the correct answer is "I don't know" or "escalate" -
Known failures from real users, with sensitive information removed

For each case, define what a good output means. Depending on the task,
evaluate correctness, completeness, relevance, groundedness, format
adherence, latency, cost, and safety.

### AI evaluation workflow

1.  Define task-specific quality criteria.
2.  Create a labelled baseline dataset.
3.  Run a baseline model and record results.
4.  Change one major factor at a time where possible.
5.  Compare results on the same test set.
6.  Review failure examples---not only aggregate scores.
7.  Add production failures to the test set.
8.  Re-run the suite after prompt, model, retrieval, or code changes.

Use automated metrics where valid, human review where needed, and
model-based judging cautiously. An LLM judge can be useful but is not
ground truth; validate it against human assessments.

## 15. Choose architecture and models by task requirements

Evaluate candidate models and providers on: - Task quality - Latency and
throughput - Cost per successful task - Context-window needs -
Structured-output support - Tool-calling reliability - Privacy and
data-handling requirements - Availability, rate limits, and operational
maturity - Portability and switching costs

Benchmark on your own task-specific evaluation set. Public model
rankings do not reliably predict performance on your product's workflow.

Start with the simplest architecture that meets the quality and latency
requirements. Add model routing, fine-tuning, complex agents, or
multiple stages only when evidence shows they solve a real limitation.

## 16. RAG, fine-tuning, and prompting are different tools

### Prompting

Use when behaviour can be improved by instructions, examples,
constraints, or clearer task decomposition.

### RAG

Use when the model must consult changing, private, or large bodies of
knowledge and provide traceable evidence.

### Fine-tuning

Consider when you have sufficient high-quality examples and need
consistent task behaviour, style, format, or specialised performance
that prompting alone cannot achieve economically.

These approaches can coexist, but none is a universal fix. Poor data,
unclear requirements, or weak evaluation will not be solved
automatically by fine-tuning.

## 17. Treat reliability as a product feature

Plan for: - Model/provider timeouts and outages - Rate limits and retry
policies - Invalid structured outputs - Empty or poor retrieval
results - Hallucinations and unsupported claims - Prompt injection and
malicious input - Duplicate requests and partial failures - Model or
prompt regressions - Unexpected cost spikes - User corrections and
escalation

Possible controls include schema validation, bounded retries, fallbacks,
caching where appropriate, source citations, confidence thresholds,
human approval, rate limits, and safe failure states.

Do not blindly retry actions with side effects. Use idempotency and
explicit confirmation for consequential operations.

## 18. Privacy, security, and responsible use

Before launch, document: - What data is collected and why - What is sent
to third-party model providers - Data retention and deletion practices -
Access controls and tenant isolation - Encryption and secret
management - Logging exclusions for sensitive content - User consent and
disclosure requirements - Legal and regulatory obligations in target
markets - Abuse scenarios and incident response - Human review and
appeal paths for high-impact decisions

Never put API keys or secrets in client-side code, public repositories,
prompts, or logs. Use least-privilege access and environment-based
secret management.

For high-impact areas---such as health, finance, hiring, education, or
legal decisions---conduct domain-specific risk assessment and expert
review. Keep accountable humans in control where required. This manual
is not legal advice.

## 19. Monitor AI quality and unit economics in production

Track: - Task success and user acceptance - Error and escalation rates -
Groundedness or factuality where relevant - Retrieval quality for RAG -
Latency percentiles - Cost per request and per successful task - Retry
and timeout rates - Model/provider error rates - User corrections and
complaint patterns - Performance by meaningful user or task segment

Define an alert threshold and an owner for each critical failure mode.
Monitor both average performance and severe tail failures; averages can
hide dangerous edge cases.

### Cost model

Estimate:

**Cost per successful task = (model + retrieval + tools +
infrastructure + review/support costs) / number of successfully
completed tasks**

This is a practical approximation. Include failed attempts and retries
in the numerator. Compare costs with the value delivered and the price
customers will pay.

------------------------------------------------------------------------

# Part V --- Build the software foundation

## 20. A practical architecture for an early AI product

The exact stack depends on the product, team, and deployment needs. A
common architecture is:

-   **Frontend:** Web or mobile interface
-   **Backend/API:** Authentication, business logic, permissions,
    orchestration
-   **Database:** Users, organisations, application state, and product
    records
-   **Object storage:** Uploaded files and generated artifacts, where
    required
-   **AI provider:** Model inference and tool APIs
-   **Retrieval layer:** Search or vector indexing only if needed
-   **Background jobs:** Long-running or asynchronous tasks
-   **Observability:** Logs, metrics, traces, and error reporting
-   **Deployment pipeline:** Tests, staging, production, rollback

Choose boring, well-supported technology unless a specific requirement
justifies complexity. Avoid microservices, custom model training, and
elaborate infrastructure before they are needed.

## 21. Engineering practices from day one

-   Keep code in version control.
-   Use separate development, staging, and production environments.
-   Store secrets securely.
-   Add automated tests for business logic and critical flows.
-   Add AI evaluation tests for model-dependent behaviour.
-   Use code review---even if initially performed by the founder.
-   Keep database migrations and deployment steps repeatable.
-   Monitor errors and performance.
-   Maintain backups and test restoration.
-   Document setup, architecture, and operational procedures.
-   Use feature flags or gradual rollouts for risky changes.
-   Keep a rollback plan for each meaningful release.

Security and maintainability are cheaper to establish early than to
retrofit after customer data and revenue depend on the product.

## 22. Define product requirements clearly

A lightweight product requirements document (PRD) should include: 1.
Problem and evidence 2. Target user and use case 3. Desired user outcome
4. Scope and explicit non-goals 5. User journey and edge cases 6.
Functional requirements 7. Quality attributes: performance, reliability,
privacy, accessibility 8. AI behaviour and evaluation criteria 9.
Analytics events and success metrics 10. Rollout plan and rollback
conditions 11. Open questions and decision owners

Avoid vague requirements such as "make it smart," "make it seamless," or
"use the best model." Define observable behaviour and acceptance
criteria.

## 23. Release checklist

Before exposing a product or significant feature to real users: - Core
workflow works end to end. - Common failures have understandable
recovery paths. - Authentication and permissions are tested. - Data
access is restricted appropriately. - AI evaluation passes the agreed
threshold. - Cost and latency are measured. - Logs do not expose secrets
or unnecessary sensitive data. - Usage analytics are verified. - Support
and incident ownership are clear. - Backups and rollback are ready. -
Users understand limitations. - A small pilot or staged rollout is
available.

------------------------------------------------------------------------

# Part VI --- Measure product outcomes

## 24. Define one primary product metric

Choose a metric that reflects users receiving the product's core value.
A useful metric is an observable outcome, not merely activity.

Examples (choose based on the product): - Completed reports accepted by
the user per active team per week - Successful workflows completed
without manual rescue - Time saved per completed task, validated against
a baseline - Qualified cases resolved within a target time - Repeated
successful use by the target customer segment

Avoid selecting a metric simply because it rises easily.

## 25. Build a balanced metric framework

### Acquisition

How do relevant people discover the product? - Qualified visitors or
leads - Cost per qualified lead - Lead-to-sign-up conversion

### Activation

Do new users reach value? - Percentage completing the core workflow -
Time to first successful outcome - Drop-off at each onboarding step

### Engagement and retention

Do users return when the problem recurs? - Weekly/monthly active target
customers - Cohort retention - Frequency of successful core actions -
Repeat usage by account or user segment

### Revenue

Does value translate into a sustainable business? - Trial-to-paid
conversion - Paid customer count - Average revenue per account -
Expansion and churn - Gross margin

### Quality and guardrails

Does the product remain dependable? - Task success and error rates - AI
quality and escalation rates - Latency - Cost per successful outcome -
Complaints, incidents, and privacy/security events

Instrument only events that answer a question. Define every event and
metric precisely so the team does not count the same thing differently.

## 26. Instrument the core journey

For a generic AI workflow, useful events may include: -
`signup_completed` - `onboarding_completed` - `core_task_started` -
`core_task_completed` - `result_accepted` - `result_edited` -
`result_rejected` - `task_escalated` - `subscription_started` -
`subscription_cancelled`

These are examples, not a universal schema. Define properties, identity
rules, timestamps, and privacy limits. Avoid collecting unnecessary
content from user prompts or documents.

## 27. Interpret metrics carefully

-   Sign-ups are not product-market fit.
-   Activity is not necessarily value.
-   A high task completion rate can hide low-quality results.
-   A low cost per request can hide a high cost per successful task.
-   Retention can be misleading if the product is used for a one-time
    job.
-   Averages can conceal differences across customer segments.
-   Correlation does not prove a feature caused a change.
-   Small samples create uncertainty.

Pair quantitative analytics with interviews, support conversations,
session observation, and task-level quality review.

------------------------------------------------------------------------

# Part VII --- Find traction and build a business

## 28. Use Traction to test acquisition channels systematically

Traction's central practical idea is to test channels rather than assume
one will work. Potential channels include: - Targeted outbound - Content
and search - Communities and audience building - Partnerships and
integrations - Public relations - Paid advertising - Events and
speaking - Marketplaces and app ecosystems - Referral and word of
mouth - Sales-led or founder-led selling

Not every channel fits every product. A technical developer tool, a
consumer application, and enterprise workflow software may need very
different acquisition strategies.

## 29. Choose channels based on customer and buying behaviour

For each channel, estimate: - Does the target customer spend time
there? - Can you reach them with a relevant message? - How quickly can
you test it? - What does a qualified lead cost? - Can the channel
scale? - Does it produce customers who activate and retain? - Is it
compatible with the expected contract value and sales cycle?

Run small, bounded experiments. Compare channels on qualified customers
and downstream value---not raw clicks alone.

### Example channel experiment

-   Segment: a narrowly defined group of potential buyers
-   Channel: personalised outbound
-   Message: a concrete pain and outcome, not a generic AI pitch
-   Offer: a short workflow review or pilot
-   Sample: a defined list of suitable prospects
-   Primary measure: qualified conversations or pilot commitments
-   Guardrails: time spent, response quality, and reputational risk
-   Decision: refine, continue, or test a different channel

Use honest, relevant outreach and follow applicable privacy and
anti-spam requirements.

## 30. Create positioning that explains the value

A strong message answers: - Who is this for? - What painful job does it
solve? - What outcome improves? - Why is it different from the current
alternative? - Why should the customer believe the claim?

Prefer a concrete promise over generic claims like "revolutionary AI,"
"next-generation intelligence," or "10x productivity" without evidence.

Test multiple messages with the same target segment. Track which
messages lead to qualified conversations, product activation, and paid
adoption.

## 31. Pricing and business model

Pricing should reflect the value delivered, the buyer's budget,
alternatives, delivery costs, and willingness to pay.

Possible models: - Subscription per user or team - Usage-based pricing -
Tiered plans - Per-workflow or per-outcome pricing - Enterprise
contracts - Service-assisted onboarding or implementation

Questions to answer: - Who controls the budget? - What is the customer's
economic benefit? - What costs vary with usage? - What usage could make
the product unprofitable? - What plan limits are understandable? - How
will you handle overages and unexpected consumption? - What level of
support does each tier require?

Test pricing with real buying conversations and offers. Survey answers
alone are weak evidence. Do not underprice indefinitely just to obtain
early users; understand the cost to deliver and support the product.

## 32. Track basic startup economics

At minimum, estimate: - Revenue per customer or account - Variable cost
to serve - Gross profit and gross margin - Acquisition cost - Sales
cycle and payback period - Retention and churn - Support and onboarding
burden - Cash burn and runway

For AI products, include inference, retrieval, tool calls, storage,
observability, human review, and support in service costs where
applicable.

A business can grow and still become less healthy if every new customer
increases costs faster than revenue.

------------------------------------------------------------------------

# Part VIII --- Product-market fit and scaling

## 33. Look for converging evidence of product-market fit

There is no single magic metric that proves product-market fit. Look for
multiple signals: - A clear segment repeatedly experiences the
problem. - Users get the promised outcome. - They return when the job
recurs. - Customers recommend or refer others. - Customers pay, renew,
or expand. - Acquisition becomes more repeatable. - The team can explain
why customers choose and keep the product. - Retention and customer
value are strong enough to support the business model.

Be wary of growth driven only by novelty, incentives, one-off publicity,
or founder relationships.

## 34. Scale only after identifying what is repeatable

Before accelerating acquisition: - The target segment is reasonably
clear. - Activation is understood and improving. - The product delivers
reliable value. - Retention has been observed over a relevant period. -
Acquisition channels show credible promise. - Unit economics are
understood. - Customer support and incident handling can cope. - AI
quality, latency, and costs remain controlled under load.

Scaling an unvalidated product multiplies uncertainty and waste.

## 35. Build a learning cadence

A small team can use a simple weekly rhythm:

### Weekly

-   Review customer conversations and support issues.
-   Review activation, retention, revenue, and quality signals.
-   Inspect AI failures and add representative cases to evaluations.
-   Review experiment results and decide what changed.
-   Select the highest-risk assumption for the next cycle.
-   Assign owners and deadlines.

### Monthly

-   Reassess the target segment and positioning.
-   Review channel performance and pipeline.
-   Review pricing, margin, AI cost, and runway.
-   Review security, privacy, and operational risks.
-   Stop initiatives that lack evidence.
-   Update the product roadmap from observed user outcomes.

The cadence should support decisions, not create meetings for their own
sake.

------------------------------------------------------------------------

# Part IX --- An actionable 90-day plan

This is a sample plan, not a promise that every startup can validate and
launch within 90 days. Enterprise procurement, regulated domains,
complex integrations, and high-risk AI applications may require much
longer.

## Days 1--15: Discover

-   Write the startup hypothesis sheet.
-   Choose one narrow customer segment.
-   Identify and contact potential interviewees.
-   Conduct roughly 10--15 problem interviews if access permits.
-   Document actual workflows, alternatives, urgency, and buying
    processes.
-   Identify the riskiest assumptions.
-   Decide whether the problem deserves further testing.

**Deliverables:** Customer profile, interview notes, evidence summary,
problem statement, and decision memo.

## Days 16--30: Define and prototype

-   Write the product promise.
-   Map the end-to-end user journey.
-   Draft a one-page MVP specification.
-   Sketch the core workflow.
-   Test a prototype or manual version with target users.
-   Ask users to complete realistic tasks.
-   Test whether the proposed result is valuable and understandable.
-   Set initial quality and success thresholds.

**Deliverables:** Prototype, revised requirements, initial evaluation
criteria, and pilot commitments where possible.

## Days 31--45: Prove technical feasibility

-   Build the smallest end-to-end technical slice.
-   Compare a simple baseline with the AI approach.
-   Create a representative AI evaluation set.
-   Measure quality, latency, and cost.
-   Implement authentication, permissions, validation, and basic
    logging.
-   Test failure and recovery paths.
-   Decide whether the current technical approach is viable.

**Deliverables:** Working prototype, baseline evaluation report,
architecture notes, risk register, and unit-cost estimate.

## Days 46--60: Build the MVP

-   Implement only the core workflow.
-   Add analytics for activation and successful outcomes.
-   Build user feedback and correction paths.
-   Test AI quality, security, and common edge cases.
-   Run internal tests and a small controlled pilot.
-   Collect observed behaviour and support issues.
-   Fix failures that block the core outcome.

**Deliverables:** Pilot-ready product, instrumentation, release
checklist, and known-limitations documentation.

## Days 61--75: Pilot and learn

-   Onboard a small set of target users.
-   Observe their real workflows.
-   Measure activation, task success, repeat use, quality, latency, and
    cost.
-   Interview users after they have tried the product.
-   Investigate non-use and rejection, not just positive feedback.
-   Improve the most important friction points.
-   Test whether a real buyer will pay.

**Deliverables:** Pilot results, updated evaluation set, customer
evidence, pricing hypotheses, and a continue/change/stop decision.

## Days 76--90: Test repeatability

-   Select one or two plausible acquisition channels.
-   Run bounded experiments.
-   Track qualified conversations, activation, conversion, and
    downstream retention.
-   Refine positioning based on actual customer language.
-   Review service costs and gross margin assumptions.
-   Strengthen reliability and support processes.
-   Plan the next 90 days around the biggest unresolved risk.

**Deliverables:** Channel test results, initial commercial model, metric
baseline, operational checklist, and evidence-based roadmap.

### Day-90 decision

Do not ask only, "Did we launch?" Ask: - Did we identify a real,
repeated problem? - Did target users achieve the intended outcome? - Did
they return or express concrete commitment? - Is AI quality adequate for
the use case? - Can we deliver the outcome at sustainable cost? - Can we
reach more customers like the initial users? - What is the strongest
evidence against continuing?

A "no" answer is not automatically failure. Discovering a false
assumption early can save months of work.

------------------------------------------------------------------------

# Part X --- Reusable founder templates

## Template A: One-page startup brief

**Working name:**

**Target customer:**

**Problem:**

**Evidence the problem exists:**

**Current alternatives:**

**Why alternatives are insufficient:**

**Product promise:**

**Why AI is needed:**

**Core workflow:**

**Primary success metric:**

**Quality and safety guardrails:**

**Business model hypothesis:**

**First acquisition channel:**

**Largest assumptions:**

**Next experiment:**

**Decision date:**

## Template B: Product requirements document

**Problem and evidence**

**Target users and context**

**Desired outcome**

**User journey**

**Functional requirements**

**Non-goals**

**AI behaviour and expected limitations**

**Evaluation dataset and acceptance criteria**

**Privacy/security requirements**

**Analytics events**

**Latency and cost limits**

**Failure and recovery states**

**Rollout plan**

**Rollback conditions**

**Open questions and owners**

## Template C: AI evaluation record

**Task/use case:**

**Model and version:**

**Prompt/configuration version:**

**Dataset version:**

**Expected behaviour:**

**Quality criteria:**

**Baseline results:**

**New results:**

**Failure examples:**

**Cost and latency:**

**Safety/privacy findings:**

**Release decision:**

**Follow-up work:**

## Template D: Weekly founder review

1.  What did we learn from customers?
2.  What did users actually do?
3.  Did the core metric improve, decline, or remain uncertain?
4.  What are the largest AI failures?
5.  What is the cost per successful outcome?
6.  What experiment finished this week?
7.  What evidence contradicted our assumptions?
8.  What is the single highest-risk assumption now?
9.  What will we test next?
10. What should we stop doing?

## Template E: Risk register

For each risk, record: - Risk description - Likelihood - Impact - Early
warning signal - Mitigation - Contingency - Owner - Review date

Include customer demand, technical feasibility, AI quality,
privacy/security, legal/compliance, cost, distribution, competition, and
founder/team capacity.

------------------------------------------------------------------------

# Part XI --- Common startup failure modes

  -----------------------------------------------------------------------
  Failure mode            Why it is dangerous     Better practice
  ----------------------- ----------------------- -----------------------
  Building before         Solves a guessed        Interview around past
  discovery               problem                 behaviour and existing
                                                  workarounds

  Asking leading          Creates false           Ask neutral questions
  questions               validation              about specific events

  Targeting everyone      Weak message and        Start with a narrow,
                          difficult distribution  reachable segment

  Treating an AI demo as  Ignores reliability,    Evaluate the complete
  a product               UX, cost, and recovery  end-to-end workflow

  No evaluation dataset   Regressions and         Create and maintain
                          failures remain         task-specific tests
                          invisible

  Overengineering early   Delays learning and     Use the simplest
                          increases maintenance   architecture that meets
                                                  requirements

  Adding features without Increases complexity    Tie features to user
  evidence                without improving value outcomes and
                                                  experiments

  Measuring vanity        Creates misleading      Track activation,
  metrics                 progress                successful outcomes,
                                                  retention, and revenue

  Ignoring distribution   Good product remains    Test channels from
                          undiscovered            early on

  Ignoring unit economics Growth can increase     Calculate cost per
                          losses                  successful task and
                                                  gross margin

  Scaling too early       Multiplies a weak       Look for repeatable
                          proposition             value and acquisition
                                                  first

  Ignoring privacy and    Risks user harm and     Apply least privilege,
  security                trust                   secure data handling,
                                                  and clear governance

  Treating model output   Can cause harmful or    Validate, ground,
  as truth                costly errors           escalate, and keep
                                                  humans involved where
                                                  appropriate

  Refusing to pivot       Sunk cost replaces      Predefine decision
                          evidence                criteria and review
                                                  disconfirming evidence
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# Part XII --- The founder's operating principles

1.  **Evidence beats enthusiasm.** Your confidence is not customer
    validation.
2.  **The customer buys an outcome.** AI is a means, not the value
    proposition by itself.
3.  **Distribution is part of the product strategy.** Know how customers
    will find and adopt the solution.
4.  **The MVP must test a real risk.** A smaller product is useful only
    if it generates meaningful learning or value.
5.  **Quality is use-case dependent.** Define what an acceptable answer
    or action means before launch.
6.  **Measure successful outcomes, not just model calls.**
7.  **Treat failure cases as product data.** Add recurring failures to
    tests and fix root causes.
8.  **Keep the architecture proportional to evidence.**
9.  **Do not automate a broken workflow.** Understand the job before
    adding AI.
10. **Trust is an operating requirement.** Privacy, reliability,
    transparency, and recovery affect adoption.
11. **Use real commitments to assess demand.** Compliments are not
    purchases.
12. **Scale what is repeatable.** Do not mistake a one-off success for a
    reliable system.
13. **Record decisions and why you made them.** This prevents the team
    from repeating disproven assumptions.
14. **Learn fast without being reckless.** Experimentation must still
    protect users and their data.
15. **Stop, pivot, or persevere based on evidence.** None of these
    decisions is inherently virtuous; the right decision depends on what
    you learn.

------------------------------------------------------------------------

# How to read and apply the five books

Read them in this order, and create a working artifact after each one:

1.  **The Mom Test** → produce interview notes and a problem-evidence
    summary.
2.  **INSPIRED** → produce a product promise, user journey, and MVP
    specification.
3.  **The Lean Startup** → produce an experiment backlog and decision
    rules.
4.  **AI Engineering** → produce an architecture sketch, evaluation set,
    and operational risk plan.
5.  **Traction** → produce channel hypotheses and a customer-acquisition
    experiment plan.

Do not wait until all five books are finished before speaking to
customers or building small tests. Apply each lesson as you learn it.

## Final checklist: Are you ready to build?

### Customer

-   [ ] I can name a specific initial customer segment.
-   [ ] I have evidence from real past behaviour, not just opinions.
-   [ ] I understand the existing alternative and why it falls short.
-   [ ] I know who uses, buys, and approves the product.

### Product

-   [ ] The desired outcome is clear and measurable.
-   [ ] The core user journey is defined.
-   [ ] The MVP has explicit non-goals.
-   [ ] I have tested the workflow with target users.

### AI and engineering

-   [ ] I have a baseline and a representative evaluation set.
-   [ ] I know the most important failure modes.
-   [ ] Quality, latency, and cost are measured.
-   [ ] Privacy, security, and permissions are addressed.
-   [ ] There is a recovery path when AI fails.

### Business

-   [ ] I have a plausible pricing hypothesis.
-   [ ] I understand the cost to serve a successful task.
-   [ ] I have chosen a channel to test.
-   [ ] I have defined activation, retention, and commercial metrics.

### Learning

-   [ ] The riskiest assumptions are documented.
-   [ ] Experiments have clear success and failure criteria.
-   [ ] I review disconfirming evidence.
-   [ ] I have a date and criteria for the next continue/change/stop
    decision.

**The core idea:** Build a company by repeatedly reducing uncertainty.
Discover a painful problem, design the smallest useful solution,
evaluate AI as a real system, measure actual outcomes, and find a
repeatable path to customers. The code matters---but the evidence that
the code creates durable value matters more.
