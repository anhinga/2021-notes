### 5) The Mind Game: towards collective VJing

### June 18, 2012

### (continues the topic started by the post on participatory VJing on May 31)

Imagine that your preset is defined as a transform/mixture of N other presets (those might belong to you or to other people, and those other people might be anywhere on the net).

Imagine a system which is aware of real-time changes in presets, and that any valid transform/mixture remains well-defined as its arguments change.

Here you would immediately have a cool setup for collective VJing.

What needs to be developed here is either an intuitive system of transforms which anyone can meaningfully use, or a system where a VJ assembles his/her preset based on other presets, and the system automatically infers a transform associated with this.

This is a relatively difficult, but exciting design task, which would be of great interest to some segments of the computer science community (including myself and, I presume, many people we know).

### (update: if one follows the spirit of DJing, the transforms would be applied to the outputs of presets. What should be done instead is, relying on the requirement that presets are open-source, the transforms should be applied to the structure of the presets (this subsumes the transforms applied to the outputs). Also, generally, I don’t assume streaming the videos themselves cross-computer, it’s enough to exchange low-bandwidth real-time information about preset changes, but it’s generally not necessary to stream the output; instead one can recreate similar output locally, if necessary.)

***

Another system one needs here is to navigate back-and-forth over one’s own changes and changes made by other people. For example, for navigation over one’s own settings, one might want to be able to mark checkpoints, to return back over those checkpoint, and either to “go back forward”, or to start developing new settings based on the current checkpoint and to be able to insert a new checkpoint between the current one and the next one (this is, basically, one-dimensional system of navigation).

It’s also important to be able to create checkpoints of other people presets (this involves cloning their preset), because often one would want to fix a “sweet spot”, rather than depend on further changes of the input preset in question.

Of course, one should be able to clone one’s own preset in such a situation, and to also have a preset which depends on the dynamic changes in the input preset, in addition to the one which uses the “sweet spot”; at that point one realizes that, perhaps, a more sophisticated navigation system is required (the one which is more aware of which presets are derived from which). And then the design of such a navigation system also becomes a task of some non-trivial interest for some segments of the computer science community.

***

What’s important is that here one enables a system of collective creation, of real-time creative communication between people, and a lot of interesting things might emerge.

This is, obviously, a very preliminary thinking, but I’d like share it, because the thinking about a system like this also needs to be collective in order to be fruitful.
