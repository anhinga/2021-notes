## Basics

Neural machines work by repeating a two-stroke cycle. 
The inner mechanisms of neurons work during the first phase of the cycle.
Then the network connectivity matrix remixes the neuron outputs with weights
and creates neuron inputs for the next cycle during the second phase of the cycle.

To allow the neural machine to modify its own connectivity matrix,
we create a dedicated neuron _Self_ which emits a new network connectivity matrix on each step
during the first phase of each cycle
(or it might emit a more complex structure which contains the connectivity matrix).
This newly created connectivity matrix is used during the second phase of the same cycle.

The newly created connectivity matrix is just one of the neuron outputs, so
along with other neuron outputs it gets remixed during the second phase (yes, this is
an example of self-application) to create neuron inputs for the next cycle.

This allows the network to analyze its own connectivity and to use its own
connectivity structure in various ways, in addition to using it directly
during the second phase of a two-stroke cycle.

### _Self_ is typically an accumulator

We usually connect the output of _Self_ containing the connectivity matrix with one of
its inputs with weight 1. This way _Self_ accumulates the connectivity matrix while
accepting updates to its value from other neurons in the network.

This is not mandatory, one can imagine different arrangements. But this is how we
were doing things in our 2016-2018 experiments.

### Unlimited dynamic self-expansion

In some of our experiments we allowed unlimited dynamics self-expansion of the network.

To do this one imagines having "an ambient infinite collection of silent neurons
which don't take any memory or computational resources, but only exist as abstract
entities in the infinite address space". Under this approach, the connectivity matrix
is infinite, but it contains only a finite number of non-zero elements (so this is
an inherently sparse matrix).

When a neuron acquires a non-zero connection within the connectivity matrix,
this neuron stops being silent and is no longer just an abstract entity, but
it gets allocated in the memory, and computational resources are now spent on
computing its inputs and outputs. Such neuron is called _active_.

## A simple scenario for self-expansion

We start with two active neurons and with the connectivity matrix containing
two non-zero elements.

One of this active neurons is _Self_, and one of the two non-zero elements
of the connectivity matrix is weight 1, connecting the output of _Self_ to one of its inputs.

Another active neuron is _Update_, and the second non-zero element of
the connectivity matrix is weight 1, connecting the output of _Update_
to one of the inputs of _Self_.

During the first phase of the two-stroke cycle, _Self_ combines its inputs
together creating a new connectivity matrix.

What is happening under this scenario depends on the specific
updates to the connectivity matrix emitted by the neuron _Update_.

