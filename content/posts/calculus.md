+++
title = "Goodbye, calculus!"
date = 2022-01-15T16:46:32+07:00
images = []
tags = []
categories = []
mathjax = true
+++

# Goodbye, calculus!

Today I passed my calculus exam. 🎉🎉🎉  
So let's prove some theorem at the end!  

### Dini's theorem
If functions $f_n, f$ are continuous and $\forall x: f_n(x) \xrightarrow[n \to \inf]{} f(x) \Rightarrow f_n \rightrightarrows f$  
&#9654;
let $g_n = f_n - f$. This function decreases monotonically. And $g_n \to 0$.  
Consequently, $\forall x \in [a,b] \\ \exists n: 0 \leq g_n < \varepsilon \Rightarrow$ because of continuity,
$\exists \delta > 0, J_{x} = (x-\delta,x+\delta): \forall t \in J_{x}: 0 \leq g_n(t) < \varepsilon$  
Collection of sets $J_x$ forms an infinite cover of the set $[a,b]$. Consequently, there is finite subset of this collection, that covers set $[a,b]$.  
Let $N = max \lbrace n_i \rbrace$.  
$\forall t \in [a,b] \\ \exists J_{x_i}: t \in J_{x_i} \Rightarrow 0 \leq g_N(t) \leq g_{n_i} < \varepsilon$  
Finally: $\forall \varepsilon > 0 \\ \exists N \\ \forall n > N \\ \forall t \in [a,b]: |g_n(t) - 0| < \varepsilon \Rightarrow g_N \rightrightarrows 0 \Rightarrow f_N \rightrightarrows f$ &#9664;
