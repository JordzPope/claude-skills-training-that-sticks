---
name: reinforcement-nudges
description: Drafts or checks the short follow-up messages sent after a training course, one per touchpoint, each asking the learner to do one thing at work and short enough to read on a phone, for Teams, email or text. Use when a Head of L&D, L&D manager, L&D coordinator or trainer asks for reinforcement nudges, post-course follow-up emails, Teams messages or reminders after training, nudge messages, weekly tips after a course, texts for field or shift staff, a message a manager can send their team, or a check of follow-up messages before they're scheduled.
---

# Reinforcement Nudges

Writes the message for each touchpoint after a course: one short email, Teams message or text that asks the learner to do one specific thing at work that week. Or checks a set someone has already drafted. It replaces "just a reminder that the materials are on the LMS" with messages people can act on from a phone between jobs.

## When to use

- "Write the follow-up messages for the 10 weeks after our customer service course."
- "I need Teams nudges for engineers using the new app. They only ever see their phones."
- "Turn this follow-up plan into the actual emails."
- "Our post-course emails get ignored. Can you check them?"
- "Write a text a supervisor could send their team after the toolbox talk."

Wrong tool for deciding when the touchpoints happen (use Spaced Follow-Up Plan first), for writing quiz questions (Retrieval Practice Set) or for the one-page reference people use on the job (Job Aid).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme and the two to four things people should do differently at work.
2. **Essential:** the touchpoints: the date of each and what it's for. [from an attached Spaced Follow-Up Plan; otherwise six messages at days 2, 7, 14, 28, 49 and 70 after the course]
3. Channel and device: Teams, email, text to a work phone or the LMS, read at a desk or on a phone. [Teams, read on a phone]
4. Who sends each message and how they sign it: L&D, the learner's manager or a senior sponsor. [the L&D coordinator, signed with a first name and "L&D"]
5. Learners' working hours and shift pattern. [08:00 to 17:00, Monday to Friday]
6. Tone, house style and any links to include: a job aid, the recording, a practice challenge, a form. [plain and friendly, first names, no exclamation marks; no links]

Never ask for learners' names, personal phone numbers, personal email addresses or results. Messages go to the whole group; any personal greeting comes from the sending tool's own fields.

## Steps

1. Read what the user has given, including any attached plan or drafts. If they've given existing messages, this is a check job: run the Quality checks on each message, list every problem with the message number, where it sits and why it matters, then write a corrected set.
2. Ask for missing essentials in one message, five questions at most, showing the defaults. If they say "just draft it", use the defaults, leave placeholders and list the assumptions.
3. Choose one action per message, matched to what the touchpoint is for:
   - **Recall:** one or two questions to answer from memory before looking anything up, with the answer in a second message later that day or below a line marked "Answer below".
   - **Practice:** one use of the skill on a named real task this week. "In your next one-to-one, ask one open question before you give your view."
   - **Manager check-in:** what to bring to the conversation. "Before your one-to-one this week, pick one time you tried the new approach."
   - **Reflect and share:** one line back to a manager or peer about what happened when they tried it.
   The action is something the learner controls, can do during normal work and takes 15 minutes or less. Where it suits, write it as an if-then plan (Gollwitzer's implementation intentions: "When [situation], I will [action]"), which raises the odds that people act.
4. Put the action in the first line or two. Then add one line on why it helps in their own work, from the user's facts; one line on how, or a link; and what to do afterwards (reply, tell your manager, or nothing). Sign off from a real role.
5. Write to the channel's length, so the whole message fits on one phone screen:
   - Text: 160 characters or fewer, one link at most.
   - Teams: 60 words or fewer.
   - Email: a subject line of 50 characters or fewer that names the action, and a body of 100 words or fewer.
   Cut greetings, thanks, course recaps and second asks before you cut the action or the reason.
6. Keep the tone respectful. No guilt ("don't let the team down"), no threats ("your manager will be told"), no "You still haven't...", and no urgency words ("urgent", "last chance", "today only") unless the user has given a real deadline. Make it fine to skip a week. Never claim others have done it unless the user gives an aggregate figure.
7. Make each message work where people are. Links open on a phone without a desktop login, and link text says where it goes. Meaning never sits in an image or colour alone. For people who drive for work, send at shift start or a break and say "when you're parked up". Use words a new starter would understand, and give any course term its plain meaning alongside.
8. Vary the openings across the set so it doesn't read like a template, and refer back to the last touchpoint where it helps ("Last week's question was about..."), without assuming they did it.
9. Keep replies and results anonymous or aggregate. A recall message never asks for named answers to be scored, and no message reports on who has or hasn't done something.
10. Run the Quality checks and fix what fails.
11. Present the schedule table, then each message, then **Assumptions** and **Check before you use it**: each link opens on the learners' phones, send times fit their shifts, the named sender has agreed, and managers have approved any version sent in their name.
12. Offer a .docx, a version for managers to send to their own team, or the Job Aid skill for the reference the messages point to.

## Output format

**Reinforcement nudges: [programme]** · [n] messages · [channel] · sent by [role]

| # | Send date and time | Channel | Type | The one action | Length |
| --- | --- | --- | --- | --- | --- |

Then, for each message:

**Message [n]** · [date, time] · [channel] · from [role]
Subject (email only): [50 characters or fewer, naming the action]

> [The action, in the first line or two]
> [One line on why it helps them at work]
> [How, or a link with descriptive text]
> [What to do afterwards, if anything]
> [First name, role]

Length: [words, or characters for a text]

Then **Assumptions** and **Check before you use it**.

## Try it

`examples/hallowmere-fieldpro-nudges-draft.md` is a set of draft follow-up messages for engineers after the FieldPro app rollout at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the messages. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every message asks for exactly one action at work that the learner controls, stated in the first two lines.
- No message only reminds, thanks or points to materials: "just a reminder" or a link with no action fails.
- Each message is within its channel's limit: a text 160 characters, a Teams message 60 words, an email body 100 words with a subject of 50 characters, or the limits the user set.
- No guilt, threats or fake urgency: no warning about who will be told, and "urgent", "last chance" or a deadline appears only when the user has given a real one.
- No message names, singles out or reports on an individual learner, and replies or form results are reported only in aggregate.
- Every link opens on the learners' device and has descriptive link text, and no meaning depends on an image or colour alone.
- Send times fall inside the learners' working hours for their shift pattern.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. These messages prompt people to practise; they never check up on, grade or report on anyone.
- Personal data: send through work channels to the whole group. Who opened, replied or answered what is personal data under UK GDPR and the Data Protection Act 2018, so report it in aggregate, follow the ICO's guidance and your organisation's AI policy, and never paste named results into Claude. Never ask for personal phone numbers or email addresses; send texts only to work phones through the organisation's own tool.
- Fairness and access: everyone in the group gets the same messages. Under the Equality Act 2010, reasonable adjustments apply to follow-up activities too, so offer the messages in an accessible format on request, such as a screen-reader-friendly version, and allow more time for a practice task where someone needs it.
- Safety-critical or regulated content: a nudge can prompt practice inside the organisation's procedure. Competence sign-off stays with a qualified person under that procedure.
- Check the current versions of the law and guidance named here. These are draft messages, never legal advice.
- No invented facts: dates, figures, links and quotes come from the user or stay as placeholders. Never add a statistic to make a message more persuasive.
