---
title: "Coinbase IPO Day, a Flash Crash, and Why Your Bot's Numbers Might Be Lying"
date: 2021-04-14
---

Today's a big day for crypto. Coinbase is going public, and I've been watching the market react in real time. But instead of writing about the IPO itself — every crypto blog on the planet is doing that — I want to talk about what's actually happening in the market around it, and a painful lesson I've learned about trusting the wrong number on your trading dashboard.

## The Flash Crash That Wasn't

Right around midday, the entire market just.. dropped. BTC, ETH, XRP — everything fell off a cliff at more or less the same time, with the crash echoing out from the majors through the altcoins seconds later.

If you've been in crypto for any length of time, you know this pattern. It happens roughly once a week. Every single coin drops like a rock simultaneously, it looks absolutely terrifying, and then — more often than not — it bounces right back. These flash crashes are one of the most confounding and ultimately lucrative features of the crypto market.

What was interesting about today's crash is how little it actually dropped. The support was STRONG. I think what's happening is that enough traders have set limit buy orders at key levels that the selling pressure gets absorbed almost instantly. That's a healthy sign. It tells me there's real demand underneath these prices — people are ready and waiting to buy the dip.

This is exactly the kind of environment where automated trading shines. If your bots are running and properly configured, they're buying those dips before you even notice the price moved. I've written before about mean reversion strategies and this is a textbook example. The crash happens, the bot buys, the price recovers, the bot sells. Rinse, repeat.

## Are People Selling Crypto to Buy Coinbase Stock?

Here's a thought that's been bouncing around in my head today. Is some of this selling pressure coming from people liquidating crypto positions to free up cash for the Coinbase IPO?

It sounds counterintuitive — selling crypto to buy a crypto company — but it makes sense if you think about it. Big IPO days pull capital. Traders need cash to participate, and if your portfolio is 90% crypto, where's that cash coming from? You sell some coins, buy the stock, and plan to rotate back later.

I think the actual impact is pretty tame, honestly. But it's worth noting as a dynamic. On days with major IPOs, capital flows get weird.

## The Number on Your Dashboard That's Wrong

Now here's the thing that's actually cost me money, and I want to save you from the same mistake.

If you're running trading bots, you're probably looking at two key metrics: **Bot Profit** and **Investment Change**. They sound similar. They are NOT the same thing. And on at least one major platform, the Investment Change number is flat-out incorrect on their older bot architecture.

Let me break it down simply:

**Bot Profit** is straightforward — it's the profit in your quote currency from executed sell limit orders. Money that's been taken out of the trade and added to your available balance. Real, realized profit. You can trust this number.

**Investment Change** is more complex. It factors in your base currency sitting in open orders at current market price, plus your quote currency in open orders, plus bot profit. It represents the total change in value of everything the bot is touching — realized AND unrealized.

Here's the problem: on the classic bot architecture (as opposed to the newer sBot), the Investment Change calculation is broken. It's always positive after the first sell order closes. ALWAYS. Regardless of what's actually happening with your position.

I ran three accounts based partly on that number. I've since cut down to one, because I was losing money while my dashboard was telling me everything was fine. Pretty frustrating, to put it mildly.

## Investor vs. Trader — Pick One

Days like today force you to make a decision, and it's the most important decision in this entire game: are you an investor or a trader?

If you're an investor, you're flat to long. You can reduce your position size, sure, but you're fundamentally betting on the long-term trajectory. A flash crash is noise. The Coinbase IPO is validation of your thesis. You hold.

If you're a trader, you need to accept something uncomfortable: losing money is part of the game. It's not what kills you. What kills you is missing moves and taking profits too early. That's what prevents you from having a great week.

I've seen the double-top pattern forming on BTC and ETH today. We rallied, we need to test it again. Same with the sell-off — everyone bought the dip, now we need to see if it holds. BTC needs to break above 65,000 and ETH above 2,400 to confirm the next leg up.

## The Takeaway

Three things I'm watching right now:

1. **Flash crash recovery speed** — today's bounce was fast and the support was real. That's bullish.
2. **Bot metrics** — if you're running automated strategies, make sure you understand EXACTLY which numbers you can trust. Don't assume your dashboard is telling you the truth. Ask your platform directly which bot architecture calculates investment change correctly.
3. **The Coinbase effect** — this IPO legitimizes the entire space in a way nothing else has. Traditional finance can't ignore crypto when one of its exchanges is trading on the NASDAQ.

Today feels like a milestone. Not because one company went public, but because the market absorbed a flash crash on the biggest crypto news day of the year and barely flinched. The support is there. The demand is there. The bots are running.

Pretty good day, honestly.
