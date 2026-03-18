---
title: "The Crypto Market Just Crashed 30% — Here's What I Did and Learned"
date: 2021-05-19
---

If you've been anywhere near a screen today, you already know. Bitcoin dropped off a cliff, dragging every altcoin with it, and for about two hours this afternoon the entire crypto market felt like it was on fire.

I've written before about how I position my bots for corrections. But today wasn't a correction — today was a full-blown crash, a recovery, and then more chaos, all compressed into a single trading session. And honestly? It was one of the most intense afternoons I've had since I started running automated strategies.

## What Actually Happened

BTC broke below $40K. I remember not long ago being pretty confident it would never go below that level again — not after Tesla's buy-in earlier this year. Well, what Elon maketh, he can taketh away too. The man tweeted, the market panicked, and suddenly we're watching billions evaporate in real time.

The selling started in Asia toward the end of their trading day, and by the time European and US markets were fully awake, it was a cascade. Exchanges started buckling. Binance slowed to a crawl. Coinbase APIs started throwing errors. CoinMarketCap itself went down for a stretch. When the infrastructure that TRACKS the market can't keep up, you know it's serious.

## The Bot Problem Nobody Talks About

Here's the thing about running automated trading bots during a crash — they're built for normal volatility. Mean reversion strategies, the kind I've been thinking about for months, assume the price will bounce back to roughly where it started. That's great when you're catching 2-3% dips throughout the day.

But when BTC drops 30% and your altcoins are down 35%? Your bots are buying the dip, buying the dip, buying the dip — and the dip keeps dipping. The "investment change" number in your dashboard starts looking pretty ugly, and as I've covered before, that number can be misleading even in GOOD times.

One thing that surprised me: the bots I run against BNB pairs actually held up well. When everything drops together, the ratios between coins stay relatively in range — which means the bots keep finding profitable trades even while the HODL side of the portfolio is bleeding. Worth keeping in mind if you're building out your strategy.

I had moments today where I had to make a call: do I let the bots keep running and trust the thesis, or do I intervene manually? I ended up doing a bit of both. Sold a chunk near what felt like a local bottom — pure gut — then bought back about 80% of it once things started stabilizing. Not my finest hour of disciplined automated trading, but when exchanges are literally dying under the load, "trust the algorithm" feels a bit naive.

## The USDT Arbitrage Nobody's Talking About

One thing I noticed in the chaos — if you're comfortable holding USDT (and I'm not saying you should be, that's a whole separate conversation) — GBP was trading against the dollar at roughly $1.50 per pound through Tether pairs. The actual forex rate is nowhere near that. You could theoretically arb back and forth between GBP and USD stablecoin pairs and pocket a pretty decent gain just waiting for the spread to normalize.

BUSD was even better for this. Not a strategy I'd write a bot for, but if you were sitting there watching the carnage and wanted something productive to do with your stablecoins, the opportunity was right there.

## The Bigger Picture: Is This the Fed?

The Federal Reserve announced today they're looking to tamp down on inflation. And I think this is MUCH bigger than Elon's tweets.

I wouldn't be at all surprised if parts of the US government wanted to quash crypto's momentum right now. Think about it — they were very quickly watching cryptocurrency threaten the global reserve status of the US dollar. I actually can't imagine a more costly loss of power than watching crypto knock the dollar out of its settlement currency position practically overnight. The regulatory signals, the tax talk, the infrastructure concerns — it all points in the same direction.

And there's the Tesla angle too. There are people out there who I think are actively trying to push BTC below Tesla's entry price of roughly $34.5K. If it drops below that, Tesla has to show an impairment on their quarterly accounts. That wouldn't just be bad for their balance sheet — it would hammer TSLA stock itself. So the pressure to sell before that threshold becomes a self-fulfilling prophecy.

Keep in mind though — the market is STILL up a ridiculous 290% for the year. Perspective matters.

## A Practical Trick: The Rebalancer as an Eject Button

Here's something I've been using that works brilliantly for situations like today. Create a Portfolio Rebalancer bot that mimics your current holdings. Then copy that same bot, add USDT as a coin, and slide your USDT allocation to 50% or 100%. Run it live and it sells you out of your positions into USDT. When you want to jump back in, run the first bot and it restores your positions automatically.

It's the equivalent of having an "eject" button and a "re-enter" button sitting on your desk. One click out. One click back in. Why NOT use it?

## What I'm Doing Now

I inched about 25% back into my portfolio this evening. Most of the altcoins I invest in are still down 30-35% from yesterday, and historically they don't recover until the majors stabilize first. So there's potentially a nice little rebound trade there if you're patient.

I think the worst of it is probably behind us — for today, at least. The people who wanted out are out. The people who bought the absolute bottom made an incredible trade and should take those winnings home and buy themselves a nice steak. The rest of us are somewhere in the middle, trying to figure out whether to restart our bots or wait for calmer waters.

I'm keeping most of my bots off overnight. Running a couple of GBP pairs that have been performing well — ETH/GBP and XRP/GBP were both solid even in the chaos. But I expect choppy waters ahead, and I'd rather miss a few small automated gains than have my bots buying into another leg down at 3 AM.

## The Takeaway

Days like today are why you need a plan BEFORE the crash. If you're manually panic-selling at the bottom and panic-buying on the way back up, you're doing exactly what the bots are supposed to prevent. But even bots have limits when exchanges can't handle the volume and APIs go dark.

My move: small positions back in, bots mostly paused, and a martini. Sometimes that's the best strategy there is.
