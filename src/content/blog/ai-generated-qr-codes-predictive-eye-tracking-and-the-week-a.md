---
title: "AI-Generated QR Codes, Predictive Eye Tracking, and the Week AI Got Weird"
date: 2023-06-06
category: "AI Tools & Products"
---

I've been watching AI developments pretty closely for a while now, and this week might be one of the strangest in terms of sheer range. We've got QR codes that look like Renaissance paintings, a startup claiming a 5 million token context window, and — buried in a thread that deserves way more attention — evidence that AI can predict you're going to click something *before you actually do it* by reading your pupils.

Let's unpack all of it.

## Stable Diffusion + ControlNet = QR Codes That Shouldn't Exist

If you haven't seen the AI-generated QR code art making the rounds this week, stop what you're doing and go look. These aren't QR codes with a pretty background slapped behind them. These are full, detailed images — landscapes, portraits, architectural scenes — that *also happen to be functional QR codes*.

The technique works like this: you generate a standard QR code first, then submit it into Stable Diffusion running ControlNet as a control image. The model then generates an image output that stays true to the original QR code data while looking like a piece of art. Prompts did all the heavy lifting here — no manual Photoshop work, no pixel-by-pixel adjustment. Just the right combination of a control signal and creative text prompts.

Now, the obvious question: could you go the other direction? Take an existing piece of artwork and a QR code and ask it to merge the two?

The answer is.. sort of. It depends on the art, but the core constraint is that QR code data is PRECISE. The positioning squares, the error correction, the actual encoded data — all of that has to remain intact and scannable. So the artwork has to bend to the QR code rather than the other way around. The QR code is the boss. The art is just allowed to play in whatever space is left.

That's a genuinely important distinction, because it tells you something about where we are with controllable generation. ControlNet isn't just "make it look nice." It's enforcing hard structural constraints while letting the generative model handle aesthetics. That's a much more interesting capability than pure text-to-image, and I think it's going to matter a LOT for commercial applications — product design, packaging, advertising, anything where you need creative output that also meets precise functional requirements.

## 5 Million Tokens — And the Catch Nobody Wants to Talk About

For those keeping track, this week brought the first announcement of a 5 million token context LLM, from Magic AI Labs. Five million tokens. That's roughly the equivalent of feeding an AI ten full novels in a single prompt.

Sounds incredible. And it might be. But there's no such thing as a free lunch.

We've already seen this dynamic play out. Anthropic's Claude with its 100k token context is genuinely useful — I've written about the implications of large context windows before — but it's measurably less effective at reasoning and coding compared to GPT-4. There's a tradeoff between how much information you can hold in context and how well you can actually THINK about that information.

Magic acknowledges a similar set of issues with their system. And that's actually the honest, respectable thing to do. The race to bigger context windows is exciting, but raw token count isn't the whole story. What matters is whether the model can actually *use* all that context effectively — retrieve the right information, reason about it, connect it to the query. A model that can hold 5 million tokens but only reliably reasons about the last 50,000 is a very different product than one that genuinely comprehends the whole window.

I'm glad we're getting so many different approaches and architectures to learn from. Competition in this space is exactly what we need. But I'd encourage everyone to watch for the benchmarks on reasoning quality at scale, not just the headline context number.

## The AI That Knows You'll Click Before You Do

This one is the sleeper of the week, and honestly it might be the most important.

Some of the AI work being done around eye tracking and predictive interaction is genuinely stunning. One of the most compelling results I've come across involves predicting that a user is going to click on something *before they actually do it*.

Here's why that works: your pupil reacts before you click, in part because you EXPECT something will happen after you click. Your brain is already anticipating the outcome — a page loading, a button responding, a menu opening — and that anticipation shows up in measurable changes to your pupil dilation. An AI model trained on that signal can effectively read your intent before you execute it.

Think about what that means for interface design. If a system knows what you're about to interact with a few hundred milliseconds before you do, it can pre-load content, adjust layouts, or prioritize rendering. Latency effectively disappears — not because the computer got faster, but because it started earlier.

This is the kind of AI application that doesn't get the flashy headlines but fundamentally changes how humans interact with technology. It's not generating art or writing code. It's reading the micro-signals of human intention and acting on them. That's a DIFFERENT kind of intelligence than what we talk about with large language models, and I think it deserves way more attention than it's getting.

## The Takeaway

What strikes me about this particular week is the sheer breadth of what's happening simultaneously. Generative models are learning to work within hard structural constraints. Context windows are racing toward absurd sizes. And meanwhile, a completely different branch of AI is learning to read human intention from pupil dilation.

We're not watching one revolution. We're watching about five of them happening in parallel, and they're all going to collide eventually. The QR code trick is cool today. Combine it with predictive intent and massive context, and you're looking at systems that know what you want, generate it within precise constraints, and start working before you even ask.

Pretty powerful. And a bit wild.
