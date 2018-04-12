---
layout: post
title: Chebyshev's Inequality
date: 2018-01-22 08:45:20
categories: math-reference
tags: [CLT, math, Cheybyshev Inequality]
description: Here are all you need to know about Chybyshev's Inequality in statistics.
image: 
---


> Let's first give you a general idea about Chybyshev's Inequality: 

Chebyshev's Inequality guarantess that , for a wide class of probability distributions(that's why so important), no more than certain fraction of values can be more than a certain distance from the mean. (Or we can state that in the opposite way: at least # of distributions are within certain range).

> In mathematical language, we write it like this

Let \\(\mu = E[X], \sigma^2 = VAR[X] \\).
For each \\(\epsilon \\) > 0

$$P(|X - \mu| > \epsilon) \leq \frac{Var[X]}{\epsilon^2} = \frac{\sigma^2}{\epsilon^2}$$


> Corollary One:
Let \\(k \geq 1 \\) be an integer, then

$$ P(|X - \mu| > k\sigma) \leq \frac{\sigma^2}{k^2 \sigma^2} = \frac{1}{k^2}$$

> Corollary Two:
Let \\(k \geq 1 \\) be an integer, then

$$ P(|X - \mu| \leq k\sigma) \geq 1 - \frac{1}{k^2}$$


---
### More

For more questions or any cooperations, please contact me at yuzhou@yuzhoulab.com!!

---

### Love & Peace !!!
