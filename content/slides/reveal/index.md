---
title: FMI | Capital Theory
summary: FMI Graduate Workshop
authors: [Nicolas Cachanosky]
tags: []
categories: []
date: "2019-02-05T00:00:00Z"
slides:
  theme: white
  highlight_style: github
  reveal_options:
    hash: true,
    slide_number: c/t,
--- 
<!-- COVER SLIDE -->
{{< slide background-color="#00447c" >}}

# FMI GRADUATE SEMINAR

## CAPITAL THEORY

**Nicolás Cachanosky**  
Metropolitan State University of Denver  
ncachano@msudenver.edu

---
<!-- SLIDE 1 -->
<div class="head_1"><p data-markdown>
## Agenda
</p></div>

<div class="text"><p data-markdown>
1. A history of roadblocks
2. Finance: A way out
3. The production function
3. Extension 1: ABCT
4. Extension 2: Reswitching
6. Extension 3: Financial microfoundations
7. Discussion: Future areas of research
</p></div>

---
<!-- SLIDE 2 -->
{{< slide background-color="#717073" >}}
## A history of roadblocks

---
<!-- SLIDE 3 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
**MENGER**
</p></div>

<div class="text"><p data-markdown>
Sets the stage: *Earlier* and *later* production goods

* Consumption goods are produced by goods of various "orders"
  * Higher order goods are transformed into lower order goods
* Structure of production
  * How to sequently order the use of production goods [<span class="red">period of production</span>]
  * How to combine different production goods [<span class="red">heterogeneity</span>]
</p></div>

---
<!-- SLIDE 4 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
**MENGER**
</p></div>

<div class="text"><p data-markdown>
* Economic progress
  * A "lenghtening" of the period of production
  * More time and more complexity
* Remember:
  * Theory of subjective (marginal) value
  * The cost of production is determined by the price of the final goods
</p></div>

---
<!-- SLIDE 5 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | **BÖHM-BAWERK**
</p></div>

<div class="text"><p data-markdown>
Builds on Menger
* Roundaboutness
  * How **long** and **complex** a production process is
  * More *roundabout* processes are chosen *only if* the output value is at least equal to the extra roundaboutness
* But... once a new technology is in place, production takes **less** time
  * Similar to highways in a city
  * Is then the **period of production** *forward* or *backward* looking?
</p></div>

---
<!-- SLIDE 6 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | **BÖHM-BAWERK**
</p></div>

<div class="text"><p data-markdown>
The average period of production

$$
\begin{align}
APP &= \sum_{t=1}^{n} [\omega_t \cdot (n-t)] \\\\[10pt]
APP &= \sum_{t=1}^{n} \left[ \frac{l_t}{\sum l_t} \cdot (n-t) \right] \\\\[10pt]
 l_t &\geq 0 \rightarrow \omega \in (0,1), \sum \omega = 1
\end{align}
$$

---
<!-- SLIDE 7 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | **BÖHM-BAWERK**
</p></div>

<div class="text"><p data-markdown>
The average period of production: Problems

* Objective measure of labor
  * Did Böhm-Bawerk became a marxist?
* Simple (rather than compounding) interest rate
* Why lower stages carry more weight than higher stages?
* There is no market (subjective) value
* APP is *backward* looking
  * APP is either infinite or arbitrary
</p></div>

---
<!-- SLIDE 8 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | **HAYEK**
</p></div>

<div class="text"><p data-markdown>
Builds on Böhm-Bawerk

* Hayekian triangle: Context
  * Pedagogical tool
  * Not for academic research
* Hayekian triangle: Improvement over Böhm-Bawerk
  * Horizontal-axis: Time-value
  * Vertical-axis: Market value

</p></div>

---
<!-- SLIDE 9 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | **HAYEK**
</p></div>

<div class="text"><p data-markdown>

{{< figure src="Fig_HayekianTriangle.png" id="wowchemy" >}}

</p></div>

---
<!-- SLIDE 10 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | **HAYEK**
</p></div>

<div class="text"><p data-markdown>
Remaining issues

* Stages of production do not exist, they are subjective
* Looping
* Simple (not componding) interest rate
* Backward looking
* Change of focus: From APP to stages of production

</p></div>

---
<!-- SLIDE 11 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | **HAYEK**
</p></div>

<div class="text"><p data-markdown>
A better Hayekian triangle (for empirical research)

{{< figure src="Fig_HayekianTriangle_2.png" id="wowchemy" >}}

</p></div>

---
<!-- SLIDE 12 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | **HAYEK**
</p></div>

<div class="text"><p data-markdown>
[Hayek (1941, pp. 3-4, see also pp. 92-93)](https://mises.org/library/pure-theory-capital-0) gives up on the APP

<blockquote><p data-markdown>
I had little idea […] that some of the simplifications employed by the earlier writers had such far-reaching consequences as to make their conceptual tools almost useless in the analysis of more complicated situations. The most important of these **inappropriate** simplifications […] was the attempt to **introduce the time factor** into the theory of capital in the form of one single relevant time interval—the ‘average period of production.’
</p></blockquote>

</p></div>

---
<!-- SLIDE 13 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | **HAYEK**
</p></div>

<div class="text"><p data-markdown>

If APP is not possible... then what?

</p></div>

---
<!-- SLIDE 14 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | **LACHMANN**
</p></div>

<div class="text"><p data-markdown>

Focus on capital **heterogeneity**

* Capital: The order in which heterogeneous goods are combined to produce specific goods
  * Capital goods are neither perfect substitutes nor perfect complements
  * Capital structure is revised as entrepreneurs think of new ways to produce goods (new -more complex- combinations)
* Capital (good) is **subjective**

</p></div>

---
<!-- SLIDE 15 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | **LACHMANN**
</p></div>

<div class="text"><p data-markdown>

If you take capital heterogeneity seriously

* Aggregation is impossible
  * Capital is heterogeneous
  * Capital is subjetive 
  * Capital goods can have different degrees of specifity
  * The market is like a kaleidoscope (complex figures are seen different by different actors)
* Technology
  * Capital accumulation leads to technological change
</p></div>

---
<!-- SLIDE 16 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | **LACHMANN**
</p></div>

<div class="text"><p data-markdown>

Capital heterogeneity vs formal economics

* For the kind of mathematics used in econoimcs, **homogeneous** capital is *easy* and *convenient*
* To model capital heterogenity increases the complexity of the model
* Capital heterogeneity was set aside and mathematical tractability took priority
</p></div>

---
<!-- SLIDE 17 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | **LACHMANN**
</p></div>

<div class="text"><p data-markdown>

Now what?

* Capital $\rightarrow$ roundaboutness
* Roundaboutness
  * Period of production: {{< icon name="ban" pack="fas" >}} <span class="red">roadblock!</span>
  * Heterogeneity: {{< icon name="ban" pack="fas" >}} <span class="red">roadblock!</span>

---
<!-- SLIDE 18 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | **MISES**
</p></div>

<div class="text"><p data-markdown>

Go back to the basics

* What is capital?
  * **View 1**: Physical goods, or tools? - *Adam Smith*
  * **View 2**: Market value of all productive assets of whatever type, form, or shape - *Mises*
* Aggregation
  * View 1: Needs to assume homogeneity
  * View 2: A money-value construct (financial capital)

---
<!-- SLIDE 19 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | **MISES**
</p></div>

<div class="text"><p data-markdown>
Some word... different meaning...

* Production function: What is $K$?
  * (1) $Q = \cdot F(A, K, N)$
* Economic profits of the firm: What is $K$?
  * (2) $\pi = PQ - wN - rK$
* Insert (1) into (2): What is $K$?
  * $\pi = P \cdot F(A, K, N) - wN - rK$

---
<!-- SLIDE 20 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | **MISES**
</p></div>

<div class="text"><p data-markdown>
Financial capital depends on historical and institutional context

* Economic calculation under socialism: $K$ does not exist
  * $\underbrace{\pi}\_{\nexists} = pq - wN - r\underbrace{K}\_{\nexists}$
</p></div>

---
<!-- SLIDE 21 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | MISES | **HICKS**
</p></div>

<div class="text"><p data-markdown>
The forerunner

* Hicks recognizes the role of time (production takes time)
  * A production process (or technoogy) is a stream of **input** and **outputs** (a cash-flow)
  * Inputs must precede outputs
  * Then, what conditions make a production technology profitable?
</p></div>

---
<!-- SLIDE 22 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | MISES | **HICKS**
</p></div>

<div class="text"><p data-markdown>
The forerunner

* What is the value of capital (CV)?
  * The net-present-value (NPV) of the cash-flow of inputs and outputs discounte at the cost of opportunity of the financial capital employed
  * $NPV>0$ profitable (and the other way around)
</p></div>

---
<!-- SLIDE 23 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | MISES | **HICKS**
</p></div>

<div class="text"><p data-markdown>
Formalization

* Assumptions and definitions
  * Discrete time: $t = 1, ..., T$
  * Inputs: $\varphi_t = \sum_{i} w_{i,t} g_{i,t} \quad (i=1,...,m)$
  * Outputs: $q_t = \sum_{j} \varphi_{j,t} p_{j,t} \quad ( j=1,...,n)$
  * $\pi_t = q_t - \varphi_t$
  * $f = \frac{1}{1+r}; \quad r=\text{discount rate}$
</p></div>

---
<!-- SLIDE 23 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | MISES | **HICKS**
</p></div>

<div class="text"><p data-markdown>
Formalization (cont...)

* Capital value
$$
\begin{align}
CV_0 &= \pi_0 f^0 + f^1 \pi_1 + f^2 \pi_2 = \sum_{t=0}^{\infty} \pi_t f^t \\\\[5pt]
CV_0 &= (q_0 - \varphi_0) + (q_1 - \varphi_1) f + (q_2 - \varphi_2) f^2 + ... \\\\[15pt]
CV_0 &= \pi_0 + CV_1
\end{align}
$$
</p></div>

---
<!-- SLIDE 24 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | MISES | **HICKS**
</p></div>

<div class="text"><p data-markdown>
Implications

* Hick's treatment is *forward-looking*
  * Must use expectations
  * Past-data is *given*, future data is *expected*
* Inverse relationship between $CV$ and $r$
  * Semi-elasticity: $\frac{\Delta CV/CV}{\Delta r} < 0$
  * How? Be an economist, apply the elasticity-operator (1939)
  * Similar and independent than Macaulay duration (1938)

</p></div>

---
<!-- SLIDE 25 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | MISES | **HICKS**
</p></div>

<div class="text"><p data-markdown>
Böhm-Bawerk vs Hicks

| Böhm-Bawerk        | Hicks             |
|      :---:         |       :---:       |
| *backward-looking* | *forward-looking* |
| $APP = \sum\_{t=1}^{n} \left[\frac{l\_t}{\sum\_t l\_t} \cdot (n-t) \right]$ | $APP = \sum\_t = \left[ \frac{f^t \pi\_t}{\sum\_t \pi\_t} \cdot t \right]$

</p></div>

---
<!-- SLIDE 26 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | MISES | **HICKS**
</p></div>

<div class="text"><p data-markdown>
Summary

* Production takes time
*   But, measuring the time involved in a production process has been unsolvable
* Production goods are heterogeneous
  * But, there is no convenient way to incorporate this into formal theory/models
* The default is
  * Production function **without** time
  * What is the interest rate then?
  * The price of capital (one way route to reswitching problems)

</p></div>

---
<!-- SLIDE 27 -->
{{< slide background-color="#717073" >}}
## Finance: A way out