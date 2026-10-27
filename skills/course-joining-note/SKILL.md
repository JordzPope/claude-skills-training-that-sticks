---
name: course-joining-note
description: Drafts or checks the joining instructions a learner gets before a course, short enough to read on a phone, with the date, time and place, what they'll be expected to do at work afterwards and when, any pre-work and the work time set aside for it, how to ask for reasonable adjustments, and a request to bring one real task. Use when an L&D manager, coordinator or trainer asks for joining instructions, a course invitation, a pre-course email, a welcome note for a training day, the text for a calendar invite, or a check of joining instructions before they go out.
---

# Course Joining Note

Produces the note each learner reads before a course: when and where, what to bring, any pre-work, and what they'll be expected to do with it back at work. Or checks a note someone has drafted. It sets the expectation of use in the first message a learner gets about the course, alongside the logistics, in a note short enough for an engineer to read on a phone between jobs.

## When to use

- "Write the joining instructions for the FieldPro training sessions."
- "I need the text for a calendar invite for the complaints workshop."
- "Our joining instructions are a page and a half about parking. Can you sort them out?"
- "Check this course invite before the coordinator sends it."
- "Half our learners only see email on their phones. Make this shorter."

Wrong tool for the manager's conversation with the learner (use Manager Pre-Course Brief) or the task template learners fill in before the course (use Real Work Brief). This note points to both.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme, what it covers, and who it's for by role. [one session for one group]
2. **Essential:** the day and date, start and finish times, and the venue or joining link. [placeholders]
3. What learners will do at work afterwards, when they'll first get the chance, and who follows up. [taken from the Manager Pre-Course Brief if there is one; otherwise drafted and marked as proposed, with the line manager following up]
4. Any pre-work: what it is, how long it takes, the device it works on and the work time set aside for it. [none]
5. Who handles adjustment requests and by when. [the L&D coordinator, 10 working days before the course]
6. How learners will read it. [an email most people open on a phone]

Never ask for learners' names, health details or the reason anyone needs an adjustment.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any existing joining instructions, venue details or course outline. If they've given an existing note, this is a check job: run the Quality checks on it, list every problem with where it sits and why it matters, then write a corrected note.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If they say "just draft it", use the defaults and list them as assumptions.
3. Fit the note to how it'll be read. For people who work from a phone, a van or a shop floor, keep it under [250] words, put the date, time and place in the first three lines, and use short labelled lines in place of paragraphs. Desk-based groups get the same order with a little more room. Everything needed on the day sits in the note itself; attachments are extra.
4. Write the logistics: day and date, start and finish times, the venue address and where to go on arrival (or the joining link and how to test it), travel and parking, food, what to bring, and a number to call on the day. Check every weekday against its date in the calendar.
5. Write the expectation of use in two or three sentences: what they'll be able to do at work afterwards, when they'll first do it (a date or a situation, such as "from go-live on [date], every job you close goes through [system]"), and who will follow up and roughly when. Use the facts the user gives. Leave out claims about how much training people forget.
6. Write the pre-work line, if there is any: what it is, how long it takes, how to do it on the device the learner actually has, and when in work time they can do it. If no work time has been set aside, flag it under **Check before you use it**.
7. Write the adjustments line. Invite anyone who'd find anything about the course hard to take part in (getting to the venue, the format of materials, timings, a screen reader, a quiet room) to tell [contact] by [date], far enough ahead to arrange it. Ask what would help and say they don't need to give a reason. Never ask for a diagnosis or medical details, and never ask for them to be kept on file. Offer materials in accessible formats.
8. Add the real task line: bring one real task from their own work, with a pointer to the Real Work Brief template if L&D is using one.
9. Close with who to contact with questions or if they're running late. No sign-off flourish.
10. Run the Quality checks below and fix what fails.
11. Present the note, then **Assumptions** and **Check before you use it**: the venue, the times, each weekday against its date, the go-live or first-use date, who follows up, the adjustments contact, and the work time for any pre-work.
12. Offer a .docx, a text message version under 300 characters, a calendar invite version, or the Real Work Brief and Manager Pre-Course Brief skills.

## Output format

**Subject:** [Programme]: [weekday date], [start time], [place]

**When:** [weekday date], [start] to [finish]
**Where:** [venue, address, where to go on arrival] or [joining link]
**Who's going:** [roles]
**Why:** [one sentence: what you'll be able to do at work afterwards]
**After the course:** [when you'll first use it at work, and who will follow up]
**Before you come:** [pre-work, how long, on which device, the work time set aside] or "Nothing to do in advance."
**Bring:** [one real task from your own work] [anything else]
**Anything that would make the day easier for you?** Tell [contact] by [date]. You don't need to say why.
**Travel, parking and food:** [one or two short lines]
**Questions, or running late on the day:** [contact role and number]

Under [250] words. No tables, so it reads well on a phone.

## Try it

`examples/hallowmere-fieldpro-joining-note.md` is an L&D coordinator's draft joining note for the FieldPro rollout, a new job-management app for engineers at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with facts from the project plan at the top and problems planted in the note. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the note. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- The date, time and place are in the first three lines, and every weekday matches its date.
- The note says what learners will do at work afterwards, when they'll first do it, and who follows up.
- Any pre-work states how long it takes, works on the device learners have, and has work time set aside for it.
- The adjustments line names a contact and a date early enough to arrange support, and asks what would help without asking for a diagnosis, a condition or a reason.
- The note asks learners to bring one real task.
- The note is under [250] words, and nothing needed on the day sits only in an attachment.
- No learner names, health details or claims about how much people forget appear.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. This note sets the expectation of use. The learner's manager follows it up at work, and any judgement about someone's skill stays with a person.
- Personal data: send the same note to the whole group and keep names out of the draft. Adjustment requests often reveal health information, which UK GDPR and the Data Protection Act 2018 treat as special category data: collect only what's needed to arrange the support, store it under your policy, and never paste it into Claude. Follow the ICO's guidance and your organisation's AI policy.
- Fairness: everyone gets the same information in the same format. Never infer or mention protected characteristics, and check the wording for assumptions about who drives, who works days or who has a laptop.
- Law: the Equality Act 2010 requires reasonable adjustments for disabled learners, including accessible materials and venues. Pre-work the organisation requires will usually count as working time for pay; check GOV.UK's guidance on calculating the minimum wage if anyone is paid by the hour. For safety-critical training, attending makes nobody competent; sign-off stays with a qualified person under your procedure. Check the current versions. This is a draft, never legal advice.
- No invented facts: dates, times, venues, contacts and go-live dates come from the user or stay as placeholders.
