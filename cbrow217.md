# A Rogue-Like Fake Stock Market

### Details

Baseline, this is a stock market simulator with these core features.

1. Generate fake stocks using a seed and specific parameters.
2. Simulate instability, failure, and success of companies over 100+ years.
3. Ability to buy stocks, ETFs, options, and cryptocurrencies.
4. Random events (Short, Booms, Bear Market, etc.)
5. Ability to speed through time (fast-forward, skip day/week/month, etc.)

Features that make it more like a game than a simulator

- Different starting funds depending on gamemode.
- Fake news headlines when starting a new day indicating possible moves.
- Brokerage options (Gives you access to different investment options at different prices).
- Ways to gain leverage both inside and outside the portfolio (margins, loans, etc.).
- Outside investment options (education, property, bonds, CDs, etc).
- Outside jobs for daily investment capital.
- Based on runs, you only get one life (just like real life). If you go bankrupt, you restart.

### Tools & Tech

Note that this isn't gonna be the best list because I'm only vaguely familiar with a lot of this.

1. Unity - This is the first and foremost, a game engine provides a lot of framework to get this done.
2. C# - As the primary language of Unity, this is a given.
3. SQL - A lot of this game is revolving around saving and delivering basic info not limited to stock values, deltas, names, and tags, and we're storing a lot of it, I'm assuming we're gonna need something to store all this.

### Audience & Purpose

Although this might seem like a bad excuse to make a game, this is really dedicated to teaching people how to more effectively utilize different investment strategies in real life scenarios. It's become glaringly obvious that more and more people are becoming adults without a good understanding of how to make money, how to store that money, and, most importantly for our case, how to invest that money to protect from things like inflation. Of course there's traditional stock market simulators, but those aren't marketed towards the average person looking to expand their investment knowledge. They're marketed towards people who really want to get into the stock market and grind it out. Plus, as a person who's done and has referred people to do multiple of them, they're typically too BORING for people to actually want to stick with it and pay attention to it. This seeks to gamify investment and hopefully teach people more about investment than any other method currently out there.

