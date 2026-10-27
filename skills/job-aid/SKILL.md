---
name: job-aid
description: Drafts or checks a one-page job aid that people use at the moment they need it, as a checklist, decision table, step flow or prompt card, with the trigger for using it at the top and everything else cut to what's needed at the point of work. Use when a Head of L&D, L&D manager, learning designer or trainer asks for a job aid, a quick reference guide, a cheat sheet, a crib sheet, a task checklist, a laminated card, a decision tree or decision guide, a one-pager to go with a course, performance support, or a check of an existing quick reference card before it's printed.
---

# Job Aid

Produces a one-page reference that people pick up in the middle of the task: a checklist, a decision table, a numbered step flow or a prompt card, with the moment to use it printed at the top. Or checks one someone has already drafted. It moves the steps people forget out of the slide deck and on to the job, where they're needed.

## When to use

- "Make a quick reference card for the new job-management app, for engineers on site."
- "Turn the return-to-work process into a checklist supervisors can use before the meeting."
- "Our cheat sheet is two pages of text. Can you cut it down?"
- "We need a decision guide for advisers on when to pass a complaint on, and to whom."
- "Check this job aid before we laminate 600 copies."

Wrong tool for teaching the skill in the first place, or for anything people must do from memory at speed, such as a live conversation or an emergency. Those need practice: use Practice Scenarios or Retrieval Practice Set.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the programme and the task: what people are doing when they reach for this, and what goes wrong now.
2. **Essential:** the steps, rules or choices in the task, from the course materials, the procedure or a process map. [from the attached materials; Claude never invents a step]
3. Where and how it's used: on a phone, a printed card in a van, a wall chart, on screen beside a system. [A5 printed card plus a PDF that reads on a phone]
4. For a safety-critical or regulated task: the procedure it supports, with its title, reference and date, and the role that owns it. [placeholder, listed under Check before you use it]
5. Who owns the job aid and when it's reviewed. [the learning designer; reviewed yearly or when the process changes]
6. Who uses it, and whether anyone needs another format: large print, screen reader, a language other than English. [no format needs flagged]

Never ask for names or personal details. A job aid is about the task, so contacts appear as roles and work channels.

## Steps

1. Read what the user has given, including any slides, procedure or process map. If they've given an existing job aid, this is a check job: run the Quality checks on it, list each problem with where it sits and why it matters, then write a corrected version.
2. Ask for missing essentials in one message, five questions at most, showing the defaults. If they say "just draft it", use the defaults, leave placeholders and list the assumptions.
3. Check that a job aid suits the task. It helps when people can glance at something while they work, when the task is done rarely or has many steps, and when a mistake is costly. It helps less when the task has to happen from memory in real time, mid-conversation or in an emergency; say so, suggest practice for that part, and keep any card for before or after the moment.
4. Write the trigger first: one line saying when to pick this up, as a situation at work. "Use this when you close a reactive job in the app." "Use this before a return-to-work conversation." If people need it at two different moments, make two job aids.
5. Pick the format from the shape of the task:
   - **Step flow:** a fixed order. Number the steps, start each with a verb, 7 steps at most.
   - **Checklist:** items that must all be done or checked, in any order. 12 items at most, each with a tick box.
   - **Decision table:** a choice that depends on conditions. "If [condition], then [action]" rows covering every likely case, plus a last row for anything else that says stop and who to ask.
   - **Prompt card:** for a conversation. The questions or phrases in order, with what to listen for.
6. Cut to what's needed at the point of work: steps, cues, limits, thresholds and who to call. Move background, theory, history, statistics, definitions people already know and "why this matters" stories back to the course, or behind a single "learn more" link. Test each line: would someone with the task in front of them read it? If not, it goes. No paragraph runs past two lines, and each step is 15 words or fewer.
7. For a safety-critical or regulated task, the organisation's procedure is the authority. Name it on the job aid (title, reference, date) and say the procedure wins if the two ever differ. Take steps from it word for word, and never add, loosen or reorder one. Where the task calls for judgement, the job aid says stop and names the role to call. Have the procedure owner check it before release. The job aid is never evidence of competence; sign-off stays with a qualified person under the procedure.
8. Make it readable where it's used: large type, high contrast, short lines. Every row and step carries its meaning in words, with colour, icons and images only backing the words up. Check it fits one side of A4 or A5 and reads on a phone without zooming. Offer an accessible digital version (real text, tagged headings, descriptive link text) and large print on request.
9. Add a footer: owner role, version and date, next review date, and where the full procedure or course materials live.
10. Run the Quality checks and fix what fails.
11. Present the job aid, then **Assumptions** and **Check before you use it**: each step against the current procedure or system; a trial with two or three people doing the real task; a print and phone test; and, for a safety-critical task, approval by the procedure owner.
12. Offer a .docx, a phone-sized version, or Reinforcement Nudges to point people to it at the right moment.

## Output format

**[Title: the task, in plain words]**
**Use this when:** [the situation at work, one line]
[Safety-critical or regulated task only: **This card supports [procedure title, reference, date]. If they differ, follow the procedure.**]

Then one of:

- **Step flow:** 1. [Verb + step, 15 words or fewer] ... 7 steps at most.
- **Checklist:** ☐ [Verb + item] ... 12 items at most.
- **Decision table:**
  | If | Then | Who to call |
  Last row: Anything else · Stop and ask · [role]
- **Prompt card:** [question or phrase] · Listen for: [cue]

**If you're stuck:** [role, and how to reach them through work channels]

Footer: Owner [role] · v[n], [date] · Review by [date] · Full procedure or course: [where]

One side of A4 or A5. Then **Assumptions** and **Check before you use it**.

## Try it

`examples/hallowmere-asbestos-job-aid-draft.md` is a draft quick reference card for the Asbestos Awareness refresher at Hallowmere Facilities, a fictional 1,400-person facilities services firm, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the card. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-training-that-sticks), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- The first line is the trigger: a situation at work that tells people when to pick it up.
- It fits one side of A4 or A5: a step flow has 7 steps at most, a checklist 12 items at most, and no paragraph runs past two lines.
- Every step or item starts with a verb and runs to 15 words or fewer.
- Background, theory, history and statistics are absent, left to the course or one "learn more" link.
- For a safety-critical or regulated task, it names the organisation's procedure as the authority, changes no step in it, sends every judgement call to a named role, and lists the procedure owner's approval under Check before you use it.
- Every row and step carries its meaning in words; nothing depends on colour or an image alone.
- The footer gives an owner role, a version date and a review date.

## Guardrails

- The one rule for this pack: Claude drafts the plans, nudges and reports. Managers do the coaching, and a person makes every call about someone's skill. A job aid helps people do the task; using it, or having read it, never shows that someone is competent.
- Personal data: a job aid needs none. Leave out names and personal contact details, give contacts as roles and work channels (a team phone line, a shared mailbox), and follow your organisation's AI policy before pasting internal procedures into Claude.
- Access: under the Equality Act 2010, reasonable adjustments apply to work materials, so the job aid should be accessible: plain words, real text, good contrast, meaning carried in words, and large print or a screen-reader version on request.
- Safety-critical or regulated tasks: the organisation's procedure, the Health and Safety at Work etc. Act 1974, and the regulations and HSE or regulator guidance for the task are the authority. Competence sign-off stays with a qualified person under the procedure, and the procedure owner approves the job aid before anyone uses it.
- Check the current versions of the law and guidance named here. This is a draft, never legal or safety advice.
- No invented facts: steps, limits, thresholds and contacts come from the user's materials or stay as placeholders.
