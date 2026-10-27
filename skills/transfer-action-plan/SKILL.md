---
name: transfer-action-plan
description: Drafts or checks the action plan learners write at the end of a course, built on implementation intentions, with if-then plans for when, where and how each learner will first use the skill at work, a first use within days, the likely obstacle and what they'll do about it, and the date their manager will review it with them. Use when an L&D manager, learning designer or trainer asks for an action plan page, a personal action plan, a learning action plan, end-of-course commitments, a transfer plan, if-then plans, worked examples for learners, or wants an existing action plan template checked.
---

# Transfer Action Plan

Produces the page learners fill in before they leave a course, with prompts, worked examples for their roles and the trainer's notes for running the planning block. Each plan names the moment a learner will first use the skill, what they'll do, what might get in the way and when their manager will go through it with them. Or checks an action plan page someone already uses.

## When to use

- "Our action plans just say 'give more feedback'. Help me write a better page."
- "Write the action plan for the end of the supervisors' programme."
- "Check our action planning template before the next cohort."
- "Give me worked examples of if-then plans for contact centre team leaders."
- "I've just finished a course and want help writing my own plan."

Wrong tool for the manager's follow-up conversations (use the Manager Follow-Up Guide) or the reminders that go out in the weeks after (use Reinforcement Nudges).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme and the skills or behaviours it teaches. [Claude proposes two or three from the programme name for you to confirm]
2. **Essential:** the learners' roles and the real situations where they'll use the skill. [Claude proposes typical situations for each role, marked for you to confirm]
3. Who reviews the plan with each learner. [their line manager]
4. When the course ends and how soon people can use the skill. [first use within [5] working days; manager review within [10] working days]
5. Format. [one page in the workbook or on the LMS, filled in by hand during a [20]-minute planning block]

Never ask for learners' names or anything about how they're performing. When a learner asks for help with their own plan, use their words, and ask about situations and roles, never about colleagues by name.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any attached workbook page, template or a plan a learner has shared for help. If they've given an existing action plan page or plan, this is a check job: run the Quality checks on it, list each problem with where it sits and why it matters, then write a corrected version. When checking one learner's plan, comment on the wording of the plan and leave the learner out of it.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Build every plan on implementation intentions (Gollwitzer): plans written as "If [situation], then I will [action]" raise the odds that people act. The "if" is a situation the learner will meet at work, with a cue they'll notice: a time, a place or an event ("If a team member comes back late from break on Monday's early shift"). The "then" is one action someone could see or hear ("then I'll have a word with them on their own before the end of the shift, using SBI"). Rewrite any goal such as "give more feedback" or "be more confident" into this form.
4. Write the learner's page with a prompt for each part:
   - **The skill I'll use first:** one behaviour from the course.
   - **My if-then plans:** two or three, each tied to a situation in the learner's real week.
   - **My first use:** a date within [5] working days of the course, and where.
   - **What might get in the way:** the most likely obstacle (no time, nerves, a target that pulls the other way, a colleague doing it the old way), with its own if-then ("If the shift's short and there's no time to talk, then I'll book ten minutes at the start of the next one").
   - **What I need from my manager:** one specific ask.
   - **Review with my manager:** a date within [10] working days, booked before the learner leaves.
   - **What I'll notice if it's working** (optional).
5. Write two worked examples for each learner role from the situations in input 2, each with a different obstacle. Label them as examples, so learners write their own plans in their own words.
6. Write trainer notes for the planning block: learners choose the situation before the action; they swap plans in pairs and test each other ("Would you know that moment had arrived?" "Could someone see you do it?"); they book the manager review in their calendar before they leave. If learners had a conversation with their manager before the course (the Manager Pre-Course Brief skill), start from what they agreed there: Broad and Newstrom's transfer matrix ranks what the manager does before training as the most powerful point for transfer.
7. Set out who owns the plan. It belongs to the learner. They keep it and share it with their manager for the review. If L&D wants to know what gets in the way, it asks learners for their obstacles without names and reports them in aggregate, for example to feed the Barrier Removal Plan. The plan stays out of appraisals, performance ratings and personnel files.
8. Run the Quality checks below and fix what fails before showing anything.
9. Present the page, the worked examples and the trainer notes, then **Assumptions** and **Check before you use it**: that the situations are real for these roles, that managers know a review is coming within [10] working days, and that managers have the time set aside to do it.
10. Offer a .docx, an LMS form version, the Manager Follow-Up Guide for the review conversation, or Reinforcement Nudges to remind learners of their first-use date.

## Output format

**Transfer action plan: [programme], for [learner roles]**

1. **Trainer notes** for the [20]-minute planning block: five or six steps, each with minutes.
2. **My action plan** (the learner's page)
   The skill I'll use first: [behaviour]
   | If (when, where, what happens) | Then I will (what someone would see or hear) |
   | If [situation] | then I will [action] |
   My first use: [date], at [place or moment].
   What might get in the way: [obstacle]. If that happens, then I will [response].
   What I need from my manager: [one ask].
   Review with my manager: [date, booked before I leave].
   What I'll notice if it's working: [optional].
   This plan is mine. I share it with my manager for our review.
3. **Worked examples**: two per role, filled in and labelled "example".
4. **Note for managers**: three or four sentences: the review date, two questions to ask ("What happened when you tried it?" "What got in the way?"), and the learner's one ask to answer.

One page for the learner's plan; the whole pack fits on three.

## Try it

`examples/hallowmere-lead-the-shift-action-plan.md` is the draft action plan page from the Lead the Shift workbook, the first-line management programme at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the page. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every "if" names a work situation with a time, place or event cue, and every "then" names an action someone could see or hear.
- Every plan has two or three if-then statements, all for skills taught on the course.
- The first use has a date within [5] working days of the course.
- At least one likely obstacle is named, with its own if-then response.
- The manager review has a date within [10] working days, booked by the learner before they leave.
- The plan stays with the learner; nothing sends it to a personnel file, rates the learner or links it to appraisals, performance ratings or pay.
- Every action is within the learner's control, or the support it needs is listed as an ask of the manager.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. Claude drafts the page and the examples. Each learner writes their own plan, and their manager coaches them through the first tries. The plan records what someone intends to do, and judges nobody.
- A plan holds the learner's own words about their work and team. It describes other people by role ("a team member"), never by name. Anything L&D collects from plans is gathered without names and reported in aggregate, in line with UK GDPR, the Data Protection Act 2018, the ICO's guidance and your organisation's AI policy.
- Everyone gets the same page and the same review timing. Because the plan stays out of performance decisions, learners can name a real weakness without it counting against them. Check the worked examples for assumptions about who people are or what they can manage.
- Under the Equality Act 2010, reasonable adjustments apply: a learner can talk their plan through, type it, or take extra time, and the page should be accessible. Check the current guidance; this is a draft, never legal advice.
- For safety-critical or regulated skills, the first use happens inside the organisation's procedure, supervised where it requires, and competence sign-off stays with a qualified person under the Health and Safety at Work etc. Act 1974 and any sector rules.
- Dates, situations and the reviewing manager's role come from the user or the learner, or stay as placeholders.
