---
name: session-plan-rework
description: Checks a training session plan block by block for the share of time spent on telling versus practice, where learners recall from memory, whether they work on their own real tasks and how the session closes, then rewrites the weak blocks while keeping the trainer's content and the session length. Also drafts a practice-led session plan from a content outline. Use when an L&D manager, learning designer or trainer asks to review or check a session plan, lesson plan, workshop outline, course agenda or a provider's running order, to add practice or make a session more hands-on, to cut down the slides and demos, or to redesign a course day so people use it at work.
---

# Session Plan Rework

Produces an audit of a session plan, block by block: how the minutes split between telling and practice, where learners recall from memory, whether they work on their own real tasks and how the session hands over to work. Then it rewrites the weak blocks, keeping the trainer's content and the session length. A trainer gets a plan that spends its time on practice without starting again from a blank page.

## When to use

- "Here's my session plan for the systems training. Is there enough practice in it?"
- "Can you check this workshop outline before we run it for 60 supervisors?"
- "Our provider sent the running order for the course day. Where's the practice?"
- "Make this half day more hands-on without losing any of the content."
- "I've got a content outline and three hours. Draft me a session plan."

Wrong tool for writing the scenarios or questions that go into the blocks (use Practice Scenarios or the Retrieval Practice Set) or for the follow-up after the course (use the Spaced Follow-Up Plan).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the session plan with timings, or for a new plan, the content outline and the session length. [check job on the plan given]
2. **Essential:** the programme, who attends, and what they should do differently at work afterwards. [Claude proposes job behaviours from the plan's aims, marked for you to confirm]
3. Group size, room and kit: phones, laptops, a training login, space to move. [12 people, one trainer, a room with tables]
4. Your targets for the split of time. [telling at most [40]% of learning time; no telling block over [20] minutes; learners recall from memory at least every [90] minutes]
5. What happens around the session: a manager conversation before, follow-up after. [nothing planned yet]

The targets in input 4 are working defaults for the user to change; no study sets a fixed ratio. Never ask for learners' names or anything about individual learners. A session plan needs no personal data.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any attached plan, slide list, trainer guide or provider outline. If they've given a session plan, this is a check job: run the audit in steps 3 to 8, list every problem with the block and time it sits in and why it matters, then rework the weak blocks in step 9. If they've given only a content outline, draft a new plan using steps 9 to 11, built to pass the same Quality checks.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. **Time audit.** List every block with its start, end and minutes, and tag it with one type:
   - **Telling:** trainer talk, demonstrations, videos, reading, a trainer recap.
   - **Practice:** learners doing the task: scenarios, role play, hands-on use of the system.
   - **Retrieval:** learners recall from memory before they look anything up.
   - **Real work:** learners work on their own live tasks or cases from their job.
   - **Close:** action planning and the handover to managers.
   - **Other:** welcome, logistics, breaks, feedback forms, and anything that fits none of the above.
   Split a mixed block by its minutes. Give each type's share of learning time (everything except breaks and logistics). Check the blocks add up to the stated length, and flag it if they don't.
4. **Telling.** Flag a telling share over the target, any single telling block over the limit, and a first hands-on block that comes after more than an hour of telling.
5. **Retrieval.** Find every point where learners recall from memory. A trainer recap counts as telling. Flag any stretch longer than the target with no retrieval, and any later day or session that opens without learners recalling the last one.
6. **Real work.** Check whether learners practise on tasks from their own jobs: their live cases, their real screens, the job types they meet every week. Practice on invented examples unlike their work counts as practice, with no link back to the job. Flag a session with no real-work block. The Real Work Brief skill in this pack asks each learner to bring one live task.
7. **The close.** Check the last [20 to 30] minutes. A strong close has each learner write a Transfer Action Plan (if-then plans for their first use at work) and hands over to managers: a short note on what was covered, what each learner will try first and when the manager reviews it with them. Flag a close that ends on questions and a feedback form alone.
8. **Other flags.** Flag any activity matched to learning styles (visual, auditory, kinaesthetic): the evidence doesn't support matching teaching to learning styles, and an L&D audience will spot it. Flag content that links to no job behaviour, practice that needs kit learners won't have at work, and materials that aren't accessible.
9. **Rework.** Rewrite each flagged block, keeping the trainer's content, examples and order wherever they work:
   - Break long telling into chunks of [10 to 15] minutes, each followed straight away by learners doing what was just shown.
   - Turn a trainer recap into retrieval: learners write or say what they remember first, then check.
   - Swap invented practice cases for learners' real tasks, or cases built from them.
   - Replace a learning styles activity with everyone practising the task the way it's done at work, with other formats offered as adjustments where someone needs one.
   - Rebuild the close: [20] minutes for the Transfer Action Plan, then the manager handover note.
   Keep the total length the same by moving time from telling to practice.
10. **Before and after the session.** Baldwin and Ford (1988) found transfer depends on three groups of inputs: the learner, the training design and the work environment. The session plan is the design; the handover links it to the work environment. Broad and Newstrom's transfer matrix ranks what the learner's manager does before training as the most powerful point for transfer, and what the trainer does before as second. If the plan has nothing before the session, add a line for each: the manager conversation (the Manager Pre-Course Brief skill) and any pre-work, such as the Real Work Brief.
11. Recalculate the shares for the reworked plan and show both versions side by side.
12. Run the Quality checks below and fix what fails before showing anything.
13. Present the audit and the reworked plan, then **Assumptions** and **Check before you use it**: that the kit and logins exist on the day, that real tasks can be used safely in training (no live customer data on a shared screen), and that managers know the handover note is coming.
14. Offer a .docx, a one-page trainer run sheet, or the skills that fill the new blocks: Practice Scenarios, the Retrieval Practice Set and the Transfer Action Plan. For further reading on the design side, Weinbauer-Heidel's *What Makes Training Really Work* covers active practice and transfer planning.

## Output format

**Session plan rework: [programme], [session], [length]**

1. **Time audit**
   | Time | Block | Minutes | Type | Note |
   Shares of learning time: telling [x]%, practice [x]%, retrieval [x]%, real work [x]%, close [x]%. Longest telling block: [x] minutes. First hands-on block starts at [time].
2. **What needs changing**: numbered, each with the block, the problem and why it matters at work.
3. **Reworked plan**
   | Time | Block | What learners do | What the trainer does | Materials |
4. **Before and after**
   | Type | Original | Rework |
5. **What changed and what stayed**: one line per reworked block.
6. **Before the session**: the manager conversation and any pre-work, one line each.
7. **Manager handover note**: four to six sentences the trainer sends each learner's manager after the session: what was covered, that the learner has an action plan, and the date to review it with them [date].

## Try it

`examples/hallowmere-fieldpro-session-plan.md` is a trainer's half-day session plan for the FieldPro rollout, a new job-management app for engineers at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before reworking the plan. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every block is tagged with a type, the minutes add up to the session length, and the shares are shown for both versions.
- Telling is at or under the target share of learning time, and no single telling block runs over the limit.
- Learners recall from memory at least once in every stretch of the target length, and any later day or session opens with recall of the last.
- At least one block has learners working on their own real tasks, or cases built from them.
- The session closes with each learner writing an action plan and a handover note to their manager with a review date.
- No activity is matched to learning styles.
- The reworked plan keeps the trainer's content and the original length, and every change is listed.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. Claude reworks the plan; the trainer runs the session, managers coach what was learned back at work, and nothing in the session scores or ranks a learner.
- A session plan needs no personal data. When practice uses real work, learners use anonymised cases or training logins, and live customer or employee data stays off shared screens, in line with UK GDPR, the Data Protection Act 2018, the ICO's guidance and your organisation's AI policy.
- Everyone gets the same practice and the same close. Role play in front of the whole room is optional, with a pairs version always available.
- Under the Equality Act 2010, reasonable adjustments for disabled learners apply to session activities and any assessment, and materials should be accessible. Offering another format to someone who needs it is an adjustment, and stays in the plan when learning styles come out.
- For safety-critical or regulated training (the Health and Safety at Work etc. Act 1974 and any sector regulator), practice in the session builds toward competence, and sign-off stays with a qualified person under your organisation's procedure. Check the current law and your procedure; this is a draft, never legal advice.
- Timings, kit, content and dates come from the user or stay as placeholders for them to confirm.
