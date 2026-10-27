---
name: peer-practice-circle
description: Drafts the plan for a peer practice circle after a training course, where small groups of four to six learners meet a few times in the weeks after to share what they tried at work, what stuck and what got in the way. Covers who sits in each circle, the dates, ground rules, a timed agenda with prompts, a host card members take in turn, and the invitation. Works for any programme. Use when an L&D manager or L&D business partner asks to set up a peer practice group, a learning circle, a peer support group for new managers, a practice group after a course, a buddy group, or a way for learners to keep practising together once the training is over.
---

# Peer Practice Circle

Produces the plan for small peer groups that meet three or four times after a course: who's in each circle, the dates, ground rules, a timed agenda with prompts, a host card each member takes in turn, and the invitation. It gives learners a regular reason to keep using what they learned, and gives L&D an early view of what's getting in the way.

## When to use

- "Set up peer groups for our new managers after the leadership programme."
- "I want people to meet after the course and swap what they've tried. What's the agenda?"
- "Write ground rules and prompts for a learning circle."
- "Here are my notes for a practice group. Can you turn them into a plan I can send?"

This skill drafts only. Bring notes, an email thread or last year's plan, and Claude lists what in them would put people off or make the circle unsafe to speak in, then drafts from them. Wrong tool for one-to-one follow-up by a manager (use the Manager Follow-Up Guide), weekly tasks for each learner (use Practice Challenges), or fixing what blocks a whole team (use the Barrier Removal Plan).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme and the two to four things learners should now do at work. [if only a course title is given, Claude proposes behaviours and marks them as proposed]
2. **Essential:** who's in it: roles, how many, where they work and their working patterns. [one cohort of learners at a similar level]
3. How they'll meet. [Microsoft Teams or the organisation's usual meeting tool, cameras optional]
4. How many meetings, how long and how far apart. [three meetings of 60 minutes, at about weeks 2, 5 and 9 after the course]
5. Whether L&D attends. [an L&D team member hosts the first meeting only; members take turns after that]

Never ask for names, health details or protected characteristics. Circles are formed by role, site and working pattern. If notes include names or health details, leave them out and say so.

## Steps

1. Read what the user has given: notes, an email, an earlier plan or a programme outline. This skill drafts only, so treat any of these as input: list every problem the Quality checks would catch in them, quoting where each sits and saying why it matters, then draft the plan with each problem fixed or left as a visible placeholder.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Form the circles. Four to six people each; split a bigger cohort into several circles. Mix sites or teams where you can, so people hear situations unlike their own. Keep people out of a circle with anyone who line-manages them, and keep senior sponsors and anyone who assesses members out of the room: people talk more openly about what went wrong when no one present has a say over their job.
4. Set the dates. Spread the meetings across the weeks when people first use the skill, with the last one around the time it should be routine. A study of 10,514 people in real workplace training (Kim and colleagues, 2019) found the best gap between returns to a skill grows with how long people need to keep it, so later gaps can be longer. Every meeting sits in work time, at a slot every member can make. For shift workers, place it inside shifts or agree with their managers that it counts as working time.
5. Write five or six ground rules for the group to agree at the first meeting. What's said stays in the circle, apart from themes the group agrees to pass on and any safety or safeguarding concern, which goes through [the organisation's procedure] straight away. Members talk about their own practice and describe customers, clients and colleagues by role. Questions come before advice. Everyone gets time, and anyone can pass.
6. Write the agenda, timed to the meeting length. For 60 minutes:
   - **Recall** (5 min): one or two questions on the course content, answered from memory before anyone looks at notes.
   - **Round** (20 min): each member says what they tried since last time, what happened, and what they'll keep.
   - **One live case** (20 min): one member brings a situation coming up; the others ask open questions first, then offer ideas; the member picks what to try.
   - **Commit** (10 min): each member writes one if-then plan for the next gap: "If [situation], then I will [action]." Gollwitzer's work on implementation intentions found plans in this form raise the odds people act.
   - **Themes** (5 min): the group agrees up to two tips or barriers to pass to L&D, with no names.
   Fit every prompt to the programme, and check the times add up.
7. Give each meeting a focus. Meeting 1: ground rules and first tries. Middle meetings: the harder cases. Last meeting: what's become habit, what each member keeps doing, and whether the circle carries on without L&D.
8. Write the host card: send the reminder two working days before, keep time, make sure everyone speaks, and send L&D the agreed themes and a head count. The host doesn't assess or report on anyone.
9. Write a short invitation to members, with a prompt to say if anything would make it easier to take part (captions, materials sent in advance, a quiet room, a different format), handled through [the organisation's adjustments process]. Invite every learner from the programme, including anyone away at the start, who can join when they're back. Add two lines to members' managers asking them to protect the time.
10. Run the Quality checks below and fix what fails.
11. Present the plan, then **Assumptions** and **Check before you use it**: the dates and slots, who hosts first, whether shift patterns allow the slot, and who in L&D receives the themes.
12. Offer a .docx, the invitation as a Teams message, the Barrier Removal Plan for themes the circles raise, or the Manager Follow-Up Guide.

## Output format

**Peer practice circle plan: [programme]**

1. **Circles**
   | Circle | Roles and sites | Members | Slot | Format |
2. **Dates**
   | Meeting | Week after the course | Date | Focus |
3. **Ground rules**: five or six, for the group to agree.
4. **Agenda** ([60] minutes)
   | Time | Round | Prompts |
5. **Host card**: five or six lines.
6. **What goes to L&D**: head count per meeting and agreed themes, no names.
7. **Invitation** to members (under 150 words) and **note to managers** (two lines).

Two pages at most.

## Try it

`examples/hallowmere-contract-conversations-circle-notes.md` holds an L&D business partner's rough notes for setting up a circle after Contract Conversations, a course on difficult client conversations at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in them. When the user says "try it", "show me" or "use the example", read that file, list every problem you find in the notes with where it sits and why it matters, then draft the plan from them with each problem fixed or left as a visible placeholder. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Each circle has four to six members, and nobody in it line-manages, assesses or reports on another member.
- Every meeting is in work time, at a slot every member can make, and the invitation asks about adjustments.
- Every learner on the programme is invited, including anyone away at the start.
- Each agenda includes recall, a round of what people tried and an if-then commitment, and the times add up to the meeting length.
- Every prompt is an open question about the member's own practice at work.
- What leaves the circle is a head count and agreed themes, with no names and nothing about any member's performance.
- No names, health details or protected characteristics appear. Dates and slots the user didn't give are marked as proposed.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. Claude drafts the plan and the prompts; members support each other, and nothing said in a circle is used to judge anyone's skill or performance.
- Work with roles, never names. Notes on what a named person said are personal data under UK GDPR and the Data Protection Act 2018, so the host records themes only. Follow the ICO's guidance and your organisation's AI policy.
- Offer the circle to everyone on the programme on the same terms. Never infer or mention protected characteristics, and leave out anyone's health or absence details. Meetings out of hours can shut out people with caring responsibilities, so keep them in work time. The Equality Act 2010 requires reasonable adjustments for disabled people taking part. Check the current version on GOV.UK. This is a draft plan, never legal advice.
- Dates, slots, numbers and programme details come from the user or stay as placeholders.
