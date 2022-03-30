# Three views on dataflow matrix machines (2015-2020)

### Continuously deformable stream-oriented progams working with linear streams
  
  * This is the orginal view. This is why dataflow matrix machines were invented in 2014-2015.

    * 2016: _Programming Patterns in Dataflow Matrix Machines and Generalized Recurrent Neural Nets_, https://arxiv.org/abs/1606.09470

    * 2017: _Dataflow Matrix Machines and V-values: a Bridge between Programs and Neural Nets_ (Sections 6 and 11.2), https://arxiv.org/abs/1712.07447

    * 2020: [Map of DMM-related programming examples and techniques](https://github.com/anhinga/2020-notes/tree/master/programming-overview)

### Generalized recurrent neural networks working with linear streams instead of streams of numbers

  * Origin (2016):

    * _Dataflow Matrix Machines as a Generalization of Recurrent Neural Networks_, https://arxiv.org/abs/1603.09002

    * _Dataflow matrix machines as programmable, dynamically expandable, self-referential generalized recurrent neural networks_, https://arxiv.org/abs/1605.05296

  * Overview (2017-2018):

    * _Dataflow Matrix Machines and V-values: a Bridge between Programs and Neural Nets_ (Sections 2, 4, 8, 9, 11.1), https://arxiv.org/abs/1712.07447

    * [Slides (IBM AI Systems Day)](https://web.archive.org/web/20220305051310/https://researcher.watson.ibm.com/researcher/files/us-lmandel/aisys18-bukatin.pdf)

### "Super-transformers": each input of a super-neuron in a dataflow matrix machine is an attention device combining incoming linear streams together

  * Materials

    * 2020-2021: Section 11, _DMMs and Transformers_, of [_Dataflow Matrix Machines: a Collaborative Research Agenda_](https://www.cs.brandeis.edu/~bukatin/dmm-collaborative-research-agenda.pdf)

    * Follow links from the footnotes of Section 11, _DMMs and Transformers_, for more details.

  * An informal outlook: 

    * [Comment on the simple-minded pragmatic attention ("content-based neural attention")](https://github.com/anhinga/2020-notes/blob/master/attention-based-models/simple-minded-attention.md)

  * An even more informal outlook:

    * Every input of a super-neuron combines linear streams together with coefficients: that is, each input of a super-neuron uses attention to create a combined local reality from separate local realities of incoming streams.

    * Then the built-in "activation function" of the super-neuron takes all combined local realities of its inputs and transforms them to produce a set of output local realities to be sent to other super-neurons in the network.
