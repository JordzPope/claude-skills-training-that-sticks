---
name: real-work-brief
description: Drafts the brief that asks each learner to bring one live task from their own job to a course, with what counts as a good task for this programme, how to keep names and confidential details out, a fallback for anyone without one, the dates, and a short template to fill in on a phone. Use when an L&D manager, learning designer or trainer asks for a real work brief, a bring-your-own-task request, pre-course work based on real work, a live case template, a workplace challenge to bring to a course, or a way to get learners to bring their actual jobs into the training.
---

# Real Work Brief

Produces the request learners get before a course: bring one live task from your own job, here's what counts, here's a short template. The trainer then builds the practice around work people really do. It's a job for the trainer before the course, the point Broad and Newstrom's transfer matrix ranked second only to the learner's manager before it.

## When to use

- "I want everyone to bring a real situation to the management course. Write the request."
- "Turn my notes into a bring-your-own-task brief for the system training."
- "Give me a template for learners to describe a live case before the workshop."
- "How do I get people to bring real work without them sending me customer details?"

This skill drafts only. Bring notes or last year's brief and Claude lists what in them would make the brief unsafe, unfair or unworkable, then drafts from them. Wrong tool for the logistics (use Course Joining Note) or the plan learners write at the end of the course (use Transfer Action Plan).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme, what it covers, and who it's for by role. [one course, one group]
2. **Essential:** what the course will do with the task: practise on it, plan it, role-play it, enter it in a practice system. [work on it in pairs during the course]
3. The course date, when the brief goes out and when the template is due back. [sent 10 working days before; due 3 working days before]
4. Who reads the completed templates, and how they're sent. [the trainer only, through the LMS or work email]
5. Any rules on data: client contracts, confidentiality, the organisation's AI policy. [roles only; no names, client details or contact details]

Never ask for the learners' tasks themselves, their names, or anyone's personal details from inside the tasks.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any notes, an earlier brief or the course outline. This skill drafts only, so treat notes or an earlier brief as input: list every problem the Quality checks would catch in them, quoting where each sits and saying why it matters, then draft from them with each problem fixed or left as a visible placeholder.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If they say "just draft it", use the defaults and list them as assumptions.
3. Define a good task for this programme, by the kind of skill it builds:
   - **People skills** (leading a team, handling complaints, client conversations): a situation coming up in the next [four] weeks that the learner will handle themselves, such as a one-to-one, a call-back or a client meeting.
   - **Systems and procedures:** a real job or record from recent work that the new way of working will change, such as the last job they closed or a recent order.
   - **Safety and compliance:** a real job they've done or are due to do, used to plan and talk through the controls. Never a task that means doing the risky work in order to bring it, and never a near miss or incident that's still under investigation.
   Give two examples of a good task and one that's too big or too vague, from the learners' own world. A good task fits the time the course gives it.
4. Write the keep-it-safe rules in three or four lines. Describe people by role ("a customer", "an adviser on my team"). Leave out names, contact details, client or site names that would identify someone, health and absence reasons, and anything in a live disciplinary, grievance or investigation. On a management course, an absence case is described by its pattern and never its medical reason. Completed templates travel only by the route the user sets, never a personal messaging app.
5. Write the fallback for anyone without a suitable live task (new starters, people whose role doesn't match the brief, people on leave or light duties): a ready-made task from the trainer, or one from the last [three] months. Everyone takes part in the practice.
6. Write the template: six questions at most, fillable on a phone in about [10] minutes, using roles throughout. Offer another way in for anyone who'd find writing it hard: a voice note, or five minutes on the phone with the trainer.
7. Set the dates. The brief goes out at least [10] working days before the course, and the template is due at least [3] working days before, so the trainer can read them all. Check both dates fall before the course date. Time to fill it in comes from work time.
8. Say what happens to the template: who reads it, how the course uses it, and that it's deleted after [the course]. The template is practice material. Nobody is marked, scored or signed off on it, and it goes to the learner's manager only if the learner chooses to share it. For safety-critical or regulated training, competence sign-off stays with [qualified role] under [the organisation's procedure].
9. Add short trainer notes, kept off the learner's copy: how to group similar tasks, how to use them in the session, and the fallback tasks to have ready.
10. Run the Quality checks below and fix what fails.
11. Present the covering note, the template and the trainer notes, then **Assumptions** and **Check before you use it**: the dates, who reads the templates, that the data rules match your AI policy and client contracts, and that the fallback tasks exist.
12. Offer a .docx, a version for Microsoft Forms, a text message version, or the Course Joining Note so the joining instructions point to it.

## Output format

**Real work brief: [programme], [course date]**

**Covering note** (under [150] words): what we're asking and why (we'll practise on your own work during the course), what counts as a good task with the two examples, the keep-it-safe rules, the fallback, the due date and where to send it, and what happens to it afterwards.

**Template**

| Question | Your answer |
| --- | --- |
| 1. What's the task or situation? One or two sentences, roles only. | |
| 2. When will it happen, or when did it? | |
| 3. Who's involved? Roles only, e.g. "a customer", "a planner". | |
| 4. What would a good result look like? | |
| 5. What makes it tricky? | |
| 6. What would you like to try differently? | |

Send by [date] to [route]. No names, contact details or health information, please.

**Trainer notes** (not sent to learners): grouping, how the tasks are used in the session, fallback tasks.

Covering note and template fit on one page.

## Try it

`examples/hallowmere-asbestos-trainer-notes.md` is a trainer's rough notes for a real work brief for the Asbestos Awareness refresher, the yearly mandatory safety course for engineers and site supervisors at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in them. When the user says "try it", "show me" or "use the example", read that file, list every problem you find in the notes with where it sits and why it matters, then draft the brief from them with each problem fixed or left as a visible placeholder. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- The task asked for fits the programme's kind of skill and the time the course gives it, with two good examples and one too-big example.
- The keep-it-safe rules ask for roles only and rule out names, contact details, identifying client or site details, health and absence reasons, and live cases.
- Completed templates travel only by the organisation's own route, and the brief says who reads them and when they're deleted.
- Everyone can take part: there's a fallback task for anyone without a suitable live one, and another way in for anyone who'd find writing it hard.
- The send date and the due date both fall before the course, with time for the trainer to read the tasks, and time to fill it in comes from work time.
- Nothing in the brief marks, scores or signs off a learner, and for safety-critical training no task requires doing the risky work to bring it.
- The template has six questions or fewer and can be filled in on a phone.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. Claude drafts the brief, the trainer uses the tasks for practice, and any judgement about a learner's skill stays with a person.
- Personal data: live tasks often hold other people's details. Under UK GDPR and the Data Protection Act 2018, a customer's or colleague's details in a task are personal data, and health or absence reasons are special category data, so the brief keeps them out. If anyone pastes completed templates into Claude, anonymise them first and follow the ICO's guidance and your organisation's AI policy.
- Fairness: every learner gets the same brief and the same fallback. Never infer or mention protected characteristics, and check the wording for assumptions about who does what kind of work.
- Law: the Equality Act 2010 requires reasonable adjustments for disabled learners, which here can mean a different way to give the task. For safety-critical or regulated training (the Health and Safety at Work etc. Act 1974 and the regulations for the topic), competence sign-off stays with a qualified person under the organisation's procedure. Check the current versions and HSE guidance. This is a draft, never legal advice.
- No invented facts: dates, routes, data rules and example tasks come from the user or stay as placeholders.
