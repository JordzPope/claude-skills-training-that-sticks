---
name: learning-impact-map
description: Drafts or checks a learning impact map for any training programme, following Brinkerhoff's impact map, one page linking each capability the programme builds to the critical actions people take at work, the team results those actions move and the business goals they serve, with a measure, source and owner for each result and the other factors that also move it. Use when someone asks for an impact map, a line of sight from a course to business results, a logic model or results chain for a programme, a way to show the exec team or a sponsor why a programme matters, how a programme links to the business plan, or a check of an impact map before a programme launches.
---

# Learning Impact Map

Produces a one-page map that links what a programme teaches to what people do at work, the team results that should move and the business goals behind them, following Robert Brinkerhoff's impact map. Or checks a map someone has already drawn. The sponsor, each learner's manager and the learners see the same line of sight before the programme starts, and the map becomes the starting point for evaluating it.

## When to use

- "The exec team keeps asking how the complaints course links to our contract targets."
- "Draw me an impact map for the new supervisors' programme."
- "I need a line of sight from this system training to the business plan."
- "Check this impact map before I take it to the sponsor."
- "What should managers expect people to do differently after this course, and why does it matter?"

Wrong tool for deciding whether training is needed at all (use Performance Gap Brief) or for planning how and when to measure each link (use Transfer Evaluation Plan).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** which programme: what it covers and who it's for (an outline, the objectives or a few lines).
2. **Essential:** the business goals it should serve, from the organisation's plan, a contract or the sponsor's own words. [none assumed; left as placeholders until the user supplies them]
3. The team results the sponsor watches, with today's figures and where they come from. [Claude proposes results that fit the goals and marks them for the sponsor to confirm]
4. The on-the-job objectives, if you have them. [Claude drafts critical actions from the outline]
5. Who sponsors the programme and who owns each result. [the sponsor owns the goals; the manager of the relevant team owns each result, marked proposed]

Never ask for data about individual learners. The map works at the level of the role and the team.

## Steps

1. Read what the user has given, including attachments. If they've given an existing impact map, logic model or results chain, this is a check job: run the Quality checks on it, list each problem with the row or cell it's in and why it matters, then write a corrected map.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If they say "just draft it", use the defaults, leave the business goals as placeholders, and list the assumptions.
3. Build from the right-hand side. Brinkerhoff's map has four columns: capabilities, critical actions, key results and business goals. Start with the business goals: one to three, worded the way the organisation words them, each with its source. Starting from the goals keeps the map from turning into a list of course topics.
4. Add the key results: the team or department measures (Brinkerhoff calls them key intermediate results) that would serve each goal if they moved, such as a fix rate, a complaint measure, an SLA count or an audit score. For each, record today's figure, the target and date, the source and the owner. Use measures the organisation already tracks where possible; mark a new one as proposed.
5. Add the critical actions: what people in the role do at work that moves each result, written as a role, an action and a situation ("an adviser confirms the fix with the customer before closing the complaint"). Two to four per result and about eight in all. This column matters most: each action must be something a manager could see happen. Reuse On-the-Job Objectives where they exist.
6. Add the capabilities: the knowledge and skills each critical action needs. Mark whether the programme builds each one (yes, partly, no).
7. Test every link both ways. Left to right: if people can do this, will they do that, and will that move this result? Right to left: what else has to happen for this result to move? Mark each link **evidence** (data, a pilot or past results show it holds) or **assumed**.
8. List the links to watch:
   - capabilities the programme teaches that no critical action needs (cut them, or say why they stay);
   - critical actions the programme doesn't build, and actions people can't take yet because of tools, time, targets or access (send these to Performance Gap Brief or Barrier Removal Plan);
   - other factors that also move each result (staffing, parts supply, another team's work, a system change), so the programme takes neither the blame nor the credit for them.
9. Add a line for each learner's manager: the one or two critical actions to agree with the learner before the course, and the first chance to use them at work. Managers can walk through the map in that conversation.
10. Run the Quality checks and fix what fails.
11. Present the map, then **Assumptions** and **Check before you use it**: the goals and their wording, every figure and target, each proposed measure and owner, and every link marked assumed.
12. Offer a .docx, a Manager Pre-Course Brief built from the critical actions, or a Transfer Evaluation Plan to measure each link.

## Output format

**Learning impact map: [programme]**
For [roles, number]. Sponsor [role]. [Date].

| Capabilities the programme builds | Critical actions at work | Key results (team) | Business goals |
| --- | --- | --- | --- |
| C1 [knowledge or skill] (built: yes, partly, no) | A1 [role, action, situation]; needs C1 | R1 [result]; moved by A1 | G1 [goal]; served by R1 |

One row per critical action. Repeat codes where a capability, result or goal serves more than one row.

**How each result is measured**

| Result | Measure | Now | Target and date | Source | Owner | Other factors that move it |
| --- | --- | --- | --- | --- | --- | --- |
| R1 | [measure] | [figure] | [figure, date] | [report or system] | [role] | [factors] |

**Links to watch**
- Capabilities no action needs: [list, or none]
- Actions the programme doesn't build, or people can't take at work yet: [list, with the cause]
- Links marked assumed: [list]

**For each learner's manager**: before the course, agree [action codes] with the learner. First chance to use them at work: [situation, within how many days].

One page.

## Try it

`examples/hallowmere-complaints-impact-map.md` is a draft impact map for Complaints That Close, the customer advisers' complaints course at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with the outline and the sponsor's notes it was built from. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing the corrected map. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every capability serves at least one critical action, every action moves at least one key result, and every result serves a business goal; anything that breaks the chain is listed under Links to watch.
- Every critical action names a role, an action and a situation a manager could see; none restates knowledge ("understands the policy").
- Every key result has a measure, a current figure or placeholder, a source and an owner; proposed measures and owners are marked and listed under Check before you use it.
- Every business goal has a source the user gave (a plan, a contract or the sponsor); none is invented.
- Every key result names the other factors that also move it, and no line claims the programme alone will move a result.
- Every link is marked evidence or assumed.
- The map fits on one page: three business goals at most and about eight critical actions.

## Guardrails

- The one rule for this pack: "Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill." The map shows what a programme should change for a role. Managers use it to coach, and whether any one person is taking the critical actions is a call for their manager, made with them. Results are shown for teams.
- Personal data: the map needs team and organisation figures only. Data about named learners is personal data under UK GDPR and the Data Protection Act 2018, so aggregate it before pasting it in, and follow the ICO's guidance and your organisation's AI policy.
- Fairness: the critical actions apply to everyone in the role. Where someone needs a reasonable adjustment to take one, their manager agrees it with them under the Equality Act 2010. Never infer or mention protected characteristics.
- Safety and regulated work: where the programme covers safety-critical or regulated tasks, competence sign-off stays with a qualified person under your organisation's procedure.
- Law: check the current versions of the laws and guidance named here. This is a draft, never legal advice.
- No invented facts: goals, figures, targets and owners come from the user or stay as placeholders marked proposed. Put a money value on a link only when the user supplies the figures.
