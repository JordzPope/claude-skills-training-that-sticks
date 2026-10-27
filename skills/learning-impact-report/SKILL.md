---
name: learning-impact-report
description: Drafts or checks a learning impact report for an executive team or board on any training programme, covering what changed in behaviour at work, which results moved, how strong the evidence is for each claim, how the programme contributed alongside other factors, and what to do next, using aggregated data only. Use when an L&D leader asks for a training impact report, an evaluation report, a report on whether a programme worked, a board paper on learning, Kirkpatrick level 3 and 4 results, the ROI of training, or a check of an impact report that may overclaim before it goes to the exec team.
---

# Learning Impact Report

Turns evaluation data into a short report an executive team can trust: what people now do differently at work, which results moved, how strong the evidence is for each claim and what the leaders are asked to decide. Or checks a report someone else wrote and catches the claims the evidence can't carry. It saves the rewrite after a finance director asks "how do you know it was the training?"

## When to use

- "Write up the results of our customer service programme for the exec team."
- "The board wants to know if the management programme was worth it."
- "Turn these survey results and KPI figures into an impact report."
- "Can I say our training delivered a 500% ROI?"
- "Check my impact report before it goes to the Director of People."

Wrong tool for deciding what to measure (use Transfer Evaluation Plan, ideally before the course runs) or for a full ROI study, which needs the Phillips ROI methodology and finance's input from the start.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme and its evaluation data, in aggregate: the Transfer Evaluation Plan if there is one, survey results with response counts, work or system data before and after with dates, and any success case write-up.
2. **Essential:** who reads it and what they have to decide. [the executive team, deciding whether to continue, extend or change the programme]
3. Anything else that changed in the same period and could have moved the same numbers: new systems, staffing, process or contract changes, the season. [I'll ask; nothing is assumed]
4. Programme costs, if you want them shown. [left out]
5. The labels your leaders use. [plain words in the report, with LTEM tiers and Kirkpatrick levels in the evidence table]
6. Length. [two pages plus an appendix]

Never ask for named learners' results, individual scores, health information or protected characteristics. If the data holds them, work from totals, leave the rest out and say so.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including attachments. If they've given a draft report, this is a check job: check every claim against the source data provided, run the Quality checks, list each problem with where it sits and why it matters, then write a corrected report.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. List every claim the data might support. For each, note the figure, the base (n of N), the period and the kind of evidence: work records, system data, observation, survey or interview. Recalculate every percentage from its counts.
4. Grade each claim:

   | Grade | What it needs |
   | --- | --- |
   | **Strong** | a measured change in work records, system data or observation, against a baseline, with a comparison group or a stated method that separates the programme's effect from other factors |
   | **Moderate** | a measured change in work records, system data or observation, against a baseline; other factors named but not separated out |
   | **Limited** | self-report (surveys, interviews), verified success cases, or a measured change with no baseline |
   | **Not shown** | no data, or data that doesn't connect to the claim: move it to "What we don't know yet" |

5. Write the behaviour section first (LTEM tier 7, Kirkpatrick level 3): what people do differently, how many, from which source. Give survey results as a share of respondents with the response rate, labelled self-report.
6. Write the results section (tier 8, level 4): what moved, from what baseline, over what period, which behaviour links to it, and the other changes in the same period. Word each result as contribution, for example "[programme] was one of [n] changes in this period that could have moved this figure". Use "caused", "delivered", "drove" or "because of" only for a claim graded Strong, and state the method beside it.
7. Handle money. Show an ROI only when the data supports the Phillips ROI methodology: the programme's effect isolated by a stated method (a comparison group, trend-line analysis, or estimates from participants or managers adjusted for their confidence); the effect turned into money at a unit value with a source; fully loaded costs (design, delivery, fees, learners' time and cover, evaluation); and the sum shown, ROI % = (benefits minus costs) ÷ costs × 100. Without all four, show costs and results side by side and say no ROI has been calculated. Report benefits that can't fairly be turned into money as intangible benefits.
8. Write "What didn't change and what we don't know yet": behaviours that didn't move, low response rates, missing baselines, and the barriers people reported. A report that shows its limits gets believed on the rest.
9. Write "What's next": two to four decisions or actions, each with an owner by role and a date: extend, change, stop, fix a barrier, measure again.
10. Write the headline last: two or three sentences carrying the strongest claim at its grade, in the same words as the body.
11. Run the Quality checks below and fix what fails before showing anything.
12. Present the report, then a short **Assumptions** list and a **Check before you use it** list: that every figure matches the source system, that the list of other changes in the period is complete, and that each sponsor has seen findings about their area before the exec team does.
13. Offer a .docx, a one-slide summary, or the Barrier Removal Plan skill for what got in the way.

## Output format

**[Programme]: impact report, [period]**
For: [audience]. Prepared by: [role]. Date: [date].

**Headline**: [two or three sentences, the strongest claim at its grade]

**Decision asked of you**: [one line]

**1. What we did**: [programme, who by role and number, when, cost if given; one paragraph]

**2. What changed in behaviour**

| Behaviour | Change, with base and period | Source | Grade |
| --- | --- | --- | --- |

**3. What results moved**

| Result | Baseline | Now | Period | Linked behaviour | Other changes in the period | Grade |
| --- | --- | --- | --- | --- | --- | --- |

[One or two sentences on the programme's contribution.]

**4. What didn't change and what we don't know yet**: [three to five bullets]

**5. What's next**

| Decision or action | Owner (role) | By |
| --- | --- | --- |

**Appendix: evidence table**

| Claim | Source | Base (n of N) | LTEM tier | Kirkpatrick level | Grade |
| --- | --- | --- | --- | --- | --- |

Costs: [as given]. ROI: [only with the method in Step 7 shown in full; otherwise "not calculated"].

Two pages plus the appendix. On a check job, the list of problems comes first and sits outside the two pages; the limit applies to the corrected report.

## Try it

`examples/hallowmere-complaints-impact-report.md` is a draft impact report on Complaints That Close, the complaint-handling course for contact centre advisers at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the report. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every claim has a source, a base (n of N, or the whole population), a period and a grade from the scale in Step 4.
- Every figure matches the data the user gave, or a calculation from it with the working shown.
- No result is credited to the programme with "caused", "delivered", "drove" or "because of" unless it's graded Strong with the method stated; every other result is worded as contribution and names the other changes in the period.
- Any ROI or money figure shows all four parts of Step 7; otherwise it's removed.
- Survey results are labelled self-report and given as a share of respondents, with the response rate.
- Learner data appears only in aggregate for groups of [10] or more: no named or numbered learner, individual score, ranking or identifying quote.
- The report says what didn't change or isn't known, and ends with actions that each have an owner by role and a date.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. This report describes a programme and groups of people. It never lists, ranks or judges an individual learner, and never recommends action on one person's skill; that conversation stays with their manager. For safety-critical or regulated training, competence sign-off stays with a qualified person under the organisation's procedure, whatever the report shows.
- Personal data: results about named people are personal data under UK GDPR and the Data Protection Act 2018. Use aggregated or anonymised data only, quote people only anonymously and with their consent, and follow the ICO's guidance and your organisation's AI policy before pasting anything in.
- Fairness: where one group's results lag (a site, a shift, part-time staff), report the barriers it faced, such as time, rotas, tools and manager support, before anything else. Breakdowns by protected characteristic come only from your organisation's equality monitoring, in aggregate and above the threshold; never infer one. Make the report accessible: every chart gets a one-line text summary and never relies on colour alone.
- Law: check the current versions of the law and guidance named here. This report is a draft, never legal advice.
- No invented facts: every number, date, cost and quote comes from the user's data or stays as a placeholder. Never estimate a figure to fill a gap.
