# Data Science Part 2: Probability Notes

---

## Permutations

You always arrange the entire set of elements in the sample space

n - many elements

P<sub>n</sub> = n! (product of natural numbers from 1 to n)

n! = n * (n-1) * (n-2) * ... * 1

---

## Variations

Use variations instead of permutations when not arranging all the elements in a sample space

Variations do not take into account double counting elements

* variations with repitition

    $\overline{V}\binom{n}{p} = n^p$

  * the number of variations when picking p-many elements out of n elements is equal to $n^p$

* variations without repetition

    $V\binom{n}{p} = \frac{n!}{(n-p)!}$

  * the number of variations without repetition when picking p-many elements out of n elements is equal to $n! / (n-p)!$

---

## Combinations

The number of combinations equals the number of variations over the number of permutations

with repetition:

  $C\binom{n}{p} = \frac{V}{P} = \frac{n!}{p!(n-p)!}$

without repetition:

  $\overline{C}\binom{n}{p} = \frac{V}{P} = \frac{(n+p-1)!}{p!(n-1)!}$

Symmetry

---

### Examples

Winning the lottery

the total number of ways to pick 5 numbers

$C\binom{69}{5} = \frac{69!}{5!(69-5)!} = 69! / 5!(64)! > 11,000,000$

to win the grand prize you need to pick the 5 correctly and the powerball

to get the probability of winning the grand prize you need the number of favorable outcomes and the total number of outcomes

favorable outcomes = 1 (tickets bought) = P(win the lottery) ~ 0.000000003
