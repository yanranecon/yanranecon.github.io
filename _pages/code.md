---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
---


My research relies heavily on computation. I started my coding adventure by replicating two classic models -- Aiyagari (1994) and Huggett (1996).

I am sharing my notes and Matlab code. Hopefully, it will help you and make your first step toward computational macroeconomics less painful. 

1. Aiyagari (1994)         
   \[[Notes](../files/Aiyagari.pdf)\] \[[Code](https://github.com/yanranecon/Aiyagari-1994-Replication/tree/main/Codes)\]
   
2. Huggett (1996)         
   \[[Notes]()\] \[[Code]()\]

**Other Extensions**

1. Castaneda, Díaz-Giménez, and Ríos-Rull (2003)  
   CDR (2003) model is an extension of Aiyagari (1994) with stochastic aging and labor supply decision.

The code I'm sharing here runs extremely slow because I use this replication exercise to understand the model without caring too much about the efficiency. Efficiency can easily be improved by just rewriting the code in matrix form, instead of looping over each state. Other fancy numerical methods like [EGM](https://www.sciencedirect.com/science/article/pii/S0165188906001783) can shorten the execution time of the code by a lot (e.g., It only took less than 30s in this case using EGM).

\[[Notes](../files/CDR.pdf)\] \[[Code]()\]
