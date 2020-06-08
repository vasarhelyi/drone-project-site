---
title: Interface2020
id: interface2020
layout: default
weight: 40
description: Details of the research article "Adaptive leadership overcomes persistence-responsivity tradeoff in flocking", Royal Society Interface, 2020
---

# Adaptive leadership overcomes persistence-responsivity tradeoff in flocking

<figure class="float-left"><img src="assets/img/interface2020.jpg" alt="Interface 2020 June Cover" width="100" /></figure>

B. Balázs, G. Vásárhelyi, T. Vicsek, **Adaptive leadership overcomes persistence-responsivity tradeoff in flocking**, _Journal of The Royal Society Interface_, Vol. 17, Issue 167, 2020 June

---

## Background

Our previous results on the cover of [Science Robotics](scirob2018.md) showed that self-organized flocking of large drone swarms in confined spaces is indeed possible. However, during the same process we have also learned that evolution has no ending and there always exists a "better" way, so we kept on pushing our limits through the deep analysis of all the bottlenecks of that solution. One major issue was the generally low speed of information propagation that is inherently present in homogeneous, "averaging-type" flocks. Simply averaging neighboring behaviour results in very efficient noise filtering and thus stable, synchronized collective motion, however, it is also the root cause of many accidents (e.g. at football matches or at Black Friday events) when the environment gets anisotropic and agents with new information content about obstacles (or in more natural settings predators) need to react more swiftly than what is allowed by this low-pass-neighbor-filter. To have a simultaneously stable/presistent __and__ reactive/responsive complex system is something very far from trivial, it is actually forbidden by the fluctuation-dissipation theorem in the non-living world. But of course, as always, evolution has found a way out of this conflict, so our new quest bacame to find a possible simple explanation how it could be done. The result is the extention from homogeneous to heterogeneous, from democratic to strictly hierarchical: the introduction of information-driven, adaptive leadership.

## Abstract

The living world is full of cohesive collectives evolved to move together with high efficiency. Schools of fish or flocks of birds maintain their global direction despite even significant noise perturbing the individuals, yet they are capable of performing abrupt collective turns when relevant agitation alters the state of a few members. 
Ruling local fluctuations out of global movement leads to persistence and needs overdamped interaction dynamics, while propagating swift turns throughout the group leads to responsivity and needs underdamped interaction dynamics.

In this paper we show a way out of the above conflict by introducing a time-dependent leadership hierarchy that adapts locally to will: agents’ intention of changing direction. 
Integrating our new concept of will-based inter-agent behaviour highly enhances responsivity of standard collective motion models, thus enables breaking out of their former limit, the persistence-responsivity tradeoff. 
We also show that the increased responsivity to environmental cues scales well with growing flock size.

Our solution relies on active communication or advanced cognition for the perception of will. 
The incorporation of these into collective motion is a plausible hypothesis in higher order species, while it is a realizable feature for artificial robots, as demonstrated by our swarm of 52 drones.

## Download Full Text

The full article is available online at the [Journal of The Royal Society Interface](https://royalsocietypublishing.org/toc/rsif/2020/17/167).


## Download Supplementary Material

TODO


## Download Flight Logs

TODO


## Download Simulation Code

The code basis of the multi-drone simulation that was used in the article is open-source and can be found at [github.com/csviragh/robotsim](https://github.com/csviragh/robotsim).


## Authors and Affiliation

* [Balázs Boldizsár]()<sup>2
* [Gábor Vásárhelyi](http://hal.elte.hu/~vasarhelyi/)<sup>1,2,3</sup>
* [Tamás Vicsek](http://hal.elte.hu/~vicsek/)<sup>1,2</sup>

<sup>1</sup>[MTA-ELTE Statistical and Biological Physics Research Group](http://hal.elte.hu/)<br/>
<sup>2</sup>[ELTE Department of Biological Physics](https://fizika.elte.hu/en/index.php?page=tanszek&tid=5)<br/>
<sup>3</sup>[CollMot Robotics](https://collmot.com/)<br/>


## Funding

* K_16 Research Grant of the Hungarian National Research, Development and Innovation Office (K 119467);
* European Union’s Horizon 2020 Research and Innovation Programme under Grant Agreement No. 740688.

## Media Coverage

TODO
