+++
title = 'Go girl, give us nothing!'
date = 2024-02-08T13:38:07+05:30
draft = false 
math = true
+++

The notion of a proof is ubiquitous through most of science and maths. The way in which one proves a claim might differ but the notion of a _proof_ is understood. Proofs are often conversational in nature. The prover is trying to convince someone of their proof. Think about a teacher trying to convince their students that $\sqrt{2}$ is irrational. The teacher starts by telling the student the idea of a proof by contradiction. They convince the student that if we assume something is false and reach a point of absurdity with regards to a pre existing knowledge, our original presumption must have been incorrect. The students are perplexed but the idea seems reasonable to them so they go along with it. The teacher starts by assuming you can write $\sqrt{2}$ as a ratio of two relatively prime integers $a$, and $b$. Then they square both sides to get $2=\frac{a^2}{b^2}$ or $2b^2=a^2$. Since $a^2$ is even, $a$ must also be even, therefore we set $a=2c$, or $b^2=2c^2$. Now since $b^2$ is even, $b$ must also be even but that means that $a$ and $b$ are both divisible by $2$ and hence not relatively prime, which is a contradiction. 

## Where's Wally?

Is it possible for a prover to convince somebody about the truth of the statement without telling them any of the _secrets_ they possess with regards to the proof. 


In cryptography, we capture these _proofs_ as interations between a prover $\mathbf{P}$ and a verifier $\mathbf{V}$.

![Where's Wally?][assets/Wally.jpeg]