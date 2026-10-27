---
name: application-survey
description: Drafts or checks the follow-up survey sent about 60 days after any training programme, asking what people used at work, how often, what got in the way and what changed, with behaviour-anchored answer options, no smile-sheet questions, anonymous or aggregated results, a send plan and an analysis plan. Also rewrites an end-of-course happy sheet into an application survey. Use when an L&D leader asks for a post-training survey, a 60-day or 90-day follow-up survey, a training transfer survey, a level 3 survey, questions to find out whether people are using what they learned, or wants to fix or rewrite a happy sheet, smile sheet or course feedback form.
---

# Application Survey

Drafts the short survey that goes to everyone who attended a programme at around day 60, asking what they've used at work, how often, what got in the way and what changed, with the send plan and how the answers will be analysed. Or checks an existing survey, often an end-of-course happy sheet, and rewrites it. It gives you the first evidence of use, and a list of barriers to fix, for five minutes of each learner's time.

## When to use

- "Write a follow-up survey for the people who did our customer service course two months ago."
- "Turn our course feedback form into something that tells us if people are using it."
- "Our happy sheets always say 4.6 out of 5 and nothing changes. What should we ask instead?"
- "We need a level 3 survey for the new system training."
- "Check this survey before it goes out to 600 engineers."

Wrong tool for planning the whole evaluation (use Transfer Evaluation Plan) or for finding out in depth why some people used it and others didn't (use Success Case Interviews).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme and the two to six behaviours it should change at work. [from your On-the-Job Objectives or Transfer Evaluation Plan; otherwise I'll draft them from the course outline for you to confirm]
2. **Essential:** who it goes to, and when they could first use it at work. [everyone who attended; the last day of the course, or the go-live date for a new system]
3. The survey tool and the device people answer on. [Microsoft Forms, a link sent by email and Teams, built to work on a phone]
4. Anonymous, or confidential with results reported in aggregate. [anonymous]
5. Any groups to split results by. [none; any split shows only for groups of 10 or more responses]
6. Whether you'll also run Success Case Interviews. [no; if yes, a separate opt-in form so survey answers stay anonymous]

Never ask for names, employee numbers, health information or protected characteristics, and never add questions that collect them.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including attachments. If they've given an existing survey or feedback form, this is a check job: run the Quality checks on it, list each problem by question number with why it matters, then write the rewritten survey. When rewriting a happy sheet, keep any question that earns its place and say which ones you dropped and why.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Set the timing. Send around day 60, counted from the first real chance to use the skill at work [between six and ten weeks after it], so people have had chances to use it and can still remember the course. One reminder after a week; close after two weeks. For cohorts, each cohort gets its own day 60.
4. Write one use question per behaviour, naming it in work terms with a set period: "In the last four weeks, when [situation] came up, how often did you [behaviour]?" Use answer options that describe what someone did, in order: "It hasn't come up", "It came up and I didn't try it", "I tried it once or twice", "I did it most times it came up". Keep "hasn't come up" apart from "didn't try": the first is a problem of opportunity, the second of confidence, support or fit, and each needs a different fix.
5. Write the barrier question: "What, if anything, has made it harder to do this at work?" Tick all that apply, with options across the three groups Baldwin and Ford found shape transfer: the person ("I'm not sure how to do it yet"), the training ("the course didn't match my job"; "I've forgotten parts of it") and the work environment ("no time"; "targets or KPIs pull the other way"; "tools or systems don't support it"; "my manager hasn't talked to me about it"; "no chance to use it yet"). Add "Nothing has got in the way" and "Something else (please say)".
6. Ask whether their manager talked with them about the course before it, after it, both or neither. In Broad and Newstrom's transfer matrix the manager's part before training ranked as the most powerful point of all, so this answer shows where to put effort next time.
7. Write the change questions: "Has anything changed in your work since you started doing this?" with "Nothing yet", "A small change I could describe" and "A clear change other people have noticed"; then one open question: "Describe one time in the last month you did this. What happened?"
8. Close with one open question: "What would help you do this more?" Keep the whole survey to [8 to 12] questions, at most three of them open, under five minutes on a phone.
9. Test every question for four faults and rewrite any that fail: leading wording that assumes the course helped; two questions in one; agree or disagree scales about feelings ("I feel confident"); course jargon people may not remember.
10. Write the intro: what the survey is for, how long it takes, that it's anonymous (or exactly who sees results, and in what form), that results are reported only for groups of [10] or more, and how to ask for another format.
11. Write the analysis plan: count answers per behaviour with the base shown ("46 of 180 responded"); report "hasn't come up" apart from "didn't try"; theme the open answers and count each theme; send barriers to the Barrier Removal Plan skill and results to the Learning Impact Report. Label the results as self-report, best read beside a measure from work records or observation in the Transfer Evaluation Plan.
12. Run the Quality checks below and fix what fails before showing anything.
13. Present the survey, then a short **Assumptions** list and a **Check before you use it** list: the send and close dates, the tool's privacy settings (some form tools record names or email addresses unless you switch it off), and who will see the raw responses.
14. Offer a .docx, a version laid out for the user's survey tool, or the Barrier Removal Plan once results are in.

## Output format

Use the template in `templates/application-survey.md`: the send plan, the intro, the questions with their answer options in order, a thank-you line and the analysis plan. Eight to twelve questions. Every behaviour, date and threshold comes from the user or stays as a `[square-bracket placeholder]`.

## Try it

`examples/hallowmere-fieldpro-feedback-survey.md` is a draft survey for the FieldPro app training at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting it as an application survey. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every use question names one behaviour in work terms and a set period, with answer options that describe what someone did, including "it hasn't come up" as a separate option.
- No question asks about satisfaction, enjoyment, the trainer, the venue or the food, and there's no recommend-to-a-colleague score.
- No question is leading (assumes the course helped) or double-barrelled (asks two things at once), and every scale includes a "no change" or "not at all" option.
- The survey asks what got in the way, with options covering the person, the training and the work environment.
- No question collects names, employee numbers or any detail that could identify someone in a group of fewer than [10]; the intro says who sees what.
- The send date falls six to ten weeks after people's first real chance to use the skill at work, with a reminder and a close date.
- The survey has [8 to 12] questions, no more than three open, and takes under five minutes.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. This survey asks about the programme and the workplace. Results are reported for groups and are never used to judge, rank or follow up one learner; any conversation about one person's use belongs to their manager, as coaching.
- Personal data: survey answers linked to a named person are personal data under UK GDPR and the Data Protection Act 2018. Keep the survey anonymous by default; never link answers to employee numbers, system usage or performance data. Remove names from open answers before pasting them into any AI tool, and follow the ICO's guidance and your organisation's AI policy.
- Fairness: if results differ between sites, shifts or contract types, look first at differences in opportunity, time, tools and manager support. Ask no question about protected characteristics, and never infer one from the answers.
- Equality Act 2010: make the survey accessible (plain English, works with a screen reader and on a phone, readable text size) and offer another format, or help to complete it, as a reasonable adjustment. Check the current law and guidance; this survey is a draft, never legal advice.
- No invented facts: behaviours, dates and response counts come from the user or stay as placeholders.
