# Learning-Minimax-Alpha-beta
An project in the Artificial Intelligence course about Minimax &amp; Alpha-Beta in TicTacToe
* Minimax Algorithm Summary<br>
Also known as a minimalist maximal algorithm, is an algorithm to find the minimum value in the maximum probability of failure (that is, to minimize the maximum benefit of the opponent).It is usually implemented in recursive form.<br>
In the Game tree node selection, Max always selects the minimum value in Min's maximum profit (which is best for max), as Will Min, and chooses what is best for you (that is, Max is likely to get the maximum value).<br>
* Alpha-beta Algorithm Summary<br>
Alpha-beta is optimized on the basis of minimax, optimized on pruning, cut Cut out some unnecessary branches to reduce the number of traversal point nodes. The essence of the algorithm execution is: by passing two parameters of alpha and beta to recursive minimum maximal functions, alpha represents the worst case of Max, Beta represents the worst case of Min, so their initial value is negative infinity and positive infinity.
In the recursive process, in the round to max, if the minimum value is larger than Alpha, the alpha is updated, and in the Min's turn, if the minimum maximum value is smaller than the beta, the beta is updated.

![Game Tree](https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg)
