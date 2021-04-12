### 3) The Mind Game: towards participatory VJing

### May 31, 2012

### (beginning to sketch an architecture for a system for participatory VJing)

Two main channels computers use to affect people’s conscious states are visual and audio.

When I think about playing with creating flows of visual and audio information by free generation + mixing and transforming other inputs, I am thinking about VJing and DJing. (There is a variety of less standard ways computers can affect conscious states, including smells, infra and ultra sound, vibrations, magic, etc, those channels might be fruitful to explore.)

My limited experience tells me that it is easier to make VJing participatory for more people, than DJing, so I am going to focus on that as a starting point. By **participatory** I mean that a person VJs for him/herself (usually building upon the creations of others, and often sharing his/her own creation with others).

***

My own minor experience was with **Milkdrop** plug-in for **Winamp**. The story of both Winamp and Milkdrop is a romantic chapter in the history of open source and struggle against abusive copyrights (see Wikipedia articles on Milkdrop, Winamp, and **Justin Frankel**, and references therein, that’s an amazing story).

What’s important is that Milkdrop “presets” are text files (essentially, simple scripts in a declarative language), and they are traditionally shared openly and can be modified and built upon. There is a vibrant open source community authoring presets, and Milkdrop comes with an amazing default collection of open source presets. There is also some limited documentation and tutorials, which help one to learn to modify other people presets (or to build one’s own from scratch). I liked the results of some limited experiments I’ve done with Milkdrop presets.

***

Still, there are some problems with Milkdrop. One is that there is no definition of the language for presets; the implementation is the definition; one learns only by imitating others and studying their work. It would be great to have a platform with similar power, but with definition as precise as it is customary for programming languages.

Another problem is that while there is some graphical user interface to edit some of the preset values, this interface is very ascetic. This makes it difficult to use for people who are less text-oriented. It would be great to have better graphical controls, while preserving the property of preset being a human-readable and human-editable text. Ideally, one would have a dual view for many values of preset variables: a graphical view and a textual view, and the system keeping them in synch as they are being edited.

Another thing is that Milkdrop is great for collaboration and building on top of each other’s work in the offline mode: one can take other people’s presets, build on top of them, and share the resulting new preset with community. It would be great to enable **real-time collaboration (“collective VJing”)**.

Another thing is a capacity to have multiple and flexible inputs (not just music, but other things, including, eventually, EEG data or features extracted from EEG data in real-time).

Another thing is a capacity to have “checkpoints” (to store the preset states as one goes, so that one can go back to previous states of the preset when necessary; essentially we are talking about the ability to navigate the history of one’s work/play with a preset).

It’s probably enough for one post; I’ll write more on “collective VJing”, and on “checkpoints” and navigating facilities later.
