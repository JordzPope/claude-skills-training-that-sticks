---
name: practice-scenarios
description: Drafts or checks work-based practice scenarios for any training programme, each with realistic decision points, options drawn from the mistakes people really make, what each choice leads to, and feedback that explains why, written at three levels of difficulty. Use when an L&D manager, learning designer or trainer asks for practice scenarios, case studies, branching scenarios, what-would-you-do exercises, role-play briefs with an observer sheet, decision-making practice, easy-to-hard practice activities, or wants existing scenarios or role plays checked.
---

# Practice Scenarios

Produces scenarios set in the learners' own work, where they make the calls they'll face on the job, see what each choice leads to and get feedback on why. Each comes at three levels, from a straightforward case to a messy one. Or checks scenarios someone already has. A course gets practice that looks like the job, built in one sitting.

## When to use

- "I need three scenarios for the complaints course, from easy to hard."
- "Write a branching scenario for supervisors handling a sickness absence call."
- "These case studies are just stories. Can you put decisions in them?"
- "Write role-play briefs for the customer and the adviser, with an observer sheet."
- "Check these scenarios before the pilot."

Wrong tool for short quiz questions (use the Retrieval Practice Set) or for planning the session time around the scenarios (use Session Plan Rework).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme and the skill to practise, as something people do at work. [Claude proposes one from the programme name for you to confirm]
2. **Essential:** the learners' roles and the real situations they meet: who's involved, where, and what's usually at stake. [two or three typical situations, proposed by Claude and marked for you to confirm]
3. The mistakes people really make, and what good looks like, from trainers, team leaders, or complaint and incident themes. [Claude proposes typical ones, marked for you to confirm]
4. Format. [written scenarios worked in pairs, then a trainer debrief; role-play briefs or an e-learning branch on request]
5. How many and how long. [one scenario at each of three levels, 15 to 20 minutes each including debrief]

Never ask for real customer, client or employee details, case files or names. If the user pastes a real case, strip anything identifying, change enough facts that no one could be recognised, and say you've done so.

## Steps

1. Read what the user has given, including attached scenarios, case studies, role-play briefs or course materials. If they've given existing scenarios, this is a check job: run the Quality checks on each one, list every problem with the scenario, the decision point and why it matters, then write corrected versions that keep the user's situations and content.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Decide whether the skill is open or closed. A closed skill has one right sequence (a system procedure, isolating a supply). An open skill depends on the person and the moment (a complaint call, feedback to a team member, a client conversation). Blume, Ford, Baldwin and Huang's 2010 meta-analysis of 89 studies found most predictors of transfer were stronger for open skills than for closed ones. For a closed skill, feedback names the right step and why it comes there. For an open skill, accept more than one good response, and write feedback around the principles a good response meets and what each route costs.
4. Build each scenario from a real situation: the setting, who's involved (by role), what has happened so far and what the learner knows, in the words, systems and paperwork the learners use. Keep the setup to 120 words or fewer.
5. Write the decision points. Each has three or four options: the good response and two or three mistakes people really make (input 3), each as tempting as the good one and about the same length. Drop any option no one would choose. After each option write what happens next: what the other person says or does, and what it leads to on the job (a reopened complaint, a missed SLA, a team member who stops raising problems). Then the feedback: why the choice works or falls short, in one to three sentences.
6. Write the three levels so each is harder in structure, beyond a longer setup:
   - **Level 1, foundation:** one decision, clear facts, a cooperative other person.
   - **Level 2, working:** two or three linked decisions, one missing fact the learner must think to ask for or look up, and one competing pressure (time, a target, a second customer waiting).
   - **Level 3, stretch:** an upset or unhappy other person, goals that pull against each other, a grey area in policy, and at least two defensible routes. Feedback compares the routes and what each costs.
7. For open skills, add a free-response step at Levels 2 and 3: "What would you say?", followed by what a good answer includes and two sample good answers that differ from each other.
8. For role plays, write a brief for each role. The other person's brief says how they react to good and poor handling, so the practice has consequences. Add an observer sheet using SBI (situation, behaviour, impact): what to watch for, one thing that worked and one to try differently. Observers give feedback, and nobody scores anybody.
9. Check the characters. Vary them, keep out any detail the scenario doesn't need, and never make age, disability, race, accent, religion, sex or any other protected characteristic the source of difficulty or a joke. Add a content note to any scenario on a distressing topic (bereavement, injury, abuse) and offer a lighter or written version.
10. Run the Quality checks below and fix what fails before showing anything.
11. Present the scenarios, then **Assumptions** and **Check before you use it**: that the good responses match your current policy and procedures, that the mistakes are ones your people make, and that the consequences are realistic for your organisation.
12. Offer a .docx, print-ready scenario cards, or the Observation Guide so managers watch for the same behaviour back at work.

## Output format

**Practice scenarios: [programme], [skill], for [learner roles]**
Skill type: [open or closed]. Format: [written, role play or e-learning]. Time: [minutes per level].

For each level:

**Level [1, 2 or 3]: [short title]**
*Setup* (120 words at most): [setting, people by role, what has happened, what the learner knows]
*Decision [n]:* [the question]
| Option | What happens next | Feedback |
| a) [option] | [consequence at work] | [why it works or falls short] |
*Free response* (Levels 2 and 3, open skills): "What would you say?" A good answer includes: [points]. Two sample good answers: [1], [2].
*Debrief questions* for the trainer: two or three.

For role plays, add: a brief per role (about 100 words each) and the observer sheet with SBI prompts.

## Try it

`examples/hallowmere-complaints-scenarios.md` is a draft set of scenarios for Complaints That Close, the customer advisers' course at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the scenarios. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every scenario is set in the learners' real work, with their systems and words, and holds no real customer or employee details.
- Every decision point has three or four options, and every wrong option is a real mistake someone could plausibly choose.
- Every option shows what happens next at work and has feedback that says why; no feedback is a bare "correct" or "try again".
- Level 2 adds linked decisions, a missing fact and a competing pressure to Level 1; Level 3 adds a grey area with at least two defensible routes.
- For an open skill, the feedback accepts more than one good response and names the principles a good response meets.
- No character's age, disability, race, accent, religion, sex or any other protected characteristic is the source of difficulty or humour.
- Where there's a role play, observers give feedback on behaviour using SBI, and no one is scored.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. Claude drafts the scenarios and feedback; the trainer runs the debrief, and how anyone does in a scenario stays in the room as practice, off their record.
- Real cases make the best scenarios, so anonymise before pasting one in: no names, account numbers, addresses or anything that could identify a customer or colleague. Follow UK GDPR, the Data Protection Act 2018, the ICO's guidance and your organisation's AI policy.
- Every learner in the group works the same scenarios at the same levels. Check the wording for stereotypes, and keep personal details out of characters unless the skill being practised needs them.
- Under the Equality Act 2010, reasonable adjustments for disabled learners apply to practice activities, including role play: time to read, a written alternative, a quieter space. Materials should be accessible. Check the current guidance; this is a draft, never legal advice.
- For safety-critical tasks, scenarios practise the decisions. The practical assessment and any competence sign-off stay with a qualified person under your organisation's procedure and the Health and Safety at Work etc. Act 1974.
- Policies, SLAs, procedures and consequences come from the user or stay as placeholders for them to confirm.
