---
layout: page
title: 概率（Probability）
---

这是 Coursera 上 NTU 的[概率](https://www.coursera.org/course/prob)课程的笔记

### 德摩根定理（De Morgan's Law）

\\[ (A\cap B)^c = A^c \cup B^c \\]

### 概率三公理

* \\( P(A)\ge 0  \\)
* \\( P(S)=1 \Rightarrow P(\emptyset)=0 \\)
* \\( P(A_1 \cup A_2 \cup A_3 \cup \cdot\cdot\cdot)=P(A_1)+P(A_2)+P(A_3)+\cdot\cdot\cdot（A_1，A_2，A_3等互斥） \\)

### 一些衍生定理

* \\( P(A\cup B)=P(A)+P(B)-P(A\cap B) \\)
* \\( P(A)=P(A-B)+P(A\cap B) \\)

### 条件概率

* \\( P(X | Y) = \frac{P(X\cap Y)}{P(Y)} \\)
* 全概率公式：\\( P(A)=\sum_{n} P(A\cap B_n)P(B_n) \\)
* 贝叶斯公式（Bayes' theorem）：\\( P(A_{i} | B)=\frac{P(B | A_{i})P(A_{i})}{\sum_{j} P(B | A_{j})P(A_{j})} \\)

### 随机变量（R.V.)

* 离散：有限或有可数的无限个
* 连续：不可数的无限个

### 累积分布函数（CDF）与概率质量函数（PMF）

* CDF: \\( F_{X}(x)=P(X \leq x) \\)
* PMF: \\( PMF: p_{X}(x)=P(X=x) \\)
* 联系: \\(  F_{X}(x)=\sum_{n=-\infty}^{|x|} p_{x}(n) \\)