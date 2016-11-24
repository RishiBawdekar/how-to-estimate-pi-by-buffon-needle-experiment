# how-to-estimate-pi-by-buffon-needle-experiment

In 1777, French mathematician Georges-Louis Leclerc, later Comte de Buffon (born on 7th September 1707) asked the following question:

Suppose you drop a short needle on a ruled paper – what is the probability that the needle comes to lie in a position where it crosses one of the lines?

Probability (p) : (2 / π) * (l / d)

A short needle is a needle whose length (l) is smaller than the distance between two parallel lines on the ruler (d). The probability depends on the ratio – l / d. Since the length is smaller than the distance, the needle will cross only one line on the ruler.

So, if I drop N needles and C out of them cross a line, my probability is C / N. Replacing and re-structuring the above equation we get:

π = 2 * (l / d) * (N / C)

This method is a type of Monte Carlo methods. The value of π is an approximation and the success of this method depends on two factors:

1. The ratio (l / d): In 1901, Italian mathematician Mario Lazzarini dropped a needle 3408 times and got success 1808 times. He chose (l / d) ratio as (5 / 6). The experiment yielded an approximation of π correct to six digits – 3.1415929.

2. Number of runs: More trials will yield better approximations.
