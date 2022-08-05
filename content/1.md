---
title: Calculation of integrals \(\textstyle \int_{0}^{+\infty}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t\) and \(\textstyle\int_{0}^{+\infty}\frac{\ln(1+t)}{t(1+t)}{\rm d}t\)

date: 2022-07-15
tags: ["Analysis","Integral"]
math: true
---

{{% center %}} 
**Part I.**
{{% /center %}}




1. Prove that the  integral $\int_{0}^{1}\frac{\ln t}{1+t}{\rm d}t$ is convergent.

2.
	(a) Prove that the integrals  $\int_{0}^{1}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t$ et $\int_{1}^{+\infty}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t$ are convergent.

	(b) Prove that
    $$
\int_{0}^{+\infty}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t= 2 \int_{1}^{+\infty}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t.
    $$
3. Using properly an integration by parts, prove that 
  $$
\int_{0}^{1}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t=-2 \int_{0}^{1}\frac{\ln t}{1+t}{\rm d}t.
  $$
  
4. (a) Prove that for all  $n\in \mathbb{N}$, the integral $u_{n}=\int_{0}^{1}t^{n}\ln t{\rm d}t$ is convergent.

   (b) prove that $\forall n\in \mathbb{N},\quad u_{n}=- \frac{1}{(n+1)^{2}}$.
   
   (c) Verify that
    $$ 
	\forall n\in \mathbb{N},\quad \sum\limits_{k=0}^{n}(-1)^{k}u_{k}=\int_{0}^{1}\frac{\ln t}{1+t}{\rm d}t+(-1)^{n}\int_{0}^{1}t^{n+1}\frac{\ln t}{1+t}{\rm d}t.
	$$

  5.  Admitting that $\sum\limits_{n=1}^{+\infty}\frac{(-1)^{n}}{n^{2}}= -\frac{\pi^{2}}{12}$, deduce from the above the values of integrals 
  $$
\int_{0}^{1}\frac{\ln t}{1+t} {\rm d}t\quad \text{et de}\quad \int_{0}^{+\infty}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t.
  $$

{{% center %}} 
**Part II.**
{{% /center %}}

We consider the function $f$ defined on  $[0,+\infty)$ by $f(t)= \frac{\ln(1+t)}{t}$, if $t\ne0$ and $f(0)=1$.

1. Verify that  $f$ is continuous on $[0,+\infty)$.

  In the following, we consider  $F:x\mapsto \int_{0}^{x}f(t){\rm d}t$, for all $x\ge0$.
  
2. Prove that $F(1)=- \int_{0}^{1} \frac{\ln t}{1+t}{\rm d}t$.

2. Prove that the function $t\mapsto \frac{f(t)}{1+t}$ is integrable on $[0,+\infty)$.
3. 
   (a) Prove that $F(x)\underset{x\to +\infty}{=}o(x)$.
   
   (b) Deduce that $t\mapsto \frac{F(t)}{(1+t)^{2}}$ is integrable on $[0,+\infty)$, and that
    $$
\int_{0}^{+\infty}\frac{F(t)}{(1+t)^{2}} {\rm d}t= \int_{0}^{+\infty}\frac{f(t)}{1+t} {\rm d}t.
    $$
4. 
   (a) prove that
    $$
\int_{0}^{+\infty}\frac{f(t)}{1+t} {\rm d}t= \frac{1}{2} \int_{0}^{+\infty}\frac{F(t)+ F \left( \frac{1}{t} \right)}{(1+t)^{2}} {\rm d}t.
    $$
	(b) prove that $\forall x>0,\quad F(x)+ F \left( \frac{1}{x} \right)= \frac{1}{2}(\ln x)^{2}+2F(1)$.
	
5. Deduce from above the value of  $\int_{0}^{+\infty}\frac{f(t)}{1+t} {\rm d}t$.


