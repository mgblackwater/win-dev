---
title: The Code Writes Itself. What Should Developers Do Now?
published: false
description: AI agents free up hours. The goal isn't to ship more, it's to ship better. Here's where I think that time should go.
tags: ai, career, softwareengineering, productivity
---

AI agents now write a large share of our code. The obvious question is: what do developers do with the hours they get back?

My answer: **those hours don't stay free, and they shouldn't turn into more output either.** They should turn into more value and higher quality.

I built an interactive page to explain this, with animated diagrams:

👉 **[Open the interactive version](https://mgblackwater.github.io/win-dev/after-the-code/)**

Read on for the short version.

## 1. The time moves rather than disappears

When agents write the code, typing shrinks, but other work grows:

- **Specifying.** A vague requirement used to cost an afternoon. Now it produces a fast, confident, wrong pull request.
- **Verifying.** Reading code you didn't write is harder than writing it.
- **Owning.** When production breaks, "the agent wrote it" is not an answer.

## 2. Deliver more value, not more changes

Agents make it possible to ship more. That doesn't mean we should.

How you spend the saved time depends on the kind of work. For prototypes and internal tools, speed is fine. In healthcare, finance and other safety-critical domains, a fast release that breaks a critical workflow costs far more than a slow one that works.

**Not the goal:** more features per sprint, more releases per week, faster ticket closure.

**The goal:**

- Changes that clearly add value and are well understood
- Fewer tickets: higher quality means fewer breaking changes, and fixing root causes stops the same bugs coming back
- Deeper testing and edge cases
- Security and compliance review
- Paying down risky legacy code
- Validating features with real users

## 3. Gates keep quality high as agents write more code

Tests, type checks, linters, security scans and architecture rules in CI. Every change an agent makes passes through them. Work you put into the gates pays off on every future change, whether a person or an agent wrote it. The aim is stable releases, not more releases.

## 4. Five core areas to invest in

Ranked by long-term value:

1. **Gates and codebase improvements.** An agent working inside strong guardrails can be trusted with much more.
2. **Secure coding.** Agents repeat insecure patterns confidently and at volume. Learn what to look for in review.
3. **Communication.** Clear specs and explained trade-offs. A prompt is a spec for an agent, so this is now a core engineering skill.
4. **Learning, deep rather than wide.** System design, data modeling and your business domain. This is how you spot when an agent's design is subtly wrong.
5. **Keeping up with AI, time-boxed.** Tools change every month. An hour or two a week is enough. Learn the patterns that last: context, verification, decomposition.

## 5. Easy to overlook

- **Getting closer to users.** When code is cheap, the engineer who knows why a feature exists is worth more.
- **Observability.** Know how the system really behaves in production, so stability and quality are measured, not assumed.
- **Mentoring.** The old learning path of writing lots of code is getting shorter. Someone has to teach judgment.
- **Rest.** Reviewing all day is draining. If every freed hour becomes more output, burnout comes sooner.

## 6. A suggested weekly split

| Area | Share |
|---|---|
| Guardrails, gates, codebase health | 30% |
| Deep learning: design, security, domain | 25% |
| Communication, specs, people | 25% |
| AI tooling (time-boxed) | 10% |
| Slack and rest | 10% |

It's a starting point, not a rule. Adjust it to your role.

## Questions for your team

- Which of your work needs speed, and which needs stability above all?
- Which guardrail would catch the most agent mistakes if you added it this month?
- How do you review agent-written code well without spending the whole day doing it?
- What should "good work" mean once lines of code and closed tickets stop meaning much?

I'd like to hear how your team is handling this. Tell me in the comments.
