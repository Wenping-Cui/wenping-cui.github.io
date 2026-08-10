---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---




Research Interests
======
My research lies at the interface of physics, biology, and machine learning. I use ideas from statistical physics to understand how collective behavior and learning emerge in systems composed of many interacting parts—from microbial ecosystems to neural networks and animal behavior. Across these systems, I ask a common question: when can high-dimensional dynamics be explained by a small set of order parameters, statistical laws, or computational strategies? I seek coarse-grained principles that yield quantitative, experimentally testable predictions.

My work combines mathematical modeling, statistical-physics theory, large-scale numerical simulation for complex systems. Depending on the system, I develop consumer-resource and population-dynamics models, analyze the internal computations of neural networks, or extract behavioral structure from high-dimensional experimental data. The goal is not only to predict what a complex system will do, but also to identify the minimal mechanisms that make its behavior understandable.

Representative works
======

Emergent Organization in Microbial Ecosystems
------
Microbial communities can contain thousands of species competing for limited resources. Their composition also changes continually through population turnover, evolution, and horizontal gene transfer. My work investigates how such ecosystems self-ogranize under complexity.

**Simplifcity from Complexity:**  We found that once a community has enough species in it, its overall behavior stops depending on the fine details of which species affects which. All the small differences average out, so a simple model that ignores those details still gets the big picture right. This matters in practice. It means we can predict, and even design, microbiomes without first mapping every single interaction — a task that would be impossible anyway. ([*Phys. Rev. Lett.* 2020](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.125.048101); [*Phys. Rev. E* 2021](https://link.aps.org/doi/10.1103/PhysRevE.104.034416))


**Robustness Through Gene Sharing:** Real ecosystems never sit still. Species keep evolving, and bacteria pass genes back and forth. We found that a stable community is not one that holds on to the same species, but one that keeps the necessary genes in circulation. To survive, a cell needs the right defense genes on hand, and those genes are constantly being shared, lost, and reassembled across the community. Because the genes keep flowing, the community as a whole stays diverse even when individual cells die at a high rate. What defines a community is the pool of genes it holds, not the list of species in it. ([*PNAS* 2025](https://doi.org/10.1073/pnas.2417628122))

Learning Dynamics in Brains and Machines
------
The same puzzle shows up in systems that learn. Learning systems face a problem analogous to that of complex ecosystems: many interacting components must collectively discover useful structure in a vast space of possibilities. I study both artificial and biological learners to understand how computational strategies and behavioral motifs (similar to species in ecology!) emerge, compete, and reorganize during learning.


**Generalization versus Memorization in Transformers** Language models make a good test case, because we know exactly how they are built and what they were trained on. That lets us watch new abilities appear as they happen. Studying small models as they learn controllable sythestic tasks, we found that whether a model picks up a real rule or simply memorizes answers depends on how varied its training examples are. Surprisingly, a model that is too good at memorizing has a harder time learning to generalize. ([arXiv:2604.12151](https://arxiv.org/abs/2604.12151))


**Behavioral Strategies for Motor Learning**: Animals have a harder problem. They learn by moving through the real world, where the number of possible movements is effectively endless. I am developing a data-analysis pipeline that reconstructs the full three-dimensional posture of freely moving rats as they learn new motor skills. Our preliminary analyses suggest that animals navigate this space by selecting, refining, and recombining a compact repertoire of movements already present early in training. This work aims to reveal how animals efficiently explore behavioral possibilities and converge on successful solutions. (In preparation.) (In preparation.)


<!-- Default Statcounter code for Github webpage
https://wenping-cui.github.io/ -->
<script type="text/javascript">
var sc_project=12455467; 
var sc_invisible=1; 
var sc_security="4f402f9f"; 
</script>
<script type="text/javascript"
src="https://www.statcounter.com/counter/counter.js"
async></script>
<noscript><div class="statcounter"><a title="Web Analytics
Made Easy - StatCounter" href="https://statcounter.com/"
target="_blank"><img class="statcounter"
src="https://c.statcounter.com/12455467/0/4f402f9f/1/"
alt="Web Analytics Made Easy -
StatCounter"></a></div></noscript>
<!-- End of Statcounter Code -->