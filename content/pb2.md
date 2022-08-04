---
title: "Decomposition of a diagonalizable endomorphism into a sum of projectors"
date: 2022-08-03T23:19:24+01:00
tags: ["Diagonalization","Projector"]
draft: false
---


We denote  $\mathbb{K}$ the field of real or complex numbers. In 
the following, $f$ denotes an endomorphism of a $\mathbb{K}$-vector space  $E$ of finite dimension $n$.

1. Show that if $f$ is diagonalizable, then there are two by two distinct scalars
     $\alpha_1,\ldots,\alpha_k$ and projectors $p_1,\ldots,p_k$ of $E$ such that:
	- $f=\alpha_1p_1+\cdots+\alpha_kp_k; \qquad (1)$
	- $\operatorname{Id}_E=p_1+\cdots+p_k; \qquad (2)$
	-  for all $i,j\in\{1,\ldots,k\}$ with $i\ne j$: $p_i\circ p_j=0. \qquad (3)$
	
	 Conversely, we consider in the following a
    endomorphism $f$ of $E$ such that there exist two by two distinct scalars
    $\alpha_1,\ldots,\alpha_k$  and
    nonzero endomorphisms $p_1,\ldots,p_k$ of $E$ verifying the three
    conditions $(1), (2)$ and $(3)$.

2. Check that $p_i$ is a projector of $E$ for all
    $i\in\llbracket1,k\rrbracket$.

3. Show by induction that, for any natural number $m$,
    $$f^m=\alpha_1^mp_1+\cdots+\alpha_k^mp_k.$$

4. Deduce that if $Q(X)\in \mathbb{K} \[X\]$, then
    $$Q(f)=Q(\alpha_1)p_1+\cdots+Q(\alpha_k)p_k.$$

5. Prove that   $(p_1,\ldots,p_k)$ is a linearly independent set in $\mathcal L(E)$.

6. Check that if $i\in \llbracket 1,k \rrbracket$ and
    $x \in \operatorname{Im}(p_i)$ then $f(x)=\alpha_i x$.

7. Deduce that
    $E=\ker (f- \alpha \operatorname{Id}_E) \oplus \cdots \oplus \ker(f-\alpha_k\operatorname{Id}_E)$.
	
    We set $$V_k(\alpha_1,\ldots,\alpha_k)=\begin{vmatrix}
                    1&\alpha_1&\alpha_1^2&\cdots&\alpha_1^{k-1}\cr
                    1&\alpha_2&\alpha_2^2&\cdots&\alpha_2^{k-1}\cr
                    \vdots&\vdots&\vdots&\vdots&\vdots\cr
                    1&\alpha_k&\alpha_k^2&\cdots&\alpha_k^{k-1}
            \end{vmatrix},$$ and
    $R(X)=V_k(\alpha_1,\ldots,\alpha_{k-1},X)$.

8. Show that $R$ is a polynomial with $\deg(R)\le k-1$.

9. Verify that $\alpha_1,\ldots,\alpha_{k-1}$ are roots of $R$.

10. Deduce that if $x\in\mathbb{K}$ then

    $$R(x)= V_{k-1}(\alpha_1,\ldots,\alpha_{k-1})\prod_{i<k}(x-\alpha_i).$$

11. Establish that
    $$V_k(\alpha_1,\ldots,\alpha_k)=\prod_{1\le i<j\le k}(\alpha_j-\alpha_i).$$

12. Deduce that, for all $i\in\llbracket1,k\rrbracket$, there exists
    $Q_i(X)\in\mathbb{K}\[X\]$ such that $\deg(Q_i(X))<k$ and $p_i=Q_i(f)$.

13. For $i\in \llbracket1,k \rrbracket$ and $x\in \operatorname{Im}(p_i)$,
    calculate $Q_i(f)(x)$.

14. Deduce that if $i,j\in \llbracket1,n \rrbracket$, then

$$Q_i( \alpha_j)=\begin{cases}
            1& \text{if } i=j\cr
            0& \text{if } i\ne j
            \end{cases}.$$


 
   For $i\in \llbracket 1,k \rrbracket$ and $x\in \mathbb{K}$, we set
    $$L_i(x)=\prod_{\underset{j\ne i}{j=1}}^k \frac{x-\alpha_j}{\alpha_i-\alpha_j}.$$


15. Compute $L_i(\alpha_j)$ for $i,j\in\llbracket1,k\rrbracket$.

16. Show that the application
    $\varphi: \mathbb{K}_{k-1}\[X\]\mapsto \mathbb{K}^k$ defined by
    $\varphi(P)=(P(\alpha_1),\ldots,P(\alpha_k))$ is an isomorphism of $\mathbb{K}$-vector spaces.

17. Deduce that for all $i\in\llbracket1,k\rrbracket$:
    $$p_i=\prod_{\underset{j\ne i}{j=1}}^k \frac{1}{\alpha_i-\alpha_j}(f-\alpha_j\operatorname{Id}_E).$$
