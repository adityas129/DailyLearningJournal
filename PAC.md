# Probably Approximately Correct : a Formal Theory of Learning



Occam's Razor : A basic philosophy concept stating that the more assumptions we have to make in a certain hypothesis, the less likely it is to be correct. 


PAC best defined by an example game. Excerpt detailing the example given below: 

------
"Imagine a game between two players. Player 1 generates numbers x at random in some fixed way, and in Player ``1's`` mind he has an interval [a,b]. Whenever Player 1 gives out an x, he must also say whether ``it’s`` in the interval (that is, whether a ``\leq`` x ``\leq`` b). ``Let’s`` say that Player 1 gives reports a 1 if x is in the interval, and a 0 otherwise. ``We’ll`` call this number the label of x, and call the pair of (x, label) a sample, or an example. We recognize that the zero and one correspond to ``“yes”`` and ``“no”`` answers to some question (Is this email ``spam``? Does the user click on my ad? etc.), and so sometimes the labels are instead \pm 1, and referred to as ``“positive”`` or ``“negative”`` examples. ``We’ll`` use the positive/negative terminology here, so positive is a 1 and negative is a 0.

Player 2 (``we’re`` on her side) sees a bunch of samples and her goal is to determine a and b. Of course Player 2 ``can’t`` guess the interval exactly if the endpoints are real numbers, because Player 1 only gives out finitely many samples. But whatever interval Player 2 does guess at the end can be tested against Player ``1’s`` number-producing scheme. That is, we can compute the probability that Player ``2’s`` interval will give an incorrect label if Player 1 were to continue giving out numbers indefinitely. If this error is small (taking into account how many samples were given), then Player 2 has ``“learned”`` the interval. And if Player 2 plays this game over and over and usually wins (no matter what strategy or interval Player 1 decides to use!), then we say this problem is PAC-``learnable``.

PAC stands for Probably Approximately Correct, and our number guessing game makes it clear what this means. Approximately correct means the interval is close enough to the true interval that the error will be small on new samples, and Probably means that if we play the game over and over ``we’ll`` usually be able to get a good approximation. That is, ``we’ll`` find an approximately good interval with high probability. "

------


This above example does a good job of providing the general idea of what PAC means. 

Basically, PAC in eli5 terms is being accurate enough due to the sample size provided and the dataset provided that the probablity of guessing wrong is very low. 

[Refer here](https://jeremykun.com/2014/01/02/probably-approximately-correct-a-formal-theory-of-learning/) for a more rigorous and detailed insight into what PAC is!


