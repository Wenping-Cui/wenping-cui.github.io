---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---




Finding the Rules Behind Complex Systems
======
I work between biology and physics, looking for the general rules that living systems follow. My starting point is an old idea: *more is different*. Put enough simple parts together and the group does things that no single part can do.

One bacterium tells you almost nothing about a whole microbiome, and one neuron tells you almost nothing about a brain. These systems have thousands of parts acting on each other at once, so taking them apart one piece at a time is hopeless — there are far too many pieces, and far too many ways they can combine. So I work the other way around, from the top down. I build math models, develop fast simulations, and use deep learning to filter out the noise and pull the meaningful signal from large, messy biological data. The aim is to find the few simple rules behind the group behavior, and then turn those rules into predictions that experiments can test.

How Complex Ecosystems Organize Themselves
======
A spoonful of soil holds thousands of microbial species, all competing for the same limited food. The old puzzle is how so many species manage to coexist at all. My work shows two things: that having many species makes a community easier to describe rather than harder, and that a community keeps doing its job even while its genes are constantly changing hands.

More Species, Simpler Rules
------
We found something surprising: once a community has enough species in it, its overall behavior stops depending on the fine details of which species affects which. All the small differences average out, so a simple model that ignores those details still gets the big picture right. This matters in practice. It means we can predict, and even design, microbiomes without first mapping every single interaction — a task that would be impossible anyway. ([*Phys. Rev. Lett.* 2020](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.125.048101); [*Phys. Rev. E* 2021](https://link.aps.org/doi/10.1103/PhysRevE.104.034416))

Staying Stable While Everything Changes
------
Real ecosystems never sit still. Species keep evolving, and bacteria pass genes back and forth. We found that a stable community is not one that holds on to the same species, but one that keeps the necessary genes in circulation. To survive, a cell needs the right defense genes on hand, and those genes are constantly being shared, lost, and reassembled across the community. Because the genes keep flowing, the community as a whole stays diverse even when individual cells die at a high rate. What defines a community is the pool of genes it holds, not the list of species in it. ([*PNAS* 2025](https://doi.org/10.1073/pnas.2417628122))

How Brains and Machines Learn
======
The same puzzle shows up in systems that learn. I use both artificial and biological networks to understand how simple building blocks come together into complex, intelligent behavior.

How Language Models Learn
------
Language models make a good test case, because we know exactly how they are built and what they were trained on. That lets us watch new abilities appear as they happen. Studying small models as they learn new tasks, we found that whether a model picks up a real rule or simply memorizes answers depends on how varied its training examples are. Surprisingly, a model that is too good at memorizing has a harder time learning to generalize. ([arXiv:2604.12151](https://arxiv.org/abs/2604.12151))

How Animals Learn to Move
------
Animals have a harder problem. They learn by moving through the real world, where the number of possible movements is effectively endless. I am building a data analysis pipeline that tracks the full 3D posture of rats as they learn a new skill. Even though the space of possible movements is huge, the animals reuse a small, steady set of moves they already had. Learning is mostly a matter of finding which combinations of those moves earn a reward, rather than inventing new ones. (In preparation.)


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