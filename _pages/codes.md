---
layout: archive
title: "Codes"
permalink: /codes/
author_profile: true
---

My research relies heavily on computational methods. I began my journey in quantitative macroeconomics by replicating two classic models: Aiyagari (1994) and Huggett (1996).

I am sharing my notes and Matlab code in the hope that they will help you take your first steps into quantitative macroeconomics and make the learning process a little smoother.

1. Aiyagari (1994)         
   \[[Notes](../files/Aiyagari.pdf)\] \[[Code](https://github.com/yanranecon/Aiyagari-1994-Replication/tree/main/Codes)\]
   
2. Huggett (1996)         
   \[[Code](https://github.com/yanranecon/Huggett-1996-Replication/tree/main/Codes)\]

**Other Extensions**

1. Transition Dynamics  
   An MIT shock is an unexpected shock that hits an economy initially at its steady state, generating a transition path toward a new steady state. This note explains how to compute the deterministic transition dynamics of a model economy following an unexpected policy change. As an illustration, I consider the Aiyagari (1994) model and study the transition dynamics induced by a change in households' borrowing constraint.
   \[[Notes](../files/MIT.pdf)\] <!-- \[[Code](https://github.com/yanranecon/MIT-Shock/tree/main/Codes)\] -->

2. Castaneda, Díaz-Giménez, and Ríos-Rull (2003)  
   CDR (2003) model is an extension of Aiyagari (1994) with stochastic aging and labor supply decision.  
   The code provided here is not optimized for speed. I wrote it as part of a replication exercise aimed at understanding the model and its mechanics, so clarity was prioritized over efficiency. Consequently, the code relies heavily on loops and may run quite slowly. There is plenty of room for improvement. Simply rewriting the code in matrix form can significantly reduce computation time. More sophisticated methods, such as [EGM](https://www.sciencedirect.com/science/article/pii/S0165188906001783) can further improve performance. For this model, an EGM implementation solves the household problem in only a few seconds.  
   \[[Notes](../files/CDR.pdf)\] \[[Code](https://github.com/yanranecon/CDR-2003-Replication/tree/main/Codes)\]

3. The endogenous grid point method (EGM)
   \[[Notes](../files/Aiyagari_EGM.pdf)\]
   
4. Aiyagari + Labor Supply (EGM)
   \[[Notes](../files/Aiyagari_CandH_EGM.pdf)\]
