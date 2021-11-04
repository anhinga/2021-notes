# Background for self-transforming neural machines

### Linear streams and V-values (2014-2017)

  * Linear streams: streams which can be combined with coefficients

  * V-values: tree-shaped "flexible tensors"

### [Three views on dataflow matrix machines (2015-2020)](https://github.com/anhinga/2021-notes/blob/main/self-transforming-neural-machines/background/three-views.md)

  * Continuously deformable stream-oriented progams working with linear streams 

  * Generalized recurrent neural networks working with linear streams instead of streams of numbers

  * "Super-transformers": each input of a super-neuron in a dataflow matrix machine is an attention device combining incoming linear streams together

### Self-referential mechanism: the theory (2016-2018)

  * A dedicated neuron _Self_ emitting a stream of network weight matrices and accepting updates to the network matrix from other neurons in the network

### Self-referential mechanisms: the experiments (2016-2018)

  * A network sending controlled waves through its own weight matrix (Processing)

  * Emerging oscillations and sleep-wake patterns in randomly initialized self-transforming neural machines (Processing)

  * Use of the self-transforming capabilities to edit a running neural machine on the fly by sending it requests to self-edit (Clojure)

### Fractal motifs

  * Duplication of subgraphs of a running network

  * Representing the state of the whole network inside a V-value available to a single neuron
