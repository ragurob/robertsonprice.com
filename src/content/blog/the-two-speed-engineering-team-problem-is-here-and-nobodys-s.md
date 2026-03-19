---
title: "The Two-Speed Engineering Team Problem Is Here"
date: 2026-02-11
category: "AI Strategy"
---

I've been watching something play out across pretty much every engineering team I'm connected to, and it's becoming impossible to ignore.

If you've got a team where some developers are using AI coding tools — Claude Code, Copilot, Cursor, whatever — and others aren't, you already know what I'm talking about. You're trying to run a relay race where some runners are lapping the track ten times a second and others are moving at a walking pace. And somehow, everyone's supposed to hand off the baton cleanly.

It doesn't work. And right now, nobody has a GREAT answer for it.

## The Velocity Gap Is Real

This isn't a theoretical problem. It's happening TODAY, in teams of every size. The developers who've embraced AI-assisted coding — the "vibe coders," as some are calling them — are shipping at a pace that makes traditional development timelines look absurd. Features that used to take a sprint are getting knocked out in an afternoon.

But here's the thing. Speed without coordination is just chaos with better commit messages.

The traditional coders on these teams aren't slow because they're bad. They're operating at the speed that software engineering has always operated at — thoughtful, methodical, careful. That used to be a virtue. Now it creates a bottleneck that frustrates everyone on both sides of the divide.

I've seen teams where one developer is spinning up agent workflows, launching parallel coding sessions, burning through tokens like there's no tomorrow — and the person sitting next to them is still manually writing unit tests. Neither one is wrong. But the team dynamics become pretty brutal pretty fast.

## The Management Nightmare

Here's where it gets really interesting. How do you run sprint planning when half your team can do 10x the work of the other half? How do you estimate story points? How do you do code review when one person's PR was largely written by an AI agent?

Traditional engineering management frameworks weren't built for this. Agile assumes roughly comparable velocity across team members. When that assumption breaks, everything downstream breaks with it.

I'm hearing the same story everywhere: teams are developing their own internal solutions, their own workflows, their own rules of engagement. Some are mandating that everyone use AI tools. Some are creating separate tracks — AI-assisted features and traditionally-developed features. Some are just.. pretending it's not happening.

None of these approaches feel like THE answer yet.

## The Safety Question Nobody Wants to Talk About

There's another dimension here that makes this even more complicated. These AI coding agents can theoretically do ANYTHING on your machine. They can run shell commands, modify files, delete things. The power that makes them fast is the same power that makes them dangerous.

I keep coming back to the fundamentals: you should really review every command that an AI agent wants to run. Running things in VMs, setting up deny lists, being thoughtful about permissions — this stuff matters. But it also slows things down, which kind of defeats the purpose.

And then there's the token economics. Agent teams — where you've got multiple AI agents coordinating on a problem — use an absolutely insane amount of tokens. The cost can spiral fast. That developer who's "10x more productive" might also be 10x more expensive in API costs. Is the math still worth it? Usually yes, but it's not the free lunch some people think it is.

## What I Think Needs to Happen

I've been pretty vocal about AI coding tools being transformative. I haven't changed my mind on that. But the team dynamics problem is the next big thing the industry needs to solve, and I don't think the answer is just "make everyone use AI."

What I'd love to see:

**Better team-level tooling.** Individual AI coding assistants are great. But we need frameworks that help TEAMS coordinate when members are working at wildly different speeds. Something that manages the handoffs, the reviews, the integration points.

**Honest conversations about roles.** If AI can write boilerplate code in seconds, maybe some developers should be spending more time on architecture, security review, and system design. The value of a senior engineer was never really in how fast they could type.

**Realistic token budgets.** Teams need to understand the actual cost of AI-assisted development and plan for it. Going all-in on agent workflows and then running out of budget mid-sprint is worse than not using them at all.

**Safety-first defaults.** As these tools get more powerful, the defaults need to get more conservative, not less. Sandboxing, permission models, audit trails — boring stuff that becomes critical when an AI agent has root access to your codebase.

## The Bottom Line

We're in this awkward middle phase where AI coding tools are clearly powerful enough to change how software gets built, but the team structures, management practices, and safety frameworks haven't caught up yet. Every team with a mix of AI-adopters and traditional developers is feeling this pain right now.

Something will emerge to solve this. Maybe it's a new category of team coordination tools. Maybe it's a shift in how we think about engineering roles entirely. I genuinely hope a solid solution sticks soon — because the current state of just winging it isn't sustainable.

The teams that figure this out first are going to have a MASSIVE advantage. The ones that pretend the two-speed problem doesn't exist are going to tear themselves apart.

Pretty high stakes for something most companies aren't even formally acknowledging yet.
