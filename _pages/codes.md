---
layout: archive
title: "Codes"
permalink: /codes/
author_profile: true
---


My research relies heavily on computation. I started my coding adventure by replicating two classic models -- Aiyagari (1994) and Huggett (1996).

I am sharing my notes and Matlab code. Hopefully, it will help you and make your first step toward computational macroeconomics less painful. 

1. Aiyagari (1994)         
   \[[Notes](../files/Aiyagari.pdf)\] \[[Code](https://github.com/yanranecon/Aiyagari-1994-Replication/tree/main/Codes)\]
   
2. Huggett (1996)         
   \[[Notes]()\] \[[Code](https://github.com/yanranecon/Huggett-1996-Replication/tree/main/Codes)\]

**Other Extensions**

1. Transition Dynamics  
   An “MIT shock” is an unexpected shock that hits an economy at its steady state, leading to a transition path back towards a new steady state. The primary purpose of this note is to expalin the computation of the deterministic transition dynamics of the model economy after an unexpected policy change. I do this exercise in Aiyagari (1994) model economy using a change in household's borrowing constraint as the shock.  
   \[[Notes](../files/MIT.pdf)\] \[[Code](https://github.com/yanranecon/MIT-Shock/tree/main/Codes)\]

2. Castaneda, Díaz-Giménez, and Ríos-Rull (2003)  
   CDR (2003) model is an extension of Aiyagari (1994) with stochastic aging and labor supply decision.  
   The code I'm sharing here runs extremely slow because I use this replication exercise to understand the model without caring too much about the efficiency. Efficiency can easily be improved by just rewriting the code in matrix form, instead of looping over each state. Other fancy numerical methods like [EGM](https://www.sciencedirect.com/science/article/pii/S0165188906001783) will shorten the execution time of the code by a lot (e.g., It only took me less than 10s in this case using EGM).  
   \[[Notes](../files/CDR.pdf)\] \[[Code](https://github.com/yanranecon/CDR-2003-Replication/tree/main/Codes)\]
