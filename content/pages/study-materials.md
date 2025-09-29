---
content_type: page
description: This section contains background information about general concepts,
  poker rules, betting, and rankings.
draft: false
learning_resource_types: []
ocw_type: CourseSection
title: Study Materials
uid: d96a648c-2f6b-e867-9e94-98735e5d67dd
---
## Good to Know Before MIT 15.S50 Begins

### Poker / Texas Hold’em Rules

Obviously, you should know the ranking of the poker hands, and how cards are dealt in texas hold’em. Know the terms straight flush, four-of-a-kind (or quads), full house (or boat), flush, straight, three-of-a-kind, two-pair, pair, high card; know preflop, postflop, flop, turn, river.

- [Texas Hold'em Rules](https://www.pokernews.com/poker-rules/texas-holdem.htm#2-texas-hold-em-rule)
- [Poker Hand Rankings](https://www.cardplayer.com/rules-of-poker/hand-rankings)

### Betting Rules

- You should know how betting in poker works. Understand the terms bet, raise, call, check, fold, and all-in. Check-raising means checking and then later raising in the same betting round.
- Know what a blind is. There will be a small blind and a big blind each hand.
- Know that preflop, the big blind is last to act. On each postflop betting round, the small blind is first to act, and the dealer is last to act. Know when a betting round ends (eg. if all players check, then the betting round ends).
- Other good terms to know for positions are cutoff (right of the dealer), hijack (right of the cutoff), under-the-gun (the person left of the big blind; first to act preflop).

### Mathematical Concepts

In class we will run through an example to illustrate the terminology you should know.

- Suppose the pot has $500 in it, and your opponent bets another $250.
- You may call his $250, in which case cards are flipped over:
    - If your cards beat his, you win the whole pot of $500 + $250 (that he just put in) + $250 (that you just put in) = $1000. You profited $750 from this gamble.
    - If his cards beat yours, you get $0 back. You lost $250 from this gamble.
- Or, you can fold, resulting in a payoff of $0.
- In this example, we say that you are getting 3-to-1 odds to call. When you win, you profit 3 times what you risk losing.
- Suppose the probability that your cards beat his is 10%. Then your expectation for calling is 0.1(+750)+0.9(-250)=-150. By calling, you expect to lose $150 in the long run. Your expectation for folding is always $0. Therefore, you should fold, since your expectation for calling is negative.
- Suppose the probability that your cards beat his is 50%. Then your expectation for calling is 0.5(+750)+0.5(-250)=250. By calling, you expect to earn $250 in the long run. Therefore, you should call, since your expectation for calling is positive. If you were to play this game a large number of times, your average payoff per game would be $250, with 100% certainty. This is called the Law of Large Numbers.
- We say that a gamble has high variance if it takes a large number of trials to converge to the expected average payoff per game. A gamble has low variance if it converges quickly. In general, high variance means high risk, and high risk usually means higher reward, ie. higher expectation.

## Book Recommendations

 Miller, Ed, David Sklansky and Mason Malmuth. *Small Stakes Holdem: Winning Big With Expert Play*.  Two Plus Two, 2004. ISBN: 978-1880685327. Only for limit hold’em, but still one of the classic books in poker and written by mathematicians.

Slightly outdated, but very good:

- Harrington, Dan. *Harrington on Hold 'em Expert Strategy for No Limit Tournaments, Vol. 1: Strategic Play*. Two Plus Two, 2004. ISBN: 978-1880685334.
- Harrington, Dan. *Harrington on Hold 'em Expert Strategy for No Limit Tournaments, Vol. 2: Endgame*. Two Plus Two, 2005. ISBN: 978-1880685358.

Rodman, Blair, Lee Nelson, Steven Heston, and Phil Hllmuth, Jr. *Kill Phil: The Fast Track to Success in No-Limit Hold 'em Poker Tournaments*. Huntington Press, 2009. ISBN:  978-1935396314.

Nelson, Lee, Tyson Steib, Steven Heston, Joe Hachem, and Bertrand Grospellier. *Kill Everyone: Advanced Strategies for No-Limit Hold 'em Poker Tournaments and Sit-n-Go's*. Huntington Press, 2009. ISBN: 978-1935396307.

More entertaining than educational:   
Hansen, Gus. *Every Hand Revealed*. Kensington Publishing Corp., 2008. ISBN: 978-0818407277. \[[Preview with Google Books](https://books.google.com/books?id=NglQ5DsdnXoC&printsec=frontcover#v=onepage&q&f=false)\]

Not that practical, but theoretically very interesting:   
Chen, Bill and Jerrod Ankenman. *The Mathematics of Poker.* Conjelco, 2006. ISBN: 978-1886070257.

Nazarewicz, Pawel. *Building a Bankroll*. Pawel Nazarewicz, 2012. ISBN: 978-0615589886. Mostly for full ring cash games.