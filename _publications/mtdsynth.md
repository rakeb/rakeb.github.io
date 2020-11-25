---
title: "Specification-driven Moving Target Defense Synthesis"
collection: publications
Authors: '<b>Islam, Md Mazharul</b>; Duan, Qi; Al-Shaer, Ehab.'
date: 2019/11/11
venue: 'ACM CCS'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3338468.3356830'
presentationurl: ''
codeurl: 'https://github.com/rakeb/activesdn'
excerpt: ''
---
---
<a href='https://www.researchgate.net/profile/Md_Mazharul_Islam5/publication/337134688_Specification-driven_Moving_Target_Defense_Synthesis/links/5f349f35458515b7291be6e8/Specification-driven-Moving-Target-Defense-Synthesis.pdf' target="_blank">[Download Paper]</a>

<!--
<div style='display: flex; justify-content: center;'><img src='https://wasiahmad.github.io/files/publications/2018/LREC-1.png' 
alt='Image not Loading' style='height:350px;' align='middle'></div><br>
-->

<p align="justify">
Cyber agility enables cyber systems to defend proactively against
sophisticated attacks by dynamically changing the system configuration parameters (called mutable parameters) in order to deceive
adversaries from reaching their goals, disrupt the attack plans by
forcing them to change their adversarial behaviors, and/or deterring them through prohibitively increasing the cost for attacks.
However, developing cyber agility such as moving target defense
techniques that are provable safe is a highly complex task that
requires significant time and expertise. Our goal is to address this
challenge by providing a framework for automating the creation of
configuration-based moving target techniques rapidly and safely.
In this paper, we present a cyber agility synthesis framework,
called MTDSynth, that contains a formal ontology, MTD policy
language, and MTD controller synthesis engine for implementing
configuration-based moving target defense techniques. The policy
language contains the agility specifications required to model the
MTD technique, such as sensors, mutation trigger, mutation parameters, mutation actions, and mutation constraints. Based on the
mutation constraints, the MTD controller synthesis engine provides
an MTD policy refinement implementation for SDN configuration
with provable properties using constraint satisfaction solvers. We
show several examples of MTD controller synthesis, including temporal and spatial IP mutation, path mutation, detector mutation.
We developed our ActivSDN over OpenDaylight SDN controller
as an open programming environment to enable rapid and safe
development of MTD sense-making and decision-making actions.
Our implementation and evaluation experiments show not only
the feasibility of MTD policy refinement but also the insignificant
computational overhead of this refinement process.
</p>
