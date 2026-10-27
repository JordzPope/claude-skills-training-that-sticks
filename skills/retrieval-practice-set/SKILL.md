---
name: retrieval-practice-set
description: Drafts or checks a retrieval practice set for any training programme, with scenario-based questions that make people recall and apply what they learned, wrong answers drawn from the mistakes people really make, feedback that explains why, and a schedule that spaces the questions across the course and the weeks after it. Use when an L&D manager, learning designer or trainer asks for knowledge check questions, quiz questions, a post-course quiz, recall questions, spaced practice questions, scenario-based multiple choice, a question bank for the LMS, or wants an existing quiz or knowledge check reviewed.
---

# Retrieval Practice Set

Produces a set of questions that make learners pull what they learned back out of memory and use it on situations from their own work, with feedback on every answer and a schedule that spreads the questions over the course and the weeks after. Or checks a quiz someone already has. The end-of-course quiz becomes practice that carries on once people are back at work.

## When to use

- "Write some knowledge check questions for the new systems training."
- "We do a quiz at the end of the course. Can you make it do more?"
- "I need questions we can send people at week 2 and week 6 after the course."
- "Check this question bank before it goes into the LMS."
- "Give me scenario questions for the complaints course, with feedback."

Wrong tool for a competence assessment or anything that signs a person off. For longer practice with branching decisions use Practice Scenarios; to fit the rounds into a dated plan of follow-up touchpoints use the Spaced Follow-Up Plan.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme and what learners should do differently at work afterwards (objectives, a content outline or the slides). [Claude proposes three to five job behaviours from the programme name for you to confirm]
2. **Essential:** the learners' roles and the situations where they'll use it. [one role group, using it in their everyday work]
3. The mistakes people really make on the job, from trainers, supervisors, or complaint and incident themes. [Claude proposes typical mistakes, marked for you to confirm]
4. When and how often people will need it at work. [from the first week, at least weekly]
5. How the questions reach people, and how many per round. [an LMS quiz or a Teams message; three to five questions, about 5 minutes]
6. Format needs for the group, such as phone-only access or screen readers. [readable on a phone, screen-reader friendly, no time limit]

Never ask for learners' names, individual scores or health details. If the user pastes results with names in them, work from the totals per question and say you've done so.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any attached slides, objectives, quiz or question bank. If they've given existing questions, this is a check job: run the Quality checks on every question and on the schedule, list each problem with the question number or schedule line and why it matters, then write a corrected set that keeps every sound question.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Turn the objectives into job behaviours, Mager-style: what someone does, in which situation, to what standard. Give each behaviour at least two questions. Content that links to no behaviour gets no question, however much slide time it had.
4. Write the questions, mostly at the apply level of Bloom's taxonomy or above:
   - **Recall:** "Write down..." or "List the steps..." from memory, with a model answer. Use for steps or rules people must have in their heads at the moment of use.
   - **Scenario choice:** a short situation from the learners' work, then "What do you do next?", with one best answer and two or three wrong ones. Each wrong answer is a mistake people really make (input 3), written as plausibly as the best answer and about the same length.
   - **Explain:** "Why does this step come first?" or "What would happen if...?", with what a good answer includes.
   Keep recognition-only items (spot the definition, pick the term) to one in five at most, and only for facts people must know cold. Word every item so it can't be answered by matching phrases from the slides.
5. Fit the mix to the programme. A systems course leans on recall of steps and "what next" screens. A management or customer course leans on scenarios with people in them. Compliance training asks when a rule applies on the job and what to do then.
6. Write feedback for every option: why it's right or wrong, and what it would lead to at work. Give a model answer for every open item. Learners see the feedback straight after they answer.
7. Schedule the set. Put rounds in the course itself: after each main block, and at the start of any later day before anyone recaps. Then space rounds after the course with gaps that grow, for example day 2, week 1, week 3, week 6. A field study of 10,514 people in workplace training (Kim, Wong-Kee-You, Wiseheart and Rosenbaum, Behavior Research Methods, 2019) found the best gap between retrieval rounds grows with the time until people need the skill, and Thalheimer's rule of thumb is to make the spacing roughly match how long people must remember it. So a skill used daily from go-live gets short gaps, and a skill used rarely, or refreshed once a year, gets rounds spread across the months in between. Mix a question or two from earlier rounds into each later one.
8. Set out how results are used. Each learner sees their own answers and the feedback. L&D sees only totals per question (how many chose each option), and only for groups of [10] or more, to find what needs teaching again. No scores reach managers by name, and nothing ranks people.
9. Make it accessible: plain English, readable on a phone, no meaning carried by colour or an image alone, alt text for any picture, no time limit unless the job itself sets one, and a spoken or printed version on request.
10. Run the Quality checks below and fix what fails before showing anything.
11. Present the set, then **Assumptions** and **Check before you use it**: that every best answer matches your current procedure, that the mistakes used are ones your people make, and that your LMS or messaging can send rounds on the dates shown.
12. Offer a .docx or an LMS import table (question, options, best option, feedback), or the Spaced Follow-Up Plan to place the rounds in a dated plan alongside other touchpoints.

## Output format

**Retrieval practice set: [programme], for [learner roles]**

1. **Behaviours covered**: a numbered list, each with a behaviour, a situation and a standard.
2. **Schedule**
   | Round | When | Questions | Format | Minutes |
   | In course 1 | after [block] | Q1 to Q4 | [paper or LMS] | [5] |
   | After course 1 | day [2] | [Q numbers] | [LMS or Teams] | [5] |
3. **Questions**, for each one:
   **Q[n]** (behaviour [n], type: recall, scenario or explain, round [n])
   [Question text]
   a) [option] b) [option] c) [option] d) [option] (scenario items)
   Best answer: [letter], or Model answer: [text]
   Feedback: one or two sentences per option, saying why and what it leads to at work.
4. **How results are used**: two or three sentences, one part for learners and one for L&D.

12 to 20 questions for a one-day course; scale to the length of the programme.

## Try it

`examples/hallowmere-asbestos-knowledge-check.md` is a draft knowledge check for the annual Asbestos Awareness refresher at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the set. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every question links to a job behaviour; none tests trivia, such as a date, a name or a figure from the slides, that would change nothing someone does at work.
- At least four in five questions make people recall or apply; recognition-only items are one in five or fewer.
- No trick questions: no double negatives, no "all of the above" or "none of the above", and no wording built to catch people out.
- Every wrong option is a mistake people really make, plausible and about the same length as the best answer.
- Every option has feedback that says why, and every open item has a model answer.
- The schedule has rounds during the course and at least three after it, with gaps that grow and fit when people need the skill.
- Each learner's results go to them alone; L&D sees only totals per question, and nothing names, ranks or scores people for their managers.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. This set is for each learner's own practice. A high score signs no one off, and a low one tells the learner, and whoever teaches it next, what to practise.
- Answers and scores tied to a named person are personal data under UK GDPR and the Data Protection Act 2018. Report totals per question, never by name, and follow the ICO's guidance and your organisation's AI policy before pasting any results into Claude.
- Under the Equality Act 2010, reasonable adjustments for disabled learners apply to practice and to any assessment, and materials should be accessible. Offer extra time, a spoken option or another format on request, without asking why.
- Treat everyone the same: one set and one schedule for the whole group, and no question that depends on idiom or cultural knowledge the job doesn't need.
- For safety-critical or regulated training (the Health and Safety at Work etc. Act 1974 and any sector regulator), this set adds practice to the course. Competence sign-off stays with a qualified person under your organisation's procedure. Check the current law and your procedure; this is a draft, never legal advice.
- Best answers, procedures and figures come from the user's materials or stay as placeholders for them to confirm.
