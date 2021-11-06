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


