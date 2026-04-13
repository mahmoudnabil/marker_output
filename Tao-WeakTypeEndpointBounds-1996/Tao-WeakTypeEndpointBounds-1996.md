![](_page_0_Picture_0.jpeg)

Weak-Type Endpoint Bounds for Riesz Means

Author(s): Terence Tao

Source: Proceedings of the American Mathematical Society , Sep., 1996, Vol. 124, No. 9

(Sep., 1996), pp. 2797-2805

Published by: American Mathematical Society

Stable URL:<https://www.jstor.org/stable/2161721>

# REFERENCES

Linked references are available on JSTOR for this article: [https://www.jstor.org/stable/2161721?seq=1&cid=pdfreference#references\\\_tab\\\_contents](https://www.jstor.org/stable/2161721?seq=1&cid=pdf-reference#references_tab_contents) You may need to log in to JSTOR to access the linked references.

JSTOR is a not-for-profit service that helps scholars, researchers, and students discover, use, and build upon a wide range of content in a trusted digital archive. We use information technology and tools to increase productivity and facilitate new forms of scholarship. For more information about JSTOR, please contact support\@jstor.org.

Your use of the JSTOR archive indicates your acceptance of the Terms & Conditions of Use, available at https://about.jstor.org/terms

![](_page_0_Picture_11.jpeg)

American Mathematical Society is collaborating with JSTOR to digitize, preserve and extend access to Proceedings of the American Mathematical Society

#### WEAK-TYPE ENDPOINT BOUNDS FOR RIESZ MEANS

#### TERENCE TAO

(Communicated by Christopher D. Sogge)

ABSTRACT. We use $L^2$ restriction theory to prove optimal weak-type bounds of Bochner-Riesz multipliers and Riesz means of elliptic pseudo-differential operators on compact manifolds, for $p \leq 2(n+1)/(n+3)$ .

## 1. Introduction

Consider the Bochner-Riesz multipliers $S^{\delta} = (1 - |D|^2)_+^{\delta}$ in dimension $n \geq 2$ . It is conjectured that, for $1 \leq p \leq 2n/(n+1)$ , these operators are of strong-type (p,p) precisely when $\delta > \delta(p) = n(1/p - 1/2) - 1/2$ . Progress on this conjecture can be found in \[7\], \[2\], \[1\]; it remains open for n \> 2 and p close to 2n/(n+1).

A natural strengthening of the above conjecture is the claim that $S^{\delta(p)}$ is of weak-type (p,p) whenever $1 \le p < 2n/(n+1)$ . (The necessity of the condition on p was shown in \[8\]). In the special n=2 case the full conjecture has been proven by Seeger \[12\]. In general dimension the conjecture was proven by Christ \[5\], \[4\] for any $p < p_0$ , where $p_0$ is such that there is a $(p_0, 2)$ restriction theorem for the sphere in $\mathbb{R}^n$ . Thus, by the well-known restriction theorem of Tomas and Stein, the conjecture is true for p \< 2(n+1)/(n+3).

Our first result is that the conjecture also holds at the endpoint p = 2(n+1)/(n+3).

**Theorem 1.1.** Suppose there is a (p,2) restriction theorem for the sphere in $\mathbb{R}^n$ . Then the operator $S^{\delta(p)}$ is of weak-type (p,p).

In fact, under the restriction theorem hypothesis we have the stronger estimate

(1) $$\int_{M_p f(x) \le \alpha} |S^{\delta(p)} f(x)|^2 dx \le C \alpha^{2-p} ||f||_p^p;$$

here $M_p f = M(|f|^p)^{1/p}$ and M is the Hardy-Littlewood maximal function.

We also show the analogous result for Riesz means on compact manifolds. More precisely, suppose P is a first-order self-adjoint elliptic pseudo-differential operator with nonnegative eigenvalues on a smooth compact manifold M. We say that there is a (discrete) (p,2) restriction theorem for P if $\|\chi_{[k,k+1]}(P)\|_{(p,2)} \leq C(1+k)^{\delta(p)}$ for all k\>0, and consider the Riesz means $S_R^{\delta}=(1-\frac{P}{R})_+^{\delta}$ , defined for $R,\delta>0$ . In Sogge \[14\] it is shown that, if there is a (p,2) restriction theorem for P, then $S_R^{\delta}$ is of strong type (p,p) uniformly in R, for $\delta>\delta(p)$ . Also, it was shown by Christ

©1996 American Mathematical Society

Received by the editors March 14, 1995.

<sup>1991</sup> Mathematics Subject Classification. Primary 42B15.

<sup>&</sup>lt;sup\>1</sup>Our notation will be explained more fully in subsequent sections.

2798 TERENCE TAO

and Sogge \[6\] that $S_R^{\delta(1)}$ is weak (1,1) uniformly in R for any P. Combining ideas from these results with the methods of \[4\], it was shown by Seeger \[11\] that $S^{\delta(p)}$ was weak (p,p) uniformly in R for $p < p_0$ , if one has a $(p_0,2)$ restriction theorem for P.

By modifying the proof of Theorem 1.1, we have an endpoint version of the result in \[11\].

**Theorem 1.2.** Suppose there is a (p,2) restriction theorem for P. Then the operators $S_R^{\delta(p)}$ are of weak-type (p,p) uniformly in R.

As in the Euclidean case, we have the stronger estimate

(2) $$\int_{M_{p}f(x)<\alpha} |S_{R}^{\delta(p)}f(x)|^{2} dx \leq C\alpha^{2-p} ||f||_{p}^{p}$$

holding uniformly in R. (The bound C depends on the balls used to define $M_p$ ).

It is known that the (1,2) restriction theorem holds for any P. Furthermore, under an additional curvature assumption, one has a (p,2) restriction theorem for all $1 \le p \le 2(n+1)/(n+3)$ . See \[13\],\[15\],\[16\]. Combining these results with (2) and interpolating with the trivial case $\delta \ge 0$ , p=2, one has a corollary:

Corollary 1.3. Suppose P is such that the co-spheres $\{\xi \in T_x^*M \setminus 0 : p(x,\xi) = 1\}$ have everywhere non-vanishing Gaussian curvature for each $x \in M$ . Then the operators $S_R^{\delta}$ are of weak-type (p,p) uniformly in R when $1 \leq p \leq 2$ and $\delta \geq \max(\delta(p), \frac{n-1}{2}(\frac{1}{p} - \frac{1}{2}))$ .

The method of proof of Theorems 1.1 and 1.2 is a modification of that used by Christ \[4\], which involved $L^2$ Calderón-Zygmund techniques (as used in \[7\]), a dyadic decomposition of the Bochner-Riesz multiplier with special properties, and the Cauchy-Schwarz inequality. Our main innovations are the replacement of the dyadic decomposition with a decomposition into two terms (which depend on the level of resolution), and a greater reliance on a certain "locality" principle. In the Euclidean case the principle is the trivial observation that if a multiplier m has its inverse Fourier transform supported on a set of width R, then the operator m(D) is local at the scale<sup>2</sup> of R. On compact manifolds the corresponding principle is that if a function m on $\mathbb R$ has its Fourier transform supported on an interval of width R, then the operator m(P) is—apart from an error with good decay—local at the scale of R.

### 2. Proof of Theorem 1.1

If I is a cube, we denote its side-length by l(I), and for any c\>1, cI will denote the cube with the same center but with side-length cl(I). If E is a set, \|E\| will denote the Lebesgue measure of E. If m is a function on $\mathbb{R}^n$ , we will denote by m(D) the operator corresponding to the multiplier m, thus $(\widehat{m(D)f})(\xi) = m(\xi)\widehat{f}(\xi)$ . We use the letter C to stand for various (large) constants.

Fix $n \geq 2$ , and assume that $1 \leq p < 2$ is such that a (p,2) restriction theorem holds for the sphere. Write $S^{\delta} = m^{\delta}(D)$ , where $m^{\delta}(\xi) = (1 - |\xi|^2)^{\delta}_+$ and $\delta = \delta(p) = n(1/p - 1/2) - 1/2$ . We have to show that $m^{\delta}(D)$ is of weak-type (p,p). Since $M_p$ is

<sup>&</sup>lt;sup\>2</sup>By this we mean that the kernel of the operator is supported in a CR-neighbourhood of the diagonal of $\mathbb{R}^n \times \mathbb{R}^n$ .

of weak-type (p, p), it suffices by Tchebyshev's inequality to prove (1). By linearity we may assume that a = C-1 for some large C to be determined later.

Fix f, and apply the dyadic Calderon-Zygmund decomposition at height C to If fP. This allows us to write f = g + \>ZI bj, where IIfgII \< C, the bj are supported on disjoint dyadic cubes I and satisfy llbillp - II'1/P, and the I are such that \>j III \< Cllf lP. Note that Mpf(x) \> C-1 whenever x E UI CI.

Since m6 is bounded, the contribution of g to (1) is acceptable. In fact, as m6 is also compactly supported, we may similarly dispose of the contribution of the small cubes.3 Specifically, let g be g + El1(I)\<1 bi and choose a Gaussian P that majorizes m6. Then the contribution of g is majorized by llP(D)?lI1. But the kernel of P(D) is positive, integrable, and radial decreasing, so we have IIP(D)IIlp \< CIIgIlp and llP(D)g1K \< C. Thus llP(D)?Il12 \< CII?IP \< ClIfllP, which is acceptable.

Define bi to be El(I)=2i bI for each i \> 0. From the above reductions, it suffices to show that

(3) $$\int_{\mathbb{R}^n - \bigcup_I CI} |\sum_{i=1}^{\infty} m^{\delta}(D) b_i(x)|^2 dx \le C \sum_I |I|$$

to finish the proof. To estimate this expression we make a decomposition of the mul tiplier m6 for each integer i \> 0, whose properties are summarized in the following lemma:

Lemma 2.1. For each i \> 0, there exists a decomposition m6 = mi + 7rhni such that:

-   

    (i) The inverse Fourier transforms of mi and ni are supported in the ball of radius 2i around the origin.

-   

    (ii) For all E RIRn we have \> 11 Im(()l2 \< C.

-   

    (iii) For a certain large N, we have In(I) \< C2-62(1 + 21 \| -161 1) -N.

Before we prove this rather technical lemma, let us see how it implies (3). Write m6(D)bi as mi(D)bi+7qi(D)ni(D)bi. By (i), the operator mi(D) is local at the scale of 2i, so mi(D)bi is supported on Ul(I)=2i CI and makes no contribution to (3). Thus it suffices to prove I\> r,1(D)ni (D)bi 112 \< C EI Il. However, from (ii), Plancherel's formula, and the Cauchy-Schwarz inequality we see that this expression is bounded by CZ\> jjni(D)bi112. So it will suffice to show that

$$||n_i(D)b_i||_2^2 = ||\sum_{l(I)=2^i} n_i(D)b_I||_2^2 \le C \sum_{l(I)=2^i} |I|$$

for each i \> 0. However, by (i) the operator ni(D) is local at the scale of 2i, so the individual ni(D)bj have almost disjoint support. Thus we only need prove the above estimate for a single cube. But by Plancherel's formula, (iii), a change to

<sup>3</sup>This can be thought of as a dual to the more well-known principle that, if the kernel has compact support, then the large cubes can be safely discarded.

polar co-ordinates, and the restriction theorem, we have

$$\begin{split} \|n_i(D)b_I\|_2^2 &= \int_{\mathbb{R}^n} |n_i(\xi)|^2 |\hat{b}_I(\xi)|^2 \ d\xi \\ &\leq C \int_0^\infty 2^{-2\delta(p)i} (1+2^i|1-r|)^{-2N} \int_S |\hat{b}_I(r\theta)|^2 \ d\theta \ r^{n-1} dr \\ &\leq C 2^{-2\delta(p)i} \int_0^\infty (1+2^i|1-r|)^{-2N} r^{-2n/p'} \|b_I\|_p^2 \ r^{n-1} dr \\ &\leq C 2^{-2\delta(p)i} 2^{-i} |I|^{2/p} \\ &= C|I|, \end{split}$$

as desired, if N is chosen to be sufficiently large.

It remains only to prove Lemma 2.1. Following \[4\], we start by choosing a smooth radial function 0 supported on the unit ball and equal to 1 on the half-unit ball, such that 4Rn ?() ( el )6 d\< = 0 for some unit vector el. Write 02i = and set ma equal to ma \* 6 2?. Thus m, obeys (i). Fturthermore, since b2i is an approximation to the identity of "thickness" 2-i, one has by repeated integration by parts that

(4) $$|m^{\delta}(\xi) - m_i(\xi)| \le C_N 2^{-\delta i} \left( 2^i |1 - |\xi| | \right)^{-N}$$

for I1 - I \> 2- and all N \> 0. When I1- - \< 2-i, we claim that the additional estimate

(5) $$|m^{\delta}(\xi) - m_i(\xi)| \le C2^{-\delta i} \left( 2^{-i} + 2^i |1 - |\xi|| \right)^{\delta}$$

holds, where E = min(6, 1) \> 0. Since (5) holds for m6(Q), it suffices to prove the corresponding estimate for m2(i). However, by differentiating under the integral sign one can see that the gradient of m (Q) is 0(2i2-6i) in the region of interest, so it suffices to prove (5) for ( on the unit sphere. Since mi is radial, it suffices to prove it for ( = el. But this follows by approximating m6(el -() by 26((,el)6 and using the assumed moment condition for b.

The next step will be to construct a positive function ni that obeys (i) and such that

$$C^{-1}2^{-\delta i}(1+2^{i}|1-|\xi||)^{-M} \le n_i(\xi) \le C2^{-\delta i}(1+2^{i}|1-|\xi||)^{-N}$$

for some large M, N, which we reserve the right to choose later. Once we do this, it can easily be seen from (4), (5), and the above estimates that the function 1n = (im6 - mi)/n. satisfies (ii), and so all the required properties will hold.

We begin by choosing some large even integer N and considering the one dimensional function o() = (sin)N/2. By taking the tensor product of n copies of 0, averaging over the orthogonal group and then rescaling, we can construct a function 'On on Rn which is positive and comparable to (1 + I ) - N - n+ 1, and whose inverse Fourier transform is supported on the unit ball. It is then a routine matter to check that the function ni = 2 62( 1)iUn(2"-) \* dO satisfies all the required properties, with M = N + n - 1; here dO is surface measure on the unit sphere. This completes the proof of Lemma 2.1, and the theorem follows. O

Remarks 2.2. 1. The method of proof of Theorem 1.1, in particular the construction of mi and the use of the Cauchy-Schwarz inequality, is essentially due to Christ \[4\]. However, a slightly different decomposition is used in \[4\]; in our notation, it would be m6 = mi + Zc%(mi+s+l - m2+5), where the individual mi+s+l - mi+s play much the same role in \[4\] as the function m -mi = rhini does here.

-   

    2.  This method can provide alternate proofs of the weak (1,1) type of various "rough" convolution operators. For example, the weak boundedness of S(n-1)/2 follows immediately from Theorem 1.1, as the (1, 2) restriction theorem is trivial. Another example is the one-dimensional operator fF-\* f \* ei7rx2 /x. The multiplier, which is roughly e-i2 /(, can be decomposed for each i \> 0 as mi + rrinz, where (i) \[for mi only\] and (ii) of Lemma 2.1 holds and ni(2) = 2-i(1 + 2\`ifI)1'+E. We omit the details.

-   

    3.  By interpolation, (1) will hold with b(p) replaced by 6, for 1 \< p \< 2 and 6 \> max(b(p), ' j 1 (- -)). Simple calculations involving bump functions on small balls or on thin tubes show that this region is best possible. In the interior of this region (1) also follows from the weighted inequality

(6) $$\int_{\mathbb{R}^n} |S^{\delta}g(x)|^2 \psi(x) \ dx \le C \int_{\mathbb{R}^n} |g|^2 M_r \psi(x) \ dx$$

proven by Christ \[3\]; here r = p/(2 - p) and 4' is any positive function. Indeed, the adjoint of (6) is fR I s6 f (J dx \< C04 n dx, which yields (1) after substituting 4' = If 12-P and using Tchebyshev's inequality. Unfortunately (6) fails for endpoint values of 6, as the bump function examples will show.

## 3. INTERMEZZO: A LOCALITY PRINCIPLE FOR FUNCTIONS OF ELLIPTIC PSEUDO-DIFFERENTIAL OPERATORS

Let M be a smooth compact connected manifold without boundary of dimension n \> 1, endowed with a smooth positive measure dx. It will be convenient to fix a smooth global Riemannian metric d(x, y) on M.

Let P = P(x, D) be a fixed first-order elliptic self-adjoint pseudo-differential operator on M. By elliptic we mean that the principal symbol

$$p(x,\xi) = \lim_{\lambda \to \infty} \lambda^{-1} P(x,\lambda\xi)$$

of P exists and is positive for non-zero elements ( of the cotangent space Tx M.

It can be shown that the spectrum of P is discrete. In particular, there exists a sequence of eigenvalues Aj tending to infinity and a sequence of mutually orthogonal rank one projections ej: L- L2, such that I = \_c- e3 and P = E \>l Aje (on smooth functions at least). Since the eigenvectors of P must belong to every Sobolev space, each projection ej must be smoothing, i.e. have a kernel that is in CO (M x M) . We will assume without loss of generality that the Aj are nonnegative.

We impose the obvious functional calculus for P, defining

$$m(P)f = \sum_{j=1}^{\infty} m(\lambda_j)e_j(f)$$

for tempered m and smooth f. We will also use m(P) to denote the (distributional) kernel of the above operator; thus m(P)f(x) = fMm(P)(x,y)f(y) dy. The main purpose of this section is to relate the "locality" (i.e. decay) properties of m(P) (x, y) to those of mh.

2802 TERENCE TAO

**Proposition 3.1.** Suppose m is a function of $\mathbb{R}$ such that $\hat{m}$ is supported on $[-\tau, \tau]$ for some sufficiently small $\tau$ . Then

-   

    (i) One has $|m(P)(x,y)| \le C ||\hat{m}||_1 \tau d(x,y)^{-n-1}$ whenever $d(x,y) > C\tau$ .

-   

    (ii) If in addition $m(\tau \cdot)$ is in $S^{-\infty}$ , then $|m(P)(x,y)| \leq C\tau^{-n}(1+\frac{d(x,y)}{\tau})^{-n-1}$ for all x, y.

Part (i) is a slightly stronger version of a result proved in \[6\]. The key idea is to exploit the fact that $e^{itP}$ is local when t=0. Further improvements in the decay estimates (including asymptotics), as well as the relaxation of various hypotheses, are possible using variants of these ideas, together with some ideas of \[11\]. We will not pursue these matters here.

*Proof.* We first prove (i). By convexity we may assume that m(P) is of the form $e^{itP}$ . But $e^{itP} = I + \int_0^t \frac{d}{ds} e^{isP} ds$ , so it suffices to show that $|\frac{d}{dt} e^{itP}(x,y)| \leq Cd(x,y)^{-n-1}$ when d(x,y)/t is large.

To do this we shall apply a well-known approximation of $e^{itP}$ by a Fourier integral operator. Specifically, if $\epsilon > 0$ is sufficiently small, the (distributional) kernel of $e^{itP}$ can be written for $|t| \le \epsilon$ in the form

(7) $$e^{itP}(x,y) = \eta_{\epsilon}(x,y) \int_{T_y^*M} e^{i\phi(x,y,\xi)} e^{itp(y,\xi)} q(t,x,y,\xi) d\xi + E_{\epsilon}(t,x,y),$$

where $\eta_{\epsilon}(x,y)$ is supported on a $C\epsilon$ -neighbourhood of the diagonal of $M\times M$ , $\phi(x,y,\xi)$ is a smooth real function such that $|\nabla_{\xi}\phi|\geq C^{-1}d(x,y)$ and $|\nabla_{\xi}^k\phi|\leq C_kd(x,y)|\xi|^{1-k}$ for small d(x,y) and $k\geq 1$ , $q(t,x,y,\xi)$ is an $S^0$ symbol in $\xi$ , and $E_{\epsilon}(t,x,y)$ is a $C^{\infty}$ error. One obtains (7) from a construction, originally due to Hörmander, of a local parametrix for the Cauchy problem for P. Details can be found in \[10\], \[16\].

If d(x,y)/t is sufficiently large and $\epsilon$ is sufficiently small, then the phase $\Psi(t,x,y,\xi)=\phi(x,y,\xi)+tp(y,\xi)$ will satisfy the same sort of bounds as $\phi$ on the support of $\eta_{\epsilon}$ . If we then differentiate (7), we obtain

$$\frac{d}{dt}e^{itP}(x,y) = \eta_{\epsilon}(x,y) \int e^{i\Psi} \left[\frac{d}{dt}q(t,x,y,\xi) + p(y,\xi)q(t,x,y,\xi)\right] d\xi + \frac{d}{dt}E_{\epsilon}(t,x,y).$$

The term $\frac{d}{dt}E_{\epsilon}(t,x,y)$ is O(1) and can be discarded. Since the integrand is $O(1+|\xi|)$ , the integral on the region $\{|\xi| \leq d(x,y)^{-1}\}$ is $O(d(x,y)^{-n-1})$ and can also be discarded. Outside of this region, the term in brackets is—after a suitable rescaling by d(x,y)—a symbol of order 1, and so this part of the integral is also $O(d(x,y)^{-n-1})$ , by the standard estimates on non-stationary oscillatory integrals. Thus one has the desired bound on $\frac{d}{dt}e^{itP}(x,y)$ , which proves (i).

To show (ii), it suffices by (i) to prove $|m(P)(x,y)| \leq C\tau^{-n}$ . From (7) we have

$$m(P)(x,y) = \eta_{\epsilon}(x,y) \int e^{i\phi(x,y,\xi)} \left( \int e^{itp(y,\xi)} q(t,x,y,\xi) \hat{m}(t) \ dt \right) \ d\xi + O(1).$$

But by the standard manipulations on symbols and the fact that $p(y,\xi) \sim |\xi|$ , the inner integral will be $O_N(1+\tau|\xi|)^{-N}$ for all N\>0. Taking N\>n thus gives the result.

We now show that operators with the decay of 3.1(i) are effectively local in a specialized $L^p$ sense.

**Proposition 3.2.** Let $\{I\}$ be a collection of disjoint, sufficiently small "cubes" in M. Suppose that for each I there is a function $b_I$ supported on I and a function $m_I$ whose Fourier transform is supported on \[-l(I), l(I)\] such that $||b_I||_1 \leq C|I|$ and $||\hat{m}_I||_1 \leq C$ . Then, for $1 \leq p < \infty$ , one has

$$\|\sum_{I} (m_{I}(P)b_{I})\chi_{CI^{c}}\|_{p}^{p} \leq C_{p}\sum_{I} |I|.$$

In particular, if the CI are almost disjoint, then

$$\|\sum_{I} m_{I}(P)b_{I}\|_{p}^{p} \leq C_{p} (\sum_{I} \|m_{I}(P)b_{I}\|_{p}^{p} + \sum_{I} |I|).$$

*Proof.* It suffices to prove the first inequality. By Proposition 3.1(i) and elementary estimates, we see that $|m_I(P)b_I(x)\chi_{CI^c}(x)| \leq C(M\chi_I(x))^q$ , where q = 1 + 1/n \> 1. Thus

$$\| \sum_{I} (m_{I}(P)b_{I}) \chi_{CI^{c}} \|_{p}^{p} \leq C \| \left( \sum_{I} (M\chi_{I})^{q} \right)^{1/q} \|_{pq}^{pq}$$

$$\leq C_{p} \| \left( \sum_{I} (\chi_{I})^{q} \right)^{1/q} \|_{pq}^{pq} = C_{p} \sum_{I} |I|$$

as desired, where we have used the vector-valued maximal theorem of Fefferman and Stein \[9\]. (It is a routine matter to adapt the theorem in \[9\] to general manifolds.)

#### 4. Proof of Theorem 1.2

Let $1 \leq p < 2$ be such that there is a (p,2) restriction theorem for P. We wish to show that $S_R^{\delta}$ is of weak type (p,p) uniformly in R, where $\delta = \delta(p)$ . Since the proof is almost identical to that of Theorem 1.1 except for a rescaling and some minor technical complications, we give only a brief sketch.

We first note that, since each projection operator is smoothing, the claim is clearly true when R is bounded. Thus we may assume that R \> C for some large C to be determined later.

Secondly, since the eigenvalues of P are nonnegative, we may write $S_R^{\delta} = m_R^{\delta}(P)$ , where $m_R^{\delta}(\lambda) = \zeta(\lambda/R)(1-\lambda/R)_+^{\delta}$ and $\zeta$ is smooth, compactly supported, and equal to 1 on \[0,1\]. Note that $\|\hat{m}_R^{\delta}\|_1 = O(1)$ .

Fix f. It suffices to show that (2) holds for $\alpha = C^{-1}$ . We may assume that f is supported on an arbitrarily small subset of M, which we can identify with a subset of $\mathbb{R}^n$ . We then decompose $f = g + \sum_I b_I$ as before except that we use a rescaled dyadic mesh, so that the cubes have sidelength $2^i/R$ instead of $2^i$ .

Since $m_R^{\delta}$ is bounded and supported in \[-CR, CR\], we may dispose of the contributions of g and the cubes of sidelength at most 1/R. Instead of a Gaussian, one uses an $S^{-\infty}$ symbol $\psi$ on $\mathbb R$ such that $\hat{\psi}$ is supported on \[-C, C\] and $\psi_R = \psi(R^{-1})$ majorizes $m_R^{\delta}$ . By Proposition 3.1(ii), the kernel of $\psi_R(P)$ is majorized by a constant multiple of a positive and "radial decreasing" approximation to the identity of "thickness" 1/R, and one can use the argument in the proof of Theorem 1.1.

The appropriate analogue of Lemma 2.1 is the following decomposition of $m_R^{\delta}$ :

**Lemma 4.1.** For each i \> 0, there exists a decomposition $m_R^{\delta} = m_i + \eta_i n_i$ such that:

(i) The functions $\hat{m}_i$ and $\hat{n}_i$ are supported on $[-2^i/R, 2^i/R]$ , and each have an $L^1$ norm which is O(1).

which is O(1).

This content downloaded from 130.160.57.1 on Wed, 31 Dec 2025 19:17:49 UTC All use subject to https://about.jstor.org/terms

-   

    (ii) For all $\lambda \in \mathbb{R}$ , we have $\sum_{i=1}^{\infty} |\eta_i(\lambda)|^2 \leq C$ .

-   

    (iii) For a certain large N, we have the estimate

$$|n_i(\lambda)| \le C2^{-\delta i} \left(1 + 2^i |1 - \lambda/R|\right)^{-N}.$$

Apart from the last part of (i), Lemma 4.1 is proved in exactly the same way as Lemma 2.1. Since $\hat{m}_i$ is by construction the product of $\hat{m}_R^{\delta}$ and a bounded expression, we see that the $L^1$ norm of $\hat{m}_i$ is O(1). To prove the corresponding bound for $\hat{n}_i$ , use (iii) to observe that $\hat{n}_i$ is uniformly bounded by $O(2^{-\delta i}2^{-i}R)$ , and so the $L^1$ norm is $O(2^{-\delta i}) = O(1)$ , as desired.

The rest of the argument, deducing (2) from the above decomposition, the Cauchy-Schwarz inequality, and the restriction theorem, is virtually unchanged, apart from a rescaling by R. There are only two technical differences: firstly, as the restriction theorem is now discrete, one replaces a certain integral by its Riemann sum instead; and secondly, because the analogous "locality" principle (i.e. Proposition 3.2 for p=2 combined with Lemma 4.1(i)) is not absolute, one incurs further error terms which are $O(\sum_I |I|)$ , but these errors are acceptable in proving (2). We omit the details.

#### ACKNOWLEDGMENT

The author thanks E. Stein and C. Feffermann for their patience and time, and also for several observations which eventually led to substantial simplifications in this paper.

#### REFERENCES

-   J. Bourgain, Besicovitch-type maximal operators and applications to Fourier analysis, Geom. and Funct. Anal. 22 (1991), 147-187. MR 92g:42010
-   L. Carleson and P. Sjölin, Oscillatory integrals and a multiplier problem for the disc, Studia Math. 44 (1972): 287–299. MR 50:14052
-   
    3.  M. Christ, On almost-everywhere convergence of Bochner-Riesz means in higher dimensions, Proc. Amer. Math. Soc. 95 (1985): 16–20. MR 87c:42020
-   Weak type endpoint bounds for Bochner-Riesz multipliers, Revista Mat. Iberoamericana 3 (1987), 25–31. MR 90i:42024
-   
    5.  \_\_\_\_\_, Weak type (1,1) bounds for rough operators, Annals of Mathematics, 128 (1988): 19-42. MR 89m:42013
-   M. Christ and C. D. Sogge, The weak-type L<sup>1</sup> convergence of eigenfunction expansions for pseudo-differential operators, Invent. Math. 94 (1988): 421-453. MR 89j:35096
-   C. Feffermann, Inequalities for strongly singular convolution operators, Acta Math. 124 (1970), 9-36. MR 41:2468
-   
    8.  \_\_\_\_\_, The multiplier problem for the ball, Ann. of Math. 94 (1971): 330-336. MR 45:5661
-   C. Feffermann and E. M. Stein, Some maximal inequalities, Amer. J. Math. 93 (1971): 107– 115. MR 44:2026
-   L. Hörmander, The spectral function of an elliptic operator, Acta Math. 121 (1968), 193–218. MR 58:29418
-   A. Seeger, Endpoint estimates for multiplier transformations on compact manifolds, Indiana Math. J. 40 (1991): 471-533. MR 92f:58166
-   Endpoint inequalities for Bochner-Riesz multipliers in the plane, to appear, Pacific J. Math.
-   A. Seeger and C. D. Sogge, On the boundedness of functions of (pseudo)-differential operators on compact manifolds, Duke Math. J. 59 (1989): 709-736. MR 91d:58244
-   C. D. Sogge, On the convergence of Riesz means on compact manifolds, Annals of Math. 126 (1987), 439-447. MR 89b:35126

| 15\. , Concerning the LP norm of spectral clusters for second-order elliptic operators on |
|------------------------------------------------------------------------|
| compact manifolds, J. Funct. Anal. 77 (1988): 123-138. MR 89d:35131 |
| 16\. , Fourier Integrals in Classical Analysis, Cambridge Tracts in Math. \# 105, Cambridge |
| Univ. Press, 1993. MR 94c:35178 |

DEPARTMENT OF MATHEMATICS, PRINCETON UNIVERSITY, PRINCETON, NEW JERSEY 08544 E-mail address: taofmath. princeton. edu