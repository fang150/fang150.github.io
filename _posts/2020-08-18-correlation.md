---
title: "Why correlation is symmetric ?"
date: 2020-08-18
tags: [causality]
categories: [foundation]
excerpt: "Prove it simply by basic math."
mathjax: "true"
---

2020-08-18

Why is the relation of positive correlation symmetric?

Specifically, if X raises the probability of Y, then Y raises the probability of X.

To understand this, we use the rules of conditional probability to demystify this phenomenon.


Firstly, we say Y is positively related to X, we mean P(Y/X) > P(Y).

By the rule of conditional probability, we can rewrite the above inequality as P(Y and X)/P(X) > P(Y).


Since P(X) and P(Y) > 0, we have P(Y and X)/P(Y) > P(X).

Again, by the rule of conditional probability, we can rewrite the above inequality as P(X/Y) > P(X).


As a result, we see that the relation of positive correlation is symmetric.






