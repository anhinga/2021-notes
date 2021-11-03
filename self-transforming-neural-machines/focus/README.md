### Current focus of the next interation of self-transforming neural machines study



### Section 3, Self-modification, learning to learn, and neuroevolution, of Dataflow Matrix Machines: a Collaborative Research Agenda, https://www.cs.brandeis.edu/~bukatin/dmm-collaborative-research-agenda.pdf

Using neural networks for metalearning is always non-trivial. In particular, dimension mismatch, namely
the number of neuron outputs being much smaller than the number of network weights, means that a neural
network can only modify itself in a highly constrained manner. Dataflow matrix machines address this problem
and have **powerful and flexible self-modification facilities**.

Therefore, a dataflow matrix machine can be equipped with a variety of primitives which perform self-modifications, 
and it can fruitfully learn various linear combinations and compositions involving those primitives.

Self-modification facilities of dataflow matrix machines are not limited to the weight changes for the existing
connections in the network. The available primitives allow to modify the network topology as well. For
example, primitives allowing the network to control its own fractal-like growth by the means of cloning its own
subnetworks are available.

Therefore, this is a very promising architecture not only for methods of learning to learn better in a
traditional sense, but also for methods of learning to perform neural architecture search better.

A dataflow matrix machine can comfortably host an evolving population of other DMMs inside itself, so it
is an excellent environment for neuroevolution experiments and, in particular, for the experiments aiming to
learn to evolve better (or to evolve to evolve better).

In our software experiments, we used self-modification facilities to

  * produce controlled wave patterns in the network matrix (see Appendix B.2 of our LearnAut 2017 paper, https://arxiv.org/abs/1706.00648);
  
  * create randomly initialized self-referential DMMs which generated interesting emerging behaviors (see Section 1.2 of our 11-2018 technical report, [dmm-notes-2018](https://www.cs.brandeis.edu/~bukatin/dmm-notes-2018.pdf));

  * edit a running network on the fly by sending it requests to edit itself (in particular, this enables live-coding, 
    but this is also quite open-ended, since it enables a population of networks to tell each other
    to modify themselves; of course, the receiving network doesn’t have to follow an incoming instruction
    to self-modify blindly, although in the most simple-minded case it would do so; see Section 1.1 of our
    11-2018 technical report, [dmm-notes-2018](https://www.cs.brandeis.edu/~bukatin/dmm-notes-2018.pdf).
