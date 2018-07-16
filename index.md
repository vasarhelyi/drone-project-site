This site is dedicated to the article

G. Vásárhelyi, Cs. Virágh, G. Somorjai, T. Nepusz, A. E. Eiben, T. Vicsek, **Optimized flocking of autonomous drones in confined environments**, _Science Robotics_, **3**, eaat3536 (2018)


## Video Abstract

<iframe width="640" height="360" src="https://www.youtube.com/embed/E4XpyG4eMKE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


## Q & A 

* **What problem is solved here?**
A flocking algorithm has been applied to large swarms of drones optimally to perform synchronized collective motion at high speeds without collision, while also avoiding obstacles.

* **Why is that problem interesting / relevant / challenging?**
This is a basic building block of self-organized drone swarm coordination using collective intelligence. Future drones must be autonomous for many applications - we provide a working solution for outdoor drone swarm control in cluttered and noisy environments.

* **What is new here? What solutions were known before this study?**
Our previous results showed maximum 10 drones at slower speed, with less stability.
Results for dozens of autonomous drones have only been presented indoors, relying on expensive and immobile local positioning systems and central computation and control.
Our solution is noise tolerant, works with low resolution outdoor positioning systems (e.g. GPS) anywhere in the world. Our drone swarm control is scalable in group size and speed due to the combination of realistic modeling and evolutionary optimization

* **What is the essence of the new solution? What is the key insight of this research? What is THE result?**
We derived a general distributed swarm control framework with many parameters. We focus on model instances instead of models, that is, (evolutionary) optimization is part of the solution.
The key concept in the model is the optimal combination of natural flocking algorithms with distributed motion planning

* **What makes the solution/insight/result so cool that Science Robotics published it?**
We presented 30 drones flying autonomously without central control (no ground station, no pilots).
The solution is scalable in the number of drones and in the speed of flight (1000 drones @ 115 km/h presented in simulation)

* **Are there any practical applications?**
This is the “coordination” level which is the basis for all swarm applications (“cooperation”, “collaboration”).
All applications where a bunch of drones need to do something autonomously together, e.g. environmental monitoring (!), collective / self-organized search and rescue operations, crowd inspection, fighting forest fires, precision agriculture, dikes inspection (Netherlands).

* **Are the autonomous drones dangerous or can they become dangerous?**
Yes, if someone makes them to do so. Just like a knife, which can be used for good and bad. It is a collective responsibility of humanity to use any technological innovation peacefully. Our drones have never been used for military applications, while we actively help wildlife protection, environmental monitoring and precision agriculture.

* **What research fields are involved in this study?**
  * biological physics
  * artificial intelligence
  * collective robotics

* **What next? Finished? Continued? Diverted?**
  * Fundamental science:
    We keep learning from natural systems (e.g. by creating hierarchical / heterogeneous flocks instead of egalitarian ones)
    We aim for real-time optimized / adaptive systems
    We do application specific research using the collective motion of drones
  * Commercial applications: 
    We provide multi-drone services through CollMot Robotics (www.collmot.com) 


## Abstract

We address a fundamental issue of collective motion of aerial robots: how to ensure that large flocks of autonomous drones seamlessly navigate in confined spaces. The numerous existing flocking models are rarely tested on actual hardware because they typically neglect some crucial aspects of multirobot systems. Constrained motion and communication capabilities, delays, perturbations, or the presence of barriers should be modeled and treated explicitly because they have large effects on collective behavior during the cooperation of real agents. Handling these issues properly result in additional model complexity and a natural increase in the number of tunable parameters, which calls for appropriate optimization methods to be coupled tightly to model development. In this paper, we propose such a flocking model for real drones incorporating an evolutionary optimization framework with carefully chosen order parameters and fitness functions. We numerically demonstrated that the induced swarm behavior remained stable under realistic conditions for large flock sizes and notably for large velocities. We showed that coherent and realistic collective motion patterns persisted even around perturbing obstacles. Furthermore, we validated our new model on real hardware, carrying out field experiments with a self-organized swarm of 30 drones. This is the largest of such aerial outdoor systems without central control reported to date exhibiting flocking with collective collision and object avoidance. The results confirmed the adequacy of our approach. Successfully controlling dozens of quadcopters will enable substantially more efficient task management in various contexts involving drones.


## Download Full Text

The full article is made open-access and is available at **TODO**.


## Download Supplementary Material

* Supplementary Text, available at **TODO**.
* Movie S1. Simulation of old flocking model (algorithm A) with 100 agents, available [here](https://youtu.be/viEfowBXzho).
* Movie S2. Simulation of new flocking model (algorithm B) after evolutionary optimization with 100 agents, available [here](https://youtu.be/t8kr79k3DUQ).
* Movie S3. Simulation of flocking for different speeds (4-32 m/s), flock sizes (30-1000 agents) and scenarios, available [here](https://youtu.be/KPVfi9Pwuq8).
* Movie S4. Flight log visualization of 30 drones at 4 m/s in a diagonal flight pattern, available [here](https://youtu.be/JMMGIQm7Ris).
* Movie S5. Flight log visualization of 30 drones at 6 m/s with obstacles, available [here](https://youtu.be/YW5zDD70x8o).
* Movie S6. Flight log visualization of 30 drones at 8 m/s in a circular flight pattern, available [here](https://youtu.be/GoiunzowSG4).
* Movie S7. Summarizing documentary with simulation, flight log visualization and footage on real flights, available [here](https://youtu.be/E4XpyG4eMKE).


## Download Flight Logs

Flight logs related to the article are accessible [here](https://doi.org/10.5061/dryad.mq85r61).


## Download Simulation Code

The code basis of the multi-drone simulation that was used in the article is open-source and can be found at [github.com/csviragh/robotsim](https://github.com/csviragh/robotsim).


## Authors and Affiliation

* [Gábor Vásárhelyi](http://hal.elte.hu/~vasarhelyi/)<sup>1,2,3</sup>
* [Csaba Virágh](https://hal.elte.hu/flocking/wiki/public/en/people/CsabaViragh)<sup>2,4</sup>
* [Gergő Somorjai](https://collmot.com/)<sup>1,2,3</sup>
* [Tamás Nepusz](http://hal.elte.hu/~nepusz/)<sup>3,5</sup>
* [Agoston E. Eiben](https://www.cs.vu.nl/~gusz/)<sup>6</sup>
* [Tamás Vicsek](http://hal.elte.hu/~vicsek/)<sup>1,2</sup>

<sup>1</sup>[MTA-ELTE Statistical and Biological Physics Research Group](http://hal.elte.hu/)<br/>
<sup>2</sup>[ELTE Department of Biological Physics](https://fizika.elte.hu/en/index.php?page=tanszek&tid=5)<br/>
<sup>3</sup>[CollMot Robotics](https://collmot.com/)<br/>
<sup>4</sup>[Morgan Stanley](https://www.morganstanley.com/)<br/>
<sup>5</sup>[Molde University College](http://www.himolde.no/english/Sider/side.aspx)<br/>
<sup>6</sup>[Vrije Universiteit Amsterdam](https://www.vu.nl/nl/index.aspx)


## Media Coverage

* Nothing yet but more to come
