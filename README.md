# Hey, I'm Mihir

Product Manager at Coding Ninjas, where I own Growth and the AI product portfolio. Before this: BITS Pilani, then a year building deep reinforcement learning systems at Samsung R&D.

Most of what I ship at work lives behind a login. The case study below is the closest thing to watching me work, including recordings of the product doing its job. Under it are things I built for myself, where the source is open because in those the code *is* the argument.

---

## The work

### → [AI Voice Agent: a production system that calls, counsels and closes](https://ai-voice-agent-six-chi.vercel.app)

A voice agent that calls every new lead within minutes, counsels them on a programme, opens the price the way the best human counsellors do, and hands the ready ones to a person with the full context. About 8,000 calls a day.

I built it 0→1 as the product owner across three generations of the assistant: the bet, the prompts, the extraction pipeline, the two-layer eval system, the A/B design and the analytics. The case study walks each generation, the stack around the call, eight product decisions and what each one cost, and the results.

**You can listen to real calls on it.** Short clips in Hinglish, an objection handled, a hard question answered, a close. Each one is reviewed for personal information and carries a line of setup so you know what you're hearing.

---

## Things I've built

### [Learning Compiler](https://learning-compiler.vercel.app): learn the thing, not the video · [source](https://github.com/bisati/learning-compiler)

YouTube already has the explanation you need. It is buried in minute 34 of an hour-long video you have not found yet. Say what you want to understand and how long you have, and this returns the exact minutes worth watching, in the order that teaches them, each timestamped so you land on the part that answers the question. Two hours on "how RAG works" comes back as 26 segments from 25 creators filling 119 of your 120 minutes.

It also tells you what it could not cover: when part of a topic has nothing good enough behind it, that part is named on the page and struck through rather than quietly padded with something loosely related.

Built with Node, no framework and no build step, on an index that ships inside the deployment rather than sitting behind a database. Nothing is rehosted or re-uploaded; every link opens the creator's own video at the right second.

---

### [Kix](https://kix-psi.vercel.app): fair football teams in thirty seconds · [source](https://github.com/bisati/kix)

I spent two years splitting my Sunday football group by hand, then by asking a language model. Kix is that prompt turned into a deterministic engine: a priority ladder of twenty-four rules, a search that climbs it, and a verifier that grades the result without trusting the thing that produced it. The same squad always produces the same teams, which is what actually ends the arguments.

Converting the prompt was the interesting part. It surfaced a rule that had been sitting in it for months and could never be satisfied. The model had been quietly picking a different interpretation every Sunday, and writing a confident team sheet either way.

Built with Next.js and TypeScript. Rosters never leave your browser.

[How the engine works](https://github.com/bisati/kix/blob/main/docs/engine.md) · [How the prompt became code](https://github.com/bisati/kix/blob/main/docs/from-prompt-to-ladder.md)

---

`TypeScript / Next.js` · `Python` · `SQL` · `Claude Code` · `Gemini` · `Vercel`

[LinkedIn](https://www.linkedin.com/in/mihir-shende-74ab1a163/)
