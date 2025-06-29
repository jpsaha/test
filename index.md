---
layout: default
title: "Elegant Math Theme"
description: "A minimal, elegant, mobile-friendly Jekyll theme with math blocks"
---

<div class="math-blocks">

{% include theorem.html title="Euclid's Theorem" content="
There are infinitely many primes.
" %}

{% include definition.html content="
A positive integer $p > 1$ is called *prime* if its only positive divisors are $1$ and $p$.
" %}

{% include proof.html content="
Suppose there are only finitely many primes $p_1, \ldots, p_n$. Consider $Q = p_1p_2\cdots p_n + 1$...
" %}

</div>
