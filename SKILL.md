---
name: email-formatter
description: Turns rough notes, messy drafts, or long rambling text into a clean, professional email with a clear subject line, greeting, short body, and closing. Use this skill whenever the user asks to write, draft, format, clean up, tighten, or rewrite an email, or pastes a block of text and says it needs to be sent to someone, even if they don't say the word "format". Also use it for replies, follow-ups, requests, and thank-you notes.
---

# Email Formatter

Turn rough input into an email that is ready to send. The goal is that the reader understands what the email is about and what they need to do within a few seconds.

## Workflow

1. **Identify the basics** from what the user gave you:
   - Who the recipient is (professor, boss, client, teammate, stranger)
   - The purpose (request, update, follow-up, reply, thank-you, apology)
   - Any deadline, date, or action the reader must take
2. **Ask one short question only if something essential is missing** (for example, you cannot tell who the email is going to). Otherwise make a reasonable assumption, write the email, and state the assumption in one line after it.
3. **Pick the tone** using the table below. If the user names a tone, use theirs.
4. **Write the email** using the structure below.
5. **Check it** against the checklist before replying.

## Structure

Always output in this order:

```
Subject: <specific, under ~8 words>

<Greeting>,

<Opening line: the purpose of the email, stated directly.>

<Body: only the details the reader needs. Short paragraphs, or a short
bulleted list if there are 3+ parallel items.>

<Call to action: what you need from them and by when, if anything.>

<Closing>,
<Name>
```

## Tone guide

| Recipient | Greeting | Tone | Closing |
|---|---|---|---|
| Professor, executive, someone senior or unfamiliar | "Dear Professor Lee," / "Hello Ms. Patel," | Formal, respectful, no slang | "Sincerely," / "Best regards," |
| Client or colleague | "Hi Jordan," | Friendly but professional | "Best," / "Thanks," |
| Close teammate | "Hey Sam," | Casual, brief | "Thanks," |

## Rules

- **Subject line must be specific.** "Question about Week 3 homework deadline" is good. "Question" or "Hello" is not.
- **Lead with the point.** The first sentence says why you are writing.
- **Keep it short.** Aim for under 150 words unless the content truly needs more. Cut filler such as "I just wanted to reach out" and "I hope this email finds you well."
- **One email, one main ask.** If there are several asks, put them in a short list.
- **Put dates and deadlines in plain words** ("by Friday, October 3") rather than "soon" or "ASAP."
- **Keep the user's facts exactly.** Never invent names, dates, numbers, or commitments. If the user left a blank, write a bracketed placeholder like [date] instead of guessing.
- **Keep the user's voice.** Improve clarity, but do not make a casual message stiff or a formal one chatty.
- **Match the language** the user wrote in.

## Checklist before replying

- [ ] Subject line is specific
- [ ] Greeting and closing match the recipient
- [ ] First sentence states the purpose
- [ ] Any required action and deadline are clearly stated
- [ ] No invented facts
- [ ] Nothing that could be cut without losing meaning

## Output format

Give the finished email first, in a code block or clearly separated so it can be copied. After it, add at most two short lines: any assumption you made, and optionally an offer to make it more formal, shorter, or friendlier. Do not explain your edits at length unless asked.

For before-and-after examples, read `references/examples.md`.
