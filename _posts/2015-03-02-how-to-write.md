---
layout: post
title: "Day 1: Some Calculus.."
date: 2018-04-07
categories: Calculus
tags: []
description: "Some Calculus..by B.Mu from 2018/04/07"
header-img: "img/black.jpg"
---
# Improper Integral

### *Type*

- $\displaystyle{\int_{a}^{b} f(x) \,dx}$ on an infinite interval

- f(x) has an infinite discontinuity in [a, b]

### *Comparison Theorem*

- Suppose that f(x) and g(x) are continuous functions with
f(x) $\ge$ g(x) $\ge$ 0 for x $\ge$ a.

<center>
a. If $\int_{a}^{\infty} f(x) dx$ is convergent, then $\int_{a}^{\infty} g(x) dx$ is convergent.
</center>


<center>
b. If $\int_{a}^{\infty} g(x) dx$ is divergent, then $\int_{a}^{\infty} f(x)
dx$ is divergent.
</center>

### *Note*

- some result: 

<center>
    $\cdot$ $\int_{1}^{\infty} dx$ is convergent if p > 1 and divergent if p$\le$1
</center>


<center>
    $\cdot$ 1 + x $\le$ $e^{x}$ for $\forall$ x $\in$ R
</center>

- sometimes *the Squeeze Theorem* and *L'Hospital's Rule* helps..

- linear approximation..

- concave up/down..

# Differential Equations

### *Initial Value Problem*

- **Euler's Method**

<center>
    Approimate values for the solution of the initial-value problem y' = F(x, y), $y(x_{0}$ = $y_{0}$, with step size h, at $x_{n}$ = $x_{n-1}$ + h, are
</center>


<center>
    $y_{n}$ = $y_{n-1}$ + hF($x_{n-1}$, $y_{n-1}$)     n = 1, 2, 3,...
</center>

- **Direction Field**

- Model 1: The Law of Natural Growth
<center>
    $\frac{dP}{dt}$ = kP, P(0) = $P_{0}$
</center>
<center>
    $\Rightarrow$ P(t) = $P_{0}e^{kt}$
</center>

- Model 2: The Logistic Model
<center>
    $\frac{dP}{dt}$ = kP(1 - $\frac{P}{M}$)
</center>
<center>
    $\Rightarrow$ P(t) = $\frac{M}{1 + Ae^{-kt}}$ where A = $\frac{M - P_{0}}{P_{0}}$
</center>

- note that range of initial value determines shape of curve..

# Sequence

### *Limit*

- A sequence {$a_{n}$} has the limit L and we write
<center>
    $\displaystyple{\lim_{n \to+{\infty}} a_{n}}$ = L  
</center>
<center>
    or $a_{n}$ $\rightarrow$ L as n $\rightarrow\infty$
</center>
<center>
    if for every $\varepsilon$ > 0 there is a corresponding integer N such that
</center>
<center>
    if n > N, then |$a_{n}$ - L| < $\varepsilon$
</center>

- $displaystyle{\lim_{n \to+{\infty}} a_{n}}$ = $\infty$ means that
for every positive number M there is an integer N such that
<center>
    if n > N, then $a_{n}$ > M
</center>

- **The Squeeze Theorem**
<center>
    if $a_{n} \le b_{n} \le c_{n}$ for n $\ge$ $n_{0}$ and
    $displaystyle{\lim_{n \to+{\infty}} a_{n}}$ = $displaystyle{\lim_{n \to+{\infty}} c_{n}}$ = L,
</center>
<center>
    then $displaystyle{\lim_{n \to+{\infty}} b_{n}}$ = L
</center>

- Theorem
<center>
    If $displaystyle{\lim_{n \to+{\infty}} |a_{n}|}$ = 0, then $displaystyle{\lim_{n \to+{\infty}} a_{n}}$ = 0
</center>

- The sequence {$r_{n}$} is convergent if -1 < r $\le$ 1 and divergent for all other values of r.
<center>
    $displaystyle{\lim_{n \to+{\infty}} r^{n}}$ = 0 if -1 < r < 1
</center>
<center>
    $displaystyle{\lim_{n \to+{\infty}} r^{n}}$ = 0 if r = 1
</center>





