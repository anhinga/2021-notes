# Additional notes for "Dataflow matrix machines, tree-shaped flexible tensors, neural architecture search, and PyTorch" research draft

Even if we decide to focus only on the next generation of flexible differential programming frameworks such as
as Julia Flux and JAX, the issues of flattening nested dictionaries for better efficience and more convenient interfaces
are important.

---

In particular, see these materials on **dictionaries with array-like interface** from JuliaCon 2021:

Dictionaries.jl - for improved productivity and performance
https://pretalx.com/juliacon2021/talk/WRNAEN/

and https://live.juliacon.org/talk/WRNAEN (that is, https://www.youtube.com/watch?v=Y-hAZcqAw28)

https://github.com/andyferris/Dictionaries.jl

---

See also the foundational materials on persistent hash maps in the modern programming languages like Clojure:

The wikipedia article:  https://en.wikipedia.org/wiki/Hash_tree_(persistent_data_structure)

https://lampwww.epfl.ch/papers/idealhashtrees.pdf (also posted here https://hashingit.com/elements/research-resources/2001-ideal-hash-trees.pdf )

These ideal hash trees are more like Tries ("Hash Array Mapped Trie").

Array Mapped Tries(AMT), first described in "Fast and Space Efficient Trie Searches", Bagwell [2000], form the underlying data structure.

In this sense, in Julia we have https://github.com/JuliaCollections/FunctionalCollections.jl

with "PersistentHashMap" and such, with the foundational file being "src/BitmappedVectorTrie.jl".
