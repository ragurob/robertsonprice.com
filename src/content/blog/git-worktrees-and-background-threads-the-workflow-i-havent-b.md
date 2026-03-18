---
title: "Git Worktrees and Background Threads: The Workflow I Haven't Built Yet"
date: 2026-02-06
---

I've been paying closer attention to how AI coding tools are evolving their workflow patterns, and there's one concept that keeps coming up that I haven't properly integrated into my own setup: git worktrees.

## The Problem With Linear Workflows

Here's the thing about how most of us work with code — even those of us using AI assistants pretty heavily. We tend to work in a single thread. One task, one branch, one context. You're deep into refactoring an API endpoint, and then something urgent comes in — a bug in production, a quick feature request, a dependency that needs updating. You stash your work, switch branches, lose your mental context, handle the interruption, then try to remember where you were.

It's inefficient. I've known this for a while. And the tooling to fix it has technically existed for years.

## What Git Worktrees Actually Do

For anyone not familiar, git worktrees let you check out multiple branches of the same repository simultaneously in different directories. Instead of stashing and switching, you just.. have both branches open. Each one is a fully functional working copy tied to the same repo.

I've known about worktrees conceptually for a while, but I'll be honest — I haven't figured out how to really leverage them in my daily workflow. That's a gap I need to close. The concept is straightforward, but building the muscle memory and the right prompt patterns to make them seamless? That's the part that takes deliberate effort.

## Background Tasks Change Everything

What's gotten me thinking about this again is how the newer AI coding tools are starting to treat parallel work as a FIRST-CLASS concept. The pattern I'm seeing is essentially this: instead of one conversation, one task, you spin up multiple background threads — each one working independently on a separate piece of work, each managed in its own worktree.

Think about what that means practically. You could have one thread refactoring your database schema, another writing tests for a new feature, and a third fixing a CSS bug — all running simultaneously, all isolated from each other, all mergeable independently when they're done.

That's not just a convenience improvement. That's a fundamentally different way of working. It's the difference between a single-threaded processor and a multi-core one.

## Why I Haven't Made the Jump Yet

I think there are two reasons most developers — myself included — haven't fully adopted worktree-based parallel workflows:

**First, the setup friction.** Creating a worktree, configuring your environment in it, making sure your tooling recognizes it, then cleaning it up afterward — it's not hard, but it's just enough friction to keep you in the old pattern. What I probably need is a solid prompt or script that handles all the scaffolding automatically. Set up the worktree, configure the environment, point the AI at the right context, and let it run.

**Second, the mental model shift.** We're used to thinking about our work as sequential. Do this, then that, then the other thing. Thinking in parallel — deciding which tasks are independent enough to run concurrently, managing the merge strategy, reviewing multiple streams of output — that requires a different kind of project management instinct.

## The Leverage Is Real Though

When I think about where AI-assisted development is heading, parallel background work is pretty clearly the direction. The bottleneck in AI coding has never really been the speed of generation — it's been the context switching and the serial nature of the interaction. You ask for something, you wait, you review, you ask for the next thing.

Background threads with worktree isolation break that pattern entirely. You're not waiting. You're dispatching work and reviewing results. That's a MUCH higher-leverage way to operate.

And the isolation that worktrees provide is what makes it safe. Each thread can't accidentally stomp on another thread's changes. When you're ready, you merge deliberately. It's parallel development with guardrails built in.

## What I'm Going to Do About It

I need to just sit down and build this into my workflow properly. Probably a prompt template that:

1. Creates a worktree for the task
2. Sets up the right context and constraints
3. Runs the work in the background
4. Notifies me when it's ready for review

That's not complicated. It's just the kind of thing you keep putting off because your current workflow is "good enough." But good enough is leaving a LOT of throughput on the table.

If you're using AI coding tools and you haven't explored worktrees yet, I'd encourage you to look into them. The combination of parallel AI threads and isolated working directories is — I think — going to become the standard way serious builders operate pretty soon. Better to build the habit now than scramble to catch up later.

I'll report back once I've got a setup I'm happy with. Pretty sure this is one of those things where, once you make the switch, you can't imagine going back.
