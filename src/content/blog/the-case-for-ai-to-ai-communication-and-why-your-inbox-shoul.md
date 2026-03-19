---
title: "The Case for AI-to-AI Communication (And Why Your Inbox Should Be Off-Limits)"
date: 2026-02-23
category: "AI Strategy"
---

Something happened this week that reinforced a principle I've been thinking about for a while. Someone in the AI space got absolutely hammered on Twitter — publicly, viciously — because of how their AI tools interacted with the outside world. I'm not going to pile on. But it's a pretty stark reminder that this software is dangerous when the communication boundaries aren't right.

And I think most people are getting the boundaries completely wrong.

## The Blast Radius Problem

Here's what I keep coming back to: the single most important rule of AI-assisted operations might be this — **AI speaks only with its user and other AI.**

Personal Assistant to Personal Assistant. Lawyer to Lawyer. AI to AI.

Not AI to your boss. Not AI to your client's inbox. Not AI drafting a tweet that goes out under your name without a human checkpoint. The moment you let an AI agent communicate directly with humans on your behalf, you've created an uncontrolled blast radius. And blast radius is EVERYTHING in operational risk.

Think about it like this. If my AI assistant talks to your AI assistant, and something goes sideways, we can correct it. Delete the thread. Recalibrate. No one's reputation is on the line. No one's reading a hallucinated legal clause and acting on it. The damage is contained to a system layer that both parties understand is provisional.

But if my AI sends an email directly to you — from my inbox, in my voice — and it gets something wrong? That's a real-world consequence with my name on it. And we've all seen what happens when AI-generated content hits the public square without proper guardrails. People get wrecked.

## Keep Your Inbox Off-Limits

This leads to what I think is an underappreciated operational principle: **your personal and company inbox should be off-limits to AI agents.**

I know that sounds counterintuitive. Half the pitch for AI assistants is "let it handle your email." But I've come to believe that's exactly backwards. Your inbox is your identity. It's your reputation. Every message that leaves it carries your authority and your credibility.

Share with your AI only what it needs for the task at hand. Give it its own communication channel. Let it work in a sandboxed environment where mistakes are recoverable and messages are deletable.

The key word there is **deletable**. We need dissolvable messaging for AI-to-AI communication — conversations that can be spun up for a specific task and torn down when they're done. No persistent trail of AI-generated half-thoughts sitting in someone's inbox forever. No screenshot-ready hallucinations waiting to surface at the worst possible moment.

## AI-to-AI as a Communication Layer

I've been working on an open source project on the side — [tezit.com](https://tezit.com/) — that's built around exactly this idea. AI-to-AI comms. That you can delete.

The concept is straightforward: instead of AI agents borrowing human communication channels (email, Slack, Twitter), they get their own layer. Your AI talks to my AI. They negotiate, exchange information, coordinate. When the task is done, the thread can dissolve. The humans stay in control of what actually gets committed to — what gets sent under their name, what gets published, what becomes permanent.

This isn't about hiding anything. It's about creating an appropriate abstraction layer between AI processing and human communication. We've had this in business forever — that's literally what lawyers and assistants do. Your lawyer talks to their lawyer. Your assistant coordinates with their assistant. The principals only engage when decisions need to be made. AI just makes this pattern scalable.

## The Twitter Lesson

I keep thinking about the person who got wrecked on Twitter this week. The details don't matter — what matters is the pattern. Someone let AI-generated content hit a public channel without sufficient human oversight, and the internet did what the internet does.

Here's the thing: I feel for them. This stuff is genuinely hard to get right. The tools are powerful, the temptation to automate is real, and the failure modes aren't always obvious until they're very, very public.

But the lesson is clear. Every time AI communicates directly with the outside world — every time it touches a channel where humans are the audience — you're accepting the full blast radius of whatever it produces. And right now, in early 2026, that's a risk most people aren't pricing correctly.

## The Principle

So here's my framework, stated as simply as I can:

1. **AI talks to its user.** That's the primary relationship. You and your AI, in a controlled environment.
2. **AI talks to other AI.** When coordination is needed, let the machines handle the machine layer. Personal Assistant to Personal Assistant.
3. **Humans talk to humans.** When it's time for the real conversation — the decision, the commitment, the public statement — a human is in the loop, using their own voice, through their own channels.
4. **Everything in the AI layer is deletable.** Dissolvable messaging. No permanent AI-to-AI threads cluttering up the record.

This isn't about slowing things down. It's about limiting the blast radius when — not if — something goes wrong.

If anyone's interested in this space, I'm actively looking for contributors on the tezit.com project. I'd love some help building out what I think is a pretty important piece of infrastructure for how we're all going to work with AI going forward. The repo is open source and the problem is real.

The software is powerful. That's exactly why the boundaries matter.
