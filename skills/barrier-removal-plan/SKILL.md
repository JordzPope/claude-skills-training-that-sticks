---
name: barrier-removal-plan
description: Drafts or checks a barrier removal plan for one training programme, setting out what in the work stops people using what they learned (no time, missing tools or access, targets or KPIs that reward the old way, little manager support, no chance to apply it, conflicting instructions) with the evidence for each barrier, the fix, the owner who can make it (often outside L&D), a date and how you'll know it's fixed. Use when a Head of L&D, L&D manager or L&D business partner says people aren't using the training, asks why a course isn't sticking, or wants a list of blockers after training, a transfer barrier analysis, an action plan to remove obstacles to applying learning, or a paper for operations leaders on what's getting in the way.
---

# Barrier Removal Plan

Produces a plan that names what in the work stops people using what they learned, the evidence for each barrier, the fix, the role that can make it and a date. Or checks a plan someone has already written. It turns "people aren't using it" into a list of things managers, planners, IT and directors can change, each with an owner named by role.

## When to use

- "Six weeks after the rollout, half the engineers still close jobs on paper. Why, and what do we do?"
- "Our advisers say the course was great but they can't do it on the phones. Help me pin down what's in the way."
- "Write a plan I can take to the ops director about what's stopping people using the training."
- "Check this list of blockers before I share it with the leadership team."
- "The manager check-ins keep coming back with 'no chance to use it'. Turn that into actions."

Wrong tool for problems in the course itself (use Session Plan Rework), for spotting risks before a programme starts (use the Transfer Risk Audit), or for measuring use at day 60 (use the Application Survey).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme and the two to four behaviours people should now be showing at work.
2. **Essential:** what you know about why it isn't happening, and where that comes from: survey results, manager check-in themes, peer circle themes, system data, complaints, conversations. [nothing gathered yet; Claude proposes a quick way to find out]
3. Who the learners are and where they work, by role and site. [one role group across all sites]
4. Who sets the targets, rotas, systems and procedures for this group, by role. [proposed from the user's description and marked for checking]
5. When the plan goes to owners and when it's reviewed. [owners within 2 weeks; review 6 weeks after that]

Never ask for names, individual survey responses, health details or protected characteristics. Evidence comes as counts and themes. If the user pastes anything that identifies a person, work from the theme and say you've done so.

## Steps

1. Read what the user has given, including any attached survey summary, check-in themes or usage report. If they've given an existing barrier plan, blockers list or action log, this is a check job: run the Quality checks on it, list every problem with where it sits and why it matters, then write a corrected plan.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. If there's little or no evidence, propose a quick way to get it: two questions ("What's made it easier to [behaviour] at work?" and "What's got in the way?") put to [6 to 8] learners and [3 or 4] of their managers across sites, or added to the next manager check-ins, reported back as themes. Draft from what's known and mark each unconfirmed barrier "suspected".
4. List the barriers in the work. Baldwin and Ford (1988) name three inputs to transfer: the learner, the training design and the work environment. This plan covers the work environment, which a meta-analysis of 89 studies (Blume, Ford, Baldwin and Huang, 2010) found linked to transfer. Sort each barrier into one type:
   - **Time and workload:** no time in the day to do it the new way.
   - **Tools and access:** systems, equipment, signal, permissions, kit.
   - **Targets and incentives:** KPIs, bonuses or league tables that reward the old way.
   - **Manager support:** managers who haven't seen the course, don't ask about it, or ask for the old way.
   - **Chance to apply:** the situation rarely comes up, or goes to someone else.
   - **Conflicting instructions:** a procedure, contract, client or other team asking for something different.
   Weinbauer-Heidel's organisation levers in *What Makes Training Really Work* (opportunity to apply, personal capacity, support from supervisors and peers, transfer expectations) cover the same ground and are good further reading.
5. Write every barrier as a condition of the work, such as "Planners still phone jobs through, so the job in the app has no fault description." Rewrite any line that blames a person or group ("lazy", "resistant to change", "set in their ways", "can't cope with technology") as the condition behind it, or drop it if no condition can be found. Remove anything that names or could identify a person, and any mention of age, disability or another protected characteristic as a cause. If a barrier falls harder on disabled staff (an app that doesn't work with a screen reader), treat it as an accessibility point under the Equality Act 2010, owned by whoever owns the tool.
6. Find the owner for each barrier: the role with the authority to change it. Targets sit with whoever sets them, often an operations director or head of department. Rotas and workload sit with the operations manager, systems with IT or the system owner, procedures with the process owner, client requirements with the contract manager. Anything touching a safe system of work goes to the health and safety manager. L&D owns only what L&D can change: the course, job aids and manager guides.
7. Write a fix for each barrier that matches its type. A refresher, reminder email or e-learning closes a gap in knowledge or practice. It leaves time, tools, targets and clashing procedures exactly as they were, so flag any such pairing and write the work fix. Give each fix one owner, a date and a sign in the work that shows it's done ("every job a planner issues carries a fault description", "the weekly KPI report shows first-time fixes alongside jobs per day").
8. Rank the barriers by how many people they affect and how often, then by how quickly they can be fixed. Mark the top three to fix first, with one line each on why.
9. List anything that points at the course itself (no practice on the real system, content that doesn't match the job) in a separate section owned by L&D.
10. Draft a short note to the owners: what was found and where it came from, what's asked of each, and by when. Keep it neutral and specific, with no blame.
11. Set the review: a date, the same evidence source used again, and who reports back.
12. Run the Quality checks below and fix what fails.
13. Present the plan, then **Assumptions** and **Check before you use it**: that each owner is the right role and has agreed, that the numbers are current, and that the dates are realistic.
14. Offer a .docx, a one-page summary for leaders, the Application Survey to measure barriers at day 60, or the Transfer Risk Audit for the next cohort.

## Output format

**Barrier removal plan: [programme]**
Prepared by [L&D role], [date]. Behaviours the programme aims for: [list].

1. **What we found**: three or four sentences: the evidence sources and dates, how many people they cover, the biggest barriers.
2. **Barriers**
   | # | Barrier (a condition of the work) | Type | Evidence | Fix | Owner (role) | By | Sign it's fixed |
3. **Fix these first**: the top three, with a line on why.
4. **Points for the course**: owned by L&D.
5. **Note to owners**: under 200 words.
6. **Review**: date, evidence source, who reports back.

Two pages at most.

## Try it

`examples/hallowmere-fieldpro-barrier-plan.md` is a draft barrier plan for the FieldPro rollout, a new job-management app for engineers at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing the corrected plan. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every barrier is a condition of the work, and none blames a person or group or names a protected characteristic as a cause.
- Every barrier has evidence listed, or is marked "suspected" with a way to check it.
- Every barrier has one owner, named by role, with the authority to make the fix; barriers in targets, tools, time or procedure have an owner outside L&D.
- No barrier in time, tools, targets or procedure has a training fix (a refresher, reminder or e-learning) as its only fix.
- Every fix is a specific action with a date and a sign in the work that shows it's fixed.
- No names or details that could identify a person appear anywhere; evidence is in counts and themes.
- Numbers, dates and owners the user didn't give are marked as proposed and listed under Check before you use it.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. Claude drafts this plan; the owners decide what to change, and nothing in it judges any learner's skill or singles anyone out.
- Work with roles and themes, never names. Survey answers and check-in notes about a named person are personal data under UK GDPR and the Data Protection Act 2018, so aggregate or anonymise them before pasting anything into Claude, and follow the ICO's guidance and your organisation's AI policy.
- Never infer or mention protected characteristics, and check the wording for blame aimed at a group. The Equality Act 2010 covers accessible tools and reasonable adjustments for disabled staff, so treat an inaccessible tool as a barrier with an owner.
- Where a barrier touches safety-critical work, the health and safety manager owns it, and competence sign-off stays with a qualified person under the organisation's procedure. Check the current versions of the laws named here on GOV.UK and the ICO website. This is a draft plan, never legal advice.
- Numbers, owners and dates come from the user or stay as placeholders.
