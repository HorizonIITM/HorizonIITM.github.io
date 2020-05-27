---
layout: post
title:  Lagrange Interpolation Formula
date:   2020-05-26 16:05:55 +0300
image:  3-1.jpg
tags:   [Math]
---
## Prelude

Interpolation is one thing humans are most comfortable about: they interpolate the thought string of their fellow humans to guess their behaviour, they interpolate their data during a lab session to obtain fake observations, they interpolate stock market data to predict profit/loss, so interpolation is something which is built into the basic inuition of Human beings. Hence this will not be much of an intuitively-taunting read (*I hope*).

Okay, lets start from block one (square one is for *flatlanders*). According to [Wikipedia](https://www.wikiwand.com/en/Interpolation "Interpolation"):
> In the mathematical field of numerical analysis, interpolation is a type of estimation, a method of constructing new data points within the range of a discrete set of known data points.

which means, **using** the given data, to **predict** the data values in the range *between* that of the given data. If the data is two speckles on a wall, then Interpolation, is your 5-year-old self drawing a crooked like between them.  
![]({{site.baseurl}}/img/3-2.jpg)
Lagrange Interpolation is just another method to interpolate the data. Okay, now what is "interpolate the data" you might ask. Well, every data, as the reductionist percieves, is a result of a mathematical structure. In this case, the mathematical structure is the **function** whose output is given by the data. Our mission is to find this function. So interpolation of a data means *to find the function whose output is the given data*.

This Lagrange Interpolation yields a function (a polynomial to be precise) of order *one less-than* the number of data points. So if we have $$N$$ data points, we get a $$(N-1)^{th}$$ order polynomial.

## Time to grind

As every interpolation method, the final interpolating function is a **Linear Combination** of the interpolating **basis**.

Given a set of $$N+1$$ data points $$(x_{0},y_{0}),(x_{1},y_{1})...,(x_{N},y_{N})$$, with the condition that none of the $$x_{i}$$ are equal, the interpolation polynomial in the Lagrange form is given by the linear combination 

$$ \begin{equation}
\label{eq:li}
\tag{1}
L(x)=\sum_{i=0}^{N}{y_{i}\cdot\ell_{i}(x)}
\end{equation} $$ 

where the $$\mathcal{l}_{i}(x)$$ form the basis of the Lagrange polynomial. The formula for the basis used in $$\eqref{eq:li}$$ is given by 

$$\begin{equation}\label{eq:lbas}\tag{2} \ell_{i}(x)=\prod_{0\leq j \leq N,j \neq i}{\frac{x-x_{j}}{x_{i}-x_{j}}} \end{equation}$$

That's it guys, now you have learned Lagrange Interpolation!!

### *The End*

<small>P.S.: We will be posting an article discussing the implementation of Lagrange Interpolation and also Newton Interpolation in Python, soon </small>




