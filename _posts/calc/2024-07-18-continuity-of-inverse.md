---
layout: post
math: "true"
toc: "false"
title: 1/x의 연속성
categories: Calculus
tags:
  - continuity
  - inverse
---

고정된 ${ a \in \mathbb{R}}$와 ${ 0< \delta < \left\lvert a \right\rvert }$ 에 대해서,

$$ \left\lvert x-a \right\rvert < \delta \Rightarrow \left\lvert x \right\rvert > \left\lvert a \right\rvert - \delta \Rightarrow \frac{1}{\left\lvert x \right\rvert} < \frac{1}{\left\lvert a \right\rvert - \delta} $$

$$ \left\lvert x-a \right\rvert < \delta \Rightarrow \left\lvert \frac{1}{ x} - \frac{1}{a} \right\rvert < \frac{\delta}{\left\lvert a \right\rvert (\left\lvert a \right\rvert - \delta)}$$

따라서 충분히 작은 ${ \varepsilon>0 }$에 대해서

$$ \delta = \frac{\varepsilon\left\lvert a \right\rvert^{2}}{1+\varepsilon \left\lvert a \right\rvert} $$

을 잡으면 (${ \varepsilon }$이 충분히 작으면 처음 가정 ${ \delta < \left\lvert a \right\rvert }$ 또한 만족)

$$ \left\lvert \frac{1}{x} - \frac{1}{a} \right\rvert < \varepsilon $$

을 얻는다. (직접 계산해보라!)