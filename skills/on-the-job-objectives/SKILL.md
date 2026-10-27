---
name: on-the-job-objectives
description: Rewrites or checks the learning objectives for any course or programme so each one describes a behaviour someone could watch happen at work, with the situation it happens in and the standard it must meet (Mager-style performance objectives), a Bloom's taxonomy verb at the level the job needs, and the practice in the course that builds it. Flags verbs nobody can observe, such as understand, know, be aware of and appreciate. Use when someone asks to write or rewrite learning objectives, learning outcomes or performance objectives, make course objectives measurable or behavioural, check a provider's or designer's objectives, or turn 'by the end of this session delegates will understand' into something a manager could see at work.
---

# On-the-Job Objectives

Rewrites course objectives as things people will do at work: the behaviour, the situation it happens in and the standard it has to meet, each linked to the practice in the course that builds it. Or checks objectives someone already has. The designer, the provider and each learner's manager then share one picture of what should look different after the course.

## When to use

- "Our provider's objectives all start with 'understand'. Can you rewrite them?"
- "Write learning objectives for our new first-line managers' programme."
- "Make these objectives measurable so managers know what to look for."
- "Check the objectives in this e-learning brief before we sign it off."
- "Turn this course outline into proper learning outcomes."

Wrong tool for deciding whether training is the answer at all (use Performance Gap Brief first) or for linking objectives to team results and business goals (use Learning Impact Map).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** which programme: the current objectives, the course outline or brief, or a few lines on what it covers and who it's for.
2. **Essential:** the job: the role, and the tasks or situations at work where people will use what they learn. [inferred from the outline and marked for the user to confirm]
3. Any standard that already exists for the task: a policy, a procedure, a checklist, a quality form or a system rule. [none; Claude proposes standards and marks them]
4. How soon after the course people will get to use it, and how often. [within two weeks, at least weekly]
5. Whether the content is safety-critical or regulated. [no]

Never ask for learners' names or anything about individual learners. Objectives describe what anyone in the role should do.

## Steps

1. Read what the user has given, including any attached outline or brief. If they've given existing objectives, this is a check job: run the Quality checks on them, list each problem with the objective it's in and why it matters, then write corrected objectives.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If they say "just draft it", use the defaults and list them as assumptions.
3. Find the job behind each objective. Ask: in which real situation at work would someone use this, and what would they do? An objective nobody would use at work is a candidate to cut or to move to background reading; say which.
4. Write the behaviour (Mager calls it the performance): one action verb a manager could see or hear, or a product they could check (a completed record, a written plan, a logged job). Replace verbs nobody can watch: understand, know, learn, be aware of, be familiar with, appreciate, recognise the importance of, gain an insight into, feel confident to. Ask what the person would do differently if they understood it, and write that. Split any objective that holds two behaviours which could happen apart.
5. Choose the verb's level with Bloom's taxonomy. The revised taxonomy has six levels, each with verbs you can observe: remember (list, state), understand (explain, classify), apply (carry out, use), analyse (diagnose, compare), evaluate (decide, prioritise, check against a standard) and create (plan, design). "Understand" is a level name, which is why it creeps into objectives; inside the course, an observable verb from that level such as explain works. At work most objectives sit at apply or above, because the job asks people to do something. Match the level to the task: a step-by-step system task sits at apply, while a complaint that doesn't fit the script needs analyse or evaluate.
6. Add the condition: the trigger or situation at work ("when a customer rings about a repeat fault", "in each monthly one-to-one"), plus anything the person has to hand or does without (the app, a job aid, no supervisor on site).
7. Add the standard (Mager's criterion): how well, how often, how fast, how complete, or to which policy step or checklist. Use the organisation's own standard where one exists. Otherwise propose one, mark it proposed and list it under Check before you use it. Describe the result and leave the method open unless the method matters, so reasonable adjustments can apply: "records the job notes in the app" leaves room for dictation.
8. Name who can see it: the person or source that shows the behaviour happening (the manager in a one-to-one, a quality review, a system report). If nobody could ever see it, rewrite the objective.
9. Link each objective to the practice in the course that builds it: an activity where learners do the behaviour, close to how it happens at work, with feedback. Where the outline offers only input for an objective (a presentation, a policy walk-through, a group discussion about it), flag "no practice yet" and suggest an activity.
10. Keep three to six on-the-job objectives for one programme, so a manager can hold them in mind. Merge or cut the rest, and say what went where.
11. For safety-critical or regulated content, use the organisation's procedure wording where it sets a standard, and add a note that the course builds the behaviour and competence sign-off stays with a qualified person under the procedure.
12. Run the Quality checks and fix what fails.
13. Present the objectives and the practice table, then **What changed and why**, **Assumptions** and **Check before you use it**: each proposed standard, who will see each behaviour, and whether the course time allows the practice.
14. Offer a .docx, a short version for the joining instructions, the Learning Impact Map to link the objectives to results, or the Transfer Risk Audit for the programme.

## Output format

**On-the-job objectives: [programme]**
For [roles, number], after [course name and format]. First chance to use it at work: [when].

| # | At work, they will (behaviour) | When (condition) | To this standard | Bloom's level | Who can see it |
| --- | --- | --- | --- | --- | --- |
| 1 | [action verb and object] | [trigger or situation, what's to hand] | [how well, how often, policy step; mark proposed] | [level] | [role or source] |

**How the course builds each one**

| # | Practice in the course | Feedback from | Gap |
| --- | --- | --- | --- |
| 1 | [activity close to the real task] | [trainer, peer, checklist] | [none, or "no practice yet" and a suggested activity] |

**What changed and why**

| Original wording | Problem | Now objective # |
| --- | --- | --- |
| [as written] | [unobservable verb, no condition, no standard, two behaviours, not used at work] | [number, or cut] |

One page.

## Try it

`examples/hallowmere-lead-the-shift-objectives.md` holds the objectives and outline a provider sent for Lead the Shift, the first-line management programme at Hallowmere Facilities, a fictional 1,400-person facilities services firm. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing the corrected objectives. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every objective has one observable verb, and none uses understand, know, learn, be aware of, be familiar with, appreciate or recognise the importance of.
- Every objective names the situation at work where it happens.
- Every objective has a standard someone could check; a proposed standard is marked and listed under Check before you use it.
- Each objective holds one behaviour, and the programme has three to six.
- Each objective names who or what can see it happen at work.
- Every objective has a practice activity in the course, or is flagged "no practice yet" with a suggested activity.
- For safety-critical or regulated content, no objective says or implies that finishing the course makes anyone competent.

## Guardrails

- The one rule for this pack: "Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill." The objectives describe what anyone in the role should do. Whether a particular person meets the standard is a call for their manager, or for a qualified person where competence sign-off applies, and the objectives give them a shared picture to judge against.
- Personal data: objectives need none. Paste the course material only; if learner data comes with it, leave it out. Follow UK GDPR, the Data Protection Act 2018, the ICO's guidance and your organisation's AI policy.
- Fairness and access: hold everyone in the role to the same standards, and never infer or mention protected characteristics. Under the Equality Act 2010, reasonable adjustments apply to the course, the practice and any assessment, and materials should be accessible; a standard written about the result leaves room for them.
- Safety and regulated work: where the Health and Safety at Work etc. Act 1974 or a sector regulator applies, the organisation's procedure sets the standard and a qualified person signs off competence.
- Law: check the current versions of the laws and guidance named here. This is a draft, never legal advice.
- No invented facts: standards, policies, timescales and figures come from the user or are marked proposed.
