---
title: Interface2020
id: interface2020
layout: default
weight: 40
description: Details of the research article "Adaptive leadership overcomes persistence—responsivity trade-off in flocking", J. Royal Society Interface, 2020
---


# Adaptive leadership overcomes persistence—responsivity trade-off in flocking

<figure class="float-left"><img src="assets/img/interface2020.jpg" alt="Interface 2020 June Cover" width="100" /></figure>

B. Balázs, G. Vásárhelyi, T. Vicsek, **Adaptive leadership overcomes persistence—responsivity trade-off in flocking**, _Journal of The Royal Society Interface_, Vol. 17, Issue 167, [0190853](https://royalsocietypublishing.org/doi/10.1098/rsif.2019.0853), 2020 June

---


## Background

Our previous results on the cover of [Science Robotics](scirob2018.md) showed that self-organized flocking of large drone swarms in confined spaces is indeed possible. However, during the same process we have also learned that evolution has no ending and there always exists a "better" way, so we kept on pushing our limits through the deep analysis of all the bottlenecks of that solution. One major issue was the generally low speed of information propagation that is inherently present in homogeneous, "averaging-type" flocks. Simply averaging neighboring behaviour results in very efficient noise filtering and thus stable, synchronized collective motion, however, it is also the root cause of many accidents (e.g. at football matches or at Black Friday events) when the environment gets anisotropic and agents with new information content about obstacles (or in more natural settings, predators) need to react more swiftly than what is allowed by this low-pass-neighbor-filter. To have a simultaneously stable/presistent *and* reactive/responsive complex system is something very far from trivial, it is actually forbidden by the fluctuation-dissipation theorem in the non-living world. But of course, as always, evolution has found a way out of this conflict, so our new quest became to find a possible simple explanation how it could be done. The result is the extention from homogeneous to heterogeneous, from democratic to strictly hierarchical: the introduction of information-driven, adaptive leadership.


## Video Abstract

There are four Supplementary Videos associated with this article (see below). This is the one about our real self-organized drone swarm demonstrating the efficiency of the new control algorithm:

<div class="video-container">
<iframe src="https://www.youtube.com/embed/87y3AsUOCaQ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen class="video"></iframe>
</div>


## Abstract

The living world is full of cohesive collectives that have evolved to move together with high efficiency. Schools of fish or flocks of birds maintain their global direction despite significant noise perturbing the individuals, yet they are capable of performing abrupt collective turns when relevant agitation alters the state of a few members. Ruling local fluctuations out of global movement leads to persistence and requires overdamped interaction dynamics, while propagating swift turns throughout the group leads to responsivity and requires underdamped interaction dynamics. In this paper we show a way to avoid this conflict by introducing a time-dependent leadership hierarchy that adapts locally to will: agents’ intention of changing direction. Integrating our new concept of will-based inter-agent behaviour highly enhances the responsivity of standard collective motion models, thus enables breaking out of their former limit, the persistence-responsivity trade-off. We also show that the increased responsivity to environmental cues scales well with growing flock size. Our solution relies on active communication or advanced cognition for the perception of will. The incorporation of these into collective motion is a plausible hypothesis in higher order species, while it is a realizable feature for artificial robots, as demonstrated by our swarm of 52 drones.


## Download Full Text

The full article is available online at the [Journal of The Royal Society Interface](https://royalsocietypublishing.org/doi/10.1098/rsif.2019.0853).


## Download Supplementary Material

All supplementary materials (texts, tables, figures, videos) are available online at [Figshare](https://doi.org/10.6084/m9.figshare.c.4977689).

Supplementary videos are also available on Youtube:

* [Supplementary Video 1: Response simulations](https://youtu.be/6rbA-kmyADs)
* [Supplementary Video 2: DroneFlock'18 model in confined environment](https://youtu.be/QyYUEOOWf9E)
* [Supplementary Video 3: WillFull model in confined environment](https://youtu.be/12Xp0eig6Uk)
* [Supplementary Video 4: WillFull model on real aerial robots](https://youtu.be/87y3AsUOCaQ)


## Flight Log Visualization

An interactive 3D flight log visualization is [available here](https://share.skybrush.io/s/pers-resp/).

While playing the visualization, use keys W, A, S, D, E and C to move around and drag scenery with mouse to look around.

Powered by [CollMot Robotics](https://collmot.com).


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

### Hungarian

* Megtalálták a madárrajok repülésének titkát [(elte.hu, 2020.06.17.)](https://www.elte.hu/content/megtalaltak-a-madarrajok-repulesenek-titkat.t.21379)
* Egyre tökéletesebben utánozzák a dróncsapatok a madárrajok repülését [(ng.hu, 2020.06.21)](https://ng.hu/tudomany/2020/06/21/madarrajok-repuleset-egyre-tokeletesebben-utanozzak-a-droncsapatok/)
* Drónrajok reptetésében értek el elképesztő áttörést az ELTE kutatói [(InfoRádió, 2020.06.23.)](https://infostart.hu/tudomany/2020/06/24/dronrajok-repteteseben-ertek-el-elkepeszto-attorest-az-elte-kutatoi)
* Az ELTE TTK fizikusai rájöttek, miként képesek a madárrajok felülkerekedni az együttmozgás elvi nehézségein [(Magyar Katolikus Rádió, 2020.06.27.)](https://www.katolikusradio.hu/archivum.php?firstaudioid=20&mev=2020&mho=06&mnap=27&mora=20&mperc=04)
* Megfejtették a madárrajok titkát, forradalmasíthatják a drónipart [(M2 Petőfi TV, 2020.07.03.)](https://youtu.be/X-H2ljZRTIA)
* Ötvenen vannak, önszerveződnek és egyre jobban hasonlítanak egy madárrajra [(Kossuth Rádió, 2020.07.16., 14:51:50-14:58:35)](https://mediaklikk.hu/radio-lejatszo-kossuth/?date=2020-07-16_14-32-00&enddate=2020-07-16_15-10-00&ch=mr1), [MP4](aassets/media/20200716-FELFEDEZO-Boldizsar.mp3)

### English

* Mimicking nature, our drones are flocking smoothly on the cover of Journal of the Royal Society Interface [(collmot.com, 2020.06.23.)](https://collmot.com/blog/mimicking-nature-our-drones-are-flocking-smoothly-on-the-cover-of-journal-of-the-royal-society-interface)

### Dutch

* Het geheim van de zwerm [(npostart.nl, 2020.08.05.)](https://www.npostart.nl/de-kennis-van-nu-special-het-geheim-van-de-zwerm/05-08-2020/VPWON_1308693)
* Nieuw wereldrecord zwermvliegen met drones [(nporadio1.nl, 2020.08.05.)](https://www.nporadio1.nl/wetenschap-techniek/25556-nieuw-wereldrecord-zwermvliegen-met-drones)