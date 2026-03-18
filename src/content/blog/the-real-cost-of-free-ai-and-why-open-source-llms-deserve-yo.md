---
title: "The Real Cost of \"Free\" AI — And Why Open Source LLMs Deserve Your Attention"
date: 2023-10-27
---

I've been thinking about something that's bugging me, and I think it's worth saying out loud: if you're still using ChatGPT without a paid subscription, you're getting third-tier AI results and you might not even realize it.

That's not a knock on OpenAI — they've built something genuinely impressive. But the free tier is running on older, smaller models while paying customers get GPT-4. The gap between those two experiences isn't subtle. It's the difference between asking a sharp analyst and asking an intern who read the summary. If you're making business decisions or building products based on free-tier output, you're working with a handicap.

## The Open Source LLM Wave Is Real

Here's what's more interesting to me right now: the open source large language model space has gotten REALLY good. Models like LLaMA 2 70B are genuinely competitive with the commercial offerings for a lot of use cases. Not all of them — but enough that it's worth paying attention.

The question I keep coming back to is practical: how do you actually get API access to these top-tier open source models without spinning up your own infrastructure?

I've been looking at a few options and there are some pretty solid paths emerging. Fireworks AI has a marketplace where you can hit various open source models on a pay-as-you-go basis. Mystic.ai offers direct access to models like LLaMA 2 70B. Modal gives you lambda-style GPU access where you pay by the second for inference on whatever model you want. These aren't theoretical — they're live, working services.

## The Economics Get Interesting Fast

Here's where my brain goes: could you build a small, sustainable business just by provisioning third-party API access to the latest and greatest open source models? I think the answer might be yes.

The math works like this. You provision GPU resources in the cloud — a box running LLaMA 70B or whatever the current best-in-class open source model is. It won't be cheap to run, but here's the thing: you don't have to carry that cost alone. Split it across a few startups. Maybe a small collective of builders who all need access to high-quality AI but can't individually justify the infrastructure spend.

You could run something like GPT-3.5 for the grunt work — the bulk processing, the simple classification tasks, the stuff where "good enough" is genuinely good enough. Then you route the hard problems, the ones that need real reasoning depth, to the 70B open source models. That tiered approach keeps costs manageable while keeping output quality high.

I keep using this phrase in my head: raise the tide. If a small group of companies can collectively access better AI infrastructure than any of them could afford individually, everyone's products get better. Everyone's costs come down. That's not charity — that's smart resource allocation.

## Why This Matters More Than People Think

I wrote earlier this year about how AI is going to reshape the labor market and what happens when everyone has access to "average" capability. This open source LLM question is directly connected to that thesis. Right now, there's a real stratification happening:

**Tier 1:** Companies with massive budgets running GPT-4 or fine-tuned models on their own infrastructure.

**Tier 2:** Paid subscribers getting solid results from commercial APIs.

**Tier 3:** Everyone else, using free tiers and getting noticeably worse output.

Open source models are the thing that could flatten this hierarchy. If a 70B parameter open source model can deliver 85-90% of GPT-4's quality at a fraction of the cost — and I think we're pretty close to that on many tasks — then the competitive moat for the big AI companies gets a lot shallower.

## The Practical Play

If I'm being honest about what I'd actually do here, it's this: find four or five companies in your network that are all paying for AI API access. Pool some of that spend into shared GPU infrastructure running the best open source models. Use the commercial APIs as a fallback for the stuff open source can't handle yet.

It's not glamorous. It's not a venture-scale idea. But it might be a "beer money" business that also happens to give your group better AI access than you'd have individually. And in this market, access to better tools is a genuine competitive advantage.

The window for this is right now. Open source models are good enough to be useful but most people haven't figured out the access and deployment piece yet. That gap between capability and accessibility is where the opportunity sits.

## What I'd Watch

Keep an eye on the open source model releases over the next few months. The pace of improvement has been staggering. What's a 70B parameter model today could be a 7B model delivering the same quality by mid-2024, and then the economics change completely — you could run that on a laptop.

But right now, today, if you're building anything that relies on AI and you're not at least exploring open source LLM access alongside your OpenAI subscription.. you're leaving capability and cost savings on the table.

The future of AI isn't one company's API. It's an ecosystem. And the people who figure out how to navigate that ecosystem early are going to have a pretty significant head start.
