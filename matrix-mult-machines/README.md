# DMMs and attention; DMMs and Transformers; matrix multiplication machines

## History (2020 only on this page)

In 2020, we studies relationships between DMMs and attention-based models including Transformers.

See Section "DMMs and Transformers" of https://www.cs.brandeis.edu/~bukatin/dmm-collaborative-research-agenda.pdf

See also https://github.com/anhinga/2020-notes/tree/master/attention-based-models

In particular, we started to focus on **"Machines with matrix multiplication as a key element"**:

https://github.com/anhinga/2020-notes/blob/master/attention-based-models/matrix-mult-machines.md

In particular, we started experimental explorations where we **interpret monochrome images as matrices and multiply them**.

In 2021 we focus on this kind of studies much more.

## Experimental studies (2021)

We did quite a bit of studies related to interpreting monochrome images as matrices and multiplying them via matrix multiplication in 2021:

https://github.com/anhinga/julia-notebooks/tree/main/images-as-matrices

This is an active work, which is continuing.

We have also resurrected some of the 2020 work by the "Grimoire team":

https://github.com/anhinga/julia-notebooks/tree/main/grimoire-team

and we married the image transformations created during that period
with matrix multiplication: 

https://github.com/anhinga/julia-notebooks/tree/main/grimoire-team/variations

and refactored those in functional and differentiable fashion:

https://github.com/anhinga/julia-notebooks/tree/main/transition-to-flux

and Flux/Zygote seems to compute gradients properly in this context.

Here is the first machine learning study we have performed using this setup:

https://github.com/anhinga/julia-notebooks/tree/main/flux-may-2021

_This is an active line of research, to be continued..._
