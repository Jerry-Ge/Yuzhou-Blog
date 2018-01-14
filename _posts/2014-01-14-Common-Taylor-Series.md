---
layout: post
title: Common Taylor Series Expansions
date: 2018-01-14 08:45:21
categories: math-reference
tags: [taylor series, math]
image: http://gastonsanchez.com/images/blog/mathjax_logo.png
---

> Taylor series is quite important no matter in math, or enginerring, here just few common taylor series expansions we will use frequently.

$$e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + .... = \sum_{k=0}^{\infty} \frac{x^k}{k!}$$

$$sin(x) = x - \frac{x^3}{3!} + \frac{x^5}{5!} - ... = \sum_{k=0}^{\infty} (-1)^k \frac{x^{(2k+1)}}{(2k+1)!}$$

$$cos(x) = x - \frac{x^2}{2!} + \frac{x^4}{4!} - ... = \sum_{k=0}^{\infty} (-1)^k \frac{x^{(2k)}}{(2k)!}$$

$$\frac{1}{1-x} = 1 + x + x^2 + x^3 + ... = \sum_{k=0}^{\infty} x^k$$

$$ln(1+x) = x - \frac{x^2}{2} + \frac{x^3}{3} - ... = \sum_{k=1}^{\infty} (-1)^{k-1}\frac{x^k}{k}$$

> General close form

$$f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n$$

> When a = 0, it's Maclaurin series.