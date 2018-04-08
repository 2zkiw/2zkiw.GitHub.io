---
layout: post
title: "Day 1: Some Calculus.."
date: 2018-04-07
categories: Calculus
tags: []
description: "Some Calculus..by B.Mu from 2018/04/07"
header-img: "img/black.jpg"
---
$\triangleright$**Inproper Integral**:

a. If $\displaystyle{\int_{a}^{t} f(x) \,dx}$ exists for
every number t $\ge$ a, then

$$\int_{a}^{\infty} f(x) \,dx =
 \displaystyle{\lim_{t \to+\infty}\int_{a}^{t} f(x) \,dx}$$

provided this limit exists(as a finite number).

b. If $\displaystyle{\int_{t}^{b} f(x) \,dx}$ exists for
every number t $\le$ b, then

$$\int_{-\infty}^{b} f(x) \,dx =
 \displaystyle{\lim_{t \to+-\infty}\int_{t}^{b} f(x) \,dx}$$

provided this limit exists(as a finite number).

  $\circ$ the improper integrals are called **convergent** if the corresponding
  limit exists and **divergent** if the limit does not exist.

c. If both $\displaystyle{\int_{a}^{\infty} f(x) \,dx}$ 
and $\displaystyle{\int_{-\infty}^{a} f(x) \,dx}$ are convergent,
then we define

$$\int_{-\infty}^{\infty} f(x) \,dx = \displaystyle{\int_{-\infty}^{a} f(x) \,dx} + \displaystyle{\int_{a}^{\infty} f(x) \,dx}$$

\star $\int_{1}^{\infty} \frac{1}{x^p} dx$ is convergent if p>1
and divergent if p\le1
