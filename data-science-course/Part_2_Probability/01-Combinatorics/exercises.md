# Combinatorics Exercises

Problem 1:

5 tasks labeled as Critical. How many ways can you complete these tasks by the end of the day?

5! ways to do it = 120 ways

Problem 2:

ad will run on facebook, messenger, instagram, twitter, and reddit.

a.) how many different options you have for the entire campaign assuming you want to use a different one for each platform.

n = 8 versions
p = 5 different

V = 8! / (8-5)! = 8! / 3! = 4 x 5 x 6 x 7 x 8 = 6720 options

b.) how many different options you have for the entire campaign assuming you can use the same banner for some or all platforms.

$\overline{V}$ = n^p = 8^5 = 32768 options

c.) Calculate how many ways we can pick which of the 8 banners to use, assuming we use different ones for each platform.

n = 8 versions
p = 5 different

with repetition:

  $C\binom{n}{p} = \frac{V}{P} = \frac{n!}{p!(n-p)!}$

8! / (5! * 3!) = 6x7x8/6 = 7x8 = 56

d.) Calculate how many ways we can pick which of the 8 banners to use, assuming we can use each one multiple times

n = 8 versions
p = 5 different

without repetition:

  $\overline{C}\binom{n}{p} = \frac{(n+p-1)!}{p!(n-p)!}$

12! / (5! *  7!)  = 12x11x10x9x8/ 2x3x4x5 =  11x9x8 = 792
