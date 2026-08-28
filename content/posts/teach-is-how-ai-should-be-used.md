+++
title = "The /teach skill is how AI should be used"
date = 2026-08-26T20:48:00+08:00
draft = false
+++

In the software realm, agentic coding is a big thing now. Had been for a year and a half, and if you have been in that space recently, you might have used skills: documents that extends an agent's capabilities by giving domain-specific information. You can give an agent a skill, for instance, for [frontend design](https://www.skills.sh/anthropics/skills/frontend-design) or [test-driven development](https://www.skills.sh/mattpocock/skills/tdd), augmenting that agent's skillset.

I was working on a coding-first learning platform the first quarter of this year which I dropped by the second quarter due to other responsibilities, when my boss sent me a link to the [/teach](https://www.aihero.dev/skills-teach) skill around two months ago, as it seemed to align with my [Code To Learn](https://github.com/codenamerey/code-to-learn) project, so I gave it a whirl. Unlike most agent skills, `/teach` is not programming-centric; it can be used to learn anything. Matt Pocock, the skill's author, said in a video, verbatim, that "The idea of this skill is you can use it to learn really anything: You can use it to teach you a new language; to learn a new coding language; to learn Rubik's cube [...]; to learn vocal harmonies". In brief, anything you want to learn, the skill can guide you through it.

[![Learn anything with the /teach skill](https://img.youtube.com/vi/s5T5oQJcJ6U/maxresdefault.jpg)](https://youtu.be/s5T5oQJcJ6U)
*Watch Matt Pocock's video on his /teach skill*

AI, particularly LLMs, is not new to students anymore. Some of my friends who are not studying IT has used AI in some way to aid their studies, by going into ChatGPT or Claude through their web apps, and asking *ELI5* and conceptual questions; one of them humorously prompted "ChatGPT, explain this to me as if I'm a donkey"!

`/teach` is new in that it establishes a mission; asks the user *why* they want to learn a subject, and builds the course off of that.

The skill is straightforward. Ask it to `/teach` you something, answer a few questions about intent and commitment, and lo a lesson is built. There is a three-question multiple choice knowledge check at the end of each lesson, and after finishing a lesson, in goes another (by telling AI to generate the next one).

I took the liberty to modify the skill quite to make it more interactive: a three-question knowledge check does not cut it, so I had it write an assignment, or assignments, each lesson; a gamified, centralized course tracker UI; finally, a pass/fail system which has the AI as the evaluator.

I pointed it to an electrical circuits resource which I used to refer to back in undergrad; so far, I've finished 15 lessons out of 80 across a month!

You can try it for yourself, dear readers, but some setup is involved.

I like the `teach` skill. I've been using it a lot recently. While 

This becomes especially interesting given that the frontier AI models have already reached PhD-level in STEM, and getting better by the day.

In a reality where AI is hugely used to cheat on exams, plagiarize essays, and generate prayers ([I wish I was joking](https://www.youtube.com/watch?v=7qM-U05mrbo)), it's an actual use case, among other things, that pushes humanity in the right direction.

*Below shows how I used `/teach` for my electrical circuits review.*

### Gallery

![Learn Electronics tracker screen](/img/learn-electronics.png)
*A look at the tracker screen for the electrical circuit course.*

![Learn Electronics lesson screen](/img/learn-electronics-lesson-screen.png)
*Learn electrical circuit's lesson screen.*

![AI's feedback on image submission](/img/learn-electronics-feedback.png)

*The AI's feedback on my image submission.*

![AI's image annotations](/img/learn-electronics-annotations.png)
*The AI's corrections on my image submission*
