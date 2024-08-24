---
title: SwarmInt2024
id: swarmint2024
layout: default
weight: 50
description: Details of the research article "Decentralized traffic management of autonomous drones", Swarm Intelligence, 2024
---

# Decentralized traffic management of autonomous drones

<figure class="float-left">
<img src="assets/img/swarmint2024.jpg" alt="SwarmInt2024" width="100" />
</figure>

Balázs, B., Vicsek, T., Somorjai, G., Nepusz, T., & Vásárhelyi, G. (2024). **Decentralized traffic management of autonomous drones.**, _Swarm Intelligence_, [doi:10.1007/s11721-024-00241-y](https://doi.org/10.1007/s11721-024-00241-y).

---


## Background

Flocking and traffic are the two basic orthogonal building blocks of swarm motion. In flocking, agents have the same goal and synchronize their motion to go together. In traffic, agents have individual goals and coordinate their motion to avoid conflicts smoothly. This article focuses on the latter case. We developed a traffic algorithm and flew the largest ever autonomous swarm of 100 drones with it. (Note that limits are purely financial, not technical as we demonstrate also in the article with 2500 drones in simulation).

To achieve these goals, we use the same mindset and concept as with our previous flocking algorithms, and combine momentary flocking terms – optimized for traffic – with self-organized path planning. The results substantially outperforms what could ever be done with human pilots.


## Video abstract

There are five Supplementary Movies associated with this article (see below). This is the summarizing documentary with simulation, flight log visualization, and footage on real flights with hundred autonomous drones in dense self-organized traffic:

<div class="video-container">
<iframe src="https://www.youtube.com/embed/VOtu6Vmkp88" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen class="video"></iframe>
</div>


## Abstract

Coordination of local and global aerial traffic has become a legal and technological bottleneck as the number of unmanned vehicles in the common airspace continues to grow. To meet this challenge, automation and decentralization of control is an unavoidable requirement. In this paper, we present a solution that enables self-organization of cooperating autonomous agents into an effective traffic flow state in which the common aerial coordination task - filled with conflicts - is resolved. Using realistic simulations, we show that our algorithm is safe, efficient, and scalable regarding the number of drones and their speed range, while it can also handle heterogeneous agents and even pairwise priorities between them. The algorithm works in any sparse or dense traffic scenario in two dimensions and can be made increasingly efficient by a layered flight space structure in three dimensions. To support the feasibility of our solution, we show stable traffic simulations with up to 5000 agents, and experimentally demonstrate coordinated aerial traffic of 100 autonomous drones within a 250 m wide circular area.


## Download Full Text

The full article is available online at [Swarm Intelligence](https://link.springer.com/article/10.1007/s11721-024-00241-y).


## Download Supplementary Material

All supplementary materials (texts, tables, figures, videos) are available online at [Swarm Intelligence](https://link.springer.com/article/10.1007/s11721-024-00241-y).

Supplementary videos are also available on YouTube:

* [Supplementary Movie S1](https://youtu.be/wIsKGkHs2Po): Realistic simulation of 2D decentralized drone traffic with 5, 50, 500 and 5000 agents
* [Supplementary Movie S2](https://youtu.be/0Ms_wkeKxzU): Realistic simulation of 2D decentralized drone traffic with heterogeneous travel speed (2-32 m/s)
* [Supplementary Movie S3](https://youtu.be/CgcgccwPm4M): Realistic simulation of 3D decentralized drone traffic with 500 drones in 1, 2, 3 and 4 layers
* [Supplementary Movie S4](https://youtu.be/VOtu6Vmkp88): Summarizing documentary (video abstract) with simulation, flight log visualization, and footage on real flights
* [Supplementary Movie S5](https://youtu.be/v0OJxjIp-HU): A three-minute recording of the field experiment with 100 real drones. Credit to: Barnabás Takács


## Flight Log Visualization

An interactive 3D flight log visualization is [available here](https://share.skybrush.io/s/traffic-layers/).

While playing the visualization, use keys W, A, S, D, E and C to move around and drag scenery with mouse to look around.

Powered by [CollMot Robotics](https://collmot.com) and [Skybrush](https://skybrush.io).


## Download Simulation Code

The code basis of the multi-drone simulation that was used in the article is open-source and can be found at [github.com/csviragh/robotsim](https://github.com/csviragh/robotsim).



## Funding

* MTA-ELTE Statistical and Biological Physics Research Group
* K\_16 Research Grant, National Research, Development and Innovation Office – NKFIH (K 119467)
* USAF Grant No: FA9550-17-1-0037
* National Research, Development and Innovation Office – NKFIH: OTKA SNN Grant No:139598
* KTNL Research Grant, National Research, Development and Innovation Office - NKFIH (2022-2.1.1-NL-2022-00012)

Special thanks to [CollMot Robotics](https://collmot.com) for using their intelligent drone swarm and their swarm-level ground control station, [Skybrush](https://skybrush.io).


## Media Coverage

### English

* Safe Drone Traffic in Smart Cities of the Future [(elte.hu, 2024.07.15.)](https://www.elte.hu/en/content/safe-drone-traffic-in-smart-cities-of-the-future.t.3347)
* Safe drone traffic in smart cities of the future [(scienmag.com, 2024.07.15.)](https://scienmag.com/safe-drone-traffic-in-smart-cities-of-the-future/)
* Safe drone traffic in smart cities of the future [(bioengineer.org, 2024.07.15.)](https://bioengineer.org/safe-drone-traffic-in-smart-cities-of-the-future/)
* Self-organizing drone flock demonstrates safe traffic solution for smart cities of the future [(morns.ca, 2024.07.15.)](https://morns.ca/2024/07/15/self-organizing-drone-flock-demonstrates-safe-traffic-solution-for-smart-cities-of-the-future/)
* The First Comprehensive Autonomous Drone Traffic Management System [(azorobotics.com, 2024.07.16.)](https://www.azorobotics.com/News.aspx?newsID=15080)
* Self-organizing drone flock demonstrates safe traffic solution for smart cities of the future [(techxplore.com, 2024.07.15.)](https://techxplore.com/news/2024-07-drone-flock-safe-traffic-solution.html)
* World-first: Flock of 5,000 drones self-fly safely during a UAV traffic test [(interestingengineering.com, 2024.07.16.)](https://interestingengineering.com/transportation/first-self-driving-drone-traffic)
* The First Comprehensive Autonomous Drone Traffic Management System [(msn.com, 2024.07.16.)](https://www.msn.com/en-gb/news/techandscience/the-first-comprehensive-autonomous-drone-traffic-management-system/ar-BB1q5w2b)
* Safe drone traffic in smart cities of the future [(innovations-report.com, 2024.07.16.)](https://www.innovations-report.com/transportation-and-logistics/safe-drone-traffic-in-smart-cities-of-the-future/)
* The First Comprehensive Autonomous Drone Traffic Management System [(azorobotics.com, 2024.07.16.)](https://www.azorobotics.com/News.aspx?newsID=15080)
* This Smart Traffic Management System Can Handle 5,000 Autonomous Drones, Researchers Say [(hackster.io, 2024.07.16.)](https://www.hackster.io/news/this-smart-traffic-management-system-can-handle-5-000-autonomous-drones-researchers-say-fc26ce0dd13e)
* Autonomous Drone Traffic: ELTE’s Revolutionary Solution [(impactlab.com, 2024.07.17.)](https://www.impactlab.com/2024/07/17/autonomous-drone-traffic-eltes-revolutionary-solution/)
* First large-scale autonomous drone traffic solution for future smart cities trialled [(dpaonthenet.net, 2024.07.17.)](https://www.dpaonthenet.net/article/206549/First-large-scale-autonomous-drone-traffic-solution-for-future-smart-cities-trialled.aspx)
* ELTE Researchers Pioneer Safe Self-Organization of Dense Drone Traffic Based on Bird Flock Flight [(flyingcarsmarket.com, 2024.07.18)](https://flyingcarsmarket.com/elte-researchers-pioneer-safe-self-organization-of-dense-drone-traffic-based-on-bird-flock-flight/)
* How to make a sky full of drones behave [(electrooptics.com, 2024.07.23.)](https://www.electrooptics.com/article/how-make-sky-full-drones-behave)
* How to make a sky full of drones behave [(imveurope.com, 2024.07.25.)](https://www.imveurope.com/article/how-make-sky-full-drones-behave)
* 5,000 drones flew safely and autonomously in traffic tests [(uavcrafts.com, 2024.07.25.)](https://uavcrafts.com/blogs/news/5-000-drones-flew-safely-and-autonomously-in-traffic-tests)
* Using drone swarms for autonomous mapping and surveillance, with CollMot Robotics CEO Gábor Vásárhelyi [(electrooptics.com, 2024.08.24.)](https://www.electrooptics.com/article/using-drone-swarms-autonomous-mapping-surveillance-collmot-robotics-ceo-gabor-vasarhelyi)


### Hungarian

* Biztonságos drónforgalom a jövő okosvárosaiban [(elte.hu, 2024.07.15.)](https://www.elte.hu/content/biztonsagos-dronforgalom-a-jovo-okosvarosaiban.t.30888)
* Biztonságos drónforgalom a jövő okosvárosaiba [(bdpst24.hu, 2024.07.15.)](https://bdpst24.hu/2024/07/15/biztonsagos-dronforgalom-a-jovo-okosvarosaiban/) 
* A madárrajok repülésének alapján világelsőként oldották meg a sűrű drónforgalom biztonságos önszerveződését az ELTE kutatói [(qubit.hu, 2024.07.15.)](https://qubit.hu/2024/07/15/a-madarrajok-repulesenek-alapjan-vilagelsokent-oldottak-meg-a-suru-dronforgalom-biztonsagos-onszervezodeset-az-elte-kutatoi)
* Száz drón sűrű önvezető forgalmát mutatták be az ELTE kutatói [(frisss.hu, 2024.07.15.)](https://www.frisss.hu/aktualis/szaz-dron-suru-onvezeto-forgalmat-mutattak-be-az-elte-kutatoi)
* Biztonságos drónforgalom a jövő okosvárosaiban [(hirnavigator.hu, 2024.07.15.)](https://hirnavigator.hu/hir/7266973-biztonsagos-dronforgalom-a-jovo-okosvarosaiban)
* Ez vár a jövő városaira magyar kutatók szerint [(firstclass.hu, 2024.07.15.)](https://firstclass.hu/life/2024/07/16/ez-var-a-jovo-varosaira-magyar-kutatok-szerint/)
* Világelső rendszert épített az ELTE, 5000 drónt is képes egyszerre baleset nélkül reptetni – videó [(hvg.hu, 2024.07.17.)](https://m.hvg.hu/tudomany/20240717_eltre-dron-repules-mozgas-baleset)
* Magyar kutatók világsikere: 5 ezer drónt kapcsoltak össze [(gyartastrend.hu, 2024.07.17.)](https://gyartastrend.hu/cikk/magyar-kutatok-vilagsikere-5-ezer-dront-kapcsoltak-ossze)
* Biztonságos drónforgalom a jövő okosvárosaiban [(autopro.hu, 2024.07.17.)](https://autopro.hu/trend/biztonsagos-dronforgalom-a-jovo-okosvarosaiban/1160751)
* Biztonságos drónforgalom a jövő okosvárosaiban [(muszaki-magazin.hu, 2024.07.18.)](https://www.muszaki-magazin.hu/2024/07/17/dronforgalom-jovo-okos-varos-biztonsag/)
* Olyan rendszert épített az ELTE, ami 5000 drónt is képes egyszerre reptetni [(pcwplus.hu, 2024.07.18.)](https://www.pcwplus.hu/pcwlite/olyan-rendszert-epitett-az-elte-ami-5000-dront-is-kepes-egyszerre-reptetni-358032.html)
* Olyan rendszert épített az ELTE, ami 5000 drónt is képes egyszerre reptetni [(hirstart.hu, 2024.07.18.)](https://www.hirstart.hu/hk/20240718_olyan_rendszert_epitett_az_elte_ami_5000_dront_is_kepes_egyszerre_reptetni)
* Az előre gondolkodó, bioinspirált rajrepülésé a jövő [(minuszos.hu, 2024.07.23.)](https://www.minuszos.hu/az-elore-gondolkodo-bioinspiralt-rajrepulese-a-jovo/)


### Romanian

* Premiera mondiala in Ungaria: Un stol de 5.000 de drone zboara fara control uman si fara sa se ciocneasca intre ele [(aktual24.ro, 2024.07.17.)](https://www.aktual24.ro/premiera-mondiala-in-ungaria-un-stol-de-5-000-de-drone-zboara-fara-control-uman-si-fara-sa-se-ciocneasca-intre-ele/#goog_rewarded)


### Spanish

* Los drones ya pueden surcar en masa los cielos de las ciudades inteligentes [(diariodemallorca.es, 2024.07.22.)](https://www.diariodemallorca.es/tendencias21/2024/07/22/drones-surcar-masa-cielos-ciudades-105930224.html)
* Los drones ya pueden surcar en masa los cielos de las ciudades inteligentes [(elperiodico.com, 2024.07.22.)](https://www.elperiodico.com/es/tendencias-21/20240722/drones-surcar-masa-cielos-ciudades-105930222)
* Los drones ya pueden surcar en masa los cielos de las ciudades inteligentes [(lne.es, 2024.07.22.)](https://www.lne.es/tendencias21/2024/07/22/drones-surcar-masa-cielos-ciudades-105930214.html)


<!--
* title [(urlshort, 2024.07.xx.)](url)
-->
