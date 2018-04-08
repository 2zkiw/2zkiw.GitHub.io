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
    $\cdot$ $\int_{1}^{\infty}\frac{1}{x^{p}} dx$ is convergent if p > 1 and divergent if p$\le$1
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
    Approimate values for the solution of the initial-value problem y' = F(x, y), $y(x_{0})$ = $y_{0}$, with step size h, at $x_{n}$ = $x_{n-1}$ + h, are
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
    $\displaystyle{\lim_{n \to+{\infty}} a_{n}}$ = L  
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

- $\displaystyle{\lim_{n \to+{\infty}} a_{n}}$ = $\infty$ means that
for every positive number M there is an integer N such that
<center>
    if n > N, then $a_{n}$ > M
</center>

- **The Squeeze Theorem**

<center>
    if $a_{n} \le b_{n} \le c_{n}$ for n $\ge$ $n_{0}$ and
    $\displaystyle{\lim_{n \to+{\infty}} a_{n}}$ = $\displaystyle{\lim_{n \to+{\infty}} c_{n}}$ = L,
</center>
<center>
    then $\displaystyle{\lim_{n \to+{\infty}} b_{n}}$ = L
</center>

- Theorem

<center>
    If $\displaystyle{\lim_{n \to+{\infty}} |a_{n}|}$ = 0, then $\displaystyle{\lim_{n \to+{\infty}} a_{n}}$ = 0
</center>

- The sequence {$r_{n}$} is convergent if -1 < r $\le$ 1 and divergent for all other values of r.
<center>
    $\displaystyle{\lim_{n \to+{\infty}} r^{n}}$ = 0 if -1 < r < 1
</center>
<center>
    $\displaystyle{\lim_{n \to+{\infty}} r^{n}}$ = 1 if r = 1
</center>

# Series

### *Convergent/Divergent*

- Given a series $\sum_{n=1}^{\infty}a_{n}$  = $a_{1}$ + $a_{2}$ + ..., let $S_{n}$ denote its nth partial sum:
<center>
    $S_{n}$ = $\sum_{i=1}^{n}a_{i}$ = $a_{1}$ + $a_{2}$ + ...+ $a_{n}$ 
</center> 

- If the sequence {$S_{n}$} is convergent and $\displaystyle{\lim_{n \to+{\infty}} S_{n}}$ = S exists as a real number, then the series $\sum$$a_{n}$ is called convergent and $a_{1}$ + $a_{2}$ + ...+ $a_{n}$ + ... = S or $\sum_{n=1}^{\infty}a_{n}$ = S

- The number S is called the sum of the series.

- If the sequence {$S_{n}$} is divergent, then the series is called divergent.

### *Geometric Series*

- The geometric series
<center>
    $\sum_{n=1}^{\infty}ar^{n-1}$ = a + ar + a$r^{2}$ + ... is convergent if |r| < 1 and its sum is
</center>
<center>
    $\sum_{n=1}^{\infty}ar^{n-1}$ = $\frac{a}{1-r}$ |r| < 1
</center>
<center>
    If |r| $\ge$ 1, the geometric series is divergent.
</center>

- e.g. $\sum_{n=0}^{\infty}x^{n}$ = $\frac{1}{1-x}$, where $|x|$ < 1

### *Harmonic series*

- $\sum_{n=1}^{\infty}\frac{1}{n}$ 1 + $\frac{1}{2}$ + $\frac{1}{3}$ + $\frac{1}{4}$ + ... is divergent

- In general, $S_{2^{n}}$ > 1 + $\frac{n}{2}$

- $S_{2^{n}}$ $\rightarrow$ $\infty$ as n $\rightarrow$ $\infty$, so $S_{n}$ is divergent, the harmonic series diverges.

### *Test for Divergence* 

- If $\displaystyle{\lim_{n \to+{\infty}}a_{n}}$ does not exist or $\displaystyle{\lim_{n \to+{\infty}}a_{n}}$ $\ne$ 0, then the seires $\sum_{n=1}^{\infty}$ is divergent.

- **Theorem**
<center>
    If the series $\sum_{n=1}^{\infty}a_{n}$ is convergent, then $\displaystyle{\lim_{n \to+{\infty}}a_{n}}$ = 0.
</center>
$\star$ The converse of theorem is not true in general, if $\displaystyle{\lim_{n \to+{\infty}}a_{n}}$ = 0, we cannot conclude that $\sum$$a_{n}$ is convergent.(counter example: harmonic series)

## Integral Test

- Suppose f is a **continuous**, **positive**, **decreasing** function on [1, $\infty$) and let $a_{n}$ = f(n). Then the series $\sum_{n=1}^{\infty}a_{n}$ is convergent <=> the improper integral $\int_{1}^{\infty}f(x)dx$ is convergent.

- If $\int_{1}^{\infty}f(x)dx$ is convergent, then $\sum_{n=1}^{\infty}a_{n}$ is convergent.

- If $\int_{1}^{\infty}f(x)dx$ is divergent, then $\sum_{n=1}^{\infty}a_{n}$ is divergent.

### *P-Series*

- $\sum_{n=1}^{\infty}\frac{1}{n^{p}}$ is convergent if p > 1 and divergent if p $\le$ 1.

## Comparison Test

- Suppost that $\sum$ $a_{n}$ and $\sum$ $b_{n}$ are series with positive terms.

- If $\sum$ $b_{n}$ is convergent and $a_{n}$ $\le$ $b_{n}$ for all n, then $\sum$ $a_{n}$ is also convergent.

- If $\sum$ $b_{n}$ is divergent, and $a_{n}$ $\ge$ $b_{n}$ for all n, the $\sum$$a_{n}$ is also divergent.

## The Limit Comparison Test

- Suppose that $\sum$ $a_{n}$ and $\sum$ $b_{n}$ are series with positive terms.

- If 
$\displaystyle{\lim_{n \to+{\infty}}\frac{a_{n}}{b_{n}}}$ = c

<center>
where c is a finite number and c > 0, then either both series converges or both diverges.
</center>

## Alternating Series Test

- If the alternating series
<center>
    $\sum_{n=1}^{\infty}b_{n}$ = $b_{1}$ - $b_{2}$ + $b_{3}$ - $b_{4}$ + $b_{5}$ - $b_{6}$ + ..., $b_{n}$ > 0 satisfies
</center>
<center>
    a. $b_{n+1}$ $\leq$ $b_{n}$ for all n
</center>
<center>
    b. $\displaystyle{\lim_{n \to+{\infty}}b_{n}}$ = 0
</center>
<center>
    then the series is convergent
</center>

### **Abosolute convergent**

- A series $\sum$ $a_{n}$ is absolutely convergent if the series of absolute value $\sum$ $\mid$$a_{n}$$\mid$ is convergent.

### *Alternating p-series*

- e.g. $\sum_{n=1}^{\infty}\frac{(-1)^{n-1}}{n^{2}}$ = 1 - $\frac{1}{2^{2}}$ + $\frac{1}{3^{2}}$ - $\frac{1}{4^{2}}$ + ... is absolutely convergent because $\sum_{n=1}^{\infty}$ $\mid$$\frac{(-1)^{n-1}}{n^{2}}$$\mid$ is a convergent p-series.

### *Alternating harmonic series*

- e.g. $\sum_{n=1}^{\infty}\frac{(-1)^{n-1}}{n}$ = 1 - $\frac{1}{2}$ + $\frac{1}{3}$ - $\frac{1}{4}$ + ... is convergent but it is not absolutely convergent because $\sum_{n=1}^{\infty}$ $\mid$$\frac{(-1)^{n-1}}{n}$$\mid$ = $\sum_{n=1}^{\infty}$ $\frac{1}{n}$ = 1 + $\frac{1}{2}$ + $\frac{1}{3}$ + $\frac{1}{4}$ + ... which is harmonic series(p-series with p = 1) and is divergent.

### **Conditionally convergent**

- A series $\sum$$a_{n}$ is conditionally convergent if it is convergent but not absolutely convergent.

### *Theorem*

- If a series $\sum$$a_{n}$ is absolutely convergent, then it is convergent.

## The Ratio Test

- a. If $\displaystyle{\lim_{n \to+{\infty}}$ $\mid$\frac{a_{n+1}}{a_{n}}$$\mid$ = L < 1, then the series $\sum_{n=1}^{\infty}$ $a_{n}$ is absolutely convergent (and therefore convergent).

- b. If $\displaystyle{\lim_{n \to+{\infty}}$ $\mid$\frac{a_{n+1}}{a_{n}}$$\mid$ = L > 1 or $\displaystyle{lim_{n \to+{\infty}}}$ $\mid$\frac{a_{n+1}}{a_{n$\mid$ = $\infty$, then the series $\sum_{n=1}^{\infty}a_{n}$ is divergent.

- c. If $\displaystyle{\lim_{n \to+{\infty}}$ $\mid$$\frac{a_{n+1}}{a_{n}}$$\mid$ = 1, the Rato Test is inconclusive; that is, no conclusion can be drawn about the convergence or divergence of $\sum$ $a_{n}$

### *Power Series*

- For a given powre series $\sum_{n=0}^{\infty}$ $c_{n}$ $(x-a)^{n}$ there are only three possibilities:

- a. The series converges only when x = a

- b. The series converges for all x.

- c. There is a positive number R such that the series converges if $\mid$x-a$\mid$ < R and diverges if $\mid$x-a$\mid$ > R.

- The number R is called the radius of convergence of the power series.

- The radius of convergence is R = 0 in a and R = $\infty$ in b.

- The interval of convergence..

- Notice! the series might converge at one or both endpoints(i.e. x = a$\pm$R)  or diverge at both endpoints..

- e.g. **Geometric series** 
<center>
    $\sum_{n=0}^{\infty}x^{n}$
</center>
<center>
    Radius of convergence: R = 1
</center>
<center>
    Interval of convergence: (-1, 1)
</center>

## Taylor Series

- The Taylor series of the function f centered at a:
<center>
    f(x) = $\sum_{n=0}^{\infty}\frac{f^{(n)}(a)}{n!}(x - a)^{n}$
</center>

- $\frac{1}{1-x}$ = $\sum_{n=0}^{\infty}x^{n}$ = 1 + x + $x^{2}$ + $x^{3}$ + ..., R = 1

- $e^{x}$ = $\sum_{n=0}^{\infty}\frac{x^{n}}{n!}$, R = $\infty$

- sin(x) = $\sum_{n=0}^{\infty}(-1)^{n}\frac{x^{2n+1}}{(2n+1)!}$, R = $\infty$

- cos(x) = $\sum_{n=0}^{\infty}(-1)^{n}\frac{x^{2n}}{(2n)!}$, R = $\infty$

- $tan^{-1}(x)$ = $\sum_{n=0}^{\infty}(-1)^{n}\frac{x^(2n+1)}{2n+1}$, R = 1

- ln(1 + x) = $\sum_{n=0}^{\infty}(-1)^{n-1}\frac{x^{n}}{n}$, R = 1

- $(1+x)^{k}$ = 1 + kx + $\frac{k(k-1)}{2!}x^{2}$ + $\frac{k(k-1)(k-2)}{3!}x^{3}$ + ..., R = 1

- **Maclaurin sries**: the special case a = 0

- *Fact*: $\displaystyle{\lim_{n \to+{\infty}}\frac{x^{n}}{n!}}$ = 0 for every real number x because the series $\sum\frac{x^{n}}{n!}$ converges for all x and so its nth term approaches 0.

# Approximate Integral

### *Midpoint Rule*

- $\int_{a}^{b}f(x)dx$ $\approx$ $M_{n}$ = $\Delta$x[f($\bar{x_{1}}$) + f($\bar{x_{2}}$) + ... + f($\bar{x_{n}}$)] where $\Delta$x = $\frac{b - a}{n}$ and $\bar{x_{i}}$ = $\frac{1}{2}$($x_{i-1}$ + $x_{i}$) = midpoint of [$x_{i-1}$, $x_{i}$]

### *Trapezoidal Rule*

- $\int_{a}^{b}f(x)dx$ $\approx$ $T_{n}$ = $\frac{\Delta x}{2}$[f($x_{0}$) + 2f($x_{1}$) + 2f($x_{2}$) + ... + 2f($x_{n-1}$) + f($x_{n}$)] where $\Delta$ x = $\frac{(b - a)}{n}$ and $x_{i}$ = a + i $\Delta$ x

### *Error Bounds*

- Suppose $\mid$f"(x)$\mid$ $\le$ K for a $\le$ x $\le$ b. If $E_{T}$ and $E_{M}$ are the errors in the Trapezoidal and Midpoint Rules, then 
<center>
    $\mid$${E_{T}}$$\mid$ $\le$ $\frac{K(b-a)^{3}}{12n^{2}}$ and $\mid$$E_{M}$$\mid$ $\le$ $\frac{K(b-a)^{3}}{24n^{2}}$
</center>

### *Simpson's Rule*

- $\int_{a}^{b}$f(x)dx $\approx$ $S_{n}$ = $\frac{\Delta x}{3}$[f($x_{0}$) + 4f($x_{1}$) + 2f($x_{2}$) + 4f($x_{3}) + ... + 2f($x_{n-2}$) + 4f($x_{n-1}) + f($x_{n}$)] where n is even and $\Delta$ x = $\frac{(b-a)}{n}$.

### *Error Bounds*

- Suppose $\mid$$f^{(4)}(x)$$\mid$ $\le$ K for a $\le$ x $\le$ b. If $E_{S}$ is the error involved in using Simpson's Rule, then 
<center>
    $\mid$$E_{S}$$\mid$ $\le$ $\frac{K(b-a)^{5}}{180n^{4}}$
</center>
