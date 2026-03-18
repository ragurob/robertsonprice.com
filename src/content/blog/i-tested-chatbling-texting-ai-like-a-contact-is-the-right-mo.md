---
title: "I Tested ChatBling — Texting AI Like a Contact Is the Right Move"
date: 2023-04-10
---

There's a service called ChatBling that puts an AI assistant in your phone contacts. No app download. No browser tab. No login screen. You add a number, you start texting, and it talks back.

I haven't done a full head-to-head against GPT-4 yet. But I've poked at it enough to have a clear read on what it's doing right, what I'm skeptical about, and why the pattern matters more than the product.

## What I Tried

ChatBling routes your texts through an AI backend and responds like any other contact in your phone. The pitch is zero friction — you're not installing anything, you're not opening a new tab, you're just... texting.

I ran some basic tasks through it. Asked it to help draft a message. Threw a recipe question at it. The mechanics work. The response comes back in a text bubble. Your parents can use this. The person who still can't clear their browser cache can use this. That's the point.

## What Actually Worked

The interface is the insight here, and it's a good one.

I've been thinking a lot about WHERE AI actually lands with everyday people — not early adopters, not developers, but the people who will eventually make this technology a real part of daily life. The answer isn't a slick new app. It's the tool they already have open.

Everyone knows how to send a text. That's not a small thing. By meeting people inside their messaging apps, ChatBling removes basically every barrier to entry. No onboarding. No learning curve. Just a conversation.

I wrote a few weeks back about a WordPress chatbot plugin that took the same approach — go to the user instead of asking the user to come to you. ChatBling pushes that instinct further. It's not embedded in a website, it's embedded in your PHONE. That's about as frictionless as it gets right now.

## What Didn't

Here's where I start asking questions.

ChatBling implies an OpenAI connection in its marketing. Maybe. But I'm skeptical that's the whole story — especially at scale. The OpenAI API isn't architected for managing thousands of persistent, individual conversation threads across a massive user base. Each conversation needs context. It needs memory. It needs to pick back up when you text again two hours later. That's not trivial infrastructure, and routing every message through GPT-4 at standard API pricing would make the economics ugly fast.

My working assumption: they're running something cheaper under the hood. A fine-tuned open-source model, self-hosted. Something like a LLaMA variant. That would explain the cost structure and give them more control over conversation state management.

That's not necessarily a problem — but it's UNVERIFIED, and that matters. If the model is substantially weaker than what they're implying, the experience degrades in exactly the cases where you need it most. Complex questions, nuanced requests, anything that requires more than a simple lookup.

The other open question is conversation persistence. If each message is essentially stateless — if the AI doesn't actually remember what you said two texts ago — then the "it's like texting a friend" framing falls apart. A friend remembers context. A service that forgets mid-conversation isn't a contact, it's a hotline.

I want receipts on both of these before I'd recommend this to someone who'd actually rely on it.

## Who Should Care

If you're building AI products, pay attention to this — not necessarily to ChatBling specifically, but to what it's attempting.

The interface layer is where the real competition is happening right now. The models themselves are getting commoditized fast. Stanford cloned ChatGPT for $600 in compute. The gap between frontier models and open-source alternatives is closing. What's NOT commoditized yet is the distribution layer — how you get this technology into someone's hands in a way that feels natural enough that they actually use it.

ChatBling's answer is: put it in their contacts. That's a legitimate answer.

If you're thinking about building something, think about WHERE your users already are. What do they already open ten times a day? What interface do they already trust? THAT's where AI needs to live.

## What This Signals

The browser-based chatbot is a transitional form factor. I'd put money on that.

What I expect to see — and what ChatBling is an early signal of — is AI getting absorbed into the channels people already use. iMessage. WhatsApp. SMS. Maybe email auto-responders that actually understand what you're asking instead of just firing back a template.

The pattern is: stop asking people to go somewhere new. Bring the capability to them. ChatGPT's initial explosion happened for the same reason — it didn't ask you to learn anything, it just worked in a text box. ChatBling is taking that instinct one step further and making the text box the one already on your phone.

The interface wars for AI are just getting started. The teams that figure out distribution — not capability, DISTRIBUTION — are going to win a disproportionate amount of the next few years.

Keep an eye on this pattern. It's moving faster than most people realize.
