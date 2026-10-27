---
name: sponsor-message
description: Drafts or checks a short message from a senior leader to the people on a training programme and their managers, saying why the programme matters, the business measure it serves, what should change at work and what leaders will do to make room for it, written without hype or threats. Use when an L&D manager or L&D business partner asks for a sponsor message, an executive launch email, a message from the director about a course, a leadership endorsement, a kick-off note from a senior leader, or a check of a sponsor's draft before it goes out.
---

# Sponsor Message

Produces the short note a senior leader sends before a programme starts: why it matters to the business, what should change at work, and what leaders will do to back it. Or checks a draft the sponsor has written. It gives a busy senior leader something specific and true to put their name to, and gives learners a reason to use the course that comes from the business itself.

## When to use

- "Our Director of Operations has agreed to send something before the FieldPro training. Can you draft it?"
- "Write a kick-off message from the Head of Customer Operations for the complaints programme."
- "The MD wants to say a few words to the new managers. Keep it short."
- "Check the director's draft. I think parts of it read like a threat."
- "Turn our sponsor's bullet points into an email."

Wrong tool for the manager's conversation with each learner (use Manager Pre-Course Brief) or the report back to leaders afterwards (use Learning Impact Report).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme, who it's for by role, and the dates. [one programme, starting in the next month]
2. **Essential:** the sponsor's role, and the business measure the programme serves, with its current figure and target. [taken from the Learning Impact Map if there is one; otherwise placeholders]
3. The one or two behaviours that should change at work. [taken from On-the-Job Objectives or the Manager Pre-Course Brief]
4. What the sponsor will do to back it: protected time, a pause on a target, joining a session, asking about it at a set meeting. [a placeholder for the sponsor to choose]
5. Channel and audience. [email to learners, copied to their managers]

Never ask for learners' names or individual results. Any figures in the message are team or organisation totals.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any programme plan, impact map or the sponsor's own draft. If they've given an existing message, this is a check job: run the Quality checks on it, list every problem with where it sits and why it matters, then write a corrected message.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If they say "just draft it", use the defaults and list them as assumptions.
3. Trace the line from the programme to the business measure. Use the user's figures exactly as given, and check every figure in a sponsor's draft against its source. If learners can only move part of the measure (an SLA that also depends on parts supply, say), name the part their behaviour affects.
4. Pick the support. Blume, Ford, Baldwin and Huang's 2010 meta-analysis found a supportive work environment linked to transfer, and this is the line learners will test against what happens when they get back to work. Choose one or two concrete things the sponsor controls, each with a date or amount, and mark anything the sponsor hasn't yet agreed as proposed.
5. Write it in the sponsor's voice, first person, plain English, about [150] words, in this order:
   - **Why:** the business problem in one or two sentences, with the measure and its figure.
   - **What should change:** the one or two behaviours, written as things people will do.
   - **What I'll do:** the commitments from step 4.
   - **What's next:** when the programme starts, and that each learner's manager will talk to them beforehand.
   If the user shares an earlier message from the sponsor, match its tone and sign-off.
6. Take out hype and pressure. Cut superlatives, claims that the programme will change everything, and any promise that the course alone will fix the measure. Cut any line that links the programme to discipline, performance ratings, pay, job security or a public ranking of people. A sponsor who wants to share results later shares team or organisation totals.
7. Run the Quality checks below and fix what fails.
8. Present the message, then **Assumptions** and **Check before you use it**: each figure against its source, that the sponsor has agreed to each commitment, and the dates.
9. Offer a .docx, a version under 60 words for Teams, a version for the learners' managers, or the Manager Pre-Course Brief skill.

## Output format

**Subject:** [Programme]: [why it matters, in under eight words]

[Greeting]

[Why: one or two sentences, with the measure and its current figure.]

[What should change: one or two behaviours at work.]

[What I'll do: one or two commitments, each with a date or amount.]

[What's next: start dates, and the conversation with each learner's manager beforehand.]

[Sponsor's first name], [role]

Under [200] words, in prose, with no bullet points or bold.

## Try it

`examples/hallowmere-complaints-sponsor-draft.md` is a first draft of a sponsor message from the Head of Customer Operations for Complaints That Close, a complaint-handling programme for customer advisers at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with facts from the programme plan at the top and problems planted in the draft. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the message. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- The message names the business measure with a figure that matches the source, and says how the programme serves it.
- It names one or two behaviours that should change at work, each something a person could be seen doing.
- The sponsor makes at least one concrete commitment with a date or amount, agreed by the sponsor or marked as proposed.
- No hype: no superlatives, no claim the programme will change everything, no promise it will fix the measure on its own.
- No threat: nothing links the programme to discipline, ratings, pay or job security.
- No named person, individual result or ranking of people appears; any figures are team or organisation totals.
- It's under [200] words and written in the sponsor's first person.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. Claude drafts the message, and the sponsor decides what they'll commit to and sends it in their own name. The message makes no judgement about any learner.
- Personal data: totals only. One adviser's reopened complaints or one engineer's fix rate is personal data under UK GDPR and the Data Protection Act 2018; keep individual results out of the message and out of Claude. Follow the ICO's guidance and your organisation's AI policy.
- Fairness: the message speaks to everyone on the programme on the same terms. Never infer or mention protected characteristics, and check the wording for assumptions about who the learners are (all new, all desk-based, all full-time).
- Law: where the programme is mandatory or safety-critical, the message must never suggest that finishing the course makes anyone competent; competence sign-off stays with a qualified person under your procedure and the Health and Safety at Work etc. Act 1974. If it mentions access or adjustments, the Equality Act 2010 applies. Check the current versions. This is a draft, never legal advice.
- No invented facts: figures, targets, dates and commitments come from the user or stay as placeholders.
