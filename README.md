# Devinci - The Open Source, Free, No-Hype Alternative to Devin with Better Features

## Summary

Within the span of 3 months, there will be a FREE, better-performing, and more useful version of the over-hyped (and guaranteed to under-deliver) promise of the recently marketed so-called "Devin - the First AI Software Engineer".

But first, let's discuss what "Devin" is not before we dive into what Devinci will be:

- **AGI** - (or Artificial General Intelligence for software development). Please, stop with this claim; none of Devin's functionalities represent AGI. Wrapping highly-available AI models around tooling is NOT AGI.
- **Revolutionary** - For the layman (especially VCs and AI YouTubers), some of what Devin does might seem like magic. But alas, there is nothing about Devin that is magic, special, or out of the ordinary. For those more knowledgeable, every component of Devin is easily replicable (if one desired to replicate it, which, as we will discuss, there are aspects of Devin that are definitely not desirable). In other words, there is no moat. Open-source efforts, whether this repo or another, will do a better job of creating what developers truly want, not what they need to show VCs and Twitter to generate hype and secure funding.
- **Taking Jobs** - If you're worried that Devin is going to take your job as a developer, the best response is to educate yourself. A good starting point is watching [this video](https://www.youtube.com/watch?v=80MPXoRHvK8) from The Primeagean. TLDR; The examples are cherry-picked, the software engineering benchmark still only represents a small fraction of real-world problems, and the company behind Devin is actively hiring entry to medium level developers. Why would they need developers, especially at this level, if they have Devin? **Makes you think...** Furthermore, if AI were to actually do what management wants without the input of developers, it would likely crash the company. **These kinds of tools cannot exist without developers.**

And if you're a layman or AI Hypetuber who is overly impressed by these clearly cherry-picked demos, watch [this video](https://youtu.be/m8VSYcLqaLQ?si=KQYN4yMc2i91JD82&t=887) from Theo to understand just how bad Devin actually is at the things it claims.

## About Devinci

Tools like Devin should possess certain characteristics - the first and most important being:

### "Free and Open Source"

Nobody should be compelled to pay for someone else's prompt engineering, no matter how inventive and revolutionary they think their specific approach to prompt engineering wrapped in everyday tools is, nor how much hype they contribute to the AI Hype Pile™ with taglines like, "The First AI Software Developer" (by the way, in all the demos I have yet to see Devin produce anything that could aptly be called Software - what's up with that?).

The Open Source community is stronger, better-aligned, and highly skilled. Closed source groups like Cognition stand no chance selling tools to developers that should be FREE AND OPEN SOURCE. Let's make that clear once and for all to the people at Cognition and all the other small startups who decide to package everyday dev tools with AI prompts, generate hype, and then sell it. We WILL surpass Cognition, and it won't even be close. For you, the developer, every last feature of Devinci or whatever other Open Source Devin-like repository that gains popularity will be FREE. Furthermore, FREE Open Source models that run locally, along with their Open Source tooling such as Ollama, will only continue to improve. Soon, this same toolset will be available even to developers who cannot afford OpenAI credits, and that should be a primary driving factor in the development of these tools.

### No Re-inventing the Wheel

Developers have tools they prefer to work with. Most of these tools are again, Free and Open Source. They have dedicated teams of passionate developers focused solely on solving ONE problem. Why would you create a subpar internal web UI representation of these same tools when the real ones exist, are FREE, and are infinitely better at solving the problems of a browser, a terminal, and an editor?

Devinci will be built in such a way that it allows you to bring your own preferred tools to the party. Like VS Code? Great. Prefer Vim? Even better (seriously, objectively better, sorry). Kitty's a great terminal, so are iTerm and Alacritty, among others. These tools are dedicated to solving the problem of BEING A TERMINAL. No developer needs or wants your contained web UI "tooling". Whoever at Cognition thought that was a good idea should probably reconsider. Was that Devin's decision? It certainly seems like a decision "the First AI Software Engineer" would make.

### No Hype, Verifiable Results by Benchmarking Real World Development Problems

The AI Hype Pile grows taller by the day. Everyone knows that most benchmarks, like the one being touted by the team at Cognition, the "SWE-Benchmark", are almost entirely useless in assessing whether AI can perform REAL software development tasks at even the level of an entry-level developer. Even on a fairly insignificant benchmark that does not at all represent the job or responsibilities of your average developer, Devin only manages to solve 13% of the problems (cue crying laughing face). But you know what the AI Hype, Get Your Wallet Out VC Daddy Bros say, "this is the first version and the worst it's ever going to be, just imagine in 1 year!"

Devinci will aim to take care of low-hanging fruit problems without creating a $700 crater in your OpenAI monthly bill (unless you prefer to feed the Beast), integrating across your own preferred editor, terminal, browser, etc. Devinci, just like Devin, will be able to:

- Create plans for how to solve given tasks (again, nothing new, many existing open-source tools do this well).
- Figure out potential solutions to problems by searching the web (widely available, open source).
- Edit code with diffs, likely initially powered by the incredible open-source work of [Paul Gauthier and Aider](https://github.com/paul-gauthier/aider) (which, by the way, does the most important job of Devin and is free and open source).
- Check the status of long-running tasks over time and continue tasks to completion with its "heartbeat" functionality ("heartbeat" certainly does not refer to a cron job that prompts the LLM every x minutes for a status update!).
- Read logs and self-correct (more revolutionary Devinci functionality that has been widely available for a year or more).
- Recreate and spawn exponential workers of itself.

### Devinci 1 Will Create the Next Version of Devinci

Just kidding! The AIs that drive all AI dev tools like this are still far too unsophisticated to be able to make real software development decisions that result in a codebase that is clean, follows best practices, and is **Clean-ish Code**, is extensible and maintainable, and that uses the technologies that you want. There is no world where you can tell a tool like Devin or Devinci anytime soon something like "OK, build an enterprise-level web application as a remote module for a MFE setup, with a backend and frontend, secure authentication, that uses oh let's say Angular 14 because that's compatible with my current shell, and this Angular template my teammate found that we've been using, and connect that to our cloud DB, then integrate the module into our existing shell with the new authentication solution, oh and don't forget to make sure all the components that you build for this application fit nicely into our existing component library and...", well, I think you get the point. There is no way that any AI tool right now or even in the near term will be able to navigate real-world development tasks like every developer gets from management or clients on a daily basis. This is true NO MATTER HOW MANY EXAMPLES THEY CHERRY PICK.

You see, we are still years away from an AI development toolset that does what the person prompting it ACTUALLY WANTS, not what they say (which are 98% of the time two totally different things). The following short scenario would be the average non-dev trying to get something actually more useful than a game of Snake done with Devin:

- "Hey Devin, build me a RAG solution so that I can ask questions to documents".
- $50 in credits later...
- Prompter: "I don't know, it's not working right, and I'm not a developer, so I don't have the slightest clue what's actually wrong."
- Devin: "OK, well, let's try $100 more in credits and see if by a stroke of pure luck one of my random changes addresses your issue."

### Conclusions

1. "Devin" is yet another overhyped tool that will probably, most likely be eclipsed by the next release of GPT 4.5 or 5, just like all the other overhyped startups that try to seem like their product is actually more than just prompts wrapped in everyday tools but ultimately fail and go under because THEY HAVE NO MOAT.
2. Free and Open Source is ALWAYS the way to make the most progress, the fastest, in a way that is most helpful to the largest number of developers, and Devinci will be that. Developers WILL NOT PAY YOU for things they can do themselves, and if your idea is to go over developers' heads and replace them with a "Devin", I'd love to see how that works out in the real world.
3. AI is not taking your job anytime soon, not even overhyped tools like "Devin".
4. Watch and Star this repo to stay on top of the development of the World's First Open Source AI Software Developer!!!1!!1!

### Contributing

If you're interested in contributing to this mission and combating the lies and hype of for-profit LLM wrapper tools like "Devin", then please join the discussion in the discussion tab to give your input on the direction of this project.

### Share

Please share and spread the word far and wide about Devinci and help disseminate this important message to the masses. We developers will determine the future of development, not four people trying to impress VCs from their garage who can't even use their own tool or even ACTUAL DEVELOPERS to build a proper and secure website (maybe that's why they need to hire more actual developers?) and whose bot makes PRs so [terrifyingly bad](https://www.reddit.com/r/singularity/comments/1bcyqup/comment/kuj0twu/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) it hurts to look at.
