---
title: "Why AI Chatbots Still Can't Close a Sale — The Hybrid Fix"
date: 2023-06-22
category: "AI Strategy"
---

I've been deep in the weeds on something that sounds simple but turns out to be genuinely hard: getting an AI chatbot to guide a customer toward a purchase decision.

Not just answer questions. Not just be helpful. Actually *walk someone through a process* — step by step — the way a good salesperson would. Ask the right questions, narrow the options, and arrive at a logical conclusion together.

Turns out, GPT-4 is pretty terrible at this.

## The Problem With Goals

Here's what most people don't understand about large language models: they don't have goals. They're incredibly good at generating the next plausible response to whatever you just said. But they're not thinking three moves ahead. They're not trying to get you somewhere.

A traditional decision tree — the kind you'd build in a sales funnel or a diagnostic tool — is stochastic by design. It branches based on your answers. Every path leads somewhere intentional. The system knows where it wants you to end up and works backward from there.

An LLM does the opposite. It works forward from your last message with no real destination in mind. You can tell it in a system prompt "your goal is to help the user choose the right insurance product," and it'll nod along and be generally helpful. But it won't systematically narrow options. It won't remember that three messages ago you already eliminated Option B. It won't drive toward consensus over multiple back-and-forths.

I've tried. I've spent real time on this — language programming, system prompt engineering, giving it example interactions as training sets. So far, no luck getting an LLM to reliably hold a multi-turn goal in its head and execute a branching logic tree through natural conversation.

## Why Prompt Engineering Alone Isn't Enough

The intuitive response is: "Can't you just teach it through prompting? Give it examples?"

I thought so too. And to be fair, you can get SOME goal-directed behavior through careful prompting. But it breaks down fast. The model drifts. It forgets constraints. It gets distracted by whatever the user just said and follows that thread instead of steering back to the decision framework.

The fundamental issue is architectural. These models are next-token predictors. They're brilliant at local coherence — making the next sentence sound right given everything that came before. But maintaining a strategic arc across 10-15 conversational turns? That's a different kind of intelligence, and it's not what transformers were optimized for.

This matters a lot for anyone building customer-facing AI. If you're in fintech, insurance, real estate, any domain where the customer needs to be guided through a structured decision — the raw LLM isn't your answer. Not yet.

## The Hybrid Approach That Actually Works

Here's where I've landed, and I'm reasonably confident this one works: you don't choose between the dumb chatbot and the smart one. You use both.

Take a traditional chat platform like Rasa — one that's built around decision trees and structured flows. It's "dumb" in the sense that it follows predetermined paths. But that's exactly what makes it good at goal-directed conversation. It knows the tree. It knows where each branch leads. It asks the right question at the right time.

Now add a release valve. At each decision point, alongside the multiple-choice options, you offer something like "Other" or "I have a different question." When the user selects that, you hand off to GPT-4 (or whatever LLM you're running). Let the AI handle the freeform, unpredictable, genuinely conversational part — the part where the customer says something you didn't anticipate.

Then — and this is the key — once the AI has addressed that tangent, a function call hands control BACK to the decision tree. The customer re-enters the structured flow and continues progressing toward a conclusion.

It's not elegant. It's a frankenstein. But it solves both problems at once:

- The **structured chatbot** handles goal-directed progression, branching logic, and ensuring the customer actually arrives at a decision
- The **AI layer** handles the messy human stuff — the off-script questions, the "wait, what about..?" moments, the need to feel heard rather than funneled

## Why This Matters Beyond Sales

I think this hybrid pattern is going to show up everywhere in the next year or two. Any domain where you need both structure AND flexibility — medical intake forms, legal consultations, financial planning, onboarding flows — the answer isn't "replace the old system with AI." It's "layer AI intelligence onto structured processes."

The people building pure-AI chatbots and expecting them to replace entire sales teams are going to be disappointed. The people wiring AI into their existing decision frameworks are going to win.

## The Takeaway

If you're building customer-facing AI right now, stop trying to make the LLM do everything. It's not a salesperson. It's not a closer. It's an incredibly powerful conversational engine with no sense of direction.

Pair it with something that HAS direction — a decision tree, a structured flow, a traditional chatbot framework — and let each component do what it's actually good at. The LLM handles the unpredictable. The framework handles the intentional. Together, they're pretty powerful.

We're still early on this. I haven't seen anyone ship a really polished version of this hybrid approach yet. But I'm convinced it's the right architecture for goal-directed conversational AI — at least until the models themselves get better at holding long-term objectives across multi-turn conversations.

And honestly? That might be a while.
