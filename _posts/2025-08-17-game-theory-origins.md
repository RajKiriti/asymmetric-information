---
title: "Game Theory: The Origin"
date: 2025-09-12
categories: [History]
tags: [History]
math: true
---

# What is Game Theory?

Game Theory, as the name suggests, is the systematic study of *games*—both in the familiar sense of chess, poker, and the like, and in the much broader sense of strategic interactions in society. The former is easy to see (and, to be honest, the number of times acquaintances have asked me if I “design games” for a living is part of the reason I wanted to write this series). But the latter—using “games” as a framework for thinking about interactions between societal systems—is where things get really interesting. This dual meaning is understandable: after all, chess, poker, and bridge are indeed “games.” They also happen to provide some of the clearest starting points for understanding what Game Theory is about.

## From Classic Games to Strategy

Take chess for example. The rules are fixed and agreed upon (though they evolved—*Chaturanga* in Ancient India was an early ancestor of chess) and each player’s actions are well-defined. As someone who might have played these games at somepoint, you might wonder, so does that mean there is an optimal way to play these games? Let us think about that question for a minute, what does one mean by optimal? Well you can say, is there a way for me to play such that I always win? A moment’s reflection shows this is too much to ask (of course one would lose from some positions!). A more reasonable question is whether you can play in such a way that you do as well as possible regardless of what your opponent does. And now we are in business—that’s exactly the idea behind equilibrium strategies, and in particular the concept of **Nash Equilibrium**, perhaps the most famous idea in all of Game Theory.  

For chess, there *is* technically an “optimal” strategy: one could, in theory, write down every possible position and work out the best move in each case. But the number of possibilities is astronomical—far beyond what a human brain can compute. That’s why chess remains fascinating: humans rely on intuition and heuristics to prune possibilities. Unsurprisingly, computers excel at brute-force search, but until the arrival of modern deep learning it wasn’t clear whether they could *learn* to play well by practicing millions of times. The stunning success of modern chess engines stands as a testament to that progress.  

Now, chess is what’s called a *perfect information game*: everyone knows everything about the state of play at all times. Once you relax that assumption, things get much more complicated. In poker, for example, you know your own hand but not your opponent’s. Here you must form beliefs about what the other players might have, update those beliefs as the game unfolds, and at the same time remember that your opponent is trying to manipulate your beliefs, while maintaining their own. This leads to an infinite regress—what do you think about their hand, what do they think you think about their hand, what do they think you think they think about your hand… and so on. If you play repeatedly against the same people, reputation matters too (does this person usually bluff?). Game Theory provides a way to formalize all these interactions (using tools like *types*). And, as you might guess, these imperfect information games are harder not just for humans but also for computers.

## The Origin
At this point you might reasonably ask: *why study any of this?* Aren’t these games just for fun? And here we come to the actual origins of the field. The birth of Game Theory (in it's present form[^1]) is usually traced to the now-classic book *Theory of Games and Economic Behavior* by John von Neumann[^2] and Oskar Morgenstern. The fascinating part of this book is not just the mathematical formalism, but the motivation. In their introduction they write:  

> “The social problems that economists were eager to address have not been formulated precisely enough to be analyzed mathematically. The behavior of individuals [was] neglected altogether, even though their decisions in aggregate can sway the economy just as the motion of molecules determine the bulk property of gas.”  

In other words, economics at the time had sweeping theories but little mathematical rigour was often “window dressing” rather than a genuine tool[^2]. Von Neumann and Morgenstern argued that this was not a reason to give up, but rather a challenge. After all, centuries earlier, people could have made the same objection about physics, chemistry, or biology. Progress came when those fields were put on a firm mathematical foundation.  

They also warned against trying to explain *everything* at once. Just as Newton didn’t solve all of physics but started with falling bodies—developing calculus in the process—they argued that economics needed to begin with small, precise models. The right approach, they wrote, was:  

> “to obtain first utmost precision and mastery in a limited field, and then to proceed to another, somewhat wider one, and so on.”  

So Game Theory was not born as an abstract or wild idea, but as a natural step: build precise models of interaction, test them against real data, and expand. Along the way, entirely new mathematics might be required, just as Newton needed calculus.

## The Evolution
Now, this is a compelling reason for one to spend time and think about Game Theory as a way, to better model this world and understand interactions helping us with everything ranging from vague and broad policy questions to more specific monetary questions. Needless to say while the initial motivation still stays put, different scientists have taken different approaches in what they think would be useful to model such interactions. Hence the field just did not proceed incremantally from what Von Neumann built but moved challenging and sometimes succedingly taking opposing views than what the founding fathers had in mind. For example, when dealing with multi-agent interactions Von Neumann suggested utilizing models of coalitions to understand range of possible outcomes while John Nash came up with the concept of *non-cooperative games*, where each individual acts in their own self-interest and equilibrium arises when no one can gain by deviating alone.

Von Neumann himself was skeptical—he thought Nash’s approach was too pessimistic[^3], and that predicting exact outcomes was unrealistic. He preferred to characterize ranges of possible outcomes. But history sided with Nash: his equilibrium concept became central to economics and beyond.

The momentum only grew. During the Cold War, repeated games with incomplete information were used to analyze negotiation strategies in nuclear disarmament[^4]. Later, Game Theory found applications in designing auctions for spectrum licenses, building life-saving kidney exchange systems, and studying the effects of *asymmetric information* in markets (a topic I’ll dive into in future posts). To date, more than a dozen Sveriges Riksbank Prize in Economic Sciences in Memory of Alfred Nobel have been awarded for contributions grounded in Game Theory.

Now, von Neumann and Morgenstern themselves admitted that a full-fledged theory of human behavior was far beyond reach, and that remains true today. Game Theory is still young, and the rise of autonomous agents and AI makes it more relevant than ever. How do we model interactions when machines, not just people, are making strategic decisions? How do we assign probabilities to events we don’t even know we should expect? These are questions for the future—but the foundations laid by von Neumann, Morgenstern, and Nash continue to guide us.  

And that is where I hope to take this series next: into the world of asymmetric information, and the sometimes dramatic consequences it can have on outcomes in everyday life.

---
[^1]: Recherches sur les Principes Mathématiques de la Théorie des Richesses by Antoine Augustin Cournot was written in 1838.
[^2]: It’s honestly hard to imagine fields von Neumann didn’t touch—he made an impact almost everywhere he went.
[^3]: The Man from the Future: The Visionary Life of John Von Neumann by Ananyo Bhattacharya, an excellent read!
[^4]: Repeated Games with Incomplete Information by Michael Maschler and Robert Aumann, beautiful reference, an excellet theory based on practical motivation.



