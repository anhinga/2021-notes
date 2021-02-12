### Research drafts

---

### January 2021

Title:

_Dataflow matrix machines, tree-shaped flexible tensors, neural architecture search, and PyTorch_

---

Focus of this draft: 

  * Dataflow matrix machines have strong affinity with methods of **Neural Architecture Search (NAS)**.
    In particular, when one reformulates program synthesis as DMM synthesis, the task of
    _learning program sketches_ is reformulated as neural architecture search. At the same time,
    the ability of DMMs to transform themselves and other DMMs make them a strong platform
    for metalearning, and, in particular, make them a strong platform for generating and learning
    novel Neural Architecture Search methods.

  * One can choose to implement DMMs within one of the next generation ultra-flexible machine
    learning platforms such as **JAX** or **Julia Flux**, or one can choose to implement DMMs within
    one of the mainstream machine learning platforms such as **PyTorch**. We consider some of the trade-offs
    and technical aspects associated with this choice.
