# AI Synthesis, Product Health & Insights Summary (Module 2)

## Responses
- **Moment of misery / red flag #1 (e.g., “user gave up after 3 tries”):** 38,000 enter the portal, 8,360 start a journey, and about 3,846 reach an agreement. That leaves roughly 4,500 starters who don't finish.
- **Moment of misery / red flag #2:** About 2,592 starters contact an agent within 7 days.
- **Moment of misery / red flag #3:** About 731 new agreements miss a payment within 60 days.
- **Product Health & Insights Summary (Claude's output):** Executive Summary

The underlying capabilities (portal, instalment processing, case management, agent workflows) exist, and nothing in the evidence points to a platform stability failure. The weakness is in how those pieces connect to the consumer: roughly 54% of started journeys end without an agreement, 31% of starters still call an agent within 7 days, and 19% of new agreements fail within 60 days. The headline metric (Self-Service Rate) counts a plan as resolved at creation, so it can improve while real outcomes for consumers, clients and purchased portfolios deteriorate.

Thematic Synthesis
1. Journey Funnel & Drop-off

Of 100,000 consumers contacted monthly, about 38,000 reach the portal and about 8,360 start an instalment journey. About 3,850 of those end in an agreement. The largest absolute loss is between starting and agreeing, which suggests the journey itself, not outreach or portal entry, is where consumers disengage. The brief doesn't say where within the journey consumers leave, so the cause is unverified.

High: About 54% of started journeys (roughly 4,500 consumers a month) end without an agreement; step-level drop-off is not instrumented.
Medium: Journey experience is fragmented across portal, letters, digital reminders and agent processes.
Medium: Only 22% of portal visitors start an instalment journey, so intent or discoverability may be limiting reach.
2. Comprehension & Trust (Discovery/UX)

Early research shows consumers are uncertain, not unwilling. They can't tell what an affordable plan looks like, don't see why income information is requested, and fear that a wrong answer or a missed payment will make things worse. These are trust and clarity failures rather than usability defects. The research also flags that some themes may matter less than they appear.

High: Consumers cannot judge what an affordable agreement looks like.
High: Fear of consequences (wrong answers, missed payments) discourages completion or leads to over-commitment.
Medium: The purpose of requested information is not explained.
Medium: It is unclear whether multiple claims can be handled together.
3. Affordability Data Quality

The affordability step produces unreliable inputs. About 28% of uploaded income documents need clarification or review, which creates downstream manual work. Variable-income consumers like Mara are poorly served by document-centric verification, and asking for documents they can't easily find pushes them toward a call.

High: 28% of uploaded income documents need clarification or review.
Medium: Incomplete affordability information is passed on to agents.
Medium: Variable or shift-based income is not clearly accommodated.
4. Agent Handoff & Operational Load

When consumers escalate, the context doesn't travel with them. Agents repeat identity, affordability and case checks and lack a clear summary, the reason behind any recommendation, data currency, or past communication. This drives avoidable handling time in a function where more than 50% of workload already relates to payment, legal and enforcement processes.

High: 31% of journey starters contact an agent within 7 days.
High: Escalations arrive with insufficient context, forcing repeated checks.
Medium: There is no easy way for agents to correct a bad automated result.
Medium: Agents have limited visibility of prior communication.
5. Outcome Quality & Metric Integrity

This is the main tension in the product. Success measured at plan creation may reward plans that don't hold. About 19% of new agreements miss a payment within 60 days, yet each counted as resolved on creation. For purchased portfolios, where Riverty bears the economics, this can mean lower long-term value despite better short-term numbers. Higher monthly payments, more agreements and fewer calls can each look like success while masking harm.

Critical: SSR counts a plan as resolved at creation, not when it is kept, so it can overstate real resolution.
High: 19% of new agreements miss a payment within 60 days.
High: There is risk of optimising toward unaffordable plans or higher payments at the expense of fairness and portfolio value.
Medium: Vulnerable consumers need an appropriate support path, and none is described.
6. Data, Instrumentation & Scalability

Analytics tooling needs better instrumentation, which limits the ability to locate drop-off or detect subgroup effects. Data quality varies between acquired portfolios, and the pilot (Germany, one segment) must later generalise without client-specific forks.

High: Analytics instrumentation is insufficient for step-level and subgroup analysis.
Medium: Data quality varies across acquired portfolios.
Medium: Local legal rules and client-specific settings are not yet separated from reusable capabilities.
Medium: The risk of proxy discrimination is not yet monitored.
Minor Technical Debt

Uneven chatbot and voicebot coverage across contexts; inconsistent messaging across letters, reminders and portal; and manual follow-up steps for failed agreements.
- **Did the AI catch the specific moment of misery / pain point you found in Step 1?:** Yes
- **Did it smooth over a critical frustration into a generic bullet point?:** Partly. The future state names the right stage, but it smoothed the sharpest part of the Step 1 friction into generic language.
- **Did the AI try to suggest features or a roadmap despite the constraints?:** -
- **Logic leak / hallucination #1 (e.g., “AI suggested a new search bar feature, roadmap leak”):** _(not filled in)_
- **Logic leak / hallucination #2:** _(not filled in)_
