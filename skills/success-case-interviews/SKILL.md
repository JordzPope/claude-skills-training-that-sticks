---
name: success-case-interviews
description: Drafts or checks a success case study for any training programme using Brinkerhoff's Success Case Method, with a short screening survey to find the most and least successful users, two to six interviews from each end, interview guides, consent wording, an evidence standard for calling something a success, and an anonymised write-up of what the programme changed and what blocked everyone else. Use when an L&D leader asks for success case interviews, the Brinkerhoff method, success stories from a programme the board will believe, why some people used the training and others didn't, interview questions to evaluate training, or a check of a success story write-up before it goes to leaders.
---

# Success Case Interviews

Plans and writes up a small study, following Brinkerhoff's Success Case Method, that finds the people who used a programme to real effect and the people who barely used it, and finds out why. It produces the screening survey, the choice of who to interview, the interview guides and consent wording, an evidence standard and the write-up. Or it checks a study or write-up someone else has done. From a dozen conversations, leaders get stories that hold up and a list of blockers to fix.

## When to use

- "I want real stories about what our management programme changed, ones the board will believe."
- "Plan a Brinkerhoff success case study for our systems rollout."
- "Half the cohort uses the new process and half doesn't. How do I find out why?"
- "Write interview questions for people who did the course three months ago."
- "Check this success story write-up before it goes to the Director of Operations."

Wrong tool for a survey of everyone who attended (use Application Survey), for the overall measurement plan (Transfer Evaluation Plan) or for the final report to leaders (Learning Impact Report, which takes this write-up as an input).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme, who attended (roles and numbers) and when it ended. [the study starts 8 to 16 weeks after the course, so people have had time to use it]
2. **Essential:** what successful use looks like: the behaviours at work and the results they should lead to. [from your Learning Impact Map; otherwise I'll draft an impact model for you to confirm]
3. Who will run the interviews. [an L&D business partner or someone else with no line responsibility for the people interviewed]
4. How many interviews there's time for. [four from each end, 30 to 40 minutes each]
5. Where evidence of a result might live: records, system data, quality checks, customer feedback. [ask each interviewee what would show it]

Never ask for names, health information or protected characteristics. The screening survey needs a way to reach people who agree to talk, so it is confidential: one role holds the contact list, and only respondent codes and answers come into this chat.

## Steps

1. Read what the user has given, including attachments. If they've given an existing study plan, interview notes or write-up, this is a check job: run the Quality checks on it, list each problem with where it sits and why it matters, then write a corrected version.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Write the impact model first: a short table running from what the programme teaches, to the behaviours at work, to the results they should produce, to the business goal. Brinkerhoff starts here because it defines "success" before anyone is interviewed. If the user has a Learning Impact Map, use it.
4. Draft the screening survey: three to five questions, sent to everyone who attended. The key question places each person using descriptions of what they did: "I've used it and can point to a result", "I've used it and there's no clear result yet", "I've tried it once or twice", "I haven't used it". Add one question asking what result, if any, and one optional question asking whether they'd talk for 30 minutes, with a line on how answers are used.
5. Choose interviewees from the two ends only: two to six from "used it and can point to a result" and two to six from "tried it once or twice" or "haven't used it". Choose from survey answers alone, spreading the choice across sites, shifts and roles where you can. Manager nominations tilt the sample towards people managers already rate, so leave them out. Record how many people gave each answer: these counts are the only proportions the write-up may give.
6. Write two interview guides, open and neutral, 30 to 40 minutes each.
   - **Success end:** "Tell me about one specific time you used [skill] at work." Then: what did you do, what happened next, what result followed, how could someone else check that (a record, a figure, a person by role), what helped (manager, tools, time, colleagues), and what would have happened without it.
   - **Other end:** "Tell me about the last time [situation] came up at work." Then: what did you do, what made the course hard to use, what would have needed to be different, and what, if anything, did you try. Probe across the three groups Baldwin and Ford found shape transfer: the person, the training design and the work environment. No question implies the person failed.
7. Apply the evidence standard to every success story. It counts as a success case only when it is **specific** (one occasion and what the person did), **verifiable** (a record, a figure or a second person, named by role, could confirm it) and would **stand up to a sceptic** (the result follows from the behaviour, and other explanations have been considered). Grade each story: **verified** (all three), **plausible** (specific, not yet checked; check it before using it) or **not a success case**. Only verified stories appear as success cases.
8. Handle consent and anonymity. Before each interview, share the consent wording: the purpose, how notes are kept and for how long, that the write-up is anonymised, that nothing is quoted without a second yes after they've seen the quote, and that they can withdraw. In the write-up, use labels (Supervisor A, Adviser B) and drop any combination of details (site, shift, role, length of service) that points to one person. Offer reasonable adjustments for the interview, such as the questions in advance or a different format.
9. Write up: the survey counts for each group; what the verified success cases did and what it produced; what blocked the least successful group, from their own interviews, sorted into person, design and work environment with how many interviews raised each; what separated the two groups; and two to four recommendations, each with an owner by role. Give no percentages from interviews; a handful of conversations can't say how common anything is.
10. Run the Quality checks below and fix what fails before showing anything.
11. Present the study or write-up, then a short **Assumptions** list and a **Check before you use it** list: that each verified story has been checked against its source, that consent is recorded for every quote, and that no detail identifies anyone.
12. Offer a .docx, the Barrier Removal Plan skill to act on what blocked people, or the Learning Impact Report to take the findings to leaders.

## Output format

Use the template in `templates/success-case-study.md`. It has six parts: the impact model, the screening survey, the selection record, consent wording, the two interview guides with an evidence log, and the write-up. The write-up runs two pages at most. Every count, story and quote comes from the user's survey results and interview notes or stays as a `[square-bracket placeholder]`.

## Try it

`examples/hallowmere-lead-the-shift-success-stories.md` is a draft write-up of success stories from Lead the Shift, the first-line management programme at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting it. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Interviewees come from both ends of a screening survey, two to six from each, chosen from survey answers alone.
- Every success case in the write-up meets all three parts of the evidence standard; the rest are graded plausible or left out.
- The write-up covers what blocked the least successful group, drawn from their own interviews, with each blocker sorted as person, design or work environment and given an owner by role.
- The only proportions come from the screening survey, with the base shown ("22 of 41 respondents"); no interview count becomes a percentage of the whole group.
- No interviewee can be identified: labels replace names, no combination of details points to one person, and every quote has recorded consent.
- Every interview question is open and neutral; none assumes the course worked or blames the person for not using it.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. This study looks at the programme and the workplace around it. Nothing in it judges anyone's skill, and nothing about a named person goes back to their manager; the least successful group are witnesses to what got in the way.
- Personal data: screening answers and interview notes are personal data under UK GDPR and the Data Protection Act 2018. Tell people what's collected and why, keep notes secure, delete identifiable notes when the write-up is done or as your retention policy says, and paste only anonymised notes into any AI tool. Follow the ICO's guidance and your organisation's AI policy.
- Taking part is voluntary. Nobody is pressed to take part, and managers aren't told who did.
- Fairness: if blockers cluster in one group (a shift pattern, part-time staff, one site), treat it as a question of opportunity and support, and never infer a protected characteristic. Under the Equality Act 2010, offer reasonable adjustments for the survey and the interviews. Check the current law and guidance; this study is a draft, never legal advice.
- No invented facts: stories, quotes and counts come from the user's survey results and notes. Never write a quote as if someone said it.
