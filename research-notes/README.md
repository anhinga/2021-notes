### Research notes

---

### March 2021

Title:

_Towards Practical Use of Dataflow Matrix Machines_

---

Abstract:
  * **Dataflow matrix machines (DMMs)** form a class of neural machines with very interesting theoretical properties. On the level of single neurons,  they replace streams of numbers by arbitrary streams allowing linear combinations of several streams (**linear streams**). It turns out that this change and a few other modifications make the resulting formalism suitable for general-purpose stream-oriented programming with **continuously deformable programs**. At the same time, these neural machines are expressive enough to provide convenient and flexible facilities for **compositional metalearning**.
  * We created experimental research-grade open-source implementations of self-referential dataflow matrix machines in Processing (with traditional mutable matrices) and in Clojure (with immutable streams of tree-shaped "flexible tensors"), and conducted a number of open-source software experiments using these implementations.
  * It is time to create a more professional implementation of DMMs in one of the modern ultra-flexible frameworks for differentiable programming such as Julia Flux or JAX, and to start using dataflow matrix machines in machine learning applications. In particular, one should be able to fruitfully target applications in **program synthesis** and in **metalearning**.

---

### April 2022

File updated to fix a broken link.

PDF files:
  * March 2021 - in this directory
  * April 2022 - linked from https://www.cs.brandeis.edu/~bukatin/dmm_next.html
