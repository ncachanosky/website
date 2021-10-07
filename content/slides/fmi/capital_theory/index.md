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
<!--  =============================================================================  -->
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
3. ABCT
4. Financial microfoundations
5. Future areas of research
</p></div>

---
<!--  =============================================================================  -->
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
  * A "lengthening" of the period of production
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
  * Similar to a highway in a city
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
APP &= \sum_{t=1}^{n} \left[ \frac{l_t}{\sum l_t} (n-t) \right] \\\\[10pt]
 l_t & \geq 0 \rightarrow \omega \in (0,1), \sum \omega = 1
\end{align}
$$

</p></div>

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
* Simple (not compounding) interest rate
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
  * Capital is subjective 
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

* For the kind of mathematics used in economics, **homogeneous** capital is *easy* and *convenient*
* Modeling capital heterogeneity increases the complexity of the model
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
</p></div>

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
</p></div>

---
<!-- SLIDE 19 -->
<div class="head_1"><p data-markdown>
### A HISTORY OF ROADBLOCKS
</p></div>

<div class="head_2"><p data-markdown>
MENGER | BÖHM-BAWERK | HAYEK | LACHMANN | **MISES**
</p></div>

<div class="text"><p data-markdown>
Some word... different meanings...

* Production function: What is $K$?
  * (1) $Q = F(A, K, N)$
* Economic profits of the firm: What is $K$?
  * (2) $\pi = PQ - wN - rK$
* Insert (1) into (2): What is $K$?
  * $\pi = P \cdot F(A, K, N) - wN - rK$
</p></div>

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
<!-- SLIDE 24 -->
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
<!-- SLIDE 25 -->
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
<!-- SLIDE 26 -->
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
| $APP = \sum\_{t=1}^{n} \left[\frac{l\_t}{\sum\_t l\_t} (n-t) \right]$ | $APP = \sum\_t = \left[ \frac{f^t \pi\_t}{\sum\_t f^t \pi\_t} t \right]$

</p></div>

---
<!-- SLIDE 27 -->
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
<!--  =============================================================================  -->
<!-- SLIDE 28 -->
{{< slide background-color="#717073" >}}
## Finance: A way out

---
<!-- SLIDE 29 -->
<div class="head_1"><p data-markdown>
### FINANCE: A WAY OUT
</p></div>

<div class="head_2"><p data-markdown>
**WHY FINANCE?**
</p></div>

<div class="text"><p data-markdown>
Go back to the beginning

* Put yourself in the shoes of an investor
* Investment decisions are decided based on free-cash-flow (FCF) evaluation
* If a formal model is consistent, then a financial interpretation should predict the same outcome than the theory
* Many business cycles occur through the financial markets, therefore a financial interpretation of business cycles should be useful
</p></div>

---
<!-- SLIDE 30 -->
<div class="head_1"><p data-markdown>
### FINANCE: A WAY OUT
</p></div>

<div class="head_2"><p data-markdown>
WHY FINANCE? | **FCF**
</p></div>

<div class="text"><p data-markdown>
Think like an investor

* Let there be $n$ different projects
* Let $FCF = NOPAT - I$
* The **expected** value of each project in $t=0$ is
  * $CV_0 = \sum_{0}^{T \rightarrow \infty} = \frac{FCF_t}{(1+i)^t}$
* Investment projects are:
  * Forward-looking
  * Measured in (expected) market values
  * Valued at the cost of opportunity
</p></div>

---
<!-- SLIDE 31 -->
<div class="head_1"><p data-markdown>
### FINANCE: A WAY OUT
</p></div>

<div class="head_2"><p data-markdown>
WHY FINANCE? | FCF | **EVA**
</p></div>

<div class="text"><p data-markdown>
Where is the financial capital?

* Let $W$ represent the amount invested in the project
* Then:
  * $CV_0 = \sum_{0}^{T \rightarrow \infty} = \frac{FCF_t}{(1+i)^t}$
  * do some math-magic...
  * $CV_0 = W_0 + \sum_{t=1}^{\infty} \frac{EVA_t}{(1+i)^t}$
  * $CV_0 = W_0 + \sum_{t=1}^{\infty} \frac{(ROIC_{t - i})W_{t-1}}{(1+i)^t}$
  * $CV_0 = W_0 + MVA$
</p></div>

---
<!-- SLIDE 32 -->
<div class="head_1"><p data-markdown>
### FINANCE: A WAY OUT
</p></div>

<div class="head_2"><p data-markdown>
WHY FINANCE? | FCF | **EVA**
</p></div>

<div class="text"><p data-markdown>
APP

* Macaulay duration $(D)$ is the financial equivalent of APP
  * The average time it takes for the cash-flow to produce $1
  * $CV = W_0 + \sum_{t=1}{\infty} \frac{EVA_t}{(1+i)^t}$
  * $D = APP = \frac{\sum_{t=1}^{\infty} \frac{t \cdot EVA_t}{(1+i)^t}}{CV}$
* Modified duration $(MD)$
  * Semi-elasticity of $CV$ with respect to $i$
  * $MD = \frac{D}{1 + YTM}$
* In continuous time
  * $D = MD$
</p></div>

---
<!-- SLIDE 33 -->
<div class="head_1"><p data-markdown>
### FINANCE: A WAY OUT
</p></div>

<div class="head_2"><p data-markdown>
WHY FINANCE? | FCF | **EVA**
</p></div>

<div class="text"><p data-markdown>
APP (cont...)

* What do we know?
  * $D = APP = \frac{\sum_{t=1}^{\infty} \frac{t \cdot EVA_t}{(1+i)^t}}{CV}$
  * $D$ is a **finite** number *even if* $T \rightarrow \infty$. Why?
  * Properties of $D$:
    * Forward-looking
    * A function of market values
    * Has a time variable
    * Has a financial capital variable
</p></div>

---
<!-- SLIDE 34 -->
<div class="head_1"><p data-markdown>
### FINANCE: A WAY OUT
</p></div>

<div class="head_2"><p data-markdown>
WHY FINANCE? | FCF | **EVA**
</p></div>

<div class="text"><p data-markdown>
APP (cont...)

* What do we know? (cont...)
  * Let two projects have same $T$ but different $W$
    * $D_{HR} > D_{LR}$ 
  * Let two projects have same $W$ but different $T$
    * $D_{HR} > D_{LR}$
</p></div>

---
<!-- SLIDE 35 -->
<div class="head_1"><p data-markdown>
### FINANCE: A WAY OUT
</p></div>

<div class="head_2"><p data-markdown>
WHY FINANCE? | FCF | **EVA**
</p></div>

<div class="text"><p data-markdown>
Some implications

* APP
  * Grounded in the well-known and widespread used financial concept of Macaulay duration
* Capital intensity
  * $K/L$ is untenable
  * Capital *intensity* is the size of $W$
</p></div>

---
<!--  =============================================================================  -->
<!-- SLIDE 36 -->
{{< slide background-color="#717073" >}}
## ABCT

---
<!-- SLIDE 37 -->
<div class="head_1"><p data-markdown>
### ABCT
</p></div>

<div class="head_2"><p data-markdown>
FINANCIAL FRAMEWORK
</p></div>

<div class="text"><p data-markdown>
Assumptions

* Let there be two investment projects:
  * HR: High roundabout
  * LR: Low roundabout
* In equilibrium:
  * $PV_{HR} = PV_{LR}$
  * $\frac{PV_{HR}}{PV_{LR}} = 1$
</p></div>

---
<!-- SLIDE 38 -->
<div class="head_1"><p data-markdown>
### ABCT
</p></div>

<div class="head_2"><p data-markdown>
FINANCIAL FRAMEWORK
</p></div>

<div class="text"><p data-markdown>

{{< figure src="Fig_ABCT_1.png" id="wowchemy" >}}

</p></div>

---
<!-- SLIDE 39 -->
<div class="head_1"><p data-markdown>
### ABCT
</p></div>

<div class="head_2"><p data-markdown>
FINANCIAL FRAMEWORK
</p></div>

<div class="text"><p data-markdown>
Important lesson

* ABCT **does not** need to assume Cantillon effects
  * If: Cantillon effects are defined as change in relative prices of goods of any level but not the price of time $(i)$
* Alternative
  * ABCT uses only **one** Cantillon effect
  * The price of time with respect to all other goods and services (of any level)
</p></div>

---
<!-- SLIDE 40 -->
<div class="head_1"><p data-markdown>
### ABCT
</p></div>

<div class="head_2"><p data-markdown>
FINANCIAL FRAMEWORK | **RATIONAL EXPECTATIONS**
</p></div>

<div class="text"><p data-markdown>
Does ABCT survive a rational expectations critique?

* Assume a continuum of investors
* Investors have a normal distribution such that: $i ∼ N(i_N, σ_i)$
* ABCT dynamics are driven by the **marginal** investor, not by the **average** (representative) investor
* Those who think $i_{LOW}$ is the equilibrium value are **willing** and **able** to displace those who think $i_N$ is the correct value
</p></div>

---
<!-- SLIDE 41 -->
<div class="head_1"><p data-markdown>
### ABCT
</p></div>

<div class="head_2"><p data-markdown>
FINANCIAL FRAMEWORK | RATIONAL EXPECTATIONS | **EMPIRICS**
</p></div>

<div class="text"><p data-markdown>
Strategy

* Use the EVA framework
  * Use EVA (perceived profits) and $W$ (net investment) as dependent variables
  * Then:
    * $\frac{\partial \text{EVA}}{\partial i} < 0$
    * $\frac{\partial W}{\partial i} < 0$
  * Variables of interest
    * Short-term interest rate (monetary policy)
    * Long-term interest rate (relevant for investors)
</p></div>

---
<!-- SLIDE 42 -->
<div class="head_1"><p data-markdown>
### ABCT
</p></div>

<div class="head_2"><p data-markdown>
FINANCIAL FRAMEWORK | RATIONAL EXPECTATIONS | **EMPIRICS**
</p></div>

<div class="text"><p data-markdown>
Strategy (cont...)

* Use the EVA framework (cont...)
  * Then, build an econometric model
    * Statistical test on different size of $\beta$ for $i$
    * ARMA(p,q) model
    * IRF from a VAR(p) model
</p></div>

---
<!--  =============================================================================  -->
<!-- SLIDE 43 -->
{{< slide background-color="#717073" >}}
## FINANCIAL MICROFOUNDATIONS

---
<!-- SLIDE 44 -->
<div class="head_1"><p data-markdown>
### FINANCIAL MICROFOUNDATIONS
</p></div>

<div class="head_2"><p data-markdown>
EVA VS FCF
</p></div>

{{< figure src="Fig_EVA_Table.png" width=45% height=45% >}}

---

<!-- SLIDE 45 -->
<div class="head_1"><p data-markdown>
### FINANCIAL MICROFOUNDATIONS
</p></div>

<div class="head_2"><p data-markdown>
EVA VS FCF
</p></div>

<div class="text"><p data-markdown>
Advantages of EVA over FCF

* EVA is a cleaner representation
  * Does not mix investment with operational costs
  * Works with percentages and economic terms
  * Has an explicit variable for (financial) capital
</p></div>

---

<!-- SLIDE 46 -->
<div class="head_1"><p data-markdown>
### FINANCIAL MICROFOUNDATIONS
</p></div>

<div class="head_2"><p data-markdown>
EVA VS FCF | **VALUE DRIVERS**
</p></div>

<div class="text"><p data-markdown>
Go more micro...
$$
\begin{align}
ROIC &= \frac{NOPAT}{w} \\\\[10pt]
ROIC &= \frac{\frac{NOPAT}{TR}×TR}{W} \\\\[10pt]
ROIC &= \frac{\frac{TR - C_1 - … - C_n}{TR}×TR}{W}
\end{align}
$$

</p></div>

---
<!-- SLIDE 47 -->
<div class="head_1"><p data-markdown>
### FINANCIAL MICROFOUNDATIONS
</p></div>

<div class="head_2"><p data-markdown>
EVA VS FCF | **VALUE DRIVERS**
</p></div>

<div class="text"><p data-markdown>
Go more micro...
$$
\begin{align}
ROIC &= \left[ 1 - \frac{C_1}{TR} - … - \frac{C_n}{TR} \right] \frac{TR}{W} \\\\[10pt]
ROIC &= \left[ \left(\frac{Ω_1}{TR} … \frac{Ω_m}{TR} \right) - \left(\frac{C_1}{TR} - … - \frac{C_n}{TR} \right) \right] \\\\[10pt]
ROIC &= \left[ \left( ω_1 + … + ω_m \right) - \left(φ_1 + … + φ_n \right) \right]
\end{align}
$$

</p></div>

---
<!-- SLIDE 48 -->
<div class="head_1"><p data-markdown>
### FINANCIAL MICROFOUNDATIONS
</p></div>

<div class="head_2"><p data-markdown>
EVA VS FCF | **VALUE DRIVERS**
</p></div>

<div class="text"><p data-markdown>
Go more micro...

* You can use the value drivers to capture Cantillon effects
* The value driver gives an estimation of the size of its effect
* Which relative prices are more and which ones are less impactful
</p></div>

---
<!-- SLIDE 49 -->
<div class="head_1"><p data-markdown>
### FINANCIAL MICROFOUNDATIONS
</p></div>

<div class="head_2"><p data-markdown>
EVA VS FCF | VALUE DRIVERS | **EVA VS ECONOMIC PROFITS**
</p></div>

<div class="text"><p data-markdown>
EVA is the financial equivalent of EP

* Assume $w$ is the price of all inputs (labor and others)
* Assume $L$ is the quantity of all inputs (labor and others)
</p></div>

---
<!-- SLIDE 50 -->
<div class="head_1"><p data-markdown>
### FINANCIAL MICROFOUNDATIONS
</p></div>

<div class="head_2"><p data-markdown>
EVA VS FCF | VALUE DRIVERS | **EVA VS ECONOMIC PROFITS**
</p></div>

<div class="text"><p data-markdown>
EVA is the financial equivalent of EP
$$
\begin{align}
π &= pq - wL - iW \\\\[10pt]
π &= \left( \frac{pq - wL}{W} - i \right) W
\end{align}
$$

Then
* $CV = W_0 + ∑\_{t=1}^{\infty} \left(\frac{p_t q_t - w_t L_t }{W_{t-1}} - i_t \right) W\_{t-1}$

</p></div>

---
<!--  =============================================================================  -->
<!-- SLIDE 51 -->
{{< slide background-color="#717073" >}}
## FUTURE AREAS OF RESEARCH



---
<!-- SLIDE 52 -->
<div class="head_1"><p data-markdown>
### FUTURE AREAS OF RESEARCH
</p></div>

<div class="head_2"><p data-markdown>
ALERTNESS
</p></div>

<div class="text"><p data-markdown>
Look at $MVA$

* $CV = W_0 + MVA$
* Can $MVA$ be the financial equivalent of Kirzner's *alertness*?
</p></div>

---
<!-- SLIDE 53 -->
<div class="head_1"><p data-markdown>
### FUTURE AREAS OF RESEARCH
</p></div>

<div class="head_2"><p data-markdown>
ALERTNESS | **MANAGERIAL ECONOMICS**
</p></div>

<div class="text"><p data-markdown>
Look at investment

* Whether an expense is considered a **cost** or an **investment** is subjective
* The value of EVA depends on whether an expense is a cost or an investment
* Therefore, the value $CV$ depends on whether an expense is a cost or an investment
* Two dimensions of subjective value:
  * External: The cash-flow that builds MVA 
  * Internal: Whether an expense is considered a cost or an investment by the investor
</p></div>

---
<!-- SLIDE 54 -->
<div class="head_1"><p data-markdown>
### FUTURE AREAS OF RESEARCH
</p></div>

<div class="head_2"><p data-markdown>
ALERTNESS | MANAGERIAL ECONOMICS | **DEVELOPMENT**
</p></div>

<div class="text"><p data-markdown>
Use EFW as a framework

* Map how changes in each EFW sub-index affects $CV$
* You have tractable and well-defined marginal effects of policy and institutional shocks
* EFW sub-indices
  * Area 1: Size of government
  * Area 2: Legal system and property rights
  * Area 3: Sound money
  * Area 4: Freedom to trade internationally
  * Area 5: Regulation
</p></div>